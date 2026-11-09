# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:Nguyễn Lê Trọng Mạnh
- MSSV:2A202603857
- Email trường (không bắt buộc, repo có thể để public): 26ai.manhnlt@vinuni.edu.vn
- Tên nhóm: A90
- Link repo nhóm:

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Khi gần tới giờ ăn, bệnh nhân muốn biết ngay hôm nay canteen có món gì, để chọn món mà không phải gọi điện hỏi |Bệnh nhân; Người trực căn tin |1-2phút/cuộc bệnh nhân có thể có 3 cuộc 1 ngày còn nhân viên căn tin có khả năng 30-40 cuộc 1 ngày |
| 2 |Tốn thời gian | Khi chưa biết mình được ăn và phải kiêng gì, bệnh nhân muốn biết nhanh món phù hợp, để đặt món mà không phải chờ hỏi điều dưỡng|Bệnh nhân; điều dưỡng trực ca | 10-15 phút/lần bệnh nhân; 3-4 lần/ca điều dưỡng|
| 3 | Tốn thời gian| Khi bệnh nhân hỏi một câu cần dựa vào tình trạng của họ, điều dưỡng muốn xem nhanh tiền sử và dị ứng liên quan, để trả lời đúng mà không phải mở lại cả bệnh án | Điều dưỡng; bệnh nhân chờ | 10-15 phút/lần bệnh nhân; 3-4 lần/ca điều dưỡng  |
| 4 | Cần đọc, tổng hợp | Khi đã biết lời dặn ăn uống và đứng trước nhiều món, bệnh nhân muốn biết nhanh món nào phù hợp, để chọn tự tin mà không phải đọc kỹ từng món | Bệnh nhân | Khoảng 20 phút |
| 5 | Pain từ người khác | Khi nhận đơn món, nhân viên bếp/dinh dưỡng muốn biết nhanh đơn có khớp y lệnh không, để giao đúng món mà không phải hỏi lại | Nhân viên bếp/dinh dưỡng; bệnh nhân | Khoảng 10 phút |
| 6 | Cần đọc, tổng hợp | Khi bệnh nhân bỏ thừa thức ăn, nhân viên dinh dưỡng muốn nắm lý do (món, giờ giao, khẩu vị, tình trạng), để điều chỉnh phục vụ | Điều dưỡng | Khoảng 2 phút/lần mỗi bệnh nhân; 3-4 lần mỗi ca  |
| 7 | Pain từ người khác | Khi bác sĩ đổi y lệnh ăn uống, bệnh nhân và người nhà muốn được báo ngay, để không ăn hoặc nhận nhầm món cũ | Bệnh nhân, người nhà; điều dưỡng | 5 phút từ bác sĩ đến điều dưỡng, 5 phút từ điều dưỡng đến bệnh nhân |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.
| # | Ý | Nguồn | Giữ / Bỏ | Lý do |
|---:|---|---|---|---|
| 1 | Nhân viên bếp/dinh dưỡng đối chiếu đơn món với y lệnh | AI gợi ý | Giữ | Bổ sung góc nhìn phía bếp mà các ý trước chưa có. Actor và quy trình rõ, liên quan an toàn người bệnh. |
| 2 | Thức ăn bệnh nhân bỏ thừa và lý do | AI gợi ý | Giữ | Là hậu quả cuối của cả chuỗi.|
| 3 | Bác sĩ đổi y lệnh ăn, bệnh nhân và người nhà được báo | AI gợi ý | Giữ | Liên quan an toàn người bệnh.|
| 4 | Điều dưỡng nhập hoặc chuyển thông tin chế độ ăn của bệnh nhân | AI gợi ý | **Bỏ** | Chồng với ý 5 và 7 (cùng là thông tin chế độ ăn đi qua nhiều bước). Tôi chưa quan sát được bước này nên không có số liệu |

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Ý 4: Bệnh nhân đã biết lời dặn ăn uống nhưng phải đọc kỹ từng món để chọn | Là bước cuối bệnh nhân phải qua trước khi đặt món, ảnh hưởng trực tiếp đến việc ăn đúng chế độ | Mỗi bữa hay mỗi ngày; chưa biết thực đơn có ghi thành phần không |
| 2 | Ý 7: Bác sĩ đổi y lệnh ăn uống, thông tin đến điều dưỡng và bệnh nhân bị chậm | Liên quan an toàn người bệnh (tránh ăn hoặc nhận nhầm món cũ), có số đo độ trễ (5 phút bác sĩ đến điều dưỡng, 5 phút điều dưỡng đến bệnh nhân) | 10 phút là độ trễ chứ không phải thời gian làm việc; chưa có ví dụ thật món cũ vẫn được giao; chưa biết tần suất đổi y lệnh |
| 3 | Ý 6: Thức ăn bệnh nhân bỏ thừa và lý do | Là hậu quả cuối của cả chuỗi; có số (2 phút/lần, 3-4 lần/ca) | Cần chốt ai là người ghi lý do bỏ thừa (điều dưỡng hay nhân viên dinh dưỡng); chưa biết Vinmec có ghi nhận không |


### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đã biết lời dặn ăn uống và đứng trước nhiều món, bệnh nhân muốn biết nhanh món nào phù hợp, để chọn tự tin mà không phải đọc kỹ từng món |
| Actor | Bệnh nhân nội trú (người chọn món) |
| Thời điểm / bối cảnh | Trước mỗi bữa ăn, khi chọn hoặc đặt món |
| Quy trình hiện tại (nháp, cần xác nhận) | 1. Nhận lời dặn ăn uống từ điều dưỡng · 2. Xem thực đơn hôm nay · 3. Đọc thành phần từng món · 4. Tự đối chiếu với lời dặn · 5. Đắn đo, có thể hỏi lại · 6. Đặt món |
| Bottleneck | Bước 3-5: đọc và đối chiếu từng món, khoảng 20 phút (số của tôi, chưa rõ mỗi bữa hay mỗi ngày) |
| Impact | Mất thời gian của bệnh nhân; nếu chọn sai có thể ăn món không hợp chế độ. Tần suất và số bệnh nhân: cần đo |
| Success metric | Baseline: khoảng 20 phút (cần đo lại, ghi rõ mỗi bữa hay mỗi ngày). Target đề xuất: giảm đáng kể thời gian chọn món, đặt sau khi có baseline. Chỉ số an toàn: số món giao không khớp chế độ không tăng |
| Phương án không dùng AI | Thực đơn ghi sẵn nhãn chế độ ăn phù hợp (ví dụ ít muối, đái tháo đường) ngay cạnh từng món |
| Giả thuyết về AI | AI lọc và giải thích các món phù hợp từ chế độ ăn đã được bác sĩ hoặc điều dưỡng xác nhận; người có chuyên môn duyệt |
| Cảm nhận nhanh | No AI hoặc Workflow (nếu nhãn thực đơn chưa đủ) |


Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi bác sĩ đổi y lệnh ăn uống, bệnh nhân và người nhà muốn được báo ngay, để không ăn hoặc nhận nhầm món cũ |
| Actor | Điều dưỡng (người chuyển thông tin); bệnh nhân và người nhà (người nhận) |
| Thời điểm / bối cảnh | Sau khi bác sĩ đổi chế độ ăn, trước bữa ăn kế tiếp |
| Quy trình hiện tại (nháp, cần xác nhận) | 1. Bác sĩ đổi y lệnh · 2. Thông tin đến điều dưỡng (khoảng 5 phút) · 3. Điều dưỡng báo bệnh nhân/người nhà (khoảng 5 phút) · 4. Bộ phận dinh dưỡng/bếp biết chế độ mới (chưa rõ bằng cách nào) · 5. Giao món theo chế độ mới |
| Bottleneck | Bước 2-3: tổng độ trễ khoảng 10 phút. Bước 4 chưa rõ, cần hỏi |
| Impact | Nếu có bữa ăn giao trong khoảng trễ, bệnh nhân có thể nhận hoặc ăn món cũ. Chưa có ví dụ thật; tần suất đổi y lệnh: cần đo |
| Success metric | Baseline: khoảng 10 phút từ bác sĩ đến bệnh nhân (cần đo thêm). Target đề xuất: rút ngắn độ trễ; số món giao theo chế độ cũ sau khi đổi y lệnh bằng 0 |
| Phương án không dùng AI | Chuẩn hóa một kênh báo duy nhất và bảng ghi chế độ ăn mới tại giường |
| Giả thuyết về AI | Chưa thấy cần AI. Bài toán chủ yếu là báo đúng người đúng lúc, nên có thể giải bằng thông báo tự động theo quy tắc |
| Cảm nhận nhanh | Rule hoặc No AI |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi bệnh nhân bỏ thừa thức ăn, nhân viên dinh dưỡng muốn nắm lý do (món, giờ giao, khẩu vị, tình trạng), để điều chỉnh phục vụ |
| Actor | Điều dưỡng (người hỏi và ghi); nhân viên dinh dưỡng (người dùng thông tin). Cần chốt ai là actor chính |
| Thời điểm / bối cảnh | Sau mỗi bữa, khi thu khay |
| Quy trình hiện tại (nháp, cần xác nhận) | 1. Thu khay, thấy thừa · 2. Hỏi bệnh nhân lý do · 3. Ghi nhận (chưa rõ nơi ghi) · 4. Chuyển cho bộ phận dinh dưỡng (chưa rõ có không) |
| Bottleneck | Bước 2-3: khoảng 2 phút/lần mỗi bệnh nhân, 3-4 lần/ca (tương đương khoảng 6-8 phút/ca) |
| Impact | Không biết lý do thì không điều chỉnh được thực đơn hoặc giờ giao; bệnh nhân ăn ít khó hồi phục. Tỷ lệ thừa tại Vinmec: cần đo |
| Success metric | Baseline: khoảng 2 phút/lần, 3-4 lần/ca. Target đề xuất: giảm thời gian ghi, tăng tỷ lệ lần thừa có ghi lý do. Cần đo hiện tại có bao nhiêu % được ghi |
| Phương án không dùng AI | Phiếu chọn sẵn lý do (món, giờ giao, khẩu vị, bệnh) để đánh dấu nhanh |
| Giả thuyết về AI | AI gom nhóm các lý do ghi dạng tự do và chỉ ra xu hướng cho bộ phận dinh dưỡng; chỉ dùng khi đã có dữ liệu ghi nhận |
| Cảm nhận nhanh | Rule hoặc Workflow |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số: 1
- Vì sao:
1. **So sánh được cả 4 mức can thiệp.** Ý này có thể giải bằng No AI (nhãn chế độ ăn ngay trên thực đơn), Rule (lọc món theo chế độ ăn), Workflow (AI giải thích món phù hợp, người có chuyên môn duyệt). Agent bị loại vì quá rộng. Card 2 gần như chỉ có No AI hoặc Rule nên khó thấy vai trò của AI.
2. **Actor rõ.** Bệnh nhân là người chịu pain trực tiếp ở mỗi bữa ăn.
3. **Kiểm soát rủi ro được.** AI chỉ lọc từ chế độ ăn đã được bác sĩ hoặc điều dưỡng xác nhận, không tự quyết định chế độ ăn hay dị ứng.
- Câu hỏi muốn nhóm phản biện:
1. Nếu thực đơn hiện tại đã ghi nhãn chế độ ăn cho từng món, pain này còn đáng giải không, hay chỉ cần No AI?
2. "Khoảng 20 phút" là mỗi bữa hay mỗi ngày? Nhóm sẽ đo thế nào để con số đáng tin trong thời gian ngắn?
3. Ai nên là người duyệt cuối (điều dưỡng, chuyên viên dinh dưỡng, hay bác sĩ), và boundary "AI chỉ lọc từ chế độ ăn đã xác nhận" đã đủ chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 20 phút mới là ước lượng, chưa rõ mỗi bữa hay mỗi ngày | Đồng ý | Ghi rõ là ước lượng trong card; lên kế hoạch hỏi 3-5 bệnh nhân để đo lại |
| Thực đơn có thể đã ghi nhãn chế độ ăn, khi đó No AI là đủ | Đồng ý | Đưa No AI thành phương án đầu tiên; thêm việc xem một thực đơn thật trước khi chốt |
| AI lọc từ chế độ ăn "đã xác nhận" nhưng chưa biết dữ liệu này có ở dạng dùng được không (Feasibility) | Đồng ý | Thêm vào danh sách cần xác nhận: chế độ ăn của bệnh nhân được lưu ở đâu, ở dạng nào |
| Metric chỉ đo thời gian, không đo an toàn: nhanh hơn nhưng chọn sai thì sao | Đồng ý | Đã thêm chỉ số an toàn trong card: số món giao không khớp chế độ không tăng |
| Bệnh nhân đang bệnh, lớn tuổi hoặc mệt có thể khó tự dùng công cụ (Usability) | Đồng ý một phần | Ghi nhận rủi ro; giả định có người nhà hoặc điều dưỡng hỗ trợ khi cần, cần kiểm lại với bệnh nhân thật |
| AI có thể bịa giải thích "vì sao món này phù hợp" | Đồng ý | Thêm vào boundary: AI chỉ dùng thành phần có trong thực đơn, không đưa nhận định y khoa |


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
