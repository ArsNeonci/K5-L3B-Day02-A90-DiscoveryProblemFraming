# CP4 — Research và thiết kế kiểm chứng

Card chung: bệnh nhân đã biết lời dặn ăn uống nhưng cần biết nhanh món phù hợp. AI đã mở bốn nguồn chính thức, đối chiếu claim, phản biện giả định và thiết kế cách thu thập bằng chứng. **Chưa thực hiện phỏng vấn hoặc survey người thật; số kết quả người dùng hiện là 0.**

## 1. Phân biệt các nguồn dữ liệu

| Loại | Hiện có gì? | Có thể kết luận | Chưa thể kết luận |
|---|---|---|---|
| Xác nhận của Linh | Đã chọn card chung trong chat | Hướng bài toán được chọn để đào sâu | Cả nhóm đã kiểm chứng hoặc sẵn sàng triển khai |
| Báo cáo Mạnh | Ước lượng khoảng 20 phút, chưa rõ đơn vị | Có giả thuyết cần đo | Baseline mỗi lượt, tỷ lệ bệnh nhân gặp hoặc mức giảm đã đạt |
| Nguồn công khai R0–R3 | Bối cảnh và case triển khai từ chính cơ sở cung cấp dịch vụ | Có các pattern và giới hạn để học | Pain và quy trình cụ thể tại cơ sở nhóm sẽ khảo sát |
| Dữ liệu tổng hợp | Fixture/eval trong repo | Có thể kiểm logic và phép tính của mô hình | Đã hỏi bệnh nhân, giải pháp được chấp nhận hoặc hiệu quả thật |

## 2. Sổ kiểm nguồn

Các claim là paraphrase; bài học áp dụng là suy luận của AI. Link đã mở lại ngày 10/11/2026, không chỉ lấy từ kết quả tìm kiếm.

