# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: nhóm A3
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Hoàng Dương Anh Quân | **Kiểm tra đủ yêu cầu bài lab:** Khi còn 1 giờ trước hạn nộp, tôi muốn biết bài đã đủ yêu cầu bắt buộc chưa, để tránh mất điểm vì thiếu mục. | Sinh viên phụ trách nộp bài nhóm 4 người. | Đối chiếu 10 yêu cầu với bản nộp: giả định 20/45 phút/bài, 2 bài/tuần. | Thời gian còn 1 giờ trước khi nộp bài là quá ngắn, liệu có đủ thời gian để khắc phục vấn đề AI tìm ra trong bài nộp?(Lâm) |
| 2 | Hoàng Dương Anh Quân | **Đối soát chi phí phòng trọ:** Khi chốt tiền cuối tháng, tôi muốn biết mỗi người đã trả và còn phải trả bao nhiêu, để chia đúng chi phí. | Sinh viên tổng hợp chi cho phòng 4 người. | Đối chiếu người trả, người chịu và khoản trùng: giả định 30/80 phút/kỳ, 30 khoản/tháng. | Chậm vì tính toán hay vì 4 khoản chưa đủ thông tin? Nếu ghi đầy đủ ngay từ đầu, vấn đề còn đáng giải không? |
| 3 | Hoàng Dương Anh Quân | **Chốt lịch học nhóm:** Khi 4 người cần học chung, tôi muốn tìm được khung giờ đủ người, để sớm chốt lịch trước bài kiểm tra. | Sinh viên điều phối nhóm học 4 người. | So sánh lịch và hỏi lại phản hồi mơ hồ: giả định 15/35 phút/lần, 1 lần/tuần. | 35 phút có gồm thời gian chờ không? Nếu không có khung chung, kết quả hợp lệ là gì? |
| 4 | Đinh Hoài Nam | **Không nhận ra sai tư thế:** Khi tự thực hiện squat hoặc push-up, tôi muốn biết tư thế có đúng không, để điều chỉnh kỹ thuật và tập hiệu quả hơn. | Người mới hoặc người tự tập không có HLV theo sát. | Tự kiểm tra tư thế khi đang vận động; chưa đo thời gian và số lỗi bỏ sót. |Sử dụng AI để phân tích hình ảnh động tác, liệu có ảnh hưởng gì đến quyền riêng tư không?(Lâm) |
| 5 | Đinh Hoài Nam | **Người mới khó chọn bài/lịch tập:** Khi mới tập và có mục tiêu cụ thể, tôi muốn chọn bài và lịch phù hợp, để tránh thử nhiều chương trình thiếu căn cứ. | Người mới tập, chưa có lịch ổn định. | So sánh và xác định lịch phù hợp; chưa đo thời gian. |Với vấn đề này, liệu bạn đã có những tiêu chí cụ thể nào để xác định bài tập phù hợp không?(Lâm) |
| 6 | Đinh Hoài Nam | **Khó theo dõi tiến độ tập:** Khi đã tập nhiều tuần, tôi muốn xem thay đổi từ kết quả đã ghi, để đánh giá tiến độ và cân nhắc điều chỉnh. | Người tập muốn theo dõi kết quả qua nhiều buổi. | Tổng hợp và so sánh kết quả; chưa đo. Bước ghi dữ liệu cũng có thể là điểm nghẽn. | Có nhật ký đủ để so sánh không? Nếu chưa ghi dữ liệu, giải tổng hợp có đúng vấn đề gốc không?(Quân) |
| 7 | Lê Đức Trúc Lâm | **Phân loại sự cố thiết bị nhân viên:** Khi nhiều yêu cầu hỗ trợ đến cùng lúc, tôi muốn xác định loại sự cố và mức ưu tiên, để chuyển đúng người và xử lý việc cấp thiết trước. | Nhân viên IT tiếp nhận yêu cầu hỗ trợ thiết bị. | Đọc mô tả, hỏi bổ sung và xác định mức ưu tiên; chưa có quy trình chi tiết hoặc thời gian. | Tiêu chí cấp thiết là gì? Có bao nhiêu ticket/tuần và bao nhiêu ticket bị phân loại lại? |
| 8 | Lê Đức Trúc Lâm | **Đối chiếu lỗ hổng với hệ thống công ty:** Khi có thông báo lỗ hổng mới, tôi muốn biết tài sản nào có thể liên quan, để ưu tiên kiểm tra đúng phạm vi. | Nhân viên IT/bảo mật theo dõi thông báo và danh mục tài sản. | Đối chiếu sản phẩm, phiên bản và điều kiện ảnh hưởng với danh mục tài sản; chưa đo thời gian. | Danh mục tài sản có đủ phiên bản không? Ai kiểm tra kết quả đối chiếu để phát hiện bỏ sót?(Quân) |
| 9 | Lê Đức Trúc Lâm | **Tổng hợp tình trạng mạng:** Khi đến kỳ kiểm tra vận hành, tôi muốn biết bất thường nào cần chú ý từ dữ liệu mạng, để ưu tiên xác minh và báo cáo kịp thời. | Nhân viên IT phụ trách theo dõi mạng nội bộ. | Gom dữ liệu và phân biệt bất thường đáng chú ý với cảnh báo thông thường; chưa rõ nguồn, chu kỳ hoặc thời gian. | Bất thường được xác định bằng ngưỡng nào? Đã có dữ liệu chứng minh báo cáo hiện tại bỏ sót vấn đề chưa? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Đối chiếu với yêu cầu/điều kiện | #1 Kiểm bài lab; #8 Đối chiếu lỗ hổng | Đối chiếu nội dung hoặc đối tượng hiện có với một tập yêu cầu/điều kiện để tìm phần thiếu hay có liên quan. Chung pattern, nhưng khác domain và mức rủi ro; không gộp thành một sản phẩm. |
| B — Tổng hợp dữ liệu đã ghi | #2 Chi phí phòng trọ; #6 Tiến độ tập | Tìm, chuẩn hóa và tổng hợp các bản ghi để có kết quả kiểm tra được. Cần phân biệt thiếu dữ liệu với khó tổng hợp dữ liệu. |
| C — Lựa chọn theo ràng buộc | #3 Lịch học nhóm; #5 Lựa chọn lịch tập | So sánh phương án theo thời gian, mục tiêu hoặc điều kiện tham gia để ra quyết định. |
| D — Phân loại và ưu tiên vận hành | #7 Sự cố thiết bị; #9 Tình trạng mạng | Đọc tín hiệu đầu vào và xác định vấn đề nào cần chú ý trước; cần tiêu chí ưu tiên rõ. |
| E — Tự đánh giá kỹ thuật vận động | #4 Sai tư thế | Đánh giá động tác đang thực hiện; cần dữ liệu quan sát và chuẩn đánh giá từ người có chuyên môn. Giữ riêng vì khác bản chất dữ liệu và cách kiểm chứng. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian kiểm tra một bài lab từ giả định 45 xuống ≤25 phút/bài,
         với 0/8 bài thử nghiệm còn thiếu yêu cầu bắt buộc lúc nộp.
