# Báo cáo cá nhân — 2A202603857_NguyenLeTrongManh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:Nguyễn Lê Trọng Mạnh
- MSSV:2A202603857
- Email trường (không bắt buộc, repo có thể để public): 26ai.manhnlt@vinuni.edu.vn
- Tên nhóm: A90
- Link repo nhóm: https://github.com/ArsNeonci/K5-L3B-Day02-A90-DiscoveryProblemFraming

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
| Success metric | Baseline: khoảng 20 phút chưa rõ mỗi bữa/ngày, cần đo lại theo một lượt chọn món. Target đề xuất sau đo: giảm trung vị thời gian ≥30% trên các lượt tương đương; nếu xác nhận baseline là 20 phút/lượt thì mốc tương ứng ≤14 phút/lượt. Đo gồm thời gian kiểm/sửa và tách thời gian chờ; không có lựa chọn không khớp bảng duyệt trong tập thử. Chưa có kết quả đã đạt target. |
| Phương án không dùng AI | Thực đơn ghi sẵn nhãn chế độ ăn phù hợp (ví dụ ít muối, đái tháo đường) ngay cạnh từng món |
| Giả thuyết về AI | Rule có thể lọc theo bảng tương thích đã duyệt; AI chỉ là giả thuyết giải thích thông tin nếu cách đơn giản chưa đủ và có người kiểm. Không suy đoán thành phần thiếu hoặc tự xác định chế độ ăn. |
| Cảm nhận nhanh | No AI trước; Rule khi cần lọc và đủ dữ liệu. Workflow chưa chọn, theo bản phân tích chung. |


Quy trình nháp hiện tại:

```text
[1 Nhận lời dặn đã xác nhận: chưa đo riêng]
→ [2 Xem thực đơn: chưa đo riêng]
→ [3 Đọc thông tin món: chưa đo riêng]
→ [4 Đối chiếu lời dặn: chưa đo riêng] ← CỤM BƯỚC CẦN KIỂM CHỨNG
→ [5 Hỏi điểm chưa rõ nếu có: chưa đo riêng]
→ [6 Ghi nhận lựa chọn: chưa đo riêng]
Ước lượng 20 phút chưa rõ phạm vi hoặc đơn vị; không cộng thêm thành tổng mới.
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
| Success metric | Baseline ước lượng: khoảng 10 phút từ thay đổi đến người nhận, chưa gồm toàn bộ kênh bếp. Target đề xuất: độ trễ trung vị ≤5 phút trên cùng phạm vi sau khi xác nhận baseline; không có món giao theo phiên bản đã hết hiệu lực trong tập thử. Ghi thời điểm đổi, nhận và xác nhận; đo riêng đường tới bếp. Chưa có kết quả đã đạt. |
| Phương án không dùng AI | Chuẩn hóa một kênh báo duy nhất và bảng ghi chế độ ăn mới tại giường |
| Giả thuyết về AI | Chưa thấy cần AI. Bài toán chủ yếu là báo đúng người đúng lúc, nên có thể giải bằng thông báo tự động theo quy tắc |
| Cảm nhận nhanh | Rule hoặc No AI |

Quy trình nháp hiện tại:

```text
[1 Bác sĩ thay đổi chỉ định: mốc bắt đầu]
→ [2 Thông tin đến điều dưỡng: khoảng 5 phút, ước lượng]
→ [3 Thông tin đến bệnh nhân/người nhà: khoảng 5 phút, ước lượng]
→ [4 Bộ phận phụ trách suất ăn xác nhận phiên bản mới: chưa rõ thời gian/kênh]
→ [5 Ghi nhận và phục vụ theo phiên bản hiện hành: chưa đo]
Khoảng 10 phút chỉ là độ trễ ước lượng của bước 2–3, không phải thời gian thao tác hoặc toàn quy trình.
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
| Success metric | Baseline ước lượng: hỏi/ghi khoảng 2 phút/lần, 3–4 lần/ca; chưa có tỷ lệ ghi nhận hiện tại. Target đề xuất: ≤1 phút hỏi/ghi mỗi lần và 100% lần thuộc phạm vi quan sát có lý do hoặc trạng thái không trả lời, không ép đoán lý do. Bấm giờ và đếm lượt trong các ca thử được phép; không suy ra tỷ lệ cải thiện khi chưa có baseline đủ. |
| Phương án không dùng AI | Phiếu chọn sẵn lý do (món, giờ giao, khẩu vị, bệnh) để đánh dấu nhanh |
| Giả thuyết về AI | AI gom nhóm các lý do ghi dạng tự do và chỉ ra xu hướng cho bộ phận dinh dưỡng; chỉ dùng khi đã có dữ liệu ghi nhận |
| Cảm nhận nhanh | Rule hoặc Workflow |

