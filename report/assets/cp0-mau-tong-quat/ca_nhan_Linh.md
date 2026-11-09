# Báo cáo cá nhân — Chu Quang Linh

## 1. Thông tin học viên

- Nhân vật: Chu Quang Linh, nhóm A90.
- MSSV theo vai: 2A202603809.
- Vai trò: điều phối, đối chiếu metric và ghi nhận phản biện.
- Card cá nhân muốn pitch: kiểm tra bài trước nộp.
- Card nhóm chọn: bệnh nhân đã biết lời dặn ăn uống nhưng cần biết nhanh món phù hợp.
- Kết quả nhóm: chọn No AI cho vòng đầu, Not Yet cho triển khai.

## 2. Scan problem — CP1

Tôi ghi các vấn đề theo tình huống, động cơ và kết quả. Thời gian trong phần cá nhân là ước lượng từ trải nghiệm, không dùng làm số liệu bệnh nhân trong bài nhóm.

| # | Lăng kính | Job Story | Actor | Dấu hiệu |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi kiểm bài trước nộp, tôi muốn hiểu đúng yêu cầu và biết phần còn thiếu, để không bỏ sót vì hiểu nhầm. | Tôi khi nộp bài | Khoảng 10 phút/lượt; từng sót 2 vấn đề vì yêu cầu mơ hồ |
| 2 | Đọc/tổng hợp nhiều thông tin | Khi nhận nhiệm vụ nhóm, tôi muốn hiểu đầu ra, người phối hợp và hạn, để bắt đầu đúng. | Tôi và người giao việc | Khoảng 20 phút tìm/đọc lại; khoảng 3 lượt hỏi |
| 3 | Lặp lại | Khi kết thúc họp, tôi muốn chốt việc, người phụ trách và hạn, để triển khai đúng cam kết. | Người ghi việc và các thành viên | Khoảng 45 phút chốt việc; 2 việc chưa có người chịu trách nhiệm được xác nhận |
| 4 | Tốn thời gian | Khi tìm lại thông báo, tôi muốn tìm đúng nội dung còn hiệu lực, để tiếp tục làm mà không hỏi lại. | Tôi | Khoảng 2 phút/lần, 6 lần/tuần, tương đương 12 phút/tuần |
| 5 | Phối hợp / pain của người tổng hợp | Khi ghép các phần báo cáo, tôi muốn tìm chỗ trùng, thiếu và mâu thuẫn, để có bản chung nhất quán. | Người tổng hợp và người sửa phần viết | Khoảng 10 phút/lần ghép; 3–5 vòng sửa, chưa cộng thành tổng vì phạm vi mỗi vòng khác nhau |

Tôi giữ các hướng có dấu hiệu cụ thể, bỏ hướng “trợ lý quản lý toàn bộ việc học” vì phạm vi quá rộng. Tôi dùng gợi ý để mở góc nhìn, sau đó chọn lại theo việc bản thân có thể giải thích và quan sát.

## 3. Top 3 Problem Cards — CP2

### 3.1. Chọn top 3

| Rank | Card | Vì sao chọn | Điều chưa chắc |
|---:|---|---|---|
| 1 | Kiểm bài | Có lỗi do hiểu nhầm và đầu ra đối chiếu được bằng rubric | Thời gian từng bước còn là ước lượng |
| 2 | Làm rõ nhiệm vụ | Có thể xác định phạm vi tìm/đọc và số lượt hỏi | Chưa biết mẫu giao việc có đủ giải quyết không |
| 3 | Chốt việc sau họp | Có việc thiếu người nhận và chi phí phối hợp rõ | Cần phân biệt chưa phân công với ghi thiếu |

### Problem Card #1 — Kiểm tra bài

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm bài trước nộp, tôi muốn hiểu đúng yêu cầu và biết phần còn thiếu, để không bỏ sót vì hiểu nhầm. |
| Actor | Tôi, người trực tiếp kiểm báo cáo trước khi nộp |
| Bối cảnh | Có bản nháp, đề và rubric; chưa đến hạn nộp |
| Quy trình | Mở nguồn → đọc/giải nghĩa → đối chiếu → ghi thiếu/sửa nhỏ → kiểm lại |
| Bottleneck | B2 giải nghĩa yêu cầu, khoảng 3 phút; hiểu sai ở đây làm các bước sau đánh dấu nhầm là đủ |
| Impact | Khoảng 10 phút/lượt nhưng từng bỏ sót hai vấn đề; chưa xác định tỷ lệ lỗi theo số lượt |
| Success metric | Không vượt 10 phút kiểm/lượt và không còn vấn đề sót do hiểu nhầm trong 3 lượt tiếp theo; kiểm độc lập bằng cùng rubric, ghi riêng thời gian sửa lớn |
| Không dùng AI | Checklist có diễn giải bằng lời của mình, nguồn và vị trí bài; hỏi lại mục chưa rõ |
| Giả thuyết AI | Phản biện cách hiểu và chỉ nguồn liên quan; người học kiểm lại, không viết thay nội dung cần tự làm |
| Cảm nhận nhanh | No AI trước |

