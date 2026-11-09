# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: A90
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Linh | Khi chuẩn bị nộp bài lab, muốn biết bài còn thiếu yêu cầu nào | Sinh viên kiểm tra báo cáo cá nhân trước khi nộp | Bước 3, đối chiếu yêu cầu với bài: 12/30 phút (giả thuyết, chưa bấm giờ) | |
| 2 | Linh | Khi nhận phần việc trong bài nhóm, muốn hiểu đầu ra, người phối hợp và hạn | Thành viên mới nhận nhiệm vụ trong nhóm lab | Bước 3, xác định yêu cầu đang có hiệu lực: 8 phút (giả thuyết) | |
| 3 | Linh | Khi kết thúc họp nhóm, muốn xác định việc đã thống nhất, người phụ trách và hạn | Người ghi và gửi biên bản họp nhóm lab | Bước 2, phân biệt điều đã chốt với đề xuất: 10/25 phút (giả thuyết) | |
| 4 | Mạnh | Khi đứng trước nhiều món, bệnh nhân muốn biết nhanh món nào phù hợp lời dặn ăn uống | Bệnh nhân nội trú | Bước 3–5, đọc và đối chiếu từng món: khoảng 20 phút | |
| 5 | Mạnh | Khi bác sĩ đổi y lệnh ăn uống, bệnh nhân và người nhà muốn được báo ngay | Điều dưỡng; bệnh nhân và người nhà | Bước 2–3: tổng độ trễ khoảng 10 phút | |
| 6 | Mạnh | Khi bệnh nhân bỏ thừa thức ăn, nhân viên dinh dưỡng muốn nắm lý do | Điều dưỡng; nhân viên dinh dưỡng (cần chốt actor chính) | Bước 2–3: khoảng 2 phút/lần, 3–4 lần/ca | |
| 7 | Khánh | Khi nhận đề lab có 7–8 file md, muốn nắm được phải làm những yêu cầu gì | Học viên nhận đề lab | Bước 3, xâu chuỗi việc cần làm: 20 phút (ước lượng) | |
| 8 | Khánh | Khi không nhớ lệnh git, muốn biết đúng lệnh cần chạy để đẩy bài lên GitHub | Học viên đẩy bài lab lên GitHub | Bước 1, tra hoặc hỏi lệnh: 3–5 phút/lần (ước lượng) | |
| 9 | Khánh | Khi gặp tắc đường trên đường đến lớp, muốn đảm bảo đến đúng giờ | Học viên đi tàu điện và xe buýt, có mặt lúc 9h | Bước 3, đoạn đường dài nhất: 75 phút, tắc thêm khoảng 20 phút (ước lượng) | |
| 10 | Chu | Khi nhận yêu cầu chuyển tiền gấp từ bên tự xưng, muốn biết cần xác minh gì qua kênh độc lập | Sinh viên dùng ngân hàng số | Bước 3, tìm đầu mối đáng tin: 8 phút/lượt (ước lượng) | |
| 11 | Chu | Khi thấy tin tuyển dụng hấp dẫn trên mạng, muốn đối chiếu với nguồn chính thức | Sinh viên tìm thực tập, việc làm thêm | Bước 3, tìm nguồn gốc và so khớp: 12 phút/tin (ước lượng) | |
| 12 | Chu | Khi bị thúc giục đặt cọc phòng trọ, muốn đối chiếu phòng, quyền cho thuê và các khoản phải trả | Sinh viên thuê hoặc chuyển trọ | Bước 3, rà soát điều kiện và phí: 12 phút/hồ sơ (ước lượng) | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Làm rõ yêu cầu và việc cần làm trong bài lab | #1 Kiểm tra bài trước khi nộp<br>#2 Làm rõ nhiệm vụ được giao<br>#3 Chốt việc sau họp<br>#7 Nắm yêu cầu từ nhiều file đề | Yêu cầu nằm rải rác ở nhiều file và tin nhắn, phải đọc và đối chiếu mới biết cần làm gì |
| B — Chế độ ăn của bệnh nhân nội trú | #4 Chọn món phù hợp lời dặn<br>#5 Báo đổi y lệnh ăn uống<br>#6 Ghi nhận lý do bỏ thừa | Thông tin chế độ ăn không đến đúng người, đúng lúc, nên bệnh nhân dễ ăn sai hoặc ăn không đủ |
| C — Xác minh trước khi giao tiền hoặc hồ sơ | #10 Yêu cầu chuyển tiền gấp<br>#11 Tin tuyển dụng<br>#12 Đặt cọc phòng trọ | Bị thúc ép quyết định nhanh, phải tự đối chiếu với nguồn độc lập trước khi giao tiền hoặc thông tin |
| D — Việc cá nhân, ít chung pattern | #8 Tra lệnh git<br>#9 Tắc đường đến lớp | Mỗi việc ngắn hoặc phụ thuộc yếu tố bên ngoài, khó gom chung với các cluster khác |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Bệnh nhân nội trú ăn đúng chế độ điều trị và chọn món nhanh, mà không tăng tải cho điều dưỡng
├── Opportunity A: Bệnh nhân không biết món nào phù hợp với lời dặn ăn uống của mình ★ nhóm chọn
├── Opportunity B: Thông tin chế độ ăn và dị ứng đến điều dưỡng, bếp, bệnh nhân chậm hoặc phải tra lại
└── Opportunity C: Không biết vì sao bệnh nhân bỏ thừa thức ăn để điều chỉnh
     ✗ "App đề xuất món theo bệnh lý"     ← solution, gạch khỏi tầng này
     ✗ "Chatbot tư vấn dinh dưỡng"        ← solution, gạch khỏi tầng này
     ✗ "Hệ thống cảnh báo món không hợp"  ← solution, gạch khỏi tầng này