Quy trình nháp hiện tại:

```text
[1 Thu khay, nhận diện còn thừa: chưa đo]
→ [2 Hỏi lý do: chưa tách thời gian]
→ [3 Ghi lý do hoặc không trả lời: chưa tách thời gian]
→ [4 Chuyển thông tin cho người phụ trách: kênh và thời gian chưa xác nhận]
Bước 2–3: khoảng 2 phút/lần theo ước lượng, 3–4 lần/ca.
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

Đối chiếu biên tập ngày 09/11/2026: Linh đã xác nhận chọn Card #1 của tôi. [Bản chung](../team/group_report.md) hiện đề xuất No AI trước, Rule khi đủ dữ liệu và cần lọc; quyết định phân tích Not Yet. Các câu hỏi được truy vết ở [Q01–Q06](../assets/cp3-so-doi-chieu-phan-bien.md); chưa gán người hỏi khi không có ghi nhận. Những chỉnh sửa đồng bộ không xác nhận thay tôi rằng đã hoàn thành các hoạt động nhóm hoặc tự viết phần giải thích.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày card "bệnh nhân chọn món phù hợp lời dặn ăn uống" và lập luận vì sao nên chọn: actor rõ (bệnh nhân), quy trình rõ, so sánh được 4 mức can thiệp, phạm vi kiểm soát được khi chỉ dùng chế độ ăn đã được xác nhận. Khi nghe pitch của bạn khác, tôi hỏi sâu vào problem, đặc biệt là chỗ nào khó triển khai và không khả thi. | Nhóm chọn ý tưởng này và ưu tiên hướng ít rủi ro, dễ kiểm soát. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: (1) Bạn lấy dữ liệu ở đâu, bên nào chịu trách nhiệm cung cấp? (2) Có rủi ro nào quá lớn không, có chấp nhận đánh đổi không? | Giúp nhóm làm rõ actor và nguồn dữ liệu của candidate đó trước khi chấm điểm, và ưu tiên ý ít rủi ro, dễ triển khai. |
| Nhận phản biện | Q03 — Câu hỏi tôi ghi nhận: “Có tiết kiệm thời gian thật không?”; “Thay thế bộ phận nào?”; chưa xác nhận người hỏi. Tôi ghi đã làm rõ 20 phút là ước lượng cần đo, không thay người có chuyên môn và bổ sung chỉ số chất lượng. | Thu hẹp phạm vi từ suy luận theo bệnh án sang đối chiếu dữ liệu chế độ ăn đã xác nhận. Câu hỏi lợi nhuận ở 6.3 được giữ riêng tại Q06 để xác nhận, không tự quy về Q01 của Linh hỏi Chủ. |
| Gom cluster / cây OST | Research các problem nhóm đưa ra và tìm câu hỏi phản biện cho từng cái; chỉ ra các ý cùng một pattern (thông tin chế độ ăn không đến đúng người đúng lúc). | Giúp nhóm hiểu sâu hơn về pain point và tách pain khỏi giải pháp. |
| Chọn candidate problem | Đề xuất các candidate có tiềm năng nhất sau giai đoạn pitch và phản biện, kèm lý do. | Góp phần để nhóm chọn được phương án có thể triển khai. |
| Kiểm chứng / research | Research pain point và nghiệp vụ đặt món, chế độ ăn nội trú; tìm các hệ thống đã có (CBORD, Epic MyChart Bedside, Computrition) và nhận ra phần lọc món theo chế độ ăn thường giải bằng Rule, không phải AI. | Giúp nhóm đi nhanh hơn, tránh xây lại thứ đã có, và cân nhắc thu hẹp vai trò của AI. |
| Quy trình nhóm | Tham gia đầy đủ các bước; góp phần tìm rủi ro của từng problem (dữ liệu bệnh án nhạy cảm, nguồn dữ liệu chế độ ăn, ai duyệt cuối). | Nhóm có nhiều góc nhìn hơn về pain point và rủi ro. |
| Problem Statement | Ba card tôi đề cử là đóng góp ở CP2/CP3. Chưa ghi rõ tôi đã sửa trường nào trong Problem Statement v0/v1; cần bổ sung đúng hoạt động. | Bản chung đã có v0/v1 nháp để đối chiếu; không dùng việc đề cử ba card làm bằng chứng đã viết Problem Statement. |
| Mức can thiệp AI | Cân nhắc 4 mức: No AI (nhãn chế độ ăn trên thực đơn), Rule (lọc theo chế độ ăn), Workflow (AI giải thích, người duyệt), Agent (loại vì quá rộng). Tôi dùng AI khoảng 35% công việc (ước lượng của tôi) chủ yếu để phản biện pain point của mình. | Hiểu vấn đề rõ hơn và có cơ sở giải thích, phản biện lại nhóm. |
| Quyết định | Đã ghi các điều kiện cần kiểm: baseline, thực đơn thật và nguồn chế độ ăn. Chưa có biên bản nhóm đánh giá lại rủi ro hoặc cho phép pilot. | Bản phân tích chung giữ Not Yet; cần xác nhận Value, dữ liệu và người duyệt trước khi cân nhắc triển khai. |

<!-- CP3_AI_REVIEW_START -->
### 4.1. CP3

[Bản chuẩn 15 cặp câu hỏi / trả lời](../assets/cp3-phien-phan-bien-ai-uy-quyen.md).

| ID | Vai hỏi | Vai trả lời | Card | Câu hỏi phản biện | Câu trả lời theo vai | Thay đổi đề xuất |
|---|---|---|---|---|---|---|
| P01 | Mạnh | Linh | L1 — Kiểm tra bài trước nộp | Kiểm tra 10 phút mà từng sót 2 vấn đề thì mục tiêu là nhanh hơn hay hiểu đúng hơn, và đã chứng minh giảm bao nhiêu phần trăm chưa? | Cần ưu tiên hiểu đúng yêu cầu. Hai vấn đề từng sót chưa được xác định cùng một lượt; chưa có cặp số trước/sau để kết luận giảm thời gian. Target là không vượt khoảng thời gian hiện tại và không còn bỏ sót do hiểu nhầm trong các lượt thử tiếp theo. | Giữ metric chất lượng; không dùng 50–56% như kết quả thật; ghi riêng mục chưa hiểu và cách xác nhận. |
| P04 | Linh | Mạnh | M1 — Chọn món theo lời dặn | Khoảng 20 phút là mỗi bữa hay mỗi ngày; nếu chưa biết thì căn cứ nào để kết luận tiết kiệm thời gian? | Chưa rõ đơn vị và phạm vi nên chưa thể tính lợi ích. Trước hết quan sát một lượt từ bắt đầu xem thực đơn đến ghi nhận lựa chọn, tách thao tác/chờ. Target giảm trung vị ít nhất 30% là đề xuất sau khi đo baseline, không phải kết quả đã đạt. | Làm rõ đơn vị baseline và cách đo, không gán 20 phút cho một bước cụ thể. |
| P05 | Chủ | Mạnh | M2 — Truyền thay đổi chế độ ăn | Rút ngắn đường bác sĩ–điều dưỡng–bệnh nhân đã đủ chưa nếu bộ phận nhận lựa chọn món chưa có thông tin mới? | Chưa đủ. Khoảng 10 phút hiện chỉ là độ trễ ước lượng của hai chặng đã nêu. Cần theo dõi người nhận thông tin tại bộ phận suất ăn và phiên bản có hiệu lực; không gọi 10 phút là tổng thời gian toàn quy trình. | Thêm điểm xác nhận phiên bản ở bộ phận suất ăn và kiểm trường hợp thay đổi khi đã ghi lựa chọn. |
| P06 | Khánh | Mạnh | M3 — Ghi lý do thức ăn thừa | Actor chính là người hỏi/ghi hay người dùng dữ liệu, và giảm thời gian ghi có làm mất lý do quan trọng không? | Với phạm vi giảm thao tác hỏi/ghi, actor chính tạm chọn người thực hiện bước ghi; nhân viên dinh dưỡng là người dùng đầu ra. Vai trò cụ thể tại cơ sở còn phải xác nhận. Phiếu chọn sẵn có mục khác và không trả lời để tránh đoán lý do. | Tách actor chính/người nhận đầu ra; đo tỷ lệ ghi nhận cùng thời gian; giữ phản hồi tự do. |
| P08 | Mạnh | Khánh | K2 — Tra lệnh Git | Nếu dùng script thay tra lệnh, làm sao tránh đẩy nhầm nhánh hoặc đưa cả file không định nộp lên repo? | Script chỉ là Rule hỗ trợ thao tác. Vẫn cần xem trạng thái, nhánh, remote và chọn file; dừng khi có xung đột hoặc khác trạng thái mong đợi. Không dùng mục tiêu không tra lệnh để bỏ qua kiểm tra trước khi đẩy bài. | Thêm bước kiểm trạng thái và chọn file, không tự stage/push mọi thay đổi. |
| P12 | Mạnh | Chủ | C3 — Hồ sơ thuê trọ | Xem được phòng thật có chứng minh người nhận tiền cọc có quyền cho thuê không? | Không. Sự tồn tại của phòng và quyền cho thuê là hai điều phải kiểm riêng. Rà soát hồ sơ chỉ chỉ ra phần thiếu/mâu thuẫn; không xác thực được giấy tờ hoặc bảo đảm an toàn giao dịch chỉ từ ảnh và tin nhắn. | Có mục riêng cho quyền cho thuê/người nhận cọc; không suy đoán phần chưa rõ. |
| P13 | Chủ | Mạnh | M1 — Phương án đơn giản | Nếu thực đơn đã có nhãn rõ và nhân viên đang hỗ trợ tốt, thêm AI mang lại lợi ích riêng nào? | Chưa có bằng chứng lợi ích riêng. Khi cách hiện tại hoặc nhãn đã đủ, dùng No AI; chỉ xem Rule khi phải đối chiếu nhiều điều kiện với bảng duyệt. Không chọn AI chỉ vì bài học có chủ đề AI. | Đưa hiệu quả nhãn/nhân viên hiện có thành giả định phản bác cần kiểm trước. |
| P14 | Khánh | Mạnh | M1 — Dữ liệu và phiên bản | Nếu món thiếu thông tin thành phần hoặc chế độ ăn vừa thay đổi, hệ thống có tự ước tính hoặc tiếp tục dùng danh sách cũ không? | Không. Dữ liệu thiếu/cũ phải chuyển người phụ trách xác nhận; không tự suy đoán thành phần, dị ứng hoặc đổi chế độ ăn. Chưa có nguồn cập nhật và người duyệt là lý do giữ Not Yet cho triển khai. | Bổ sung chặn dữ liệu thiếu/cũ, kiểm phiên bản và đường quay về người hỗ trợ. |

<!-- CP3_AI_REVIEW_END -->

### 4.2. CP4–CP5.

| Phần | Đầu ra và nguồn | Trạng thái |
|---|---|---|
| CP4 | [Research, sáu giả định, chín câu hỏi và kế hoạch kiểm chứng](../assets/cp4-research-va-ke-hoach-kiem-chung-ai.md) | Đã mở lại R0–R3/survey người thật |
| CP5 | [Quy trình, metric, v0 và sáu phản biện](../assets/cp5-quy-trinh-va-phan-bien-ai.md) | Có mô hình sáu → năm bước, 20 → 14 phút thao tác tổng hợp; chi phí chuẩn bị tính riêng; chưa có số đo tại cơ sở |

Ước lượng 20 phút gốc của Mạnh chưa được xác nhận đơn vị bằng mô hình này. Kết quả phân tích vẫn Not Yet.

<!-- CP6_CP7_AI_START -->
### 4.3. CP6 và CP7

[CP6: No AI, Not Yet, v1, rủi ro và gate chất lượng](../assets/cp6-phan-tich-va-quyet-dinh-ai.md). [Kết quả kiểm fixture](../assets/cp6-ket-qua-kiem-tra-fixture.json) chỉ kiểm logic tài liệu; không phải kết quả sản phẩm.



[Checklist trạng thái hoàn tất](../assets/cp7-checklist-hoan-tat-va-trang-thai.md) phân biệt đầu ra AI và bằng chứng chưa có.
<!-- CP6_CP7_AI_END -->

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Viết lại các ý thô thành Job Story, hỏi câu để làm rõ số liệu, gợi ý thêm góc nhìn (bếp, dinh dưỡng, đổi y lệnh, thức ăn bỏ thừa), tìm tài liệu tham khảo về đặt món và thức ăn thừa ở bệnh viện | Chỉ ra chỗ số liệu còn mơ hồ (của ai, mỗi bữa hay mỗi ngày), nhắc các góc nhìn tôi chưa dùng, đưa tài liệu tham khảo | Các ý AI gợi ý (bếp đối chiếu y lệnh, đổi y lệnh, thức ăn bỏ thừa, điều dưỡng chuyển thông tin chế độ ăn) ban đầu không có dữ kiện nào từ Vinmec, chỉ là lập luận. Tìm kiếm không thấy trang công khai nào mô tả cách bệnh nhân Vinmec xem thực đơn hoặc đặt món, nên quy trình trong Job Story vẫn phải tự xác nhận | Tự nghĩ 4 ý đầu, bổ sung số liệu cho cả 7 ý, sửa số của ý 2 (từ 30-40 xuống 10-15 phút), bỏ ý "điều dưỡng nhập hoặc chuyển thông tin chế độ ăn" |
| CP2 Problem Card | Chấm điểm sơ bộ, soạn khung Problem Card, soạn bảng phản biện | Chỉ ra ý 2 và ý 3 cùng số liệu nên dễ đếm đôi, chỉ ra ý đổi y lệnh có thể không cần AI, nhắc thêm chỉ số an toàn bên cạnh chỉ số thời gian | Quy trình hiện tại trong card là giả thuyết AI dựng từ lời kể của tôi, chưa kiểm với điều dưỡng. Điểm chấm 27/23/20. Top 3 AI đề xuất ban đầu khác với lựa chọn của tôi | Chọn lại top 3 theo ưu tiên của mình (ý 4, 6, 7), chọn card muốn pitch, chọn lý do nào giữ hoặc bỏ |
| CP4 Research | Đã ghi tìm các case đặt món; bản chung được AI bổ sung nguồn chính thức R0–R3 để nhóm tự kiểm | Có mô tả tính năng và ngoại lệ từ cơ sở sử dụng, không chỉ tên nhà cung cấp | Không suy ra kiến trúc bên trong là Rule/AI. Nguồn Vinmec có mô tả nhân viên nhận lựa chọn; chưa có baseline hoặc xác nhận quy trình từng cơ sở | Đề xuất cần tôi xác nhận sau khi tự mở nguồn: chỉ giữ claim có link hỗ trợ; bỏ claim 18 tháng chưa có nguồn trực tiếp; không thay research bằng phỏng vấn. |
| CP5 Quy trình | Đã ghi nhờ AI dựng khung; bản chung hiện có sơ đồ hiện tại và hướng No AI/Rule | Phân biệt đọc/đối chiếu, xác nhận dữ liệu và kênh nhận lựa chọn | Quy trình chưa quan sát, thời gian từng bước chưa có; không mặc định bệnh nhân tự đặt trên app | Bản biên tập giữ đúng trạng thái giả thuyết; tôi cần xác nhận bước thực tế và ghi đóng góp cụ thể thay vì coi sơ đồ nháp là quy trình đã kiểm chứng. |
| CP5–6 Problem Statement | Soạn Problem Statement v0 từ các dữ kiện tôi cung cấp | Gom đủ 6 trường và chỉ ra chỗ còn trống (baseline, tần suất) | Metric ban đầu chỉ có thời gian, chưa có chất lượng; vai trò của AI ở bước giải thích chưa được kiểm chứng sau research | ✎ Thêm chỉ số an toàn (món không khớp chế độ ăn không tăng) và giữ boundary: AI không tự quyết định chế độ ăn hay dị ứng |
| CP6 Mức can thiệp / quyết định | AI hỗ trợ so sánh No AI/Rule/Workflow/Agent; đề xuất Go có điều kiện trước đây được đối chiếu lại với dữ liệu còn thiếu | Làm rõ cần thử cách đơn giản, có bảng duyệt và fallback; không cần Agent | Chưa có người dùng, dữ liệu cơ sở hoặc người duyệt; không đủ căn cứ hạ các rủi ro Cao | Bản chung đề xuất Not Yet. Đây là hiệu chỉnh phân tích do AI hỗ trợ, chưa phải bằng chứng nhóm đã biểu quyết hoặc tôi đã thử thành công pilot. |

---

## 6. Reflection (CP7)

<!-- CP7_AI_REFERENCE -->


Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe pitch của các bạn, tôi nhận ra những ý tưởng thiếu actor rõ hoặc chưa biết lấy dữ liệu từ đâu thì rất khó đi tiếp. Vì vậy tôi hỏi các bạn: đối tượng chính là ai, dữ liệu lấy ở đâu, bên nào chịu trách nhiệm cung cấp, và có chấp nhận đánh đổi rủi ro không. Tôi cũng thấy mình hay chọn problem theo độ hấp dẫn, trong khi nhóm nên ưu tiên problem có dữ liệu thật và đo được.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có. Lập luận ban đầu của tôi cho ý 4 là "bệnh nhân nhận đề xuất món ăn dựa theo bệnh án". Đó là một giải pháp, chưa phải vấn đề, và còn quá rộng vì "bệnh án" kéo theo dữ liệu y tế nhạy cảm. Tôi nhận ra khi đối chiếu với yêu cầu tách opportunity khỏi solution. Tôi viết lại thành vấn đề: bệnh nhân đã biết lời dặn ăn uống nhưng khó biết nhanh món nào phù hợp, và giới hạn phạm vi ở chế độ ăn đã được xác nhận.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Tôi nhận ba câu hỏi: lợi nhuận thực tế có tăng không, có tiết kiệm thời gian thật không, và thay thế bộ phận nào. Sau đó tôi đổi cách nhìn: con số 20 phút mới là ước lượng nên cần đo lại; AI hỗ trợ người có chuyên môn chứ không thay thế điều dưỡng hay bộ phận dinh dưỡng; và tôi thêm chỉ số an toàn bên cạnh chỉ số thời gian (số món không khớp chế độ ăn không được tăng).

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Có, ở phần research. Điều tôi ghi nhận là đã có hệ thống hỗ trợ chọn món theo dữ liệu chế độ ăn, nên không nên mặc định phải tự xây Agent. Bản đối chiếu nguồn hiện tại không kết luận kiến trúc của các hệ thống là Rule hay AI và chưa có link trực tiếp cho con số 18 tháng, nên không giữ các claim đó làm kết luận. Vai trò AI nếu xem xét sau này chỉ là giải thích dữ liệu đã duyệt; thiếu thành phần thì chuyển người phụ trách, không dùng AI ước tính để quyết định món phù hợp.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là tách vấn đề khỏi giải pháp và giữ các con số trung thực. Nhiều con số của tôi (như 20 phút) mới là ước lượng, chưa phải số bấm giờ thật, nên tôi phải ghi rõ nguồn của từng số và chưa dám đặt target khi chưa có baseline đo được. Phần boundary cũng khó, vì bài liên quan dữ liệu y tế và phải xác định ai duyệt cuối.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Tôi sẽ xem một thực đơn thật và hỏi vài điều dưỡng hoặc bệnh nhân trước khi chốt card, vì hai giả định quan trọng nhất (thực đơn chưa ghi nhãn chế độ ăn, và dữ liệu chế độ ăn lấy được ở dạng dùng được) vẫn chưa được kiểm chứng. Tôi cũng sẽ phản biện nhóm mạnh hơn ở câu hỏi: card nào thật sự cần AI, và card nào có thể giải bằng nhãn hoặc quy tắc.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
**Bản tham chiếu đã biên tập theo card chung; tôi cần tự diễn đạt và giải thích khi chấm.** Vấn đề là bệnh nhân có lời dặn ăn uống đã xác nhận nhưng khó đối chiếu với các món, còn khoảng 20 phút là ước lượng chưa rõ mỗi bữa hay mỗi ngày. Quy trình đọc và đối chiếu phải kiểm lại với cơ sở, kể cả kênh nhân viên nhận lựa chọn hiện có. Metric đề xuất là sau khi đo baseline cùng phạm vi, giảm trung vị thời gian ít nhất 30% và không có lựa chọn không khớp bảng duyệt trong tập thử. Boundary là không tự xác định chế độ ăn, dị ứng hoặc thành phần còn thiếu và không tự đặt món. Hướng thử bắt đầu từ No AI, chỉ dùng Rule nếu nhãn chưa đủ và có dữ liệu được duyệt; Workflow/Agent chưa được chọn. Bản phân tích hiện giữ Not Yet vì chưa có kiểm chứng người dùng, dữ liệu và người duyệt tại cơ sở.

---

## 7. Tài liệu tham khảo
| # | Nguồn | Link | Dùng cho việc gì | Ghi chú |
|---:|---|---|---|---|
| 1 | Hướng dẫn dành cho khách hàng điều trị nội trú tại Vinmec | https://www.vinmec.com/vie/bai-viet/huong-dan-danh-cho-khach-hang-dieu-tri-noi-tru-tai-vinmec-vi | Bối cảnh suất ăn; nguồn còn mô tả nhân viên phục vụ phòng nhận lựa chọn cho ngày hôm sau vào 13–15 giờ | Cần kiểm từng cơ sở, không suy ra có app tự đặt hoặc baseline 20 phút |
| 2 | Khoa Dinh dưỡng, Bệnh viện Vinmec Central Park | https://www.vinmec.com/vie/co-so-y-te/khoa-dinh-duong-benh-vien-da-khoa-quoc-te-vinmec-central-park | Biết khoa Dinh dưỡng phối hợp tiết chế để cung cấp suất ăn theo bệnh lý | Chỉ là một cơ sở của Vinmec |
| 3 | Suy dinh dưỡng khi nằm viện, VnExpress | https://vnexpress.net/suy-dinh-duong-khi-nam-vien-4548150.html | Bối cảnh Việt Nam: nhiều bệnh viện ghi nhận 40-50% bệnh nhân suy dinh dưỡng khi nằm viện | Trích lời bác sĩ trong bài báo |
| 4 | Khảo sát hài lòng của người bệnh nội trú về suất ăn, BVĐK tỉnh Thái Bình 2018 | https://lib.hutech.edu.vn/chi-tiet?id=322352 | Số tham khảo về mức hài lòng với thời gian giao suất ăn và món ăn | Khảo sát hài lòng, không phải dữ liệu về thời gian chờ |

-
