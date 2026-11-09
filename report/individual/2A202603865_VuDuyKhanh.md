# Báo cáo cá nhân — 2A202603865_VuDuyKhanh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Duy Khánh
- MSSV: 2A202603865
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repo nhóm:

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
| Phương án không dùng AI | Xuất phát sớm hơn: rời nhà lúc 6h45 thì kịp 9h ngay cả ngày tắc |
| Giả thuyết về AI (nếu có) | Không có, vì đi sớm hơn đã giải được phần lớn |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
HIỆN TẠI: 115 phút từ lúc rời nhà, 135 phút nếu tắc (chưa tính 30' chuẩn bị)

[Chuẩn bị: 30'] → [Đoạn 1: 30'] → [Đoạn 2: 75'] ← BOTTLENECK → [Từ điểm xuống đến lớp: 10']

Khi tắc ở Nguyễn Trãi: thêm khoảng 20'
```

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

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