```
Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 Kiểm tra bài trước khi nộp (cluster A) | 5 | 4 | 2 | 3 | 5 | 3 | 5 | 27 |
| #4 Bệnh nhân chọn món phù hợp lời dặn (cluster B) | 4 | 4 | 2 | 4 | 3 | 5 | 3 | 25 |
| #10 Xác minh yêu cầu chuyển tiền gấp (cluster C) | 4 | 3 | 3 | 4 | 4 | 4 | 3 | 25 |

**Candidate được chọn:** #4 Bệnh nhân chọn món phù hợp với lời dặn ăn uống.

**Vì sao chọn:**
- Nhóm chọn #4 dù tổng điểm không cao nhất, vì đây là candidate so sánh rõ nhất cả 4 mức can thiệp: No AI (nhãn chế độ ăn trên thực đơn), Rule (lọc và cảnh báo theo chế độ ăn), Workflow (AI đề xuất và giải thích trong danh sách đã lọc, có người duyệt), Agent (loại vì quá rộng).
- Impact lớn hơn chuyện tiết kiệm thời gian: ăn sai chế độ hoặc ăn không đủ ảnh hưởng đến hồi phục; bằng chứng chung ở Việt Nam cho thấy suất ăn bệnh lý chưa đáp ứng đủ nhu cầu người bệnh.
- Actor và boundary rõ: bệnh nhân là người chọn món, bác sĩ và chuyên viên dinh dưỡng chịu trách nhiệm chế độ ăn.

**Vì sao loại các candidate còn lại:**
- **#1 Kiểm tra bài trước khi nộp:** điểm cao về vừa sức và domain, nhưng một checklist theo rubric có thể đã đủ (card của Linh cũng đề xuất thử No AI trước), nên khó thấy khác biệt giữa các mức can thiệp.
- **#10 Xác minh chuyển tiền gấp:** impact cao, nhưng quy trình thay đổi theo từng kiểu lừa đảo nên khó vẽ quy trình cố định, và rủi ro khi đưa ra kết luận sai rất lớn.
- **#8, #9 (cluster D):** pain ngắn hoặc phụ thuộc yếu tố bên ngoài, không có quy trình lặp lại đủ rõ.
- **#5, #6 (cùng cluster B):** giữ làm nhánh phụ; #5 giải được bằng thông báo theo quy tắc, #6 cần dữ liệu ghi nhận chưa có.

**Xử lý bất đồng (nếu có):** 
---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Bệnh nhân hoặc người nhà mất thời gian đáng kể để chọn món sau khi biết lời dặn (ước lượng khoảng 20 phút) | Value | 5 | 1 | ✅ |
| 2 | Thực đơn căn tin không cho biết món nào hợp với chế độ ăn bệnh lý nào | Value | 5 | 2 | ✅ |
| 3 | Bệnh nhân cần đề xuất kèm giải thích, không chỉ danh sách món đã lọc | Value | 4 | 1 | ✅ |
| 4 | Chế độ ăn do bác sĩ chỉ định và dữ liệu thành phần món lấy được ở dạng dùng được | Feasibility | 5 | 2 | ✅ |
| 5 | Bệnh nhân hoặc người nhà tự dùng được công cụ chọn món | Usability | 4 | 2 | Sau |
| 6 | Bệnh viện cho phép dùng dữ liệu chế độ ăn và dị ứng trong công cụ có AI | Viability | 5 | 1 | Hỏi trước pilot |

**Căn cứ điểm bằng chứng:**
- **#2 (2 điểm):** bằng chứng chung ở Việt Nam cho thấy phần lớn thức ăn của người bệnh đến từ căn tin, mua ngoài hoặc người nhà nấu, và suất ăn bệnh lý chưa đáp ứng đủ (Tuổi Trẻ 2019, Báo Pháp Luật 2015). Chưa xác nhận ở bối cảnh của nhóm.
- **#4 (2 điểm):** research cho thấy hệ thống ở nước ngoài lấy chế độ ăn trực tiếp từ hồ sơ bệnh nhân, nhưng một bệnh viện mất 18 tháng để xây dữ liệu thành phần món.
- **#5 (2 điểm):** research cho thấy chỉ khoảng 25% bệnh nhân ở một bệnh viện tự đặt món, các nơi đều cần điều dưỡng hỗ trợ.
- **#1, #3, #6 (1 điểm):** chưa có bằng chứng, mới là ước lượng hoặc giả định của nhóm.

**Thứ tự kiểm:** #2 và #4 trước (nếu thực đơn đã ghi rõ chế độ ăn thì kết luận là No AI), rồi #1 và #3 qua survey và phỏng vấn, cuối cùng hỏi #6 trước khi pilot.
*Điền 4–6 giả định; xóa dòng thừa.*

**Giả định nhóm kiểm chứng trong buổi này:** 

- **#1 Thời gian chọn món:** hỏi 5-10 bạn trong lớp từng nằm viện hoặc từng chăm người nhà nằm viện: lần gần nhất mất bao lâu để chọn được món, có phải hỏi điều dưỡng không.
- **#2 Thực đơn không cho biết món nào hợp chế độ ăn:** hỏi cùng nhóm người trên: thực đơn hoặc căn tin lúc đó có ghi món nào hợp với chế độ ăn bệnh lý không; xin xem ảnh thực đơn nếu ai còn giữ.
- **#3 Cần giải thích, không chỉ danh sách đã lọc:** hỏi về lần gần nhất họ phải tự đối chiếu món với lời dặn và họ đã làm gì khi không chắc.

**Chưa kiểm trong buổi này:**
- **#4 Dữ liệu chế độ ăn và thành phần món:** cần hỏi bếp hoặc khoa Dinh dưỡng của một bệnh viện, không làm được trong lớp.
- **#5 Bệnh nhân tự dùng được công cụ:** chỉ kiểm được khi có bản thử.
- **#6 Quyền dùng dữ liệu:** cần hỏi người phụ trách ở bệnh viện, để trước pilot.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn + Survey + Research tài liệu

Interview snapshot #1:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Người nhà chăm bệnh nhân tăng huyết áp nằm viện 5 ngày ở bệnh viện công tuyến tỉnh |
| Câu nói đáng nhớ nhất (nguyên văn) | "Bác sĩ dặn ăn nhạt, nhưng xuống căn tin thì món nào cũng chỉ ghi tên với giá, chẳng biết món nào nhạt." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Bữa trưa, đứng ở căn tin, phải hỏi người bán từng món có nêm mặn không, rồi chọn cháo trắng cho chắc |
| Hiện đang xử lý bằng cách nào (workaround)? | Hỏi người bán, chọn món đơn giản nhất, đôi khi nấu ở nhà mang vào |
| Mất bao lâu, bao lần? | Khoảng 15 phút mỗi bữa, 3 bữa mỗi ngày |
| Insight / opportunity rút ra | Người chọn món thường là người nhà, không phải bệnh nhân; thiếu thông tin ở thực đơn, không phải thiếu thời gian đọc |


Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 3 | 2/3 phải hỏi hoặc tự đoán món nào hợp chế độ ăn |  1/3 được phát suất ăn theo chế độ, không có pain  |
| Survey | 8 | Dự kiến 5/8 phải hỏi người khác khi chọn món | Dự kiến 3/8 thấy chọn món nhanh, dưới 5 phút  |
| Research tài liệu | 6 nguồn nước ngoài, 3 nguồn Việt Nam | Ở Việt Nam, phần lớn thức ăn của người bệnh đến từ căn tin, mua ngoài, người nhà nấu; suất ăn bệnh lý chưa đáp ứng đủ (Tuổi Trẻ 2019, Báo Pháp Luật 2015) | Ở nước ngoài, lọc món và cảnh báo theo chế độ ăn đã làm được bằng Rule, không cần AI; AI tư vấn dinh dưỡng chỉ phù hợp khoảng 56-73% và dễ sai khi bệnh nhân có nhiều bệnh (Nutrients 2024) |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
- **Sau research:**
  - Đổi bối cảnh sang bệnh viện công tuyến tỉnh hư cấu, dựa trên bằng chứng công khai, không quy kết một bệnh viện thật.
  - Thu hẹp vai trò của AI: lọc món và cảnh báo do Rule làm; AI chỉ đề xuất và giải thích trong danh sách đã lọc.
- **Hướng sửa dự kiến nếu kết quả thật giống kịch bản giả lập:**
  - Actor chính chuyển thành **người nhà** chọn món ở căn tin, không phải mọi bệnh nhân.
  - Thu hẹp phạm vi: chỉ áp dụng cho bệnh nhân **tự mua món**, không áp dụng cho bệnh nhân đã được phát suất ăn bệnh lý.
  - Thêm phương án No AI: dán nhãn chế độ ăn lên thực đơn căn tin có thể đã đủ cho phần lớn trường hợp.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **CBORD Patient App**<br>Stony Brook, 2024 | [Link](https://news.stonybrookmedicine.edu/news/meal-ordering-app-nourishes-recovery-and-empowers-hospital-patients) | Lọc món theo chế độ ăn, dị ứng | Lọc hơn 30 loại chế độ ăn; điều dưỡng đặt hộ được | Không có số kết quả; bệnh nhân phải cài app | Lọc món làm được bằng **Rule** |
| **Let's Eat (Epic MyChart)**<br>UW Health, 2023 | [Link](https://www.uwhealth.org/files-directory/mychart/Dining/MYC_MealOrder.pdf) | Chọn món tại giường; xử lý khi đổi chế độ ăn | Hướng dẫn rõ; hiện dinh dưỡng theo chế độ ăn | Chỉ một số chế độ ăn dùng được; đổi y lệnh phải gọi hỗ trợ | Cần **phương án quay về** và **tạm giữ đơn** |
| **TouchPoint Dining**<br>Computrition | [Link](https://www.computrition.com/product-solutions/patient-meal-ordering-software/) | Lọc món và cảnh báo vượt giới hạn | Có bước cảnh báo; hiện thành phần từng món | Trang của nhà cung cấp, không có số kết quả | Cảnh báo làm được bằng **Rule** |
| **At Your Service Dining**<br>Scottsdale, 2008 | [Link](https://www.nrn.com/restaurant-technology/patients-see-only-approved-foods-with-self-order-tech) | Thực đơn trên TV đã lọc sẵn | Thức ăn thừa giảm từ khoảng 20% xuống dưới 10% | Bài cũ; 25% bệnh nhân dùng; 18 tháng xây dữ liệu | Chi phí lớn nhất là **dữ liệu thành phần món** |
| **AI gợi ý món tại giường**<br>Oneview, 2025 | [Link](https://www.oneviewhealthcare.com/blog/ai-bedside-technology-product-updates/) | Đề xuất món theo chế độ ăn và sở thích | Thị trường đã đưa AI vào bước đề xuất | Bản tin sản phẩm; không nói có người duyệt; chưa đo hiệu quả | AI đề xuất có tiền lệ nhưng **chưa có bằng chứng** |
| **Nghiên cứu ChatGPT tư vấn dinh dưỡng**<br>Nutrients, 2024 | [Link](https://www.mdpi.com/2072-6643/16/4/469/htm) | Đánh giá lời khuyên dinh dưỡng của AI | Chuyên gia chấm theo hướng dẫn quốc tế | Chỉ phù hợp 56-73%; sai khi nhiều bệnh cùng lúc | AI **không được tự suy ra chế độ ăn** |

**Kết luận research:**
- Bước **lọc món** và **cảnh báo** đã được các hệ thống hiện có làm bằng Rule gắn với chế độ ăn do bác sĩ chỉ định. Không nên tự xây lại, và không nên dùng AI cho hai bước này.
- Bước **AI đề xuất** đã bắt đầu xuất hiện trên thị trường nhưng chưa có số liệu về hiệu quả hay an toàn.
- Nghiên cứu cho thấy AI dễ sai khi bệnh nhân có nhiều bệnh cùng lúc, nên boundary "AI không tự xác định chế độ ăn, chỉ đề xuất trong danh sách đã lọc" là bắt buộc.
- Khoảng trống chung: chưa thấy nguồn nào ở Việt Nam hay tại Vinmec; dữ liệu thành phần món là điều kiện tiên quyết.

**Nhóm sửa problem sau research:**
Từ "AI đề xuất món dựa theo bệnh án" sang "Rule lọc món và cảnh báo theo chế độ ăn đã được xác nhận; AI chỉ đề xuất và giải thích trong danh sách đã lọc; người có chuyên môn chịu trách nhiệm chế độ ăn".

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI: 6 bước, 6/6 thủ công (giả thuyết, cần xác nhận)

[1 Nhận lời dặn ăn uống từ điều dưỡng]
→ [2 Xem thực đơn căn tin hôm nay]
→ [3 Đọc thành phần từng món]        ← BOTTLENECK
→ [4 Tự đối chiếu với lời dặn]       ← BOTTLENECK
→ [5 Đắn đo, hỏi lại nếu cần]        ← BOTTLENECK
→ [6 Đặt món]

Bước 3-5: khoảng 20 phút (ước lượng, chưa bấm giờ)
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Điều dưỡng → bệnh nhân, người nhà | Chế độ ăn bác sĩ chỉ định | Lời dặn ăn uống (thường nói miệng) | Khi nhập viện hoặc đổi y lệnh | Lời dặn thường chung chung ("ăn nhạt, ít đường") |
| 2 | Bệnh nhân, người nhà | Thực đơn căn tin | Danh sách món hôm nay | Mỗi bữa, 3 lần/ngày | Thực đơn chỉ có tên món và giá (giả định #2) |
| 3 | Bệnh nhân, người nhà | Danh sách món | Thông tin thành phần từng món | Gộp trong khoảng 20 phút của bước 3-5 (ước lượng) | Phải hỏi người bán vì thực đơn không ghi |
| 4 | Bệnh nhân, người nhà | Thành phần món + lời dặn | Món có vẻ phù hợp | Như trên | Tự phán đoán, dễ sai |
| 5 | Bệnh nhân, người nhà; điều dưỡng | Món còn phân vân | Câu trả lời của điều dưỡng | Điều dưỡng bị hỏi 3-4 lần/ca (ước lượng) | Điều dưỡng phải tra lại bệnh án |
| 6 | Bệnh nhân, người nhà | Món đã chọn | Đơn món hoặc món mua về | Mỗi bữa | Không ai kiểm món có khớp chế độ ăn không |

**Bottleneck chính:** bước 3-5, đọc và đối chiếu từng món với lời dặn, khoảng 20 phút mỗi lần chọn (ước lượng, chưa rõ mỗi bữa hay mỗi ngày). Nguyên nhân gốc là thực đơn không cho biết món nào hợp với chế độ ăn nào.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

Sơ đồ (ảnh: `report/assets/quy-trinh-tuong-lai.png`):

```text
TƯƠNG LAI: 8 bước, 4 bước con người, 3 bước tự động, 1 nhánh cảnh báo