```text
[B1 Mở nguồn: 1'] → [B2 Giải nghĩa: 3'] ← ĐIỂM VƯỚNG
→ [B3 Đối chiếu: 3'] → [B4 Ghi thiếu/sửa nhỏ: 2'] → [B5 Kiểm lại: 1']
Tổng ước lượng: 10 phút; sửa nội dung lớn ghi riêng.
```

### Problem Card #2 — Làm rõ nhiệm vụ

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận nhiệm vụ nhóm, tôi muốn hiểu đầu ra, người phối hợp và hạn, để bắt đầu đúng. |
| Actor | Tôi, thành viên nhận việc |
| Bối cảnh | Nhiệm vụ và thay đổi xuất hiện ở nhiều tin/tài liệu |
| Quy trình | Mở tin → tìm nguồn → đọc/ghép yêu cầu → ghi câu cần hỏi → tự kiểm mô tả đầu ra |
| Bottleneck | B3 đọc/ghép, khoảng 8 phút trong 20 phút tìm và đọc |
| Impact | Mất khoảng 20 phút chuẩn bị hiểu việc và khoảng 3 lượt hỏi; chờ trả lời ghi riêng |
| Success metric | Tìm/đọc từ 20 xuống ≤10 phút, hỏi từ khoảng 3 xuống ≤1 lượt; đầu ra được người giao xác nhận đúng |
| Không dùng AI | Một mô tả nhiệm vụ hiện hành có đầu ra, nguồn, người phối hợp và hạn |
| Giả thuyết AI | Trích bản nháp có nguồn nếu nội dung dài; không tự thêm người hoặc hạn thiếu |
| Cảm nhận nhanh | No AI, cần thử mẫu giao việc trước |

```text
[B1 Mở tin: 2'] → [B2 Tìm nguồn: 5'] → [B3 Đọc/ghép: 8'] ← BOTTLENECK
→ [B4 Ghi điểm cần hỏi: 3'] → [B5 Tự kiểm mô tả: 2']
Tổng ước lượng tìm/đọc/chuẩn bị: 20 phút; các lượt hỏi và chờ phản hồi ghi riêng.
```

### Problem Card #3 — Chốt việc sau họp

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc họp, tôi muốn chốt việc, người phụ trách và hạn, để triển khai đúng cam kết. |
| Actor | Tôi, người tổng hợp việc sau họp |
| Bối cảnh | Ghi chú có cả đề xuất, quyết định và thông tin chưa chốt |
| Quy trình | Gom ghi chú → tách việc → đối chiếu người/hạn → xin xác nhận → gửi bản chốt |
| Bottleneck | B4 xin xác nhận khoảng 15 phút, gồm 10 phút chủ động và 5 phút chờ |
| Impact | Khoảng 45 phút/lượt; từng có 2 việc chưa xác nhận người chịu trách nhiệm |
| Success metric | Tổng từ 45 xuống ≤25 phút trong 3 buổi tiếp theo; không có việc đã chốt thiếu người nhận; mục chưa thống nhất ghi rõ trạng thái |
| Không dùng AI | Ghi việc–người–hạn trong họp, dành phần kết thúc để xác nhận |
| Giả thuyết AI | Trích nháp từ ghi chú, không biến đề xuất thành quyết định hay tự phân công |
| Cảm nhận nhanh | No AI trước |

```text
[B1 Gom: 5'] → [B2 Tách việc: 10'] → [B3 Đối chiếu người/hạn: 10']
→ [B4 Xin xác nhận: 15'] ← BOTTLENECK → [B5 Gửi: 5']
Tổng 45 phút = 40 phút chủ động + 5 phút chờ trong kịch bản này.
```

### Card pitch và phản biện AI

Tôi pitch Card #1 vì có đầu vào và lỗi chất lượng cụ thể. Câu hỏi muốn nhóm phản biện là checklist có giúp hiểu đúng yêu cầu hay chỉ giúp đánh dấu có mục.