├── Opportunity A: Người nộp phải tìm yêu cầu trong đề, rubric và thông báo bổ sung.
├── Opportunity B: Người kiểm khó xác định đoạn nào trong bài đáp ứng từng yêu cầu.
├── Opportunity C: Nhóm khó nhận ra yêu cầu chưa có bằng chứng trước hạn nộp.
└── Opportunity D: Người kiểm sau khó biết mục nào đã được kiểm và còn thiếu gì.
```

Những ý **loại khỏi tầng opportunity** vì là solution: 
- “Checklist kiểm bài tự động”: là cách giải; opportunity tương ứng là khó biết yêu cầu nào chưa được đáp ứng.
- “Chatbot đọc rubric”: là công cụ; opportunity tương ứng là yêu cầu nằm rải rác và khó tra cứu.
- “Agent tự sửa và nộp bài”: là phương án can thiệp; chưa có bằng chứng cần tự động hóa các hành động này.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 — Kiểm tra bài lab | 5 | 5 | 1 | 5 | 5 | 5 | 5 | **31** |
| #2 — Đối soát chi phí phòng trọ | 5 | 5 | 1 | 5 | 4 | 5 | 5 | **30** |
| #7 — Phân loại sự cố thiết bị | 4 | 3 | 1 | 4 | 4 | 5 | 3 | **24** |


**Candidate được chọn:** Kiểm tra đủ yêu cầu bài lab trước khi nộp.

**Vì sao chọn:** Do có điểm cao nhất và dễ tổ chức kiểm chứng trong điều kiện lớp học. Nếu baseline được xác nhận, giảm 45 xuống 25 phút/bài ở tần suất 2 bài/tuần giúp người nộp tiết kiệm khoảng 40 phút/tuần. Mục tiêu đi kèm là giảm số bài còn thiếu yêu cầu bắt buộc từ giả định 2/8 xuống 0/8; nhanh hơn nhưng bỏ sót nhiều hơn không được coi là thành công. Phạm vi chỉ là kiểm độ đầy đủ của một bài có 10 yêu cầu, chưa chấm toàn bộ tính đúng của nội dung. Chọn problem ở CP3 không đồng nghĩa chọn dùng AI.

**Vì sao chưa chọn các candidate còn lại:**

| Candidate | Lý do chưa chọn ở vòng này | Điều kiện để xem xét lại |
|---|---|---|
| #2 — Chi phí phòng trọ | Chênh #1 chỉ 1 điểm, vẫn là ứng viên mạnh; kỳ đối soát thật diễn ra hằng tháng và phụ thuộc chứng từ của nhiều người. | Có sổ chi 30 khoản và người dùng sẵn sàng tái hiện kỳ chốt; nếu #1 không có pain đáng kể, ưu tiên kiểm chứng #2. |
| #3 — Lịch học nhóm | Cần tách thiếu lịch chung khỏi khó thu thập lịch; mẫu trả lời thống nhất và phép tìm giao có thể đủ. | Sau khi thu lịch theo mẫu, người điều phối vẫn mất nhiều thời gian hoặc vẫn chốt sai lịch. |
| #4 — Sai tư thế | Chưa có baseline hoặc chuẩn xác định đúng/sai; việc kiểm chứng cần người có chuyên môn và dữ liệu động tác. | Có người hướng dẫn đánh giá độc lập, giới hạn một động tác và thống nhất tiêu chí quan sát. |
| #5 — Chọn lịch tập | Chưa xác định “phù hợp” và chưa biết thời gian mất chủ yếu ở tìm, so sánh hay quyết định. | Có một lần chọn lịch thực tế được tái hiện và tập ràng buộc cụ thể. |
| #6 — Tiến độ tập | Chưa rõ dữ liệu đã được ghi đủ hay chưa; có thể điểm nghẽn là ghi dữ liệu thay vì tổng hợp. | Có nhật ký nhiều buổi và đo riêng thời gian ghi, tìm lại, tổng hợp. |
| #7 — Sự cố thiết bị | Chưa có card đầy đủ, bộ ticket và tiêu chí mức khẩn cấp để chấm kết quả phân loại. | Có ticket đã ẩn thông tin riêng, nhãn chuẩn và người IT xác nhận phạm vi. |
| #8 — Đối chiếu lỗ hổng | Phụ thuộc danh mục tài sản, phiên bản và điều kiện ảnh hưởng; chưa rõ dữ liệu đầu vào hoặc cách phát hiện bỏ sót. | Có bộ thông báo và tài sản được phép dùng, cùng người phụ trách kiểm tra kết quả. |
| #9 — Tình trạng mạng | Chưa rõ nguồn log, chu kỳ báo cáo và tiêu chí bất thường; phạm vi dễ mở rộng vượt một buổi lab. | Giới hạn một nguồn dữ liệu, một kỳ báo cáo và bộ tiêu chí bất thường xác nhận được. |

**Xử lý bất đồng (nếu có):**  Mối người thực hiện đưa ra các câu hỏi cho các bạn trong nhóm nhưng kèm theo đó là lý do vì sao đưa ra câu hỏi như vậy để thể hiện quan điểm của mình trước nhóm bày tỏ cách suy nghĩ để cả nhóm xem có hợp lý hay không. Tương tự đối với bạn giải thích, điều này giúp nhóm có thể hiểu được cách suy nghĩ của nhau và giải quyết các vấn đề còn tồn tại.    

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Thang điểm bằng chứng: 1 = mới có giả định; 5 = có nhiều bằng chứng trực tiếp, nhất quán.

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người nộp mất khoảng 45 phút kiểm bài, trong đó đối chiếu yêu cầu chiếm 20 phút. | Value | 5 | 1 | Có — bấm giờ theo từng bước. |
| 2 | Một số bài thiếu mục vì người kiểm không phát hiện yêu cầu chưa đáp ứng, không chỉ vì thành viên chưa làm xong. | Value | 5 | 1 | Có — xem bản nộp và nguyên nhân thiếu mục. |
| 3 | Checklist có vị trí bằng chứng có thể giảm thời gian kiểm xuống ≤25 phút/bài. | Usability | 5 | 1 | Có — thử phương án không AI trước. |
| 4 | AI có thể gợi ý vị trí bằng chứng để giảm công sức đối chiếu mà vẫn giữ chất lượng kiểm tra. | Feasibility | 5 | 1 | Có — so với kết quả kiểm độc lập. |
| 5 | Người dùng có thể hiểu và kiểm lại kết quả AI mà không mất quá nhiều thời gian. | Usability | 4 | 1 | Có — quan sát thao tác kiểm lại. |
| 6 | Tài liệu được phép đưa vào công cụ AI và chi phí phù hợp với quy mô nhóm. | Viability | 4 | 1 | Có — kiểm quy định môn học và công cụ dự kiến. |

**Giả định nhóm ưu tiên kiểm chứng trong buổi này:** #1 và #2.

Nhóm cần xác định việc đối chiếu thực sự là điểm nghẽn hay thời gian chủ yếu nằm ở chờ thành viên bổ sung. Nếu nguyên nhân là bài chưa hoàn thành, công cụ kiểm tra sẽ không giải quyết được vấn đề chính.

### 3.2. Kiểm chứng

**Cách dùng:** Phỏng vấn theo 5 câu hỏi, kết hợp đối chiếu bản nộp và rubric.

**Quy mô mô phỏng:**

- 3 sinh viên từng phụ trách nộp bài nhóm.
- Mỗi người trả lời 5 câu hỏi, tổng cộng 15 lượt trả lời.
- 8 bản nộp được dùng để đối chiếu mức độ đầy đủ.
- 3 lượt tái hiện thao tác kiểm bài để ước lượng thời gian.

**Năm câu hỏi phỏng vấn:**

1. Lần gần nhất bạn kiểm bài nhóm trước khi nộp diễn ra như thế nào?
2. Bạn mất bao lâu và bước nào mất nhiều thời gian nhất?
3. Nếu bài thiếu mục, nguyên nhân là chưa làm xong hay chưa phát hiện ra?
4. Bạn đang dùng cách nào để hạn chế bỏ sót?
5. Nếu có bảng yêu cầu kèm vị trí bằng chứng, bạn có dễ kiểm hơn không?

#### Interview snapshot 1

| Trường | Nội dung |
|---|---|
| Người được hỏi Hùng |  sinh viên thường phụ trách nộp bài nhóm. |
| Câu nói đáng nhớ nhất | Không có trích dẫn thực tế. Ý kiến mô phỏng: khó nhất là tìm đoạn đáp ứng từng yêu cầu. |
| Lần gần nhất gặp vấn đề này | Bản nộp có phần kết quả nhưng thiếu phần giải thích theo rubric. |
| Hiện đang xử lý bằng cách nào (workaround)? | Mở đề và bài cạnh nhau, kiểm lần lượt. |
| Mất bao lâu, bao lần? | Ước lượng 45 phút/bài, khoảng 2 bài/tuần. |
| Insight / opportunity rút ra | Cần gắn từng yêu cầu với vị trí bằng chứng để giảm tìm kiếm. |

#### Interview snapshot 2

| Trường | Nội dung |
|---|---|
| Người được hỏi Lan |  Sinh viên tổng hợp nội dung của các thành viên. |
| Câu nói đáng nhớ nhất | Không có trích dẫn thực tế. Ý kiến mô phỏng: có mục đã được làm nhưng chưa đưa vào bản cuối. |
| Lần gần nhất gặp vấn đề này | Thành viên gửi phần bổ sung riêng, người tổng hợp chưa cập nhật trước lượt kiểm cuối. |
| Hiện đang xử lý bằng cách nào (workaround)? | Nhắn từng người xác nhận và kiểm lại file chung. |
| Mất bao lâu, bao lần? | Ước lượng 50 phút/bài; có thời gian chờ được ghi riêng. |
| Insight / opportunity rút ra | Cần xác định bản cuối và trạng thái từng yêu cầu, không chỉ kiểm sự hiện diện của tiêu đề. |

#### Interview snapshot 3

| Trường | Nội dung |
|---|---|
| Người được hỏi Tú | Sinh viên kiểm bài bằng checklist cá nhân. |
| Câu nói đáng nhớ nhất | Không có trích dẫn thực tế. Ý kiến mô phỏng: checklist giúp nhớ mục nhưng vẫn phải đọc lại để xác nhận. |
| Lần gần nhất gặp vấn đề này | Bài có đủ tiêu đề nhưng một phần chưa trình bày đủ nội dung được yêu cầu. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đánh dấu checklist rồi đọc lại các mục chưa rõ. |
| Mất bao lâu, bao lần? | Ước lượng 40 phút/bài. |
| Insight / opportunity rút ra | Checklist cần có bằng chứng và trạng thái “chưa đủ cơ sở”. |

**Tổng hợp dữ liệu mô phỏng:**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | 3 người, 5 câu/người | 2/3 trường hợp xem tìm và đối chiếu bằng chứng là phần khó nhất. | 1/3 trường hợp còn chậm do tổng hợp thiếu nội dung từ thành viên. |
| Tái hiện thao tác | 3 lượt | Thời gian 40, 45 và 50 phút; trung bình 45 phút/lượt. Bước đối chiếu trung bình 20 phút. | Các lượt có độ dài bài khác nhau nên chưa đủ để suy rộng. |
| Đối chiếu bản nộp với rubric | 8 bài | 2/8 bài còn thiếu ít nhất một yêu cầu bắt buộc. | Trong 2 bài thiếu, 1 bài liên quan nội dung chưa được đưa vào bản cuối; không phải mọi lỗi đều do kiểm tra. |

**Nhóm đã sửa problem thế nào sau phân tích tình huống mô phỏng:**

- Giới hạn vấn đề vào tìm và đối chiếu bằng chứng cho yêu cầu bắt buộc.
- Bổ sung bước xác nhận phiên bản bản nộp trước khi kiểm.
- Chuyển lượt kiểm đầu sang trước hạn ít nhất 2 giờ.
- Mỗi yêu cầu có trạng thái, vị trí bằng chứng và người xác nhận.
- Thử checklist trước; chỉ cân nhắc AI khi bước đối chiếu vẫn chậm.

### 3.3. Research giải pháp đã có

Nhóm tham khảo các giải pháp liên quan đến kiểm bài theo rubric và kiểm tra tự động. Nội dung dưới đây dựa trên tài liệu chính thức; nhóm chưa chạy thử để đo hiệu quả.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Grammarly AI Grader | [Hướng dẫn AI Grader](https://support.grammarly.com/hc/en-us/articles/38552360525837-AI-Grader-user-guide) | Đọc bài viết và đưa phản hồi dựa trên rubric hoặc hướng dẫn bài tập trước khi nộp. | Cho phép bổ sung rubric; phản hồi ở mức tài liệu và đoạn văn. | Tập trung vào bài viết; chưa chứng minh phù hợp với mọi loại bài lab. Điểm dự đoán không phải điểm chính thức. | Có thể tham khảo cách cung cấp yêu cầu cùng bản nộp để nhận phản hồi cụ thể; nhóm chỉ cần kiểm độ đầy đủ, không cần dự đoán điểm. |
| Gradescope — Grading submissions with rubrics | [Chấm bài bằng rubric](https://guides.gradescope.com/hc/en-us/articles/22249389005709-Grading-submissions-with-rubrics) | Đối chiếu bài nộp với từng tiêu chí và ghi phản hồi. | Giao diện đặt bài nộp và rubric trong cùng quy trình kiểm; tiêu chí được tổ chức theo câu hỏi. | Chủ yếu phục vụ giảng viên và trợ giảng chấm bài, không phải công cụ sinh viên tự kiểm trước khi nộp. | Tổ chức bảng kiểm theo từng yêu cầu; đặt bằng chứng cạnh tiêu chí để giảm chuyển qua lại giữa các nguồn. |
| GitHub Classroom — Autograding | [Kiểm tra tự động bài tập](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding) | Chạy các bài kiểm tra được cấu hình khi người học đẩy bài lên repo. | Kiểm tra lặp lại theo quy tắc, phù hợp với bài lập trình trên GitHub. | Chỉ kiểm được điều kiện đã cấu hình; vượt qua test không chứng minh đã đáp ứng mọi yêu cầu trong báo cáo. | Dùng Rule cho phần có thể kiểm chính xác; giữ bước con người kiểm nội dung và bằng chứng. |

**Kết luận từ research:**

- Đã có giải pháp phản hồi bài viết theo rubric và giải pháp kiểm bài bằng test.
- Nhóm cần phân biệt kiểm cấu trúc, kiểm độ đầy đủ và chấm chất lượng nội dung.
- Phương án thử đầu tiên vẫn là checklist kết hợp Rule.
- Nếu thử Workflow AI, đầu ra cần gồm: yêu cầu, vị trí bằng chứng, trạng thái và điểm cần người dùng xác nhận.
- Chưa kết luận giải pháp hiện có không đáp ứng nhu cầu; cần thử trên cùng bộ bài trước khi quyết định xây thêm công cụ.

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
[1. Mở đề, rubric, thông báo: 5']
                ↓
[2. Liệt kê yêu cầu bắt buộc: 7']
                ↓
[3. Đối chiếu với bản nộp: 20'] ← BOTTLENECK
                ↓
[4. Ghi mục thiếu, liên hệ bổ sung: 8']
                ↓
[5. Kiểm tên file, định dạng và nộp: 5']

Tổng ước lượng: 45 phút thao tác/bài.
Thời gian chờ và thời gian sửa nội dung được ghi riêng.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người nộp | Đề, rubric, thông báo | Bộ nguồn yêu cầu | 5 phút/bài | Xác nhận phiên bản hiện hành. |
| 2 | Người nộp | Bộ nguồn yêu cầu | Danh sách 10 yêu cầu | 7 phút/bài | Phân biệt bắt buộc và khuyến nghị. |
| 3 | Người kiểm | Danh sách và bản nộp | Bảng đối chiếu | 20 phút/bài | Phải tìm bằng chứng cho từng mục. |
| 4 | Người nộp | Danh sách thiếu | Yêu cầu bổ sung cho thành viên | 8 phút/bài | Chỉ tính thao tác liên hệ, ghi nhận. |
| 5 | Người nộp | Bản cuối | Bài được nộp | 5 phút/bài | Kiểm file trước khi gửi. |

**Bottleneck chính:** Bước 3 chiếm khoảng 44% tổng thời gian. Người kiểm phải chuyển qua lại giữa nhiều nguồn và tìm đoạn đáp ứng từng yêu cầu.

### 4.2. Quy trình tương lai

**Vòng thử đầu: No AI kết hợp Rule.**

```text
[CON NGƯỜI — 5']
Lập và xác nhận checklist từ nguồn yêu cầu
                ↓
[CON NGƯỜI — 10']
Gắn từng yêu cầu với vị trí bằng chứng trong bài
                ↓
[RULE + CON NGƯỜI — 2']
Kiểm tên file, đuôi file và file bắt buộc
                ↓
[CON NGƯỜI — 5']
Kiểm mục chưa rõ và giao việc bổ sung
                ↓
[CON NGƯỜI — 3']
Rà bản cuối và tự nộp

Mục tiêu: ≤25 phút thao tác/bài.
```

Chi phí lập checklist vẫn được tính vào tổng thời gian dù thực hiện từ lúc nhận đề. Lượt kiểm đầu diễn ra trước hạn ít nhất 2 giờ.

**Workflow AI dự phòng nếu checklist chưa đủ:**

```text
[CON NGƯỜI]
Xác nhận yêu cầu và bản nộp được phép sử dụng
                ↓
[AI]
Gợi ý vị trí bằng chứng cho từng yêu cầu
                ↓
[CON NGƯỜI — HITL]
Mở nguồn, kiểm từng gợi ý và xác nhận trạng thái
                ↓
[RULE]
Kiểm cấu trúc file
                ↓
[CON NGƯỜI]
Bổ sung, kiểm bản cuối và tự nộp
```

**Boundary:**

- AI chỉ gợi ý bằng chứng và mục cần kiểm lại.
- AI không tự sửa, chấm điểm hoặc nộp bài.
- Không có bằng chứng thì ghi “chưa đủ cơ sở”.
- Người nộp chịu trách nhiệm xác nhận bản cuối.

**Phương án quay về:** Khi AI dẫn sai hoặc không đọc được file, chuyển sang checklist và kiểm thủ công. Thời gian xử lý lỗi được tính vào tổng công sức.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---|---|---|
| Số bước chính | 5 | 5 | Tối ưu công sức trong bước. |
| Tổng thời gian | 45 phút/bài | ≤25 phút/bài | Bao gồm chuẩn bị và kiểm lại. |
| Số bước hoàn toàn thủ công | 5 | 4 | Một bước có Rule hỗ trợ. |
| Bottleneck chính | Đối chiếu: 20 phút | Đối chiếu: ≤10 phút | Cần đo khi thử. |
| Bài còn thiếu mục | 2/8 bài | 0/8 bài | Chất lượng do người khác kiểm độc lập. |
| Rủi ro mới phát sinh | Kiểm thiếu nhất quán | Tin checklist hoặc cảnh báo máy quá mức | Cần bằng chứng và người xác nhận. |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách kiểm và nộp bài nhóm 4 người. |
| **Quy trình** | Gom yêu cầu → liệt kê → đối chiếu → yêu cầu bổ sung → kiểm file và nộp. |
| **Bottleneck** | Đối chiếu 10 yêu cầu với bản nộp mất khoảng 20/45 phút. |
| **Impact** | Ước lượng 90 phút kiểm bài/tuần ở tần suất 2 bài; 2/8 bài vẫn thiếu ít nhất một yêu cầu bắt buộc. |
| **Success Metric** (baseline → target, cách đo) | 45 → ≤25 phút/bài; 2/8 → 0/8 bài thiếu mục. Bấm giờ từng bước và có thành viên kiểm độc lập. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Chỉ kiểm độ đầy đủ; không tự sửa, chấm điểm hoặc nộp. Con người kiểm nguồn và xác nhận kết quả cuối. |

**Phản biện nhận được và hướng điều chỉnh:**

- Lâm đặt câu hỏi về việc chỉ còn 1 giờ trước hạn nộp. Nhóm tiếp thu, đề xuất kiểm lượt đầu trước hạn ít nhất 2 giờ.
- AI hỗ trợ phản biện rằng có tiêu đề chưa đồng nghĩa đáp ứng yêu cầu. Bản đề xuất bổ sung vị trí bằng chứng cho từng mục.
- AI gợi ý thử checklist trước. Bản đề xuất dùng No AI/Rule làm phương án đầu tiên.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô:** Độ mơ hồ trung bình × độ phức tạp thấp.

**Vì sao:** Quy trình có thứ tự rõ và phạm vi nhỏ. Phần mơ hồ nằm ở cách hiểu yêu cầu và xác định bằng chứng; phần tên, đuôi và file bắt buộc có thể kiểm bằng Rule.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Checklist, phân công người kiểm, kiểm sớm. | Đạt thời gian và chất lượng mục tiêu. | Checklist thiếu hoặc đánh dấu hình thức. | Chọn làm phương án đầu tiên. |
| **Rule** | Kiểm tên, đuôi và file bắt buộc. | Điều kiện được mô tả chính xác. | Không kiểm được nội dung ngữ nghĩa. | Chọn hỗ trợ cấu trúc. |
| **Workflow** | AI gợi ý bằng chứng theo trình tự cố định, người dùng xác nhận. | Checklist chưa đủ và bottleneck đối chiếu được xác nhận. | Dẫn sai, bỏ sót, tăng công kiểm lại. | Dự phòng có điều kiện. |
| **Agent** | Tự chọn hành động, sửa hoặc nộp bài. | Chưa có nhu cầu phù hợp trong phạm vi này. | Vượt quyền, khó kiểm soát thay đổi. | Không chọn. |

**Mức chọn:** No AI kết hợp Rule cho vòng thử đầu; Workflow là phương án dự phòng.

**Vì sao không chọn mức đơn giản hơn:** No AI vẫn là đối chứng chính. Rule được thêm cho các điều kiện cấu trúc rõ ràng để giảm thao tác lặp. Nếu chi phí thiết lập lớn hơn lợi ích, nhóm giữ checklist thủ công.

### 6.3. AI Canvas rút gọn

Canvas áp dụng khi thử Workflow dự phòng.

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Gợi ý vị trí đáp ứng và các yêu cầu chưa đủ bằng chứng. |
| **Judgment** — con người cân nhắc, quyết định gì? | Bằng chứng có thực sự đáp ứng yêu cầu không. |
| **Action** — hành động cuối cùng là gì, ai làm? | Thành viên bổ sung; người nộp kiểm cuối và nộp bài. |
| **Outcome** — đo kết quả bằng gì? | Tổng thời gian, số mục bỏ sót và công sức kiểm lại. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Đề, rubric, thông báo và bản nộp. Cần xác nhận phiên bản và quyền sử dụng trước khi chạy. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Bảng kiểm độc lập và nhật ký lỗi của từng lần thử. |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ hay giao hẳn việc?** Thiết kế đề xuất là hỗ trợ (augment), vì người nộp vẫn cần xác nhận yêu cầu và chịu trách nhiệm với bài. Đây là lựa chọn thiết kế, chưa phải kết luận từ phỏng vấn.
- **Báo nhầm hay bỏ sót tệ hơn?** Bỏ sót đáng ngại hơn vì làm nhóm tin bài đã đủ. Thiết kế yêu cầu nguồn dẫn, trạng thái “chưa đủ cơ sở” và bước con người xác nhận. Báo nhầm cũng được ghi nhận vì làm tăng thời gian kiểm.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên phụ trách kiểm và nộp bài nhóm 4 người. |
| **Quy trình** | Lập checklist → gắn bằng chứng → kiểm cấu trúc → xử lý mục chưa rõ → rà bản cuối và nộp. |
| **Bottleneck** | Tìm và đối chiếu bằng chứng; cần phân biệt với việc nội dung chưa hoàn thành. |
| **Impact** | Ước lượng 90 phút/tuần và nguy cơ thiếu mục ảnh hưởng bài chung. |
| **Success Metric** (baseline → target, cách đo) | 45 → ≤25 phút/bài; 2/8 → 0/8 bài thiếu mục. So 8 bài baseline và 8 bài thử có phạm vi tương đương; ghi riêng chờ và sửa nội dung. |
| **Boundary** | Kiểm độ đầy đủ; không chấm toàn bộ tính đúng; không tự sửa hoặc nộp; chỉ dùng tài liệu được phép. |
| **AI intervention point** | Gợi ý vị trí bằng chứng sau khi checklist chưa đạt mục tiêu. |
| **Mức chọn** | No AI + Rule; Workflow dự phòng. |
| **Rủi ro & người kiểm tra** | Người nộp kiểm từng mục; một thành viên khác kiểm độc lập bản cuối. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Thời điểm | Kiểm sát hạn | Kiểm lượt đầu trước hạn ít nhất 2 giờ | Có thời gian bổ sung. |
| Bottleneck | Đối chiếu chậm | Phân biệt đối chiếu chậm với chưa hoàn thành | Tránh giải sai nguyên nhân. |
| Phương án | Chưa chốt | Checklist và Rule trước | Có đối chứng đơn giản. |
| Metric | Tổng thời gian | Tính cả chuẩn bị, kiểm lại, xử lý lỗi | Đánh giá đúng công sức. |
| Boundary | Con người kiểm cuối | Xác nhận từng yêu cầu với bằng chứng | Hạn chế tin kết quả máy quá mức. |

**Tiêu chí đánh giá đầu ra của AI nếu thử Workflow:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Bao phủ yêu cầu | Mỗi yêu cầu có một dòng đối chiếu. | Bỏ hoặc tự thêm yêu cầu. |
| 2 | Bằng chứng chính xác | Dẫn tới nội dung tồn tại, đúng phiên bản. | Bịa đoạn hoặc dẫn sai. |
| 3 | Thể hiện thiếu chắc chắn | Ghi “chưa đủ cơ sở” khi không xác nhận được. | Suy đoán rồi kết luận hoàn tất. |
| 4 | Phát hiện mục thiếu | Không bỏ sót mục thiếu trong bộ thử có chuẩn độc lập. | Báo đủ cho mục thực tế thiếu. |
| 5 | Hiệu quả sử dụng | Tổng quy trình ≤25 phút và giữ chất lượng. | Kiểm lại làm mất lợi ích hoặc tăng bỏ sót. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

Đánh giá áp dụng cho Workflow AI dự kiến.

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Cao | Checklist có thể đã đủ; chưa có thử nghiệm so sánh. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | TB | Bảng đối chiếu dễ trình bày nhưng chưa thử với người dùng. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | TB | Phạm vi nhỏ nhưng chưa đánh giá chất lượng tìm bằng chứng. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Cần kiểm quy định môn học, quyền dữ liệu và chi phí; nhóm tự vận hành pilot. |

### 8.2. Kết luận

**Quyết định:** Not Yet đối với triển khai Workflow AI.

**Lý do:** Problem có phạm vi rõ nhưng cần xác nhận nguyên nhân và xem checklist có giải quyết đủ không.

**Nếu Go — pilot nhỏ nhất:**

Một đề, một rubric, một bản nộp có khoảng 10 yêu cầu; người kiểm độc lập lập chuẩn đối chiếu. AI chỉ gợi ý bằng chứng, không tự sửa hoặc nộp. Chỉ chuyển sang pilot này sau khi đạt điều kiện kiểm chứng.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Tái hiện cách kiểm bài của 3 người từng phụ trách nộp.
- Đo thời gian và xác định nguyên nhân thiếu mục.
- Thử checklist trên 4 bài đầu.
- Xác nhận tài liệu được phép dùng với AI.
- Nếu đối chiếu vẫn là bottleneck và thời gian còn >25 phút/bài, cân nhắc Workflow.

**Nếu No-Go — nên làm gì thay AI:**

Giữ checklist, Rule kiểm cấu trúc, phân công người kiểm và kiểm sớm. Nếu chậm do nội dung chưa hoàn thành, chuyển trọng tâm sang quản lý tiến độ.

**Ngưỡng dừng:**

- Nếu checklist đạt mục tiêu sau 4 bài đầu, tiếp tục đánh giá bằng phương án này, chưa thêm AI.
- Nếu Workflow báo đủ cho mục thực tế thiếu, tạm dừng dùng kết quả đó để quyết định nộp và kiểm thủ công.
- Nếu sau 4 bài dùng Workflow tổng công sức không giảm so với checklist, quay về No AI/Rule.
- Nếu đổi phương án giữa đợt thử, báo cáo riêng từng giai đoạn.

---

## 9. Hạn chế và hướng tiếp theo

- Baseline và mục tiêu đang dựa trên số liệu ước lượng.
- Chưa có kết quả phỏng vấn và thử nghiệm thực tế.
- Phạm vi khoảng 10 yêu cầu chưa đại diện cho bài dài hoặc đồ án phức tạp.
- Chưa đánh giá tài liệu quét, ảnh và bảng biểu khó đọc.
- Tiếp theo: thu dữ liệu, thử checklist, cập nhật Problem Statement và quyết định theo kết quả.

**AI hỗ trợ:** Nhóm sử dụng AI để gợi ý cách trình bày, tổng hợp ý và phản biện phương án. Nhóm rà soát, điều chỉnh và chịu trách nhiệm về nội dung cuối cùng.

---

## 10. Tài liệu tham khảo

1. Grammarly Support. *AI Grader user guide*. Hướng dẫn phản hồi bài viết theo rubric trước khi nộp.  
   https://support.grammarly.com/hc/en-us/articles/38552360525837-AI-Grader-user-guide

2. Gradescope Guides. *Grading submissions with rubrics*. Hướng dẫn tổ chức tiêu chí và đối chiếu với bài nộp.  
   https://guides.gradescope.com/hc/en-us/articles/22249389005709-Grading-submissions-with-rubrics

3. GitHub Docs. *Use autograding*. Hướng dẫn kiểm tra bài tập tự động trong GitHub Classroom.  
   https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding

4. Google PAIR. *People + AI Guidebook*. Tài liệu tham khảo cho phần lựa chọn vai trò AI, quyền kiểm soát của người dùng và xử lý lỗi tại CP6.  
   https://pair.withgoogle.com/guidebook/