[1 Xác nhận bệnh lý và chế độ ăn]          ← CON NGƯỜI (bác sĩ, chuyên viên dinh dưỡng)
→ [2 Lọc món theo chế độ ăn, loại món dị ứng] ← RULE
→ [3 Đề xuất món phù hợp, kèm giải thích]    ← AI (chỉ trong danh sách đã lọc)
→ [4 Bệnh nhân, người nhà chọn món]          ← CON NGƯỜI
→ [5 Kiểm tra món đã chọn]                   ← RULE
      ├─ Phù hợp → [6 Đặt món, gửi bếp]       ← CON NGƯỜI
      └─ Không phù hợp → [Cảnh báo kèm lý do] ← RULE → quay lại bước 4 hoặc hỏi điều dưỡng
→ [7 Bếp chuẩn bị món theo đơn và chế độ ăn] ← CON NGƯỜI
→ [8 Giao tận giường, đối chiếu đúng bệnh nhân] ← CON NGƯỜI

BOUNDARY:
- AI không tự xác định bệnh lý, chế độ ăn hay dị ứng.
- AI chỉ đề xuất trong danh sách đã được Rule lọc; cảnh báo do Rule tạo ra, không do AI.
- AI không đưa nhận định y khoa ngoài thông tin thành phần có trong thực đơn.
- Chế độ ăn đổi sau khi đặt: đơn bị tạm giữ, kiểm lại trước khi giao.

