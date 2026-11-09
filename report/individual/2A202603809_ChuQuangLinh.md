# Báo cáo cá nhân — 2A202603809_ChuQuangLinh

> **BẢN MÔ PHỎNG HAI VAI — TÀI LIỆU THAM KHẢO, KHÔNG PHẢI BÀI CÁ NHÂN ĐÃ KIỂM CHỨNG.**
> Học viên đã đề nghị AI đóng hai vai: **AI phản biện** và **Linh**. Bản hiện tại có nội dung CP1–CP2 minh họa; chưa có lời xác nhận trải nghiệm hoặc hoạt động nhóm thật của Chu Quang Linh để điền CP3 và CP7.
> Số liệu trong ví dụ không phải bằng chứng người dùng hay hoạt động nhóm đã xảy ra. Mục 6 giữ câu hỏi và hướng dẫn để học viên tự trả lời. Theo [RUBRIC.md](../../RUBRIC.md), reflection do AI viết thay có C4 = 0; không thể xác nhận bản nháp này đạt 40/40.
> Khi chuẩn bị bản nộp, học viên cần dùng dữ liệu và đóng góp thật, tự thực hiện CP3, tự viết CP7 và công khai việc sử dụng AI. Không đổi nhãn mô phỏng thành kết quả đã thực hiện.

## 1. Thông tin học viên

- Họ tên: Chu Quang Linh
- MSSV: 2A202603809
- Tên nhóm: A90
- Link repo nhóm: https://github.com/ArsNeonci/K5-L3B-Day02-A90-DiscoveryProblemFraming
- Nguồn ý tưởng: 5 đề xuất của AI trong cuộc trao đổi; chưa có bản tự scan của học viên được cung cấp.
- Hướng phân tích đề xuất: ưu tiên vấn đề #1 và xem xét No AI trước; chưa có kết luận triển khai được nhóm xác nhận.
- Quyết định nhóm thực tế: chưa được cung cấp; `report/team/group_report.md` hiện còn là template.
- Hướng dẫn hoàn thiện và bảng ghi bằng chứng: [cp1-ca-nhan-bang-chung-va-tu-kiem.md](../assets/cp1-ca-nhan-bang-chung-va-tu-kiem.md).

---

## 2. Scan problem (CP1)

**Toàn bộ số liệu trong bảng là mô phỏng, không phải kết quả đo.** Bảng trải đủ 4 lăng kính; chưa đáp ứng yêu cầu “dấu hiệu thật” của C1 cho đến khi được thay bằng dữ liệu thực tế.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi chuẩn bị nộp bài lab, tôi muốn biết bài còn thiếu yêu cầu nào, để sửa kịp trước deadline và tránh mất điểm vì bỏ sót. | Sinh viên trực tiếp kiểm tra và nộp bài | 2 lần kiểm tra gần nhất mất 32 và 28 phút; lần thứ nhất còn sót 2 mục sau lượt kiểm tra đầu. Cần thay bằng nhật ký bấm giờ và danh sách mục bị sót. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một phần việc trong bài nhóm, tôi muốn hiểu đầu ra, người phối hợp và hạn hoàn thành, để bắt đầu đúng mà không phải hỏi lại nhiều lần. | Thành viên nhận nhiệm vụ; người giao việc | 3 nhiệm vụ mất trung bình 20 phút để làm rõ; trung bình 3 lượt hỏi lại/nhiệm vụ. Cần thay bằng thời điểm giao việc, lúc xác nhận hiểu và nội dung trao đổi đã ẩn danh. |
| 3 | Lặp lại | Khi kết thúc buổi họp nhóm, tôi muốn xác định các việc đã thống nhất cùng người phụ trách và thời hạn, để triển khai đúng cam kết. | Người ghi biên bản; thành viên thực hiện | 2 buổi họp trong 1 tuần, mỗi buổi mất 25 phút chốt biên bản; 2/8 đầu việc trong một buổi thiếu người hoặc hạn ở bản đầu. Cần thay bằng ghi chú và bản biên bản được xác nhận. |
| 4 | Tốn thời gian | Khi cần xác nhận một yêu cầu đã được giải đáp trong kênh lớp, tôi muốn tìm đúng thông tin còn hiệu lực cùng nguồn gốc, để tiếp tục làm bài mà không phải hỏi lại. | Sinh viên đang làm một bài lab cụ thể | 4 lượt tìm/tuần, trung bình 8 phút/lượt; 1 lượt phải hỏi lại vì gặp thông báo mâu thuẫn. Cần thay bằng nhật ký tìm kiếm và nguồn thông báo. |
| 5 | Pain từ người khác | Khi nhận các phần viết của nhóm để ghép báo cáo, tôi muốn xác định phần trùng, thiếu và mâu thuẫn, để hoàn thiện bản chung nhất quán trước hạn nộp. | Người tổng hợp báo cáo; thành viên phải sửa phần viết | người tổng hợp mất 45 phút/lần ghép báo cáo của 4 thành viên; cần 2 vòng sửa; bản đầu có 3 chỗ mâu thuẫn. Chưa có người thật xác nhận pain này. |

