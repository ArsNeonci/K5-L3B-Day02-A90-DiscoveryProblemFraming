# Báo cáo cá nhân — 2A202603865_VuDuyKhanh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Duy Khánh
- MSSV: 2A202603865
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: A90
- Link repo nhóm: https://github.com/ArsNeonci/K5-L3B-Day02-A90-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi đi từ nhà đến lớp mỗi ngày mất 2 tiếng một lượt, tôi muốn đến trường nhanh hơn, để có thêm thời gian cho việc riêng cá nhân | Tôi | 2 tiếng mỗi lượt, 4 tiếng mỗi ngày |
| 2 | Lặp lại | Khi đang trên đường đến lớp và gặp tắc đường, tôi muốn đảm bảo đến đúng giờ, để không bị mất điểm danh | Tôi | 2 lần đi muộn do tắc đường, bị mất điểm danh |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận đề lab có 7–8 file md và nhiều yêu cầu, tôi muốn nắm được phải làm những yêu cầu gì, để làm xong nhiều task hơn trong giờ lab | Tôi | 7–8 file md, 4 tiếng chỉ xong 1/5 task, vừa đọc vừa làm nên chưa tách được thời gian đọc |
| 4 | Lặp lại | Khi cần điền MSSV vào bài nộp hoặc biểu mẫu, tôi muốn có sẵn MSSV ngay lúc cần, để đỡ phải tra lại hằng ngày | Tôi | Mỗi ngày, mở Gmail, khoảng 2 phút mỗi lần |
| 5 | Lặp lại | Khi cần làm một thao tác git mà không nhớ lệnh, tôi muốn biết đúng lệnh cần chạy, để đẩy được bài lên GitHub mà không phải dừng lại tra lệnh | Tôi | Việc gì liên quan đến git cũng phải tra hoặc hỏi AI, riêng hôm nay 2 lần (tạo branch, đổi branch) |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Ý số 5 do AI gợi ý, từ việc tôi phải hỏi lệnh git. Tôi giữ vì việc gì liên quan đến git tôi cũng phải tra.
- Bỏ: các hướng AI gợi ý cho lăng kính "Pain từ người khác" (bạn cùng lớp hỏi lại deadline, kẹt GitHub, chờ thành viên nhóm...), vì tôi chưa kiểm được là có thật.
- AI hỏi gợi mở và xếp câu trả lời của tôi theo mẫu Job Story. Tôi bỏ "tóm tắt" và "tự động điền" khỏi Job Story vì đó là giải pháp.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Định hình đề lab (dòng 3) | Bước nghẽn cụ thể, 4 tiếng chỉ xong 1/5 task | Số phút là ước lượng. Chưa biết 45 phút định hình có phải nguyên nhân chính khiến chỉ xong 1/5 task không. Chưa biết bạn khác có gặp không |
| 2 | Tra lệnh git khi đẩy bài (dòng 5) | Lặp lại 3–5 lần/tuần, quy trình rõ | Số phút là ước lượng. Chưa biết bạn khác có gặp không |
| 3 | Đến lớp đúng giờ (dòng 2) | Có hậu quả rõ: muộn 2 lần/tuần, bị mất điểm danh | Số liệu là ước lượng và chưa khớp: theo số thì xuất phát 7h30 ngày nào cũng muộn, nhưng thực tế muộn 2 lần/tuần. Chưa xác định đường Nguyễn Trãi thuộc đoạn nào |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận đề lab có 7–8 file md và nhiều yêu cầu, tôi muốn nắm được phải làm những yêu cầu gì, để làm xong nhiều task hơn trong giờ lab |
| Actor | Học viên khóa AI thực chiến nhận đề lab gồm 7–8 file md |
| Thời điểm / bối cảnh | Đầu buổi lab, ngay khi nhận đề |
| Quy trình hiện tại (3–7 bước) | 1. Đọc README: 10' · 2. Đọc các file md còn lại: 15' · 3. Xâu chuỗi xem phải làm gì, làm gì trước: 20' · 4. Bắt đầu task đầu tiên. Số phút là ước lượng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, xâu chuỗi việc cần làm: 20'. Khó nhất là biết phần nào quan trọng và làm theo thứ tự nào |
| Impact (nếu không giải thì sao) | Mất 45 phút trước khi bắt đầu task đầu tiên. Ở Lab1, 4 tiếng chỉ xong 1/5 task |
| Success metric (baseline → target) | Thời gian từ lúc mở đề đến lúc bắt đầu task đầu tiên: từ 45 phút (ước lượng) xuống 15 phút, đo bằng cách bấm giờ ở các lab tiếp theo |
| Phương án không dùng AI | Đọc RUBRIC và CHECKPOINTS trước, tự rút ra phần nào nặng điểm và thứ tự làm |
| Giả thuyết về AI (nếu có) | Tóm tắt đề để đỡ phải đọc nhiều. Chưa kiểm chứng |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text
HIỆN TẠI: 45 phút trước khi bắt đầu task đầu tiên (ước lượng)

