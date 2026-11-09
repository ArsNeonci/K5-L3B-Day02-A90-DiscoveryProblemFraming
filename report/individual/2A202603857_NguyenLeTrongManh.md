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
| 3 | Ý 6: Thức ăn bệnh nhân bỏ thừa và lý do | Là hậu quả cuối của cả chuỗi; có số (2 phút/lần, 3-4 lần/ca) | Cần chốt ai là người ghi lý do bỏ thừa (điều dưỡng hay nhân viên dinh dưỡng); chưa biết bệnh viện có ghi nhận không |


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

```
[1 Nhận lời dặn ăn uống] → [2 Xem thực đơn hôm nay]
→ [3 Đọc thành phần từng món]        ← BOTTLENECK
→ [4 Tự đối chiếu với lời dặn]       ← BOTTLENECK
→ [5 Đắn đo, hỏi lại nếu cần]        ← BOTTLENECK
→ [6 Đặt món]

Bước 3-5: khoảng 20 phút (ước lượng)

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

```
[1 Bác sĩ đổi y lệnh ăn uống]
→ [2 Thông tin đến điều dưỡng: ~5']        ← BOTTLENECK
→ [3 Điều dưỡng báo bệnh nhân/người nhà: ~5'] ← BOTTLENECK
→ [4 Bếp/dinh dưỡng biết chế độ mới: chưa rõ cách nào]
→ [5 Giao món theo chế độ mới]

Tổng độ trễ: khoảng 10 phút (độ trễ, không phải thời gian làm việc)

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

```
[1 Thu khay, thấy thức ăn thừa]
→ [2 Hỏi bệnh nhân lý do: ~2'/lần]   ← BOTTLENECK
→ [3 Ghi nhận: chưa rõ ghi ở đâu]     ← BOTTLENECK
→ [4 Chuyển cho bộ phận dinh dưỡng: chưa rõ có không]

3-4 lần/ca, tương đương khoảng 6-8 phút/ca

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
| Pitch Problem Card | Trình bày card "bệnh nhân chọn món phù hợp lời dặn ăn uống" và lập luận vì sao nên chọn: actor rõ (bệnh nhân), quy trình rõ, so sánh được 4 mức can thiệp, phạm vi kiểm soát được khi chỉ dùng chế độ ăn đã được xác nhận. Khi nghe pitch của bạn khác, tôi hỏi sâu vào problem, đặc biệt là chỗ nào khó triển khai và không khả thi. | Nhóm chọn ý tưởng này và ưu tiên hướng ít rủi ro, dễ kiểm soát. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Bạn lấy dữ liệu ở đâu, bên nào chịu trách nhiệm cung cấp? (2) Có rủi ro nào quá lớn không, có chấp nhận đánh đổi không? | Giúp nhóm làm rõ actor và nguồn dữ liệu của candidate đó trước khi chấm điểm, và ưu tiên ý ít rủi ro, dễ triển khai. |
| Nhận phản biện | Câu hỏi tôi nhận: (1) Có tiết kiệm thời gian thật không? (2) Thay thế bộ phận nào? Tôi đã sửa: thừa nhận con số 20 phút mới là ước lượng cần đo lại; làm rõ hướng là hỗ trợ người có chuyên môn chứ không thay thế điều dưỡng hay bộ phận dinh dưỡng; thêm chỉ số an toàn bên cạnh chỉ số thời gian; chuyển từ "đề xuất món theo bệnh án" sang "lọc và giải thích dựa trên chế độ ăn đã xác nhận". | Đổi cách nhìn bài toán, từ giải pháp rộng sang một vấn đề hẹp có boundary rõ. |
| Gom cluster / cây OST | Research các problem nhóm đưa ra và tìm câu hỏi phản biện cho từng cái; chỉ ra các ý cùng một pattern (thông tin chế độ ăn không đến đúng người đúng lúc). | Giúp nhóm hiểu sâu hơn về pain point và tách pain khỏi giải pháp. |
| Chọn candidate problem | Đề xuất các candidate có tiềm năng nhất sau giai đoạn pitch và phản biện, kèm lý do. | Góp phần để nhóm chọn được phương án có thể triển khai. |
| Kiểm chứng / research | Research pain point và nghiệp vụ đặt món, chế độ ăn nội trú; tìm các hệ thống đã có (CBORD, Epic MyChart Bedside, Computrition) và nhận ra phần lọc món theo chế độ ăn thường giải bằng Rule, không phải AI. | Giúp nhóm đi nhanh hơn, tránh xây lại thứ đã có, và cân nhắc thu hẹp vai trò của AI. |
| Quy trình nhóm | Tham gia đầy đủ các bước; góp phần tìm rủi ro của từng problem (dữ liệu bệnh án nhạy cảm, nguồn dữ liệu chế độ ăn, ai duyệt cuối). | Nhóm có nhiều góc nhìn hơn về pain point và rủi ro. |
| Problem Statement | Đóng góp 3 problem card (bệnh nhân chọn món, đổi y lệnh ăn uống, ghi nhận thức ăn bỏ thừa) vào ngân hàng ý tưởng của nhóm. | Nhóm có nhiều lựa chọn để cân nhắc. |
| Mức can thiệp AI | Cân nhắc 4 mức: No AI (nhãn chế độ ăn trên thực đơn), Rule (lọc theo chế độ ăn), Workflow (AI giải thích, người duyệt), Agent (loại vì quá rộng). Tôi dùng AI khoảng 35% công việc (ước lượng của tôi) chủ yếu để phản biện pain point của mình. | Hiểu vấn đề rõ hơn và có cơ sở giải thích, phản biện lại nhóm. |
| Quyết định | Chọn ý tưởng hợp lý nhất trong ngân hàng problem; ghi rõ điều kiện cần kiểm trước khi triển khai (đo baseline, xem thực đơn thật, xác nhận nguồn dữ liệu chế độ ăn). | Giúp nhóm cân nhắc thêm về kế hoạch triển khai. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Viết lại các ý thô thành Job Story, hỏi câu để làm rõ số liệu, gợi ý thêm góc nhìn (bếp, dinh dưỡng, đổi y lệnh, thức ăn bỏ thừa), tìm tài liệu tham khảo về đặt món và thức ăn thừa ở bệnh viện | Chỉ ra chỗ số liệu còn mơ hồ (của ai, mỗi bữa hay mỗi ngày), nhắc các góc nhìn tôi chưa dùng, đưa tài liệu tham khảo | Các ý AI gợi ý (bếp đối chiếu y lệnh, đổi y lệnh, thức ăn bỏ thừa, điều dưỡng chuyển thông tin chế độ ăn) ban đầu không có dữ kiện nào từ Vinmec, chỉ là lập luận. Tìm kiếm không thấy trang công khai nào mô tả cách bệnh nhân Vinmec xem thực đơn hoặc đặt món, nên quy trình trong Job Story vẫn phải tự xác nhận | Tự nghĩ 4 ý đầu, bổ sung số liệu cho cả 7 ý, sửa số của ý 2 (từ 30-40 xuống 10-15 phút), bỏ ý "điều dưỡng nhập hoặc chuyển thông tin chế độ ăn" |
| CP2 Problem Card | Chấm điểm sơ bộ, soạn khung Problem Card, soạn bảng phản biện | Chỉ ra ý 2 và ý 3 cùng số liệu nên dễ đếm đôi, chỉ ra ý đổi y lệnh có thể không cần AI, nhắc thêm chỉ số an toàn bên cạnh chỉ số thời gian | Quy trình hiện tại trong card là giả thuyết AI dựng từ lời kể của tôi, chưa kiểm với điều dưỡng. Điểm chấm 27/23/20 là ước lượng của AI. Top 3 AI đề xuất ban đầu khác với lựa chọn của tôi | Chọn lại top 3 theo ưu tiên của mình (ý 4, 6, 7), chọn card muốn pitch, chọn lý do nào giữ hoặc bỏ |
| CP4 Research | Tìm công cụ và case tương tự về đặt món theo chế độ ăn ở bệnh viện; soạn assumption map nháp và bộ câu hỏi phỏng vấn theo The Mom Test | Tìm ra các hệ thống đã có (CBORD, Epic MyChart Bedside, Computrition, Scottsdale) và chỉ ra họ giải phần lọc món bằng Rule gắn với dữ liệu chế độ ăn, không phải AI | Một link tìm được (Alton Memorial) mở ra trang không liên quan nên bị loại. Nhiều nguồn là trang quảng cáo của nhà cung cấp, không có số kết quả. Bài Scottsdale là năm 2008. Điểm assumption map do AI chấm nháp. Không tìm được tài liệu công khai nào về cách bệnh nhân Vinmec đặt món | *(bạn điền)* |
| CP5 Quy trình | Dựng sơ đồ quy trình hiện tại (6 bước) và tương lai (5 bước) cho ý 4, đề xuất vị trí đặt Rule, AI và người duyệt | Ra nhanh khung quy trình và chỉ ra bước 3-5 là bottleneck | Quy trình hiện tại là giả thuyết dựng từ lời kể của tôi, chưa kiểm với điều dưỡng hay bệnh nhân. Chưa có baseline đo thật nên không đặt được target | *(bạn điền)* |
| CP5–6 Problem Statement | Soạn Problem Statement v0 từ các dữ kiện tôi cung cấp | Gom đủ 6 trường và chỉ ra chỗ còn trống (baseline, tần suất) | Metric ban đầu chỉ có thời gian, chưa có chất lượng; vai trò của AI ở bước giải thích chưa được kiểm chứng sau research | ✎ Thêm chỉ số an toàn (món không khớp chế độ ăn không tăng) và giữ boundary: AI không tự quyết định chế độ ăn hay dị ứng |
| CP6 Mức can thiệp / quyết định | Phân tích 4 mức No AI / Rule / Workflow / Agent, trả lời câu hỏi PAIR, đánh giá 4 rủi ro và đề xuất Go có điều kiện kèm pilot và ngưỡng dừng | Chỉ ra phần lọc món nên là Rule, Feasibility là rủi ro cao vì cần dữ liệu thành phần món, và đưa ngưỡng dừng cụ thể | Mức rủi ro AI chấm chưa dựa trên dữ liệu Vinmec; chưa biết thực đơn đã có nhãn chưa nên quyết định còn có điều kiện | ✎ Chấm lại mức rủi ro theo hiểu biết của nhóm, chọn mức can thiệp nhóm đồng ý, và quyết định có đi tiếp pilot hay không |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe pitch của các bạn, tôi nhận ra những ý tưởng thiếu actor rõ hoặc chưa biết lấy dữ liệu từ đâu thì rất khó đi tiếp. Vì vậy tôi hỏi các bạn: đối tượng chính là ai, dữ liệu lấy ở đâu, bên nào chịu trách nhiệm cung cấp, và có chấp nhận đánh đổi rủi ro không. Tôi cũng thấy mình hay chọn problem theo độ hấp dẫn, trong khi nhóm nên ưu tiên problem có dữ liệu thật và đo được.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có. Lập luận ban đầu của tôi cho ý 4 là "bệnh nhân nhận đề xuất món ăn dựa theo bệnh án". Đó là một giải pháp, chưa phải vấn đề, và còn quá rộng vì "bệnh án" kéo theo dữ liệu y tế nhạy cảm. Tôi nhận ra khi đối chiếu với yêu cầu tách opportunity khỏi solution. Tôi viết lại thành vấn đề: bệnh nhân đã biết lời dặn ăn uống nhưng khó biết nhanh món nào phù hợp, và giới hạn phạm vi ở chế độ ăn đã được xác nhận.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Tôi nhận ba câu hỏi: lợi nhuận thực tế có tăng không, có tiết kiệm thời gian thật không, và thay thế bộ phận nào. Sau đó tôi đổi cách nhìn: con số 20 phút mới là ước lượng nên cần đo lại; AI hỗ trợ người có chuyên môn chứ không thay thế điều dưỡng hay bộ phận dinh dưỡng; và tôi thêm chỉ số an toàn bên cạnh chỉ số thời gian (số món không khớp chế độ ăn không được tăng).

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Có, ở phần research. Tôi thấy các bệnh viện khác giải phần lọc món theo chế độ ăn chủ yếu bằng quy tắc gắn với dữ liệu chế độ ăn của bệnh nhân, không dùng AI, và khoản tốn nhất là xây dữ liệu thành phần món (một bệnh viện mất 18 tháng). Vì vậy tôi thu hẹp vai trò của AI về khâu giải thích hoặc ước tính thành phần khi thiếu dữ liệu.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là tách vấn đề khỏi giải pháp và giữ các con số trung thực. Nhiều con số của tôi (như 20 phút) mới là ước lượng, chưa phải số bấm giờ thật, nên tôi phải ghi rõ nguồn của từng số và chưa dám đặt target khi chưa có baseline đo được. Phần boundary cũng khó, vì bài liên quan dữ liệu y tế và phải xác định ai duyệt cuối.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Tôi sẽ xem một thực đơn thật và hỏi vài điều dưỡng hoặc bệnh nhân trước khi chốt card, vì hai giả định quan trọng nhất (thực đơn chưa ghi nhãn chế độ ăn, và dữ liệu chế độ ăn lấy được ở dạng dùng được) vẫn chưa được kiểm chứng. Tôi cũng sẽ phản biện nhóm mạnh hơn ở câu hỏi: card nào thật sự cần AI, và card nào có thể giải bằng nhãn hoặc quy tắc.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Vấn đề của nhóm là bệnh nhân nội trú Vinmec đã biết lời dặn ăn uống nhưng vẫn phải đọc thành phần từng món rồi tự đối chiếu, khoảng 20 phút theo ước lượng chưa đo. Quy trình hiện tại gồm nhận lời dặn, xem thực đơn, đọc thành phần, đối chiếu, hỏi lại nếu cần, rồi đặt món; điểm nghẽn là bước đọc và đối chiếu. Metric là thời gian chọn món so với baseline cần đo, số lần phải hỏi lại điều dưỡng, và chỉ số an toàn là số món không khớp chế độ ăn không được tăng. Boundary là AI không tự quyết định chế độ ăn hay dị ứng, chỉ dùng chế độ ăn đã được xác nhận và có người có chuyên môn duyệt. Về mức can thiệp, nền nên là Rule lọc món theo chế độ ăn, Workflow chỉ xét thêm cho phần giải thích, còn Agent bị loại vì quá rộng. Quyết định là Go có điều kiện, phạm vi nhỏ: trước hết xem thực đơn thật và kiểm tra dữ liệu chế độ ăn, và dừng nếu thực đơn đã có nhãn hoặc không lấy được dữ liệu.

---

## 7. Tài liệu tham khảo
| # | Nguồn | Link | Dùng cho việc gì | Ghi chú |
|---:|---|---|---|---|
| 1 | Tuổi Trẻ (28/08/2019), dẫn nghiên cứu 887 người bệnh tại 6 bệnh viện công ở TP.HCM | https://tuoitre.vn/tang-suat-an-dinh-duong-khi-nam-vien-ra-sao-20190827215444484.htm | Chỉ khoảng 13% thức ăn đến từ khoa Dinh dưỡng; phần còn lại từ căn tin, mua ngoài, người nhà nấu. Chỉ 4,2% người bệnh ăn đủ 100% nhu cầu năng lượng; 34,1% suy dinh dưỡng | Số năm 2019, ở TP.HCM, dùng làm tham khảo |
| 2 | Báo Pháp Luật Việt Nam (02/04/2015) | https://baophapluat.vn/nhieu-benh-vien-chua-quan-tam-den-dinh-duong-cho-nguoi-benh-post193543.html | Ngoài một số bệnh viện lớn, phần lớn bệnh viện chưa đáp ứng chế độ ăn cho người bệnh đang điều trị; khoảng 20% người bệnh nội trú cần chế độ ăn bệnh lý | Bài cũ, cần đối chiếu số mới hơn |
| 3 | Thông tư 18/2020/TT-BYT về hoạt động dinh dưỡng trong bệnh viện (hiệu lực 01/01/2021) | https://luatvietnam.vn/tin-van-ban-moi/tren-100-giuong-thanh-lap-khoa-dinh-duong-186-27643-article.html | Bệnh viện từ 100 giường phải có khoa Dinh dưỡng; nếu không tự chế biến được thì thuê ngoài và khoa Dinh dưỡng giám sát | Thay Thông tư 08/2011. Có văn bản hợp nhất năm 2025, cần kiểm bản đang hiệu lực |

-
