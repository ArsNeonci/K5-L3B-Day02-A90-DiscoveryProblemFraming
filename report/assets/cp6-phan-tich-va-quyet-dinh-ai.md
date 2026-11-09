# CP6 — Phân tích và quyết định

**Mức chọn cho vòng thử đầu: No AI. Quyết định triển khai: Not Yet.** Hai lựa chọn trả lời hai câu hỏi khác nhau: nên thử cách nào trước và đã sẵn sàng đưa vào sử dụng chưa.

## 1. Chuỗi quyết định

| Mắt xích | Nội dung chốt trong bản phân tích |
|---|---|
| Problem | Bệnh nhân biết lời dặn ăn uống nhưng khó biết nhanh món nào khớp |
| Quy trình | Nhận/kiểm lời dặn → xem món → đọc/đối chiếu → hỏi khi cần → ghi nhận lựa chọn |
| Bottleneck | Đọc/đối chiếu là giả thuyết, chưa có quan sát xác nhận bước lâu nhất |
| Metric | Sau baseline cùng phạm vi: giảm trung vị tổng thời gian ≥30%, không có lựa chọn không khớp bảng duyệt trong tập thử, 100% mẫu thiếu/cũ chuyển xác nhận |
| Boundary | Không suy đoán thông tin chuyên môn, không tự đổi điều kiện hoặc tự đặt món |
| Mức chọn | No AI: nhãn/danh sách và hướng dẫn đã duyệt, có nhân viên hỗ trợ |
| Quyết định | Not Yet vì chưa có kiểm chứng người dùng, dữ liệu cơ sở và người duyệt |

## 2. Vì sao chọn No AI

- Chưa có bằng chứng nhãn/danh sách được duyệt và nhân viên hỗ trợ là không đủ.
- Chọn Rule lúc này sẽ thêm yêu cầu chuẩn hóa và cập nhật dữ liệu khi nguồn tại cơ sở chưa được xác nhận.
- Workflow thêm phần giải thích có thể tăng công kiểm và nguy cơ diễn giải sai; chưa có bằng chứng lợi ích riêng.
- Agent không có vai trò cần thiết trong chuỗi bước đã xác định, và không được giao quyền tự suy luận điều kiện hoặc đặt món.

No AI vẫn phải có người chịu trách nhiệm về nhãn và phiên bản. Chọn mức đơn giản không làm rủi ro Value hoặc dữ liệu tự biến mất.

Rule là phương án tiếp theo chỉ khi No AI không đạt mục tiêu do thao tác đối chiếu nhiều điều kiện, có dữ liệu đủ và quy tắc đã được cơ sở duyệt. Workflow chỉ được xét nếu phần giải thích còn gây khó sau các mức trên. Đây là điều kiện chuyển mức, chưa phải điều đã xảy ra.

## 3. Ma trận và AI Canvas

Đối chiếu theo bảng đã duyệt có đúng/sai rõ nên mơ hồ thấp. Quy trình phối hợp nhiều bên có thể phức tạp, nhưng không tạo nhu cầu để AI tự quyết bước tiếp. Điểm khó hiện tại là dữ liệu và quy trình thực tế chưa biết, không phải thiếu khả năng tạo nội dung.

No AI được chọn nên **AI intervention point: Không có**; AI Canvas và câu hỏi PAIR cho một hệ thống tạo nội dung không áp dụng ở vòng này theo worksheet. Nhóm vẫn cần xác định người duyệt và tiêu chí đầu ra. Không coi vai trò AI soạn bài lab là mức can thiệp của giải pháp cho bệnh nhân.

## 4. V1 sau phản biện CP5

| Trường | Nội dung |
|---|---|
| Actor | Bệnh nhân nội trú có lời dặn đã xác nhận; có người hỗ trợ theo nhu cầu và điều kiện cơ sở |
| Quy trình | Giữ kênh nhận lựa chọn hiện có; chưa mặc định tự đặt qua app |
| Bottleneck | Giả thuyết khó đọc/đối chiếu; cần xác nhận bước và thời gian thật |
| Impact | Chưa có số mẫu/tần suất/tỷ lệ lỗi tại cơ sở; không suy ra lợi nhuận |
| Success Metric | Baseline thật cần đo; target thời gian ≥30% và các gate chất lượng như mục 1; tính cả công tạo/cập nhật dữ liệu riêng |
| Boundary | Nhãn/thông tin phải có nguồn, người duyệt và phiên bản; thiếu/cũ thì chuyển hỗ trợ, không suy đoán |
| AI intervention point | Không có; chưa chứng minh cần nội dung do AI tạo |
| Mức chọn | **No AI** cho vòng thử đầu |
| Rủi ro / người kiểm | Người phụ trách do cơ sở chỉ định kiểm nguồn, phiên bản, bảng tương thích và ngoại lệ; chưa có người được xác nhận nhận vai |