PHƯƠNG ÁN QUAY VỀ:
- AI đề xuất sai hoặc giải thích không rõ: bỏ đề xuất, bệnh nhân chọn từ danh sách đã lọc (Rule vẫn bảo vệ).
- Thiếu dữ liệu chế độ ăn hoặc hệ thống lỗi: quay về hỏi điều dưỡng như hiện tại.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 8 | Thêm bước kiểm tra, cảnh báo, chuẩn bị và giao món; số bước bệnh nhân tự làm giảm còn 1 (chọn món) |
| Tổng thời gian | khoảng 20' (ước lượng) | cần đo trong pilot | Chưa đặt target số khi chưa có baseline đo thật |
| Số bước thủ công | 6/6 | 4/8 | Bước thủ công còn lại là xác nhận chế độ ăn, chọn món, chuẩn bị và giao món |
| Bottleneck chính | Đọc và đối chiếu từng món | Xây và cập nhật dữ liệu thành phần món | Research: một bệnh viện mất 18 tháng xây cơ sở dữ liệu này |
| Rủi ro mới phát sinh | — | AI giải thích sai; dữ liệu chế độ ăn sai hoặc cũ; bỏ sót cảnh báo | Xử lý bằng Rule lọc và cảnh báo, người xác nhận chế độ ăn, tạm giữ đơn khi đổi y lệnh |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Bệnh nhân nội trú hoặc người nhà chọn món ở căn tin bệnh viện công tuyến tỉnh (bối cảnh hư cấu) |
| **Quy trình** | Nhận lời dặn ăn uống → xem thực đơn căn tin → đọc thành phần từng món → tự đối chiếu → hỏi lại điều dưỡng nếu cần → đặt hoặc mua món |
| **Bottleneck** | Đọc và đối chiếu từng món với lời dặn, khoảng 20 phút (ước lượng), vì thực đơn không cho biết món nào hợp với chế độ ăn nào |
| **Impact** | Mất thời gian của bệnh nhân và người nhà; điều dưỡng bị hỏi lặp lại 3-4 lần/ca (ước lượng); nguy cơ ăn sai chế độ hoặc ăn không đủ, ảnh hưởng hồi phục |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian chọn món: baseline khoảng 20 phút (cần bấm giờ lại) → target đặt sau khi đo baseline, đo bằng bấm giờ trong pilot. (2) Số lần hỏi lại điều dưỡng mỗi ca giảm, đo bằng điều dưỡng tự ghi. (3) An toàn: số món đặt không khớp chế độ ăn lọt qua mà không có cảnh báo bằng 0 |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không tự xác định bệnh lý, chế độ ăn hay dị ứng; chỉ đề xuất trong danh sách đã được Rule lọc; không đưa nhận định y khoa. Bác sĩ hoặc chuyên viên dinh dưỡng xác nhận chế độ ăn trước khi lọc (HITL). Khi món không phù hợp, Rule cảnh báo và bệnh nhân chọn lại hoặc hỏi điều dưỡng. Đơn bị tạm giữ nếu chế độ ăn đổi sau khi đặt |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

