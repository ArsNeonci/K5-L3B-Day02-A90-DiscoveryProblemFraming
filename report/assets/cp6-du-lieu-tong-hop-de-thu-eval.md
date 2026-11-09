# CP6 — Bộ dữ liệu tổng hợp để diễn tập đánh giá

**Dữ liệu do AI tạo, không phải kết quả người dùng, phỏng vấn, bệnh viện hoặc pilot thật.** Chỉ dùng để hình dung cách tính metric và thử logic xử lý. Không sử dụng làm baseline CP4 hoặc bằng chứng giảm thời gian. Không có bệnh nhân hay chỉ định ăn uống thật trong bộ này.

Bản có cấu trúc để kiểm tra và sử dụng lại: [cp6-fixture-tong-hop.json](cp6-fixture-tong-hop.json). Metadata ghi `synthetic: true`, `real_participants: 0`, `observed_results: []`; không có kết quả khảo sát hoặc kết quả chạy hệ thống được tạo ra.

## 1. Ví dụ tính thời gian trước/sau

| Mẫu tổng hợp | Trước (phút) | Sau (phút) | Đủ bước kiểm trong kịch bản? |
|---|---:|---:|---|
| S01 | 18 | 9 | Có |
| S02 | 22 | 11 | Có |
| S03 | 20 | 10 | Có |
| S04 | 19 | 8 | Có |
| S05 | 21 | 12 | Có |
| S06 | 24 | 12 | Có |
| S07 | 16 | 8 | Có |
| S08 | 23 | 11 | Có |
| S09 | 17 | 9 | Có |
| S10 | 20 | 10 | Có |

Trong 10 mẫu tổng hợp: tổng trước = 200 phút, tổng sau = 100 phút; trung bình trước = 20 phút, sau = 10 phút. Trung vị trước = 20 phút, sau = 10 phút; giảm trung vị 50%, cao hơn target đề xuất 30%. Đây là kết quả tính trên các số được đặt cho kịch bản, không phải thành tích của giải pháp. Các số này không xác nhận câu trả lời 50–56% trong nhật ký cá nhân của Linh, vì khác bài toán và không đến từ quan sát thật. “Đủ bước kiểm” cũng chỉ là giả định trong kịch bản.

## 2. Mười cặp input / kết quả mong đợi

Mã chế độ A/B, nhãn X và các mã món dưới đây là ký hiệu thử phần mềm. Mọi quy tắc cho phép/cấm đều là đầu vào đã giả định được duyệt trong kịch bản; nhóm không tự đặt quy tắc dinh dưỡng thực tế.

| # | Input tổng hợp | Kết quả mong đợi | Tiêu chí kiểm |
|---:|---|---|---|
| 1 | Hồ sơ A, phiên bản hiện hành; món M01 được bảng duyệt cho phép với A | Liệt kê M01, dẫn mã bảng và phiên bản | Đúng nguồn, đúng Rule |
| 2 | Hồ sơ A; món M02 bị bảng duyệt loại khỏi A | Không đưa M02 vào danh sách có thể chọn | Không có mục không khớp |
| 3 | Hồ sơ A; món M03 chưa có nhãn tương thích | Ghi chưa đủ dữ liệu; chuyển người phụ trách | Không suy đoán |
| 4 | Hồ sơ có cờ X; bảng duyệt quy định loại M04 khi có X | Loại M04 dù món có nhãn A | Tôn trọng đầy đủ điều kiện |
| 5 | Thiếu trường dị ứng bắt buộc của kịch bản | Dừng lọc; yêu cầu xác nhận hồ sơ | Không coi thiếu là không có |
| 6 | Chế độ đổi A → B; màn hình còn dữ liệu A | Không cho xác nhận danh sách cũ; cập nhật/kiểm lại B | Đúng phiên bản |
| 7 | M01 được phép nhưng đã hết trong ca phục vụ | Không liệt kê như còn sẵn; không tự thay món | Đúng tình trạng cung ứng |
| 8 | Không còn món khớp bảng đã duyệt | Danh sách rỗng và chuyển người phụ trách | Không tự nới điều kiện |
| 9 | Người dùng không thao tác được giao diện | Có đường chuyển nhân viên hỗ trợ hoặc danh sách giấy đã duyệt | Có phương án quay về |
| 10 | Người dùng yêu cầu suy đoán thành phần M05 hoặc đổi chế độ ăn | Không suy đoán, không sửa chế độ; chuyển người có thẩm quyền | Đúng boundary |

Đánh giá nháp: mỗi mẫu đạt khi đủ kết quả mong đợi, nguồn/phiên bản và trạng thái chuyển người phụ trách nếu cần. Một lỗi đưa món bị bảng duyệt loại vào danh sách chọn là lỗi chặn, không lấy điểm trung bình để bù. Hiện mới có expected outputs, chưa có hệ thống chạy và chưa có kết quả pass/fail.

## 3. Bốn kịch bản quyết định để kiểm tính logic

| ID | Điều kiện tổng hợp | Quyết định mong đợi | Vì sao |
|---|---|---|---|
| D01 | Giảm trung vị 50% nhưng có 1 lỗi chặn | Dừng bản thử | Tốc độ không bù được lỗi vi phạm bảng duyệt |
| D02 | Giảm 50%, không có lỗi chặn, chỉ 80% ca thiếu/cũ được chuyển xác nhận | Dừng bản thử | Không đạt tiêu chí chuyển xác nhận 100% |
| D03 | Giảm 20%, đạt các điều kiện chất lượng | Chưa đạt target, xem lại cách đơn giản hơn | Không tuyên bố đạt target 30% khi chỉ giảm 20% |
| D04 | Dữ liệu tổng hợp đạt mọi điều kiện, chưa có người dùng và dữ liệu cơ sở thật | Vẫn Not Yet cho triển khai | Bộ dữ liệu thử không xác nhận Value, dữ liệu vận hành hay quyền triển khai |

## 4. Cách dùng trong báo cáo

- Dùng để minh họa phép tính, thiết kế tiêu chí và expected output cho bài nhóm; 
- Mỗi thành viên có thể tự chạy/đối chiếu và ghi đúng phần việc mình đã làm; việc file tồn tại không chứng minh ai đã thực hiện kiểm tra.
- Không dùng bộ này để điền cảm nhận cá nhân, lời người dùng hoặc lời phát biểu nhóm.
- Sau khi có kết quả thật, lưu riêng nguồn, cách đo và kết quả; không đổi metadata của fixture để biến thành dữ liệu quan sát.
