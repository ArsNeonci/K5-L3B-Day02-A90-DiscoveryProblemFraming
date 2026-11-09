# CP7 — Dữ kiện và nguồn để Linh tự viết reflection

Ngày tra cứu: 09/11/2026. Phạm vi: hỗ trợ mục 6 trong [báo cáo cá nhân](../individual/2A202603809_ChuQuangLinh.md). CP7 phản ánh trải nghiệm học và làm nhóm; chứng minh đã pitch, nhận phản biện hoặc phỏng vấn người dùng.

## 1. Dữ kiện có thể đối chiếu trong repo

| Nguồn | Nội dung quan sát được | Câu tự soi liên quan | Giới hạn khi sử dụng |
|---|---|---|---|
| [Bài của Mạnh, mục 2–3](../individual/2A202603857_NguyenLeTrongManh.md) | Các vấn đề về chọn món theo lời dặn ăn uống, truyền thông tin thay đổi y lệnh và ghi nhận lý do bỏ thừa thức ăn; shortlist nêu rõ điều còn chưa chắc. | 6.1: actor và đầu ra trong bài của Mạnh khác bài của mình thế nào? | Đây là nội dung  Linh đã nghe pitch ,kiểm chứng các số liệu trong đó. Không dùng để kết luận chuyên môn y tế. |
| [Bài của Khánh, Card #3](../individual/2A202603865_VuDuyKhanh.md) | Card đi học đúng giờ chọn No AI, có phản biện về giờ xuất phát và thời gian dự phòng. | 6.1–6.2: có trường hợp nào chỉnh quy trình đã đủ thay vì dùng AI? | coi phương án đã chứng minh hiệu quả: thời gian và giờ đến trong card còn cần thống nhất. |
| [Bài của Chủ, mục 3](../individual/2A202603873_VuVanChu.md) | Ba card phân biệt đọc nội dung với xác minh qua nguồn độc lập, có phương án checklist và trạng thái chưa xác minh. | 6.1: hoàn thành một bảng thông tin có đồng nghĩa giải quyết vấn đề không? | Chỉ so sánh cách đặt boundary trong file; không chứng thực các nguồn ngoài hoặc ca cá nhân của Chủ. |
| [Bài của Linh, mục 2–3](../individual/2A202603809_ChuQuangLinh.md) | Linh cung cấp kiểm bài khoảng 10 phút, từng sót 2 vấn đề do yêu cầu mơ hồ; làm rõ nhiệm vụ 20 phút, 3 lượt hỏi; chốt việc 45 phút, 2 việc thiếu người. | 6.3, 6.5: dữ liệu mới làm thay đổi baseline và trọng tâm chất lượng như thế nào? | Đây là hồi tưởng cá nhân, chưa có số phút từng bước. |
| [Báo cáo nhóm](../team/group_report.md), [TEAM.md](../../TEAM.md) | Linh đã chốt card chọn món theo lời dặn trong chat; bản phân tích đề xuất No AI/Rule và Not Yet; chưa có kiểm chứng tại cơ sở. | 6.7: tự giải thích cùng card, phân biệt lựa chọn candidate với sẵn sàng triển khai. | Phân công trong TEAM. Quyết định phân tích chưa phải biên bản cả nhóm biểu quyết. |

## 2. Ba nguồn chính thức đã mở và đọc

Những nguồn này liên quan hướng cá nhân #1 “hiểu yêu cầu và kiểm tra bài trước nộp”, không phải research của card suất ăn đã chọn. Chỉ dùng nếu phản ánh việc tìm hiểu cá nhân thực tế; phần research nhóm đã được bổ sung tại [mục 3.3 của bản chung](../team/group_report.md) với R0–R3.

| Nguồn chính thức | Nội dung được nguồn hỗ trợ | Có thể suy nghĩ thêm cho bài của Linh | Điều nguồn không chứng minh |
|---|---|---|---|
| [GitHub Docs — About tasklists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists) | Danh sách tác vụ Markdown dùng ô đánh dấu để thể hiện hoàn thành/chưa hoàn thành; có cú pháp `- [ ]` và `- [x]`. Tài liệu phân biệt danh sách Markdown với tính năng tasklist blocks đã ngừng cung cấp. | Checklist là một phương án No AI có sẵn cho theo dõi yêu cầu. Cần thêm diễn giải và bằng chứng ở từng mục để xử lý việc hiểu nhầm đề. | Đánh dấu xong không chứng minh đã hiểu đúng hoặc đạt rubric; tài liệu không chứng minh giảm thời gian kiểm bài của Linh. |
| [MoodleDocs — Rubrics](https://docs.moodle.org/503/en/Rubrics) | Rubric gắn tiêu chí với các mức đạt và điểm; có tùy chọn cho học viên xem tiêu chuẩn trước khi nộp. | Có thể chuyển yêu cầu thành tiêu chí quan sát được, phân biệt “có mục” với “đạt mức yêu cầu”. Đây là pattern tham khảo, không cần triển khai Moodle để làm lab. | Không có căn cứ khẳng định LMS của lớp đang bật tùy chọn này hoặc một checklist có thể thay người chấm. |
| [Google Help — Use chat in Gemini Notebook](https://support.google.com/gemininotebook/answer/16179559?hl=en) | Cho phép chọn nguồn để hỏi đáp; câu trả lời có trích dẫn dẫn về nội dung nguồn để kiểm tra. Tài liệu nhắc công cụ có thể sai và người dùng cần kiểm lại. Địa chỉ trợ giúp NotebookLM đã chuyển hướng sang Gemini Notebook khi mở. | Nếu thử hỗ trợ đọc yêu cầu, đầu ra nên chỉ rõ nguồn và đoạn liên quan; người học phải xác nhận cách hiểu. So sánh lợi ích này với checklist trước khi chọn AI. | Có trích dẫn không bảo đảm diễn giải đúng rubric, kiểm hết mọi lỗi hoặc đạt điểm tối đa; chưa có thử nghiệm trên bài của Linh. |

## 3. Gợi ý tự soi theo từng câu CP7

- **6.1:** Chọn một vấn đề của thành viên khác mà bản thân thực sự đã đọc/nghe; chỉ ra actor, bước nghẽn hoặc boundary giúp mình thấy điều gì khác. Nếu mới đọc file, ghi là đọc file, không ghi thành nghe pitch.
- **6.2:** Nhớ lại một đề xuất giải pháp đã thực sự xuất hiện trong thảo luận. Nhóm đã tìm hiểu quy trình trước hay sau đề xuất đó? Nếu chưa có sự kiện này, không tạo một đoạn hội thoại cho đủ câu.
- **6.3:** Phân biệt cập nhật số liệu với đổi quan điểm. Bản nháp đã đổi thời gian kiểm bài từ 30 thành 10 phút và chốt việc từ 25 thành 45 phút khi Linh cung cấp thông tin. Học viên tự xác định điều đó có làm mình đổi cách ưu tiên vấn đề không, và vì sao.
- **6.4:** Chọn một phát hiện từ ba nguồn trên sau khi tự mở và đọc. Phát hiện đó có làm mình bất ngờ không? Có khác giả định trước đó không? Nếu chưa có phỏng vấn/survey, ghi rõ phần đang phản ánh là research tài liệu.
- **6.5:** Dùng chi tiết “10 phút nhưng từng sót 2 vấn đề vì yêu cầu mơ hồ” để tự xác định trường khó nhất: mô tả bottleneck, metric chất lượng, hay cách tách thời gian. Không tự suy ra 2 lỗi/lượt vì Linh chưa cung cấp phạm vi đó.
- **6.6:** Từ trải nghiệm thật, chọn một thay đổi bản thân muốn thực hiện: ghi giờ từng bước, hỏi rõ yêu cầu trước khi làm, xác nhận người nhận việc, hoặc thử checklist. Học viên tự chọn và giải thích, không phải thực hiện tất cả.
- **6.7:** Card chung đã chốt là chọn món theo lời dặn; bản nháp quy trình, metric, boundary, hướng No AI/Rule và Not Yet đã có trong báo cáo nhóm. Linh tự giải thích bằng 5–8 câu, ghi đúng phần nào là giả thuyết và không coi target hoặc ví dụ tổng hợp là kết quả đo thật.

## 4. Kiểm tra bản tự viết

- Mục 6.1–6.6 có tổng ít nhất 200 từ, không tính 6.7 và các bảng.
- Có ví dụ cụ thể và chỉ rõ vai trò cá nhân; không chỉ nhắc lại framework.
- Những điều đã xảy ra, điều dự định làm và điều suy ra từ nguồn được phân biệt rõ.
- Mục 4–5 phản ánh đúng đóng góp và cách dùng AI; không coi nghiên cứu nguồn là phỏng vấn.
- Mục 6.7 khớp bài nhóm, có đủ chuỗi problem → quy trình → metric → boundary → mức can thiệp → quyết định.