| Phản biện | Từ đâu | Đồng ý? | Nhóm xử lý thế nào |
|---|---|---|---|
| Metric chỉ đo thời gian: chọn nhanh hơn nhưng chọn sai thì sao? | AI | Đồng ý | Thêm metric an toàn: không có món không khớp chế độ ăn lọt qua mà không cảnh báo |
| Baseline 20 phút mới là ước lượng, chưa rõ mỗi bữa hay mỗi ngày | AI | Đồng ý | Ghi rõ "ước lượng", chưa đặt target số; đo lại trong pilot |
| Nếu thực đơn đã có nhãn chế độ ăn thì No AI là đủ | AI | Đồng ý | Giữ No AI làm phương án đầu tiên; kiểm giả định #2 trước |
| AI có thể bịa giải thích hoặc sai khi bệnh nhân có nhiều bệnh | AI (dựa trên research Nutrients 2024) | Đồng ý | AI chỉ đề xuất trong danh sách đã lọc; cảnh báo do Rule tạo ra |
| Có tiết kiệm thời gian thật không? Thay thế bộ phận nào? | Nhóm ([Tự điền người hỏi]) | Đồng ý một phần | Làm rõ hướng là hỗ trợ, không thay thế điều dưỡng hay khoa Dinh dưỡng; thời gian tiết kiệm phải đo trong pilot |

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **độ mơ hồ trung bình × độ phức tạp trung bình → Workflow có AI ở một bước**.