[1 Đọc README: 10'] → [2 Đọc các file còn lại: 15']
→ [3 Xâu chuỗi việc cần làm: 20'] ← BOTTLENECK → [4 Bắt đầu task đầu tiên]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần làm một thao tác git mà không nhớ lệnh, tôi muốn biết đúng lệnh cần chạy, để đẩy được bài lên GitHub mà không phải dừng lại tra lệnh |
| Actor | Học viên phải đẩy bài lab lên GitHub, chưa nhớ lệnh git |
| Thời điểm / bối cảnh | Khi làm xong bài và cần đẩy lên GitHub |
| Quy trình hiện tại (3–7 bước) | 1. Tra hoặc hỏi lệnh add, commit, push: 3–5' · 2. Chạy lệnh · 3. Mở GitHub kiểm tra bài đã lên (bước 2 và 3 tổng cộng 1'). Số phút là ước lượng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1, tra hoặc hỏi lệnh: 3–5' mỗi lần |
| Impact (nếu không giải thì sao) | 3–5 lần/tuần × 3–5 phút, khoảng 9–25 phút/tuần, và bị ngắt việc mỗi lần đẩy bài |
| Success metric (baseline → target) | Số lần phải tra lệnh từ 3–5 lần/tuần xuống 0 lần/tuần, đo bằng cách tự đếm trong 2 tuần |
| Phương án không dùng AI | Viết sẵn một script, chạy một lệnh là đẩy xong |
| Giả thuyết về AI (nếu có) | Không cần thêm: hiện đã hỏi AI để tra lệnh, script có thể giải được việc này |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI: khoảng 4–6 phút mỗi lần đẩy bài (ước lượng)

