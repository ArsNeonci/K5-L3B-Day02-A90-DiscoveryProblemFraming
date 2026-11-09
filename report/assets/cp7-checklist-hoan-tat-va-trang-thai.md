# Checklist hoàn tất và trạng thái


## 1. Các đầu ra đã chuẩn bị

| Phần | Đầu ra | Trạng thái |
|---|---|---|
| CP1 | Bốn báo cáo có bảng scan; Linh đã cung cấp số liệu hồi tưởng cho 5 hướng | Có nội dung; nguồn/cách lấy số được ghi |
| CP2 | Mỗi báo cáo có 3 card và 3 sơ đồ; đã thêm target, cách đo và phương án đơn giản | Có cấu trúc; thời gian thật từng bước còn thiếu ở một số card |
| CP3 theo vai | [15 cặp hỏi–trả lời](cp3-phien-phan-bien-ai-uy-quyen.md), lịch sử [Q01–Q06](cp3-so-doi-chieu-phan-bien.md) được lưu riêng | Đã có đầu ra AI; không xác nhận đã tự pitch/phản biện trực tiếp |
| CP4 research | [Bốn nguồn, sáu giả định và kế hoạch kiểm chứng](cp4-research-va-ke-hoach-kiem-chung-ai.md) | Đã có đầu ra AI; phỏng vấn/survey thật hiện 0 kết quả |
| CP5 | [Quy trình, mô hình thời gian, v0 và phản biện](cp5-quy-trinh-va-phan-bien-ai.md) | Đã có bản thiết kế; số 20→14 phút là tổng hợp |
| CP6 | [Phân tích chốt No AI, Not Yet](cp6-phan-tich-va-quyet-dinh-ai.md), v1, gate chất lượng và rủi ro | Đã có quyết định phân tích AI; không phải quyền triển khai ở cơ sở |
| Bộ dữ liệu thử | [10 mẫu eval, 10 lượt thời gian, 4 tình huống](cp6-du-lieu-tong-hop-de-thu-eval.md), [kết quả kiểm fixture](cp6-ket-qua-kiem-tra-fixture.json) | Đã kiểm tính nhất quán; 0 người dùng thật và 0 kết quả chạy sản phẩm |
| CP7 tham khảo | [Bốn vai, đủ 6.1–6.7](cp7-ban-tham-khao-ai-theo-vai.md) | Do AI soạn; không thay reflection tự viết |
| Bản chung và TEAM | Card chung, hướng can thiệp, quyết định và nguồn liên kết đã đồng bộ | Có bản nháp; vai trò/GitHub và đóng góp thật chưa đầy đủ |

## 2. Những việc chưa được nguồn hiện có chứng minh

| Mục | Thông tin còn thiếu | Trạng thái phải giữ |
|---|---|---|
| CP3 trực tiếp | Người hỏi/người nhận của các câu cũ, phản hồi và thay đổi thật | Không gán ngược từ phiên |
| CP4 người dùng | 2–3 phỏng vấn ngoài nhóm hoặc survey 5–10 người đúng đối tượng, tín hiệu phản bác | Chưa thực hiện/chưa được cung cấp; không lấy fixture thay |
| Baseline card chung | Đơn vị và phạm vi 20 phút, các bước thật, số mẫu và cách đo | Chưa xác lập baseline thật |
| Reflection Linh | Câu trả lời tự viết 6.1–6.7; đóng góp cụ thể còn trống | Bản AI chỉ tham khảo |
| Reflection Khánh | Nhật ký đóng góp/dùng AI và câu trả lời tự viết 6.1–6.7 | Bản AI không ghi thành trải nghiệm của Khánh |
| Reflection Chủ | Tự trả lời 6.6, tự diễn đạt 6.7 và cụ thể hóa đóng góp | Không dùng đoạn gợi ý làm câu trả lời đã hoàn tất |
| Phần Mạnh | Xác nhận nguồn baseline và đóng góp, tự giải thích 6.7 sau biên tập | Không nhận phần AI làm thay hoạt động đã thực hiện |
| TEAM | Tài khoản GitHub, vai trò và đóng góp do từng người xác nhận | Không tạo tài khoản hoặc dấu vết đóng góp giả |
| Nộp bài | Commit/push các cập nhật và nộp link trên LMS bằng từng tài khoản | Chưa thực hiện trong đợt biên tập này |

Không cần xây sản phẩm hoặc chạy pilot thật để làm xong lab; tuy nhiên chọn Not Yet không thay thế yêu cầu kiểm chứng và hoạt động cá nhân của rubric. Kết quả fixture chỉ kiểm logic tài liệu, không chứng minh người bệnh đã dùng hoặc target đã đạt.

## 3. Kiểm tra tài liệu

- Bốn tên file cá nhân theo mẫu MSSV_HoTen; báo cáo nhóm và TEAM có mặt.
- Kiểm đường dẫn nội bộ, khối code, ID các cặp phản biện và phép tính của fixture bằng script kiểm tra cục bộ.
- Các sơ đồ Mermaid nằm trong Markdown, không dẫn `.mmd` bằng cú pháp ảnh.
- Bộ nguồn CP4 có link chính thức; phân biệt claim nguồn, suy luận và dữ liệu tổng hợp.
- Tên remote hiện dùng `Day02`, trong khi mẫu SUBMISSION viết `DAY02`; chưa đổi tên repo/URL của cả nhóm trong đợt biên tập này.
- Không tạo xác nhận đã nộp LMS, đã có coach duyệt hoặc đã hết rủi ro khi chưa có dữ liệu đó.

Tham chiếu: [RUBRIC.md](../../RUBRIC.md), [SUBMISSION.md](../../SUBMISSION.md), [báo cáo nhóm](../team/group_report.md), [TEAM.md](../../TEAM.md).