| ID | Nguồn chính thức | Nội dung được hỗ trợ | Giới hạn / phản bác | Ảnh hưởng tới bài |
|---|---|---|---|---|
| R0 | [Hướng dẫn nội trú Vinmec](https://www.vinmec.com/vie/bai-viet/huong-dan-danh-cho-khach-hang-dieu-tri-noi-tru-tai-vinmec-vi), mục chế độ dinh dưỡng | Có nhân viên nhận lựa chọn thực đơn cho ngày hôm sau vào khung 13–15 giờ | Không chứng minh có app tự đặt, thành phần đầy đủ hoặc thời gian chọn 20 phút | Không thay kênh nhận lựa chọn khi chưa khảo sát; hỏi rõ ai đang hỗ trợ bệnh nhân |
| R1 | [Cambridge Memorial Hospital — CBORD Patient](https://www.cmh.org/patients/how-order-patient-meals), FAQ 3, 6, 8, 12 | Có lựa chọn theo dữ liệu ăn uống, có trường hợp không dùng app và có kênh nhân viên hỗ trợ | Điều kiện sử dụng và dữ liệu hiện hành là quan trọng; không đại diện mọi bệnh viện | Cần eligibility, phiên bản và fallback; không giả định mọi bệnh nhân đều tự dùng được |
| R2 | [PVHMC — HS onTray](https://www.pvhmc.org/blog/2025/july/pvhmc-receives-prodigy-award-for-innovation-from/), 15/07/2025 | Bệnh viện mô tả tự chọn suất ăn theo điều kiện đã chỉ định, triển khai theo giai đoạn | Không đưa ra baseline thời gian của nhóm hoặc chứng minh cần AI | Thử nhỏ, kiểm thao tác và dữ liệu trước; không tự suy ra kiến trúc bên trong |
| R3 | [UW Health — MyChart Bedside](https://www.uwhealth.org/files-directory/mychart/Dining/MYC_MealOrder.pdf), 2 trang | Có hướng dẫn chọn món trên tablet; không phải chế độ ăn nào cũng dùng được, có kênh hỗ trợ khi cần | Thay đổi điều kiện có thể cần nhân viên hỗ trợ; không đủ dữ liệu suy ra mức tiết kiệm | Có đường xử lý phiên bản thay đổi và quay về người phụ trách |

Ba case R1–R3 đáp ứng phần research công cụ/pattern. R0 cung cấp bối cảnh. Việc có bốn trang không đồng nghĩa có bốn người được phỏng vấn.

## 3. Phản biện sáu giả định

Điểm là đánh giá nháp của AI. Bằng chứng ngoại cảnh không được nâng thành bằng chứng đã kiểm tại Vinmec.

| ID | Giả định then chốt | Rủi ro | Quan trọng / bằng chứng hiện có (1–5) | Tín hiệu cần tìm | Tín hiệu có thể bác bỏ |
|---|---|---|---|---|---|
| A1 | Pain nằm ở đối chiếu món với lời dặn đã biết | Value | 5 / 1 | Một lần cụ thể người dùng phải tự đọc/đối chiếu, thời gian và điểm khó | Người dùng chưa biết chế độ ăn hoặc đã được nhân viên chọn hộ; actor/bottleneck cần đổi |
| A2 | Có bảng món và điều kiện đủ để lập danh sách đã duyệt | Feasibility | 5 / 1 | Mẫu dữ liệu được phép dùng, nguồn, chủ sở hữu, phiên bản | Thiếu thành phần hoặc nguồn cập nhật; không thể lọc đáng tin |
| A3 | Có người duyệt dữ liệu và ngoại lệ | Viability | 5 / 1 | Vai trò nhận trách nhiệm và cách chuyển xử lý | Không có người nhận vai; không nên pilot |
| A4 | Giao diện hoặc bản giấy phù hợp người dùng | Usability | 4 / 1 | Quan sát thao tác, lỗi đọc hiểu, người hỗ trợ | Người dùng không tự thao tác hoặc không muốn tự chọn; cần kênh hỗ trợ khác |
| A5 | Nhãn/nhân viên hiện có chưa đủ | Value | 5 / 1 | Thiếu sót vẫn xảy ra dù đã dùng cách hiện tại | Cách hiện tại nhanh và đủ rõ; No AI đã đủ hoặc không cần can thiệp |
| A6 | Lợi ích lớn hơn công cập nhật và kiểm dữ liệu | Feasibility / Viability | 4 / 1 | Thời gian mỗi lượt cùng công chuẩn bị/cập nhật | Tiết kiệm mỗi lượt nhỏ hơn công tạo và duyệt dữ liệu |

Ưu tiên A1, A2, A5. Không dùng dữ liệu tổng hợp để tăng điểm bằng chứng của các giả định này.

## 4. Thiết kế kiểm chứng cho người thực hiện

### 4.1. Đối tượng và cách làm

- Chọn 2–3 người thật sự gặp quy trình, ngoài nhóm: bệnh nhân/người hỗ trợ hoặc nhân viên liên quan; người thực hiện ghi đúng vai trò và phạm vi trải nghiệm.
- Hoặc survey 5–10 người đúng đối tượng; không gộp câu trả lời người không có trải nghiệm vào baseline.
- Ghi thời điểm, cách hỏi, lần xảy ra gần nhất; không lưu tên, hồ sơ bệnh án, mã bệnh nhân hoặc thông tin định danh trong repo.
- Không yêu cầu người tham gia chọn hoặc ăn món để thử một quy tắc nhóm tự nghĩ. Chỉ quan sát hoặc dùng dữ liệu/bản thử được phép sử dụng và đã có người phụ trách duyệt khi liên quan chuyên môn.

### 4.2. Bộ câu hỏi hành vi

| # | Câu hỏi đề xuất | Dùng để kiểm |
|---:|---|---|
| 1 | Lần gần nhất anh/chị tham gia chọn món trong thời gian nội trú là khi nào, và vai trò của anh/chị là gì? | Đúng đối tượng, đúng bối cảnh |
| 2 | Khi đó lời dặn ăn uống được nhận bằng cách nào, và ai xác nhận? | A1, A2 |
| 3 | Anh/chị có thể kể lần lượt từ lúc xem thực đơn tới lúc ghi nhận lựa chọn không? | Quy trình hiện tại |
| 4 | Ở lần đó, bước nào khó nhất? Anh/chị đã làm gì để xử lý? | Bottleneck, workaround |
| 5 | Mất khoảng bao lâu ở từng bước? Số đó là nhớ lại hay có thời điểm ghi nhận? | Baseline và cách lấy số |
| 6 | Có lần nào phải hỏi lại hoặc đổi lựa chọn vì thông tin chưa rõ không? Chuyện gì đã xảy ra? | Lỗi, ngoại lệ |
| 7 | Những nhãn, bảng hoặc người hỗ trợ hiện có đã giúp thế nào? Trường hợp nào không cần trợ giúp thêm? | A5, tín hiệu phản bác |
| 8 | Khi thông tin món hoặc lời dặn thay đổi, ai cập nhật và người chọn biết bằng cách nào? | Phiên bản, handoff |
| 9 | Có tài liệu đã ẩn danh hoặc mô tả quy trình nào được phép cho xem để đối chiếu không? | Nguồn bằng chứng, bước tiếp theo |

Không hỏi lời hứa dùng sản phẩm tương lai để thay cho bằng chứng hành vi đã xảy ra.

### 4.3. Trường cần ghi cho mỗi kết quả thật

Vai trò ẩn danh; ngày/cách hỏi; sự việc gần nhất; câu nguyên văn do người tham gia nói; từng bước và nguồn thời gian; cách đang xử lý; tín hiệu xác nhận; tín hiệu phản bác; ảnh hưởng đến actor/bottleneck/metric. Hiện chưa có dữ liệu để điền các trường này như một Interview Snapshot đã thực hiện.

## 5. Kịch bản diễn tập quyết định — không phải câu trả lời người dùng

| Tình huống giả định | Điều nên thay đổi nếu gặp thật | Không được suy ra |
|---|---|---|
| Người dùng nói đã có nhân viên chọn hộ, không đọc từng món | Thu hẹp actor hoặc xem lại pain | Toàn bộ bệnh viện đều không có pain |
| Thực đơn có nhãn rõ và chọn rất nhanh | Thử No AI hoặc dừng hướng thêm công cụ | Nhãn chắc chắn giải mọi ca |
| Dữ liệu món thiếu thành phần hoặc phiên bản | Dừng lọc tự động, chuyển người phụ trách | AI có thể điền phần thiếu cho đúng |
| Thời gian chủ yếu là chờ người xác nhận | Thiết kế lại handoff và đo thời gian chờ | Tóm tắt bằng AI giảm toàn bộ thời gian |
| Người dùng khó thao tác với màn hình | Giữ kênh giấy/người hỗ trợ | Có app nghĩa là Usability đã thấp rủi ro |

## 6. Kết luận CP4 do AI thực hiện

- Đã hoàn thành research trên bốn trang, bảng giả định, phân tích giới hạn, thiết kế câu hỏi và kế hoạch ghi bằng chứng.
- Research dẫn tới phạm vi hẹp: đối chiếu chế độ ăn đã xác nhận, giữ kênh hiện có; không tự suy luận từ bệnh án hoặc thành phần thiếu.
- Phần kiểm chứng người thật còn 0 kết quả. Trạng thái **Not Yet** không thay đổi.
- Chuyển sang CP5 bằng mô hình quy trình thiết kế; thời gian tự phân bổ phải gắn nhãn tổng hợp, không đổi thành số đo hiện trạng.

Liên kết: [báo cáo nhóm](../team/group_report.md), [CP5 do AI thực hiện](cp5-quy-trinh-va-phan-bien-ai.md), [sổ CP3](cp3-so-doi-chieu-phan-bien.md).