Vì sao:
- **Độ mơ hồ trung bình:** phần lọc món theo chế độ ăn là rõ ràng (món có vi phạm chế độ ăn hay không), nên giải được bằng quy tắc. Chỉ phần đề xuất món phù hợp và giải thích bằng lời là mơ hồ, vì có nhiều cách đề xuất đều chấp nhận được.
- **Độ phức tạp trung bình:** có nhiều bên tham gia (bác sĩ, bệnh nhân, người nhà, bếp) nhưng các bước cố định, không rẽ nhánh khó đoán; chỉ có một nhánh cảnh báo quay lại bước chọn món.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Dán nhãn chế độ ăn (ít muối, ít đường, mềm…) cạnh từng món trên thực đơn căn tin; điều dưỡng phát phiếu lời dặn ăn uống rõ ràng | Ít loại chế độ ăn, thực đơn cố định, bệnh nhân không có nhiều bệnh cùng lúc | Không cá nhân hóa; bệnh nhân vẫn phải tự đối chiếu khi có nhiều bệnh hoặc dị ứng | Dùng trước, làm phương án nền và phương án quay về |
| **Rule** | Lọc thực đơn theo chế độ ăn đã xác nhận, loại món chứa dị ứng; cảnh báo khi món đã chọn vi phạm chế độ ăn | Có dữ liệu chế độ ăn và thành phần món ở dạng dùng được | Cần xây dữ liệu thành phần món; quy tắc thiếu thì bỏ sót | **Chọn cho bước lọc và cảnh báo** |
| **Workflow** | Rule lọc → AI đề xuất và giải thích trong danh sách đã lọc → bệnh nhân chọn → Rule kiểm tra, cảnh báo → đặt và giao món | Danh sách sau lọc vẫn dài, bệnh nhân cần biết món nào hợp nhất và vì sao | AI giải thích sai hoặc nghe như lời khuyên y khoa | **Chọn** |
| **Agent** | AI tự đọc bệnh án, tự suy ra chế độ ăn, tự chọn và đặt món | Khi bước tiếp theo không đoán trước được | Quá rộng, truy cập toàn bộ bệnh án; research cho thấy AI dễ sai khi bệnh nhân có nhiều bệnh | Không chọn |

**Mức chọn:** Workflow (Rule lọc và cảnh báo, AI chỉ ở bước đề xuất và giải thích).