| Phản biện AI ở CP2 | Nhận định của tôi | Sửa card |
|---|---|---|
| Chỉ giảm phút chưa bảo đảm không bỏ sót | Đồng ý, vì tôi từng kiểm xong vẫn hiểu sai | Thêm kiểm độc lập cách hiểu và lỗi còn sót |
| Tìm/đọc khác chờ phản hồi | Đồng ý, hai nguyên nhân cần hai cách xử lý | Card #2 ghi riêng hỏi/chờ ngoài 20 phút chuẩn bị |
| Không thể tự gán người cho việc chưa chốt | Đồng ý, đầy đủ hình thức không bằng có người nhận thật | Card #3 có trạng thái chưa chốt và xác nhận người nhận |

## 4. Tôi đã tham gia phần nào — CP3–CP6

| Hoạt động | Tôi đã làm gì? | Kết quả / minh chứng |
|---|---|---|
| Pitch | Trình bày Card #1 kiểm bài | Có phản biện P01, không trở thành card nhóm sau khi chọn |
| Phản biện bạn khác | P04 hỏi Mạnh về đơn vị 20 phút; P07 hỏi Khánh về quan hệ thời gian đọc–tiến độ; P11/P15 hỏi Chủ về kết luận và outcome | Câu trả lời và thay đổi cùng mã tại [sổ phản biện](cp3-phan-bien.md) |
| Nhận phản biện | P01 từ Mạnh, P02 từ Chủ, P03 từ Khánh | Thêm metric chất lượng, tách chờ, phân biệt chưa phân công/ghi thiếu |
| Cluster / OST | Cùng nhóm gom pattern đọc/đối chiếu và chuyển giao | Không đặt chatbot ở tầng opportunity |
| Chọn candidate | Ban đầu ưu tiên kiểm bài, sau đó thống nhất chọn suất ăn với điều kiện kiểm chứng và không cam kết dùng AI | [Mục 2.4 bài nhóm](group_report.md) |
| Kiểm chứng / research | Cùng Mạnh ghi I01–I03, tổng hợp U01/U02; cùng Chủ đối chiếu các link | Có tín hiệu phản bác I03, actor được thu hẹp |
| Quy trình | Kiểm phạm vi một lượt và tổng thời gian với Khánh | 22/18 phút, trung vị 20; không coi là thời gian của mọi bệnh nhân |
| Problem Statement | Đề nghị thêm chất lượng, nguồn và phiên bản vào v1 | V1 khác v0 ở actor, metric và boundary |
| Mức can thiệp | Lập luận chưa thử nhãn/danh sách thì chưa chọn mức cao hơn | Chọn No AI |
| Quyết định | Đề nghị không chuyển Go khi chưa có bảng món và người duyệt | Not Yet, có ngưỡng dừng và bước tiếp theo |

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | Hữu ích | Sai/hời hợt | Tôi sửa gì? |
|---|---|---|---|---|
| CP1 | Gợi thêm góc nhìn sau khi tôi ghi các pain | Nhắc cách viết Job Story | Đề xuất có hướng quá rộng | Giữ ý gắn trải nghiệm và số liệu mình giải thích được |
| CP2 | Phản biện card | Chỉ ra thiếu metric chất lượng và thời gian chờ | Có thể đề xuất tự động hóa trước khi rõ quy trình | Thêm No AI, điều kiện kiểm và boundary |
| CP3 | Không dùng để pitch/phản biện | — | — | Tự ghi câu hỏi, câu trả lời và thay đổi vào sổ |
| CP4 phỏng vấn | Không dùng AI đóng vai người dùng | — | — | Nhóm hỏi người thật, ghi giới hạn từng nguồn |
| CP4 research | Gợi ý case và phản biện claim | Tìm hướng để tra nguồn | Tính năng sản phẩm dễ bị suy ra thành kiến trúc hoặc hiệu quả | Tự mở link, chỉ giữ claim có nguồn, tách khỏi dữ liệu kiểm chứng |
| CP5 | Chuyển mô tả đã thống nhất sang Mermaid | Có sơ đồ nhanh | Có thể gộp hỏi và ghi nhận thành một bước | Kiểm từng bước, giữ duyệt và fallback |
| CP5–CP6 | Chỉ ra lỗ hổng metric, rủi ro và mức can thiệp | Nhắc công chuẩn bị | Đề xuất Go có điều kiện dù còn rủi ro Cao | Nhóm tự chốt v0/v1, No AI và Not Yet |
| CP7 | Gợi ý câu hỏi tự soi | Nhắc điều cần liên hệ với đóng góp | Không biết trải nghiệm của tôi | Tôi tự viết phần trả lời và tự giải thích bài nhóm |

## 6. Reflection — CP7

### 6.1. Tôi học được gì từ các bạn?