Thay đổi so với v0: chốt No AI, phân biệt thời gian từng lượt với công chuẩn bị, thêm điều kiện nguồn/phiên bản và giữ Not Yet. Bản CP5 20→14 phút và bộ S01–S10 20→10 đều là mô hình khác nhau, không dùng làm baseline thật của v1.

## 5. Tiêu chí đánh giá

| Tiêu chí | Đạt khi | Không đạt / xử lý |
|---|---|---|
| Khớp nguồn duyệt | Tất cả lựa chọn được bảng hiện hành cho phép | Một mục bảng loại vẫn được cho chọn: dừng bản thử |
| Không suy đoán | Mọi mẫu thiếu/cũ chuyển người phụ trách | Tự điền phần thiếu hoặc dùng bản cũ: dừng bản thử |
| Truy vết | Có nguồn và phiên bản cho dữ liệu quyết định | Thiếu nguồn: chưa xác nhận, không kết luận đạt |
| Có hỗ trợ | Người không thao tác được có kênh hỗ trợ hiện có | Không có fallback: chưa đủ điều kiện thử |
| Lợi ích | Target chỉ xét sau khi vượt chất lượng, tính đủ phạm vi | Nhanh hơn bằng bỏ bước hoặc bỏ công cập nhật: không tính đạt |

Mười mẫu E01–E10 chỉ là input/expected output để thiết kế kiểm tra. Chưa có sản phẩm được chạy trên các mẫu đó, nên chưa có tỷ lệ đúng của giải pháp để công bố.

## 6. Bốn rủi ro và hành động

| Rủi ro | Mức | Căn cứ hiện có | Điều cần làm trước khi hạ rủi ro |
|---|---|---|---|
| Value | Cao | Chưa hỏi đúng đối tượng; cách hiện tại có thể đã đủ | Hỏi hành vi đã xảy ra, giữ cả phản bác |
| Usability | Trung bình | Chưa quan sát thao tác với nhãn/danh sách | Thử cách trình bày và đường hỗ trợ khi được phép |
| Feasibility | Cao | Chưa có nguồn/phiên bản bảng món và điều kiện dùng được | Xác nhận mẫu dữ liệu và cách cập nhật |
| Viability | Cao | Chưa có cơ sở, người duyệt, người vận hành được xác nhận | Xác định vai trò, phạm vi thử, công chuẩn bị và dữ liệu được phép dùng |

**Not Yet**, không đưa bản thử cho người bệnh như công cụ đã được xác minh. Bước tiếp theo là kiểm chứng và xác lập dữ liệu; không phải tự xây Agent.

Ngưỡng dừng kế hoạch: nếu hết tuần chuẩn bị đầu tiên vẫn không có dữ liệu được phép dùng/người duyệt thì dừng pilot tại cơ sở; một lỗi chặn khi kiểm bảng thì dừng bản thử. Nếu No AI đáp ứng mục tiêu thì giữ No AI, không thêm Rule/AI chỉ để tăng mức công nghệ. Không chuyển Go chỉ vì bộ tổng hợp cho ra con số đẹp.

## 7. Kết quả kiểm tra tài liệu và dữ liệu tổng hợp

Đã kiểm tra số lượng mẫu, ID, phép tính thời gian và logic ngưỡng quyết định D01–D04; xem [kết quả kiểm tra fixture](cp6-ket-qua-kiem-tra-fixture.json). Đây là kiểm tra tính nhất quán của tài liệu, không phải đánh giá hiệu quả sản phẩm hay dữ liệu người dùng. D04 vẫn Not Yet dù số liệu tổng hợp đạt các gate.

Nguồn: [CP4](cp4-research-va-ke-hoach-kiem-chung-ai.md), [CP5](cp5-quy-trinh-va-phan-bien-ai.md), [bộ tổng hợp](cp6-du-lieu-tong-hop-de-thu-eval.md), [worksheet](../../docs/01-worksheet.md), [báo cáo nhóm](../team/group_report.md).