### Nguồn AI

- Trong bản nháp, giữ phạm vi một bài lab, một nhóm và một lần thực hiện để dễ đo; tránh mở rộng thành quản lý toàn bộ việc học. Sẽ giữ lại vì phương án đúng chỉ phù hợp với nhóm user nhỏ thay vì phát triển rộng cho đại chúng.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

**Top 3 dưới đây là đề xuất cá nhân trong bản mô phỏng, chưa phải kết quả lựa chọn của nhóm tại CP3.** Tất cả số phút trong card và sơ đồ đều là số mô phỏng. Các target là mục tiêu đề xuất, chưa phải kết quả đã đạt.

### Bảng chọn top 3

| Rank | Problem | Vì sao đề xuất chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra bài trước nộp (#1) | Có đầu vào là đề, rubric và bài làm; đầu ra là danh sách thiếu sót; dễ đo thời gian và lỗi còn sót | Vấn đề thật nằm ở đối chiếu yêu cầu hay ở chưa hiểu yêu cầu? Checklist có đủ không? |
| 2 | Làm rõ nhiệm vụ được giao (#2) | Có điểm bắt đầu/kết thúc rõ; quan sát được số lượt hỏi lại và thời gian chờ | Người giao việc có thể chuẩn hóa đầu vào ngay từ đầu không? Thời gian chờ chiếm bao nhiêu? |
| 3 | Chốt việc sau họp (#3) | Hoạt động lặp lại; đầu ra kiểm tra được theo việc–người–hạn | Đâu là quyết định thật? Nội dung nào còn mở? Người phụ trách đã xác nhận chưa? |

Hai hướng còn lại được giữ trong bảng scan: #4 cần kiểm tra quyền truy cập và phiên bản thông báo; #5 có thể phụ thuộc nhiều vào chất lượng từng phần viết. Đây là nhận xét chuẩn bị CP2 của AI, không phải lý do loại đã được nhóm thống nhất tại CP3.

### Problem Card #1 — Kiểm tra bài trước nộp

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp bài lab, tôi muốn biết bài còn thiếu yêu cầu nào, để sửa kịp trước deadline và tránh mất điểm vì bỏ sót. |
| Actor | Sinh viên chịu trách nhiệm kiểm tra báo cáo cá nhân trước khi nộp lên repo chung. |
| Thời điểm / bối cảnh | Sau khi có bản nháp, trước deadline của một bài lab; đề, rubric, hướng dẫn nộp và báo cáo đang ở các file khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Mở đúng bộ hướng dẫn → 2. Trích yêu cầu → 3. Đối chiếu với bài làm → 4. Ghi và sửa thiếu sót → 5. Kiểm tra lại cấu trúc và liên kết. Đây là quy trình giả lập, cần học viên xác nhận. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 3, đối chiếu yêu cầu với vị trí tương ứng trong bài, mất 12/30 phút. Chưa được bấm giờ thực tế. |
| Impact (nếu không giải thì sao) | Trong mô phỏng, mất trung bình 30 phút/lượt kiểm tra; một lượt đầu còn bỏ sót 2 mục. Có nguy cơ phải sửa sát hạn; chưa có bằng chứng mất điểm thực tế. |
| Success metric (baseline → target) | Baseline mô phỏng: (32 + 28)/2 = 30 phút/lượt. Target đề xuất: ≤15 phút/lượt trên bài có phạm vi tương đương. Chất lượng: không còn thiếu mục bắt buộc trong checklist đã đối chiếu với rubric. Khi thử thật, bấm giờ toàn bộ lượt kiểm tra và nhờ người khác đối chiếu lại trên cùng bộ yêu cầu. |
| Phương án không dùng AI | Lập checklist một lần theo đúng bài lab, mỗi mục có đường dẫn tới nguồn và vị trí trong báo cáo; tự đánh dấu đạt/thiếu/chưa rõ. Có thể dùng Rule kiểm tra tên file và sự tồn tại của mục bắt buộc. |
| Giả thuyết về AI (nếu có) | Chỉ thử nếu checklist vẫn không xử lý được yêu cầu nội dung: gợi ý chỗ thiếu và chỉ ra nguồn yêu cầu, vị trí bài tương ứng. Người học tự kiểm và sửa; không để AI viết thay bài, tự nộp hoặc tự kết luận điểm số. |
| Cảm nhận nhanh | Chưa biết; thử No AI trước. Chưa có bằng chứng cần Workflow hoặc Agent. |

Quy trình nháp hiện tại — **mô phỏng, tổng 30 phút**:

```text
[1 Mở hướng dẫn: 3'] → [2 Trích yêu cầu: 6']
→ [3 Đối chiếu từng mục với bài: 12'] ← BOTTLENECK GIẢ ĐỊNH
→ [4 Ghi và sửa thiếu sót: 6'] → [5 Kiểm tra lại: 3']
```

### Problem Card #2 — Làm rõ nhiệm vụ được giao

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một phần việc trong bài nhóm, tôi muốn hiểu đầu ra, người phối hợp và hạn hoàn thành, để bắt đầu đúng mà không phải hỏi lại nhiều lần. |
| Actor | Thành viên mới nhận một nhiệm vụ cụ thể trong nhóm làm bài lab. |
| Thời điểm / bối cảnh | Sau khi được giao việc qua kênh chat; yêu cầu hoặc thay đổi nằm ở nhiều tin nhắn và tài liệu. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc tin giao việc → 2. Tìm tài liệu liên quan → 3. Ghép yêu cầu và thay đổi → 4. Hỏi, chờ làm rõ → 5. Xác nhận đầu ra và bắt đầu làm. Đây là quy trình giả lập. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 3 mất 8 phút để xác định yêu cầu đang có hiệu lực. Bước 4 mất 5 phút nhưng phải đo riêng thời gian hỏi chủ động và thời gian chờ; dữ liệu thật có thể cho thấy chờ mới là nghẽn chính. |
| Impact (nếu không giải thì sao) | Mô phỏng: 20 phút/nhiệm vụ, 3 nhiệm vụ tương đương 60 phút làm rõ; trung bình 3 lượt hỏi lại/nhiệm vụ. Chưa tính thời gian thực hiện và chưa có bằng chứng làm lại. |
| Success metric (baseline → target) | Baseline mô phỏng: 20 phút/nhiệm vụ và 3 lượt hỏi lại. Target đề xuất: ≤10 phút và ≤1 lượt hỏi lại. Đo từ lúc đọc giao việc đến lúc xác nhận hiểu; ghi riêng thời gian chủ động/chờ. Chất lượng: mô tả đầu ra, người phối hợp và hạn được người giao xác nhận đúng trước khi bắt đầu. |
| Phương án không dùng AI | Người giao dùng mẫu có mục tiêu, đầu ra, nguồn yêu cầu, người phối hợp và deadline; giữ một mô tả nhiệm vụ hiện hành; người nhận xác nhận lại các mục còn thiếu. |
| Giả thuyết về AI (nếu có) | Nếu đầu vào vẫn là nhiều đoạn văn, AI có thể trích bản nháp mô tả nhiệm vụ có nguồn. Thiếu deadline hoặc người phụ trách phải ghi “chưa xác định”; người giao xác nhận, AI không tự đặt hạn hay phân công. |
| Cảm nhận nhanh | Chưa biết; ưu tiên No AI. Chỉ cân nhắc Workflow nếu mẫu giao việc không đủ và còn mất thời gian tổng hợp ngữ cảnh. |

Quy trình nháp hiện tại — **mô phỏng, tổng 20 phút**:

```text
[1 Đọc giao việc: 2'] → [2 Tìm tài liệu: 3']
→ [3 Ghép yêu cầu và thay đổi: 8'] ← BOTTLENECK GIẢ ĐỊNH
→ [4 Hỏi và chờ làm rõ: 5'] → [5 Xác nhận hiểu: 2']
```

Tổng trên chỉ là một kịch bản. Khi đo thật, cần tách phút thao tác và phút chờ; không suy ra rằng AI có thể giảm thời gian chờ người giao việc.

### Problem Card #3 — Chốt việc sau họp

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc buổi họp nhóm, tôi muốn xác định các việc đã thống nhất cùng người phụ trách và thời hạn, để triển khai đúng cam kết. |
| Actor | Thành viên chịu trách nhiệm ghi và gửi biên bản của một buổi họp nhóm bài lab. |
| Thời điểm / bối cảnh | Ngay sau họp, khi ghi chú còn gồm cả đề xuất, ý kiến chưa thống nhất và quyết định. |
| Quy trình hiện tại (3–7 bước) | 1. Gom ghi chú → 2. Tách quyết định và việc cần làm → 3. Đối chiếu người, hạn, điểm chưa rõ → 4. Xin nhóm xác nhận → 5. Gửi bản chốt. Đây là quy trình giả lập. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: bước 2 mất 10/25 phút để phân biệt điều đã chốt với đề xuất chưa được đồng ý. |
| Impact (nếu không giải thì sao) | Mô phỏng: 25 phút/buổi, 2 buổi/tuần thành 50 phút/tuần; một bản đầu có 2/8 việc thiếu người hoặc hạn. Chưa có bằng chứng việc bị trễ thực tế. |
| Success metric (baseline → target) | Baseline mô phỏng: 25 phút/buổi → target đề xuất ≤12 phút/buổi. Trong bản chốt, 100% việc đã thống nhất phải có người và hạn được xác nhận; nội dung chưa chốt được đánh dấu rõ. Đo cả thời gian ghi biên bản, xin xác nhận và sửa; kiểm lại với ghi chú được phép sử dụng. |
| Phương án không dùng AI | Ghi trực tiếp theo mẫu việc–người–hạn–trạng thái trong cuộc họp; dành phần kết thúc để nhóm xác nhận; lưu ý riêng những nội dung chưa chốt. |
| Giả thuyết về AI (nếu có) | AI chỉ trích bản nháp từ ghi chú được phép sử dụng, gắn nguồn cho từng việc. Không biến đề xuất thành quyết định; không tự đặt hạn, giao việc hoặc gửi biên bản. Người ghi và người nhận việc xác nhận trước khi dùng. |
| Cảm nhận nhanh | Chưa biết; ưu tiên No AI. Chỉ thử Workflow nếu phần ghi chú tự do vẫn gây tốn thời gian sau khi đã chuẩn hóa họp. |

Quy trình nháp hiện tại — **mô phỏng, tổng 25 phút**:

```text
[1 Gom ghi chú: 3']
→ [2 Tách quyết định và việc cần làm: 10'] ← BOTTLENECK GIẢ ĐỊNH
→ [3 Đối chiếu người và hạn: 5'] → [4 Xin xác nhận: 5']
→ [5 Gửi bản chốt: 2']
```

### Card dự kiến muốn pitch nhất

- Đề xuất từ bản nháp: Card #1, vì đầu vào và tiêu chí đối chiếu có thể giới hạn trong một bài lab.
- Học viên tự xác nhận card lựa chọn và lý do sau khi thay dữ liệu mô phỏng: **[CẦN TỰ ĐIỀN]**.
- Câu hỏi muốn nhóm phản biện tại CP3: **[HỌC VIÊN TỰ ĐẶT; KHÔNG DÙNG AI VIẾT THAY]**.

### AI đã phản biện card thế nào

Đây là phản biện AI thực hiện cho bản nháp hiện tại. Phần phản hồi được AI đề xuất bằng ngôi “tôi” để học viên xem xét và xác nhận; chưa phải nhận định cá nhân đã được học viên xác nhận. Cột sửa đổi ghi thay đổi thực tế trong bản nháp, không phải hoạt động đã thực hiện ngoài đời.

| Card | Điểm yếu AI chỉ ra | Phản hồi đề xuất — đồng ý và lý do | Thay đổi đã đưa vào bản nháp |
|---|---|---|---|
| #1 | Đo tốc độ mà không đo lỗi còn sót có thể tạo ra lượt kiểm tra nhanh nhưng thiếu chính xác. | Đồng ý. Mục tiêu của tôi là nộp bài đủ yêu cầu, nên giảm thời gian chỉ có ý nghĩa khi không làm tăng số mục bị bỏ sót. Tôi chọn đo cả thời gian kiểm tra và số mục bắt buộc còn thiếu sau lượt kiểm tra, có đối chiếu độc lập theo cùng rubric. | Thêm điều kiện kiểm tra mục bắt buộc và người khác đối chiếu lại trên cùng rubric; giới hạn phạm vi một bài lab. |
| #2 | Không thể quy toàn bộ thời gian làm rõ cho việc đọc hiểu; thời gian chờ người giao là một nguyên nhân khác. | Đồng ý với yêu cầu tách hai loại thời gian, nhưng chưa đủ dữ liệu để kết luận chờ phản hồi là bottleneck chính. Nếu thời gian chờ chiếm phần lớn, tôi cần ưu tiên làm rõ cách giao việc và xác nhận thông tin; hỗ trợ đọc hiểu không tự giải quyết được việc người giao chưa phản hồi. | Yêu cầu tách thời gian chủ động/chờ; đổi bottleneck thành giả thuyết cần kiểm tra; thêm mẫu giao việc làm phương án No AI. |
| #3 | Trích được một câu có vẻ là việc cần làm chưa chứng minh nhóm đã đồng ý; AI dễ tự gán người hoặc hạn. | Đồng ý. Một đề xuất trong ghi chú chưa phải cam kết của nhóm. Tôi chỉ coi một việc là đã chốt khi nội dung, người phụ trách và thời hạn được xác nhận; thông tin thiếu phải để “chưa xác định”. AI có thể hỗ trợ trích nháp, còn quyết định và xác nhận thuộc về con người. | Phân biệt đã chốt/chưa chốt; bổ sung xác nhận người–hạn; cấm tự phân công, đặt hạn và gửi. |
| Cả 3 | Baseline và bottleneck chưa có bằng chứng thật; target chưa chứng minh khả thi. | Đồng ý. Số liệu minh họa giúp tôi hình dung cách đo nhưng chưa chứng minh vấn đề có thật hoặc mục tiêu khả thi. Tôi giữ baseline và bottleneck ở trạng thái cần kiểm chứng, xem target là giả thuyết để thử; trước khi kết luận cần thu thập số đo thật, nêu nguồn và cập nhật đồng bộ card với sơ đồ. | Gắn nhãn mô phỏng cho mọi số liệu, giữ target ở mức đề xuất và bổ sung bảng thu thập bằng chứng. |

Để hoàn tất yêu cầu phản biện của CP2, học viên cần tự xác nhận ít nhất một điểm đồng ý/không đồng ý và sửa card theo dữ liệu của mình. Không chỉ giữ nguyên nhận xét AI.

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

 Các ô dưới đây là chỗ ghi nhận sau khi thực hiện, không phải hoạt động đã diễn ra. CP3 phải tự pitch và tự đặt câu hỏi; không dùng AI để dựng hội thoại phản biện.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | [Card đã pitch; thời điểm; người nghe theo vai trò] | [Ý kiến nhận được; vị trí trong báo cáo nhóm] |
| Phản biện bài của bạn khác | [Câu hỏi thực tế tôi tự đặt; candidate được hỏi] | [Người nhận phản hồi thế nào; thay đổi hoặc lý do giữ nguyên] |
| Nhận phản biện | [Câu hỏi thực tế tôi nhận; vai trò người hỏi] | [Nội dung trước → sau; lý do sửa/không sửa] |
| Gom cluster / cây OST | [Phần thực tế đã tham gia] | [Nhánh hoặc outcome bị ảnh hưởng; nguồn] |
| Chọn candidate problem | [Lập luận thực tế đã đóng góp] | [Kết quả thực tế; không dùng top 3 mô phỏng làm kết luận nhóm] |
| Kiểm chứng / research | [Hoạt động thực tế; nguồn đã kiểm; không ghi tên người được hỏi] | [Tín hiệu xác nhận/phản bác và điều thay đổi] |
| Quy trình nhóm | [Bước đã quan sát/vẽ/kiểm tra] | [Bottleneck hay thời gian đã sửa; dẫn nguồn] |
| Problem Statement | [Trường thực tế đã góp ý] | [Trước → sau và lý do] |
| Mức can thiệp AI | [Lập luận thực tế về mức đơn giản nhất đủ dùng] | [Quyết định thật của nhóm và bằng chứng] |
| Quyết định | [Rủi ro hoặc ngưỡng dừng thực tế đã đóng góp] | [Go / Not Yet / No-Go đã được nhóm chốt] |

---

## 5. Dùng AI

Bảng ghi các thao tác có thể xác nhận từ cuộc trao đổi. Các câu xưng “tôi” ở hai dòng CP1–CP2 chỉ mô tả yêu cầu học viên đã gửi; không suy diễn cảm nhận hoặc trải nghiệm ngoài cuộc trao đổi.

| Checkpoint | AI được dùng để làm gì? | AI hữu ích ở đâu? | AI sai hoặc còn hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Đọc Markdown trong repo; đề xuất 5 hướng; theo yêu cầu tiếp theo tạo tình huống mô phỏng | Diễn đạt Job Story, phân biệt vấn đề với giải pháp và gợi ý cách đo | Không có trải nghiệm hoặc bằng chứng của học viên; số liệu mô phỏng không chứng minh pain thật | Tôi đã yêu cầu AI đọc các file Markdown, đề xuất 5 vấn đề rồi phát triển tình huống minh họa. Tôi chưa cung cấp số đo hoặc bằng chứng trải nghiệm thật trong cuộc trao đổi này. |
| CP2 Problem Card | Phát triển 3 card mô phỏng, quy trình và phản biện | Cụ thể hóa actor, bước nghẽn, metric chất lượng, phương án No AI và giới hạn | Chưa biết quy trình có khớp thực tế; target chưa thử nghiệm; top 3 chưa do học viên xác nhận | Tôi đã yêu cầu phát triển phần cá nhân theo rubric 40 điểm. Chưa có thông tin xác nhận tôi đã đo lại quy trình hoặc tự sửa card theo dữ liệu thực tế. |
| CP3 Pitch + challenge | Không dựng pitch, câu hỏi hay cuộc thảo luận nhóm | Chỉ để các trường ghi nhật ký trống | Chưa có hoạt động CP3 được cung cấp | [Học viên tự thực hiện và ghi nhận] |
| CP4 Research | Chưa thực hiện research bên ngoài trong phiên này | Chưa có | Chưa có link công cụ được kiểm; không dùng bài mẫu làm bằng chứng về sản phẩm hiện tại | [Điền sau nếu thực tế sử dụng AI] |
| CP5 Quy trình | Chưa thực hiện quy trình nhóm CP5; sơ đồ ở mục 3 chỉ thuộc CP2 mô phỏng | Chưa có kết quả CP5 | Chưa có số đo hay quy trình được nhóm xác nhận | [Điền sau nếu thực tế sử dụng AI] |
| CP5–6 Problem Statement | Chưa phản biện Problem Statement của nhóm | Chưa có | Chưa có bản v0/v1 của nhóm để kiểm tra | [Điền sau nếu thực tế sử dụng AI] |
| CP6 Mức can thiệp / quyết định | Chỉ nêu giả thuyết sơ bộ trong card CP2; chưa chọn thay nhóm | Nhắc kiểm tra phương án đơn giản trước | Chưa đủ bằng chứng để kết luận mức can thiệp hoặc Go/Not Yet/No-Go | [Điền sau nếu thực tế sử dụng AI] |
| CP7 Reflection | Giữ câu hỏi tự soi và phần trả lời trống | Hỗ trợ kiểm tra yêu cầu, không tạo trải nghiệm cá nhân | Chưa có reflection do học viên viết | [Học viên tự viết sau hoạt động thật] |

---

## 6. Reflection (CP7)

**Học viên tự viết bằng trải nghiệm thật.** Mục 6.1–6.6 tổng cộng tối thiểu 200 từ, không tính mục 6.7 và các bảng. Không dùng AI viết thay hoặc dùng tình huống mô phỏng như trải nghiệm của mình. Các ghi chú bên dưới chỉ là gợi ý tự soi, không phải câu trả lời.

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Gợi ý tự soi: ghi một candidate thực tế đã nghe và điều mình nhận ra về actor, pain hoặc cách đo.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.2. Nhóm có lúc nào bị “solution-first” không? Nhóm nhận ra và xử lý thế nào?

Gợi ý tự soi: nhớ lại một thời điểm cụ thể, dấu hiệu nhận ra và cách nhóm phản ứng. Nếu không có, trình bày đúng điều mình quan sát được.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Gợi ý tự soi: quan điểm trước đó, phản biện thực tế, bằng chứng và điều đã sửa. Không nhận một sửa đổi của AI là trải nghiệm thảo luận của mình.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?

Gợi ý tự soi: so sánh giả định ban đầu với một tín hiệu thực tế, đặc biệt tín hiệu phản bác; chỉ rõ điều giữ nguyên hoặc thay đổi.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Gợi ý tự soi: chỉ ra một trường đã khó viết và nguyên nhân, gắn với bản Problem Statement thực tế của nhóm.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Gợi ý tự soi: chọn một thay đổi cụ thể về cách thu thập bằng chứng, giới hạn phạm vi hoặc đo kết quả; nói vì sao trải nghiệm vừa rồi dẫn tới thay đổi đó.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI THAM GIA]

### 6.7. Hiểu bài

Tự giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi **problem → quy trình → metric → boundary → mức can thiệp AI → quyết định** của bài nhóm. Phải dựa trên candidate và quyết định thật của nhóm, không lấy card mô phỏng làm kết quả đã chốt.

**Trả lời của học viên:** [TỰ VIẾT SAU KHI NHÓM CHỐT BÀI]

---

## 7. Tài liệu tham khảo

- [README — mục tiêu và đầu ra](../../README.md).
- [RULES — quy định sử dụng AI và bằng chứng](../../RULES.md).
- [CHECKPOINTS — yêu cầu CP1, CP2, CP3 và CP7](../../CHECKPOINTS.md).
- [Worksheet — cấu trúc card và cách kiểm chứng](../../docs/01-worksheet.md).
- [Rubric — C1 đến C5, tổng 40 điểm](../../RUBRIC.md).
- [Submission — quy tắc tên file và nộp bài](../../SUBMISSION.md).
- Cuộc trao đổi hỗ trợ với AI: nguồn của 5 hướng đề xuất, nội dung card mô phỏng và phản biện trong bản nháp này. Chưa có nguồn thực nghiệm bên ngoài.