Tôi thấy mỗi người tiếp cận vấn đề từ một vai trò khác nhau. Mạnh chú ý cách bệnh nhân chọn món, Khánh quan tâm thời gian và thao tác, Chủ tập trung vào nguồn thông tin và mức chắc chắn của kết luận. Tôi học được rằng một actor rõ chưa đủ; vẫn phải biết họ đang làm bước nào, đầu vào đến từ đâu và thế nào là đầu ra đúng. Các góc nhìn này giúp tôi đặt câu hỏi cụ thể hơn thay vì chỉ nhận xét ý tưởng hay.

### 6.2. Nhóm có bị solution-first không?

Có. Ban đầu hướng suất ăn dễ được nói thành công cụ đề xuất món theo bệnh án. Khi đối chiếu lại, nhóm nhận ra vấn đề cần hiểu là người dùng khó nối lời dặn đã biết với thông tin món. Tôi cùng nhóm tách chatbot và ứng dụng khỏi opportunity, giữ lại các pain rồi mới so sánh cách giải. Nhờ vậy, lựa chọn No AI không còn bị xem là thiếu tham vọng mà là phương án cần thử trước.

### 6.3. Tôi đổi ý sau phản biện thế nào?

Mạnh hỏi ở P01 rằng kiểm bài 10 phút nhưng vẫn sót thì cần tối ưu điều gì. Lúc đầu tôi chú ý việc giảm thời gian, sau đó nhận ra kiểm nhanh mà hiểu nhầm vẫn không có giá trị. Tôi thêm chỉ số lỗi còn sót và cách kiểm độc lập theo cùng rubric. Khi hỏi Mạnh về 20 phút ở P04, tôi cũng thấy mình cần áp dụng cùng yêu cầu về đơn vị và phạm vi cho số liệu của chính mình.

### 6.4. Điều bất ngờ từ kiểm chứng là gì?

I03 làm tôi bất ngờ vì một số người đã được nhân viên hỗ trợ nên không có pain tự đọc từng món như nhóm đang giả định. Nếu chỉ giữ hai ý kiến xác nhận, nhóm có thể viết vấn đề cho mọi bệnh nhân và phóng đại impact. Sau đó chúng tôi thu hẹp actor, giữ kênh hỗ trợ hiện có và ghi baseline 20 phút chỉ từ hai lượt tái hiện. Tôi hiểu rằng tín hiệu phản bác giúp bài rõ hơn, không phải thứ cần loại bỏ.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Khó nhất với tôi là tách điều đã có bằng chứng khỏi điều nhóm muốn thử. Baseline hai lượt nhỏ không đủ để khẳng định thời gian vận hành toàn cơ sở; target 14 phút cũng chưa phải kết quả. Tôi phải kiểm lại các câu mô tả để không đưa giải pháp vào bottleneck và không lấy giảm thời gian thay cho chất lượng. Việc bổ sung nguồn, phiên bản và người kiểm làm boundary cụ thể hơn câu nói chung rằng sẽ có con người giám sát.

### 6.6. Nếu làm lại, tôi sẽ đổi gì?

Tôi sẽ lập sổ nguồn và biểu mẫu ghi thời gian trước khi pitch để tránh dùng cùng một con số với nhiều nghĩa. Tôi cũng sẽ tìm tín hiệu phản bác sớm hơn, hỏi rõ điều kiện nào khiến cách hiện tại đã đủ tốt. Trong phần nhóm, tôi sẽ ghi ngay người hỏi, người nhận và thay đổi sau câu hỏi để cuối buổi không phải nhớ lại. Với kế hoạch thử, tôi sẽ kiểm dữ liệu và người duyệt trước khi dành công bàn công cụ.

### 6.7. Hiểu bài

Vấn đề nhóm chọn là người đã có lời dặn ăn uống nhưng phải tự đọc và đối chiếu nhiều món để lựa chọn. Qua hai lượt tái hiện, tổng thời gian là 22 và 18 phút, trung vị 20 phút, trong đó bước đối chiếu lâu nhất. Nhóm đặt target trung vị không quá 14 phút nhưng chỉ tính đạt khi lựa chọn vẫn khớp bảng duyệt và thông tin thiếu/cũ được chuyển xác nhận. Boundary không cho tự suy đoán thành phần, đổi điều kiện chuyên môn hoặc tự đặt món. Nhóm chọn No AI vì chưa có bằng chứng nhãn/danh sách và hỗ trợ trực tiếp không đủ. Quyết định là Not Yet do còn thiếu bảng món đầy đủ và người nhận trách nhiệm duyệt, cập nhật trước pilot.

## 7. Tài liệu tham khảo

- [Báo cáo nhóm](group_report.md), [sổ phản biện](cp3-phan-bien.md), [bằng chứng CP4](cp4-bang-chung.md), [TEAM](TEAM.md).
- [RUBRIC](../../../RUBRIC.md), [RULES](../../../RULES.md).