[1 Tra hoặc hỏi lệnh: 3–5'] ← BOTTLENECK → [2 Chạy lệnh] → [3 Kiểm tra trên GitHub]
(bước 2 và 3 tổng cộng 1')
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đang trên đường đến lớp và gặp tắc đường, tôi muốn đảm bảo đến đúng giờ, để không bị mất điểm danh |
| Actor | Học viên đi học bằng tàu điện và xe buýt, phải có mặt lúc 9h |
| Thời điểm / bối cảnh | Buổi sáng đi học, thường xuất phát lúc 7h30 |
| Quy trình hiện tại (3–7 bước) | 1. Chuẩn bị trước khi đi: 30' · 2. Đoạn đường 1: 30' · 3. Đoạn đường 2: 75' · 4. Từ điểm xuống đến lớp: 10'. Số phút là ước lượng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đoạn đường dài nhất: 75'. Khi tắc ở đường Nguyễn Trãi mất thêm khoảng 20'. Giờ xuất phát 7h30 không có thời gian dự phòng cho khoản này |
| Impact (nếu không giải thì sao) | Muộn 2 lần/tuần, bị mất điểm danh |
| Success metric (baseline → target) | Số lần đi muộn từ 2 lần/tuần xuống 0 lần/tuần, đo bằng cách ghi giờ đến lớp trong 2 tuần |
| Phương án không dùng AI | Phương án tính theo các ước lượng đang có: nếu cần 135 phút di chuyển thì rời nhà 6h30 sẽ đến khoảng 8h45, có 15 phút dự phòng trước 9h. Rời 6h45 chỉ vừa đúng 9h, chưa có dự phòng. Đây là kế hoạch cần kiểm bằng giờ đến thật, không phải kết quả đã thực hiện. |
| Giả thuyết về AI (nếu có) | Không có, vì đi sớm hơn đã giải được phần lớn |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
HIỆN TẠI: 115 phút từ lúc rời nhà, 135 phút nếu tắc (chưa tính 30' chuẩn bị)

[Chuẩn bị: 30'] → [Đoạn 1: 30'] → [Đoạn 2: 75'] ← BOTTLENECK → [Từ điểm xuống đến lớp: 10']

Khi tắc ở Nguyễn Trãi: thêm khoảng 20'
```

Kiểm tra tính nhất quán: 7h30 + 115 phút = 9h25; 7h30 + 135 phút = 9h45. Vì vậy các con số hiện tại chưa giải thích được vì sao chỉ muộn 2 lần/tuần. Giữ các mốc này là ước lượng cần xác nhận, không tự đổi giờ thực tế hoặc tần suất để làm khớp câu chuyện.

### Card muốn pitch nhất

- Card số: 1 (định hình đề lab)
- Vì sao: Bước nghẽn cụ thể (xâu chuỗi việc cần làm, 20 phút), và cùng một đề nên có thể kiểm chứng với bạn cùng lớp. Ở Lab1, tôi 4 tiếng chỉ xong 1/5 task.
- Câu hỏi muốn nhóm phản biện: Đọc RUBRIC và CHECKPOINTS trước đã đủ để biết phần nào quan trọng và làm theo thứ tự nào chưa, hay vẫn kẹt ở bước xâu chuỗi?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #3: bước nghẽn có thể là giờ xuất phát không có dự phòng, không chỉ là tắc đường | Đồng ý | Thêm phương án xuất phát sớm hơn vào ô "Phương án không dùng AI", đổi cảm nhận nhanh thành No AI |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Đối chiếu chung: Linh đã xác nhận chọn Card #1 của Mạnh về chọn món phù hợp lời dặn ăn uống; xem [báo cáo nhóm](../team/group_report.md). No AI/Rule là hướng thử đề xuất, quyết định phân tích Not Yet. Các ô dưới đây chờ Khánh ghi hoạt động đã thực sự làm. [Phân công trong TEAM.md](../../TEAM.md) là đề xuất cho bước tiếp theo, không phải công việc đã hoàn thành.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

<!-- CP3_AI_REVIEW_START -->
### 4.1. CP3 

[Bản chuẩn 15 cặp câu hỏi / trả lời](../assets/cp3-phien-phan-bien-ai-uy-quyen.md). Các dòng dưới là vai Khánh.

| ID | Vai hỏi | Vai trả lời | Card | Câu hỏi phản biện | Câu trả lời theo vai | Thay đổi đề xuất |
|---|---|---|---|---|---|---|
| P03 | Khánh | Linh | L3 — Chốt việc sau họp | Hai việc thiếu người phụ trách là chưa được phân công hay đã phân công nhưng biên bản ghi thiếu? | Chưa có dữ liệu phân biệt. Vì vậy cần tách trạng thái chưa phân công với chưa ghi nhận; người có liên quan xác nhận trước khi chốt. Không tự thêm tên cho đủ bảng. Khoảng 45 phút cũng cần đo riêng tổng hợp và chờ xác nhận. | Thêm bước xác nhận việc–người–hạn, trạng thái chưa chốt và cách đo thời gian. |
| P06 | Khánh | Mạnh | M3 — Ghi lý do thức ăn thừa | Actor chính là người hỏi/ghi hay người dùng dữ liệu, và giảm thời gian ghi có làm mất lý do quan trọng không? | Với phạm vi giảm thao tác hỏi/ghi, actor chính tạm chọn người thực hiện bước ghi; nhân viên dinh dưỡng là người dùng đầu ra. Vai trò cụ thể tại cơ sở còn phải xác nhận. Phiếu chọn sẵn có mục khác và không trả lời để tránh đoán lý do. | Tách actor chính/người nhận đầu ra; đo tỷ lệ ghi nhận cùng thời gian; giữ phản hồi tự do. |
| P07 | Linh | Khánh | K1 — Hiểu đề lab | Mất 45 phút định hình đề có chứng minh đó là nguyên nhân khiến 4 giờ chỉ xong 1/5 task không? | Chưa chứng minh quan hệ nguyên nhân. Còn có thể do độ khó thao tác hoặc kỹ năng. Cần đo riêng thời gian định hình, thực hiện và sửa lỗi; thử đọc rubric/checkpoint trước rồi so sánh các lab có phạm vi tương đương. | Không suy ra toàn bộ tiến độ chậm do đọc đề; giữ các phần thời gian riêng. |
| P08 | Mạnh | Khánh | K2 — Tra lệnh Git | Nếu dùng script thay tra lệnh, làm sao tránh đẩy nhầm nhánh hoặc đưa cả file không định nộp lên repo? | Script chỉ là Rule hỗ trợ thao tác. Vẫn cần xem trạng thái, nhánh, remote và chọn file; dừng khi có xung đột hoặc khác trạng thái mong đợi. Không dùng mục tiêu không tra lệnh để bỏ qua kiểm tra trước khi đẩy bài. | Thêm bước kiểm trạng thái và chọn file, không tự stage/push mọi thay đổi. |
| P09 | Chủ | Khánh | K3 — Đi học đúng giờ | Rời 7h30 và đi 115 phút sẽ tới 9h25; tại sao chỉ muộn 2 lần/tuần? | Các ước lượng chưa thống nhất nên chưa thể giải thích tần suất muộn. Cần đối chiếu giờ rời nhà/đến thật theo từng ngày. Nếu giả định đường đi mất 135 phút, kế hoạch rời 6h30 cho giờ đến 8h45 là phép tính dự phòng, không phải lịch sử đã thực hiện. | Ghi rõ mâu thuẫn và nguồn cần đo; không tự đổi số quá khứ để làm khớp. |
| P10 | Khánh | Chủ | C1 — Xác minh chuyển tiền | Vì sao không kết luận ngay một tin nhắn là lừa đảo hoặc an toàn từ các dấu hiệu nội dung? | Nội dung chỉ nêu điều cần kiểm, không xác thực được danh tính. Đầu ra cần là nguồn đối chiếu độc lập và trạng thái chưa xác minh khi thiếu bằng chứng; AI không xác nhận an toàn để chuyển tiền hoặc thực hiện giao dịch. | Giữ đầu ra hỗ trợ xác minh, không phân loại chắc chắn chỉ bằng văn bản. |
| P14 | Khánh | Mạnh | M1 — Dữ liệu và phiên bản | Nếu món thiếu thông tin thành phần hoặc chế độ ăn vừa thay đổi, hệ thống có tự ước tính hoặc tiếp tục dùng danh sách cũ không? | Không. Dữ liệu thiếu/cũ phải chuyển người phụ trách xác nhận; không tự suy đoán thành phần, dị ứng hoặc đổi chế độ ăn. Chưa có nguồn cập nhật và người duyệt là lý do giữ Not Yet cho triển khai. | Bổ sung chặn dữ liệu thiếu/cũ, kiểm phiên bản và đường quay về người hỗ trợ. |

<!-- CP3_AI_REVIEW_END -->

### 4.2. CP4–CP5 

| Phần | Đầu ra và nguồn | Trạng thái |
|---|---|---|
| CP4 | [Research, sáu giả định, chín câu hỏi và kế hoạch kiểm chứng](../assets/cp4-research-va-ke-hoach-kiem-chung-ai.md) | Đã mở lại R0–R3; chưa có phỏng vấn/survey người thật |
| CP5 | [Quy trình, metric, v0 và sáu phản biện](../assets/cp5-quy-trinh-va-phan-bien-ai.md) | Có mô hình sáu → năm bước, 20 → 14 phút thao tác tổng hợp; chi phí chuẩn bị tính riêng; chưa có số đo tại cơ sở |

Phần thao tác mô hình có thể dùng để hiểu cách tính và đối chiếu sơ đồ; việc tài liệu tồn tại chưa chứng minh Khánh đã thực hiện kiểm tra. Kết quả phân tích vẫn Not Yet.

<!-- CP6_CP7_AI_START -->
### 4.3. CP6 và CP7

[CP6: No AI, Not Yet, v1, rủi ro và gate chất lượng](../assets/cp6-phan-tich-va-quyet-dinh-ai.md). [Kết quả kiểm fixture](../assets/cp6-ket-qua-kiem-tra-fixture.json) chỉ kiểm logic tài liệu; không phải kết quả sản phẩm.



[Checklist trạng thái hoàn tất](../assets/cp7-checklist-hoan-tat-va-trang-thai.md) phân biệt đầu ra AI và bằng chứng chưa có.
<!-- CP6_CP7_AI_END -->

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

<!-- CP7_AI_REFERENCE -->


Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Khung để tự giải thích: bệnh nhân có lời dặn đã xác nhận → đọc/đối chiếu món → baseline 20 phút còn cần kiểm đơn vị và đo lại → target sau đo, có kiểm chất lượng → không suy đoán phần thiếu hoặc tự đặt món → thử No AI rồi Rule → Not Yet vì thiếu kiểm chứng và dữ liệu cơ sở. Card đi học/Git của cá nhân vẫn ở CP2, không dùng làm kết quả nhóm trong 6.7.

---

## 7. Tài liệu tham khảo

-
