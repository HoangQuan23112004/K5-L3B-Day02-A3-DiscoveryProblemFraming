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

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người nộp thường mất nhiều thời gian đối chiếu yêu cầu với nội dung bài; bước này có thể chiếm 20/45 phút. | Value | 5| | Có — quan sát và bấm giờ từng bước.|
| 2 | Bài thiếu mục chủ yếu vì không phát hiện yêu cầu chưa đáp ứng, thay vì thành viên chưa hoàn thành nội dung. | Value | 5| | Có — xem các trường hợp thiếu mục gần nhất.|
| 3 | Checklist có vị trí bằng chứng giúp giảm tổng thời gian kiểm xuống ≤25 phút/bài. | Usability | 5| | 	Có — thử phương án không AI trước|
| 4 | Nếu checklist chưa đủ, AI có thể gợi ý vị trí bằng chứng mà không khiến người kiểm bỏ sót nhiều hơn. | Feasibility | 5| | Có — dùng bản nộp có chuẩn kiểm độc lập|
| 5 | Người dùng hiểu trạng thái “chưa đủ cơ sở” và kiểm lại đầu ra AI trước khi nộp. | Usability | 5| | Có — quan sát thao tác xác nhận.|

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