**Vì sao không chọn mức đơn giản hơn:** No AI và Rule giải được việc loại món vi phạm, nhưng sau khi lọc bệnh nhân vẫn phải tự cân nhắc trong nhiều món còn lại, nhất là khi có nhiều bệnh cùng lúc. Phần "món nào hợp nhất và vì sao" là phần ngôn ngữ mà Rule khó làm. Tuy vậy, giả định "bệnh nhân cần giải thích, không chỉ danh sách đã lọc" (#3) chưa được kiểm chứng; nếu kiểm chứng cho thấy danh sách đã lọc là đủ, nhóm sẽ dừng ở Rule.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | 3-5 món đề xuất trong danh sách đã lọc, mỗi món kèm 1-2 câu giải thích dựa trên thành phần có trong thực đơn |
| **Judgment** — con người cân nhắc, quyết định gì? | Bác sĩ, chuyên viên dinh dưỡng xác nhận chế độ ăn; bệnh nhân hoặc người nhà quyết định chọn món nào |
| **Action** — hành động cuối cùng là gì, ai làm? | Bệnh nhân hoặc người nhà đặt món; bếp chuẩn bị; nhân viên giao tận giường và đối chiếu đúng bệnh nhân |
| **Outcome** — đo kết quả bằng gì? | Thời gian chọn món; số lần hỏi lại điều dưỡng mỗi ca; số món không khớp chế độ ăn lọt qua mà không có cảnh báo |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Mã chế độ ăn đã xác nhận, danh sách dị ứng, danh sách món đã lọc kèm thành phần. **Chưa chắc có sẵn**: chế độ ăn có trong y lệnh, nhưng dữ liệu thành phần món của căn tin có thể chưa có |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Món bệnh nhân chọn so với món được đề xuất; số lần bị cảnh báo; câu hỏi còn phải hỏi điều dưỡng; ghi nhận thức ăn bỏ thừa |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? **Augment.** Quyết định chế độ ăn thuộc bác sĩ, quyết định chọn món thuộc bệnh nhân; AI chỉ thu hẹp lựa chọn và giải thích. Bằng chứng: các hệ thống trong research đều giữ người hỗ trợ (điều dưỡng đặt hộ, gọi bộ phận dinh dưỡng khi cần). Bằng chứng từ phỏng vấn mới là kịch bản giả lập, cần kiểm chứng.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? **Bỏ sót tệ hơn.** Không cảnh báo một món chứa chất gây dị ứng hoặc vi phạm chế độ ăn có thể gây hại trực tiếp, còn cảnh báo nhầm chỉ làm bệnh nhân chọn lại. Thiết kế xử lý bằng cách: cảnh báo do Rule tạo ra (không do AI), quy tắc đặt theo hướng chặt (chấp nhận cảnh báo thừa), và AI chỉ đề xuất trong danh sách đã lọc nên AI sai cũng không đưa ra món vi phạm.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Bệnh nhân nội trú hoặc người nhà **tự chọn món ở căn tin** bệnh viện công tuyến tỉnh (bối cảnh hư cấu); không gồm bệnh nhân đã được phát suất ăn bệnh lý |
| **Quy trình** | Nhận lời dặn ăn uống → xem thực đơn căn tin → đọc thành phần từng món → tự đối chiếu → hỏi lại điều dưỡng nếu cần → đặt hoặc mua món |
| **Bottleneck** | Đọc và đối chiếu từng món với lời dặn, khoảng 20 phút (ước lượng), vì thực đơn không cho biết món nào hợp với chế độ ăn nào |
| **Impact** | Mất thời gian của bệnh nhân và người nhà; điều dưỡng bị hỏi lặp lại 3-4 lần/ca (ước lượng); nguy cơ ăn sai chế độ hoặc ăn không đủ |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian chọn món: baseline khoảng 20 phút (bấm giờ lại) → target đặt sau khi có baseline thật. (2) Số lần hỏi lại điều dưỡng mỗi ca giảm (điều dưỡng tự ghi). (3) Món không khớp chế độ ăn lọt qua mà không có cảnh báo = 0. (4) Bệnh nhân chọn món trong danh sách đề xuất ở phần lớn các bữa |
| **Boundary** | AI không tự xác định bệnh lý, chế độ ăn hay dị ứng; chỉ đề xuất trong danh sách đã được Rule lọc; không đưa nhận định y khoa ngoài thành phần có trong thực đơn; không tự đặt món. Đơn bị tạm giữ nếu chế độ ăn đổi sau khi đặt |
| **AI intervention point** | Sau khi Rule đã lọc món theo chế độ ăn, trước khi bệnh nhân chọn món |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | Chế độ ăn sai hoặc cũ → bác sĩ, chuyên viên dinh dưỡng xác nhận; món vi phạm chế độ ăn → Rule cảnh báo; AI giải thích sai → bệnh nhân vẫn chọn trong danh sách đã lọc, nhóm rà mẫu giải thích hằng tuần trong pilot; giao nhầm bệnh nhân → nhân viên giao đối chiếu khi giao |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Bệnh nhân nội trú hoặc người nhà chọn món ở căn tin | Chỉ người **tự chọn món ở căn tin**, không gồm bệnh nhân đã được phát suất ăn bệnh lý | Kịch bản phỏng vấn giả lập cho thấy bệnh nhân được phát suất ăn không có pain; cần kiểm chứng thật |
| Success Metric | Thời gian, số lần hỏi lại, an toàn | Thêm tỷ lệ chọn món trong danh sách đề xuất | Đo được AI có thật sự giúp chọn món hay không |
| AI intervention point | Chưa có | Sau Rule lọc, trước bệnh nhân chọn | Research: lọc và cảnh báo đã làm được bằng Rule, AI chỉ cần ở phần đề xuất |
| Rủi ro & người kiểm tra | Chưa có | Ghi rõ người kiểm cho từng rủi ro | Phản biện: phải biết ai chịu trách nhiệm khi sai |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Chỉ đề xuất món đã được lọc | Mọi món AI đề xuất đều nằm trong danh sách Rule đã lọc | Có món nằm ngoài danh sách đã lọc |
| 2 | Không bịa | Mọi lý do trong giải thích truy được về thành phần có trong thực đơn | Có lý do không có trong dữ liệu món (ví dụ "món này tốt cho thận" khi thực đơn không ghi) |
| 3 | Không đưa lời khuyên y khoa | Chỉ mô tả thành phần và mức phù hợp với chế độ ăn đã xác nhận | Đề nghị đổi chế độ ăn, liều lượng, hay khẳng định tác dụng điều trị |
| 4 | Dễ hiểu | Mỗi giải thích tối đa 2 câu, ngôn ngữ phổ thông, người nhà đọc hiểu được | Dài, dùng thuật ngữ y khoa, hoặc mâu thuẫn giữa các món |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Bằng chứng chung ở Việt Nam cho thấy suất ăn bệnh lý chưa đáp ứng đủ và phần lớn thức ăn đến từ căn tin, mua ngoài; nhưng thời gian 20 phút mới là ước lượng và phỏng vấn mới là giả lập |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | TB | Bệnh nhân có thể lớn tuổi, mệt; research cho thấy ở một bệnh viện chỉ khoảng 25% bệnh nhân tự đặt món, các nơi đều cần người hỗ trợ |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Cao** | Cần dữ liệu thành phần món của căn tin, có thể chưa có; research cho thấy một bệnh viện mất 18 tháng xây cơ sở dữ liệu dinh dưỡng |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Dữ liệu chế độ ăn và dị ứng là dữ liệu sức khỏe nhạy cảm; chưa biết quy định của bệnh viện; cần khoa Dinh dưỡng vận hành theo Thông tư 18/2020/TT-BYT |

### 8.2. Kết luận

**Quyết định:** Not Yet

**Lý do:** Feasibility ở mức Cao (chưa biết có dữ liệu thành phần món không) và Value chưa được kiểm chứng bằng dữ liệu thật (phỏng vấn mới là giả lập). Đi tiếp khi chưa kiểm hai điểm này có thể dẫn đến xây một công cụ mà bệnh viện không có dữ liệu để chạy, hoặc giải một pain không tồn tại.

**Nếu Go — pilot nhỏ nhất:** (sau khi qua các bước kiểm chứng bên dưới) Không xây hệ thống. Trong 2 tuần ở một khoa: chuyên viên dinh dưỡng gán nhãn chế độ ăn cho khoảng 20 món căn tin; nhóm dùng một prompt chuẩn để tạo giải thích cho từng món, chuyên viên dinh dưỡng duyệt trước khi in kèm thực đơn; bấm giờ chọn món và đếm số lần hỏi điều dưỡng, so với 2 tuần trước pilot.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. Xem thực đơn căn tin thật: đã có nhãn chế độ ăn hay thành phần chưa (giả định #2).
2. Hỏi khoa Dinh dưỡng hoặc bếp: có dữ liệu thành phần món không, ai cập nhật (giả định #4).
3. Phỏng vấn thật 3 người và survey 5-10 người: thời gian chọn món, có phải hỏi người khác không, có cần giải thích không (giả định #1, #3).
4. Hỏi người phụ trách: có được dùng dữ liệu chế độ ăn, dị ứng trong công cụ có AI không (giả định #6).

**Nếu No-Go — nên làm gì thay AI:** Dán nhãn chế độ ăn lên thực đơn căn tin và phát phiếu lời dặn ăn uống rõ ràng cho từng bệnh nhân (phương án No AI). Nếu có dữ liệu chế độ ăn nhưng không được dùng AI, dừng ở Rule: lọc và cảnh báo theo quy tắc.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):
- Nếu sau khi xem thực đơn mà thực đơn **đã có nhãn chế độ ăn rõ ràng** → dừng, kết luận No AI.
- Nếu sau khi hỏi khoa Dinh dưỡng mà **không có và không xây được dữ liệu thành phần món** → No-Go cho Rule và Workflow, giữ phương án nhãn thủ công.
- Nếu trong pilot có **1 lần món vi phạm chế độ ăn lọt qua mà không có cảnh báo** → dừng pilot, xem lại quy tắc lọc.
- Nếu sau 2 tuần pilot **bệnh nhân hiếm khi chọn món trong danh sách đề xuất**, hoặc chuyên viên dinh dưỡng phải sửa phần lớn giải thích → bỏ bước AI, quay về Rule.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**
- **Chưa có số đo thật.** Các con số chính (khoảng 20 phút chọn món, 3-4 lần/ca điều dưỡng bị hỏi) mới là ước lượng của nhóm, chưa bấm giờ hay đếm thực tế.
- **Phỏng vấn mới là kịch bản giả lập.** Ba snapshot ở mục 3.2 do nhóm dựng để chuẩn bị, chưa phải lời người thật; survey chưa được gửi.
- **Bối cảnh là bệnh viện hư cấu.** Bối cảnh dựa trên bằng chứng chung về bệnh viện công ở Việt Nam, nhưng số liệu đã cũ (2015, 2019) và chủ yếu ở TP.HCM, chưa chắc đúng với bệnh viện tuyến tỉnh hiện nay.
- **Research chủ yếu từ nước ngoài.** Các hệ thống đặt món theo chế độ ăn đều ở Mỹ; nhiều nguồn là trang của nhà cung cấp, không có số kết quả độc lập.
- **Quy trình hiện tại chưa được xác nhận** với điều dưỡng, bệnh nhân hoặc khoa Dinh dưỡng.
- **Chưa biết dữ liệu thành phần món và quyền dùng dữ liệu sức khỏe**, hai điều kiện quyết định có làm được Rule và Workflow hay không.

**Hướng tiếp theo:**
1. **Kiểm chứng thật:** phỏng vấn 3 người (người nhà, điều dưỡng, bệnh nhân từng nằm viện) và survey 5-10 người; thay toàn bộ dữ liệu giả lập ở mục 3.2.
2. **Xem thực đơn căn tin thật** của ít nhất một bệnh viện công để kiểm giả định #2. Nếu đã có nhãn chế độ ăn, chuyển kết luận sang No AI.
3. **Hỏi khoa Dinh dưỡng** về dữ liệu thành phần món và người cập nhật (giả định #4), và hỏi về quy định dùng dữ liệu (giả định #6).
4. **Đo baseline** thời gian chọn món và số lần hỏi điều dưỡng trong 1-2 tuần, rồi đặt target cụ thể cho Success Metric.
5. **Các candidate cho vòng sau:**
   - #5 Báo đổi y lệnh ăn uống: có thể giải bằng thông báo theo quy tắc, nên đi kèm workflow hiện tại (bước tạm giữ đơn).
   - #6 Ghi nhận lý do bỏ thừa: đáng làm khi đã có dữ liệu chọn món và ghi nhận sau bữa ăn.
   - #10 Xác minh yêu cầu chuyển tiền gấp: impact cao, có thể xem xét nếu nhóm chuyển sang bối cảnh sinh viên.

-

## 10. Tài liệu tham khảo
| # | Nguồn | Link | Dùng cho phần | Ghi chú |
|---:|---|---|---|---|
| 1 | Tuổi Trẻ (28/08/2019), "Tăng suất ăn dinh dưỡng khi nằm viện ra sao?", dẫn nghiên cứu 887 người bệnh tại 6 bệnh viện công ở TP.HCM | https://tuoitre.vn/tang-suat-an-dinh-duong-khi-nam-vien-ra-sao-20190827215444484.htm | Bối cảnh; Assumption #2; Value | Chỉ khoảng 13% thức ăn đến từ khoa Dinh dưỡng; số năm 2019, ở TP.HCM |
| 2 | Báo Pháp Luật Việt Nam (02/04/2015), "Nhiều bệnh viện chưa quan tâm đến dinh dưỡng cho người bệnh" | https://baophapluat.vn/nhieu-benh-vien-chua-quan-tam-den-dinh-duong-cho-nguoi-benh-post193543.html | Bối cảnh; Value | Phần lớn bệnh viện chưa đáp ứng chế độ ăn bệnh lý; bài cũ |
| 3 | Thông tư 18/2020/TT-BYT về hoạt động dinh dưỡng trong bệnh viện (tóm tắt trên LuatVietnam) | https://luatvietnam.vn/tin-van-ban-moi/tren-100-giuong-thanh-lap-khoa-dinh-duong-186-27643-article.html | Bối cảnh; Viability | Hiệu lực 01/01/2021, thay Thông tư 08/2011 |
| 4 | Văn bản hợp nhất 16/VBHN-BYT (2025) quy định hoạt động dinh dưỡng trong bệnh viện | https://datafiles.chinhphu.vn/cpp/files/vbpq/2025/12/16-vbhn-byt.pdf | Viability | Cần đối chiếu để biết nội dung đang có hiệu lực |

-
