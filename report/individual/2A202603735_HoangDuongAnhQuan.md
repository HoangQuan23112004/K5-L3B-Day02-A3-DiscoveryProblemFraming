# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Hoàng Dương Anh Quân
- MSSV: 2A202603735
- Tên nhóm: A3
- Link repo nhóm: https://github.com/HoangQuan23112004/K5-L3B-Day02-A3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi còn 1 giờ trước hạn nộp bài lab, tôi muốn biết bản nộp đã đáp ứng đủ các yêu cầu bắt buộc chưa, để nộp đúng cấu trúc và không mất điểm vì thiếu mục. | Sinh viên phụ trách nộp bài của nhóm 4 người. | Giả định 2 bài/tuần, kiểm tra 45 phút/bài; 2/8 bài vẫn thiếu ít nhất 1 mục bắt buộc. Cần đối chiếu 8 bản nộp, rubric, phản hồi chấm và nhật ký bấm giờ. |
| 2 | Lặp lại | Khi chốt tiền phòng trọ cuối tháng, tôi muốn xác định rõ từng người đã trả và còn phải trả bao nhiêu, để chia đúng chi phí và tránh chuyển tiền nhầm. | Người tổng hợp chi phí và 2 bạn cùng phòng. | Giả định 30 khoản chi/tháng, tổng 6.000.000 đồng; đối soát 80 phút/tháng và 4/30 khoản cần hỏi lại người trả hoặc người sử dụng. Cần kiểm sổ chi, hóa đơn và lịch sử chuyển khoản đã che thông tin riêng. |
| 3 | Tốn thời gian | Khi nhóm 4 người cần học chung trước bài kiểm tra, tôi muốn xác định được một khung giờ đủ người tham dự, để không mất cả buổi nhắn tin mà vẫn chưa chốt được lịch. | Người điều phối và 3 thành viên còn lại. | Giả định 1 lần/tuần, người điều phối thao tác 35 phút/lần, khoảng 25 tin nhắn/lần; 2/4 buổi phải đổi lịch. Cần kiểm thời điểm tin nhắn, số lần đổi lịch và bấm giờ thao tác riêng với thời gian chờ. |
| 4 | Tốn thời gian | Khi chuẩn bị ôn một chương trước kỳ thi, tôi muốn tìm được tài liệu đúng phiên bản và đúng phạm vi thi, để dành thời gian làm bài thay vì tìm lại file. | Sinh viên ôn từ slide, LMS và tin nhắn lớp. | Giả định 3 phiên ôn/tuần, tìm tài liệu 20 phút/phiên; mở nhầm phiên bản ở 2/6 phiên. Cần ghi nhật ký tìm kiếm và đối chiếu thông báo phạm vi thi với phiên bản file. |
| 5 | Tốn thời gian | Khi khách yêu cầu báo giá cho 10 mặt hàng trước 16h, tôi muốn xác định đúng giá, tồn kho và điều kiện giao hàng, để gửi báo giá đúng hạn mà không phải đính chính sau đó. | Nhân viên kinh doanh tại cửa hàng vật tư có 5 nhân viên bán hàng. | Giả định 4 báo giá/ngày, 25 phút/báo giá; riêng tra và đối chiếu thông tin mất 15 phút/báo giá; 3/20 báo giá phải sửa giá hoặc thời gian giao. Cần bấm giờ 20 báo giá và đối chiếu bản gửi khách với bảng giá, sổ kho và tin nhắn xác nhận giao hàng. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi tiếp nhận yêu cầu đổi trả từ một khách đã liên hệ nhiều lần, tôi muốn nắm đủ lịch sử mua hàng, các lần xử lý và chính sách áp dụng, để trả lời nhất quán mà không bắt khách kể lại từ đầu. | Nhân viên chăm sóc khách hàng của cửa hàng trực tuyến, tiếp nhận yêu cầu từ ca trước. | Giả định 12 ca đổi trả phức tạp/tuần, đọc lịch sử trên 3 nguồn mất 18 phút/ca; 3/12 ca phải hỏi lại thông tin khách đã cung cấp. Cần đối chiếu mã đơn, lịch sử hội thoại và phiếu xử lý; ghi thời gian đọc và số câu hỏi trùng. |
| 7 | Pain từ người khác | Khi bắt đầu ca tối ở quán cà phê, tôi muốn biết các đơn chưa hoàn tất, nguyên liệu sắp hết và thiết bị đang lỗi, để phục vụ liên tục mà không phải gọi lại người ca trước. | Nhân viên ca tối nhận bàn giao từ ca sáng tại quán có 6 nhân viên. | Giả định 7 lần bàn giao/tuần; 4/7 lần người nhận ca phải gọi hỏi lại, mất 10 phút thao tác/lần; 2/7 ca có ít nhất 1 đơn phục vụ chậm do thiếu thông tin bàn giao. Cần kiểm sổ bàn giao, lịch sử gọi và thời điểm hoàn tất đơn; xác nhận nguyên nhân với người nhận ca. |
| 8 | Pain từ người khác | Khi xử lý hồ sơ thanh toán đầu tiên sau khi nhận việc, tôi muốn biết đủ giấy tờ, thứ tự duyệt và người phụ trách, để nộp đúng ngay lần đầu và không làm chậm khoản thanh toán. | Nhân viên hành chính mới và kế toán tiếp nhận hồ sơ tại đơn vị. | Giả định nhân viên mới xử lý 5 hồ sơ trong tháng đầu; 2/5 hồ sơ bị trả lại vì thiếu chứng từ; mỗi hồ sơ bị trả mất thêm 30 phút thao tác bổ sung và 1 ngày làm việc chờ duyệt lại. Cần kiểm phiếu trả hồ sơ, danh mục chứng từ, mốc gửi–nhận và bấm giờ thao tác; tách riêng thời gian chờ. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

AI hỗ trợ gợi ý và diễn đạt 4 scan ở trên bao gồm 2, 4, 7, 8 đồng thời phản biện sâu 4 scan dưới đây để làm rõ phạm vi, nguyên nhân và cách kiểm chứng. Các con số vẫn là dự đoán, chưa phải bằng chứng đã thu thập.

| Scan được phản biện | AI phản biện | Giữ / bỏ và vì sao | Điều chỉnh sau phản biện |
|---|---|---|---|
| **#1 — Kiểm tra bài lab trước khi nộp (sinh viên)** | “Bài thiếu mục vì người nộp không phát hiện, hay vì thành viên chưa làm xong? Nếu nguyên nhân là chưa hoàn thành bài, kiểm tra nhanh hơn có giải quyết được không?” | **Bỏ** hướng mở rộng thành chấm điểm toàn bộ bài vì vượt phạm vi và khó xác định chuẩn đúng. | Giới hạn việc kiểm tra ở 10 yêu cầu bắt buộc; tách thời gian kiểm khỏi thời gian chờ bổ sung. Kiểm chứng dự đoán 45 phút/bài và 2/8 bài thiếu mục bằng bản nộp, rubric và phản hồi chấm. |
| **#3 — Chốt lịch học nhóm (sinh viên)** | “35 phút là thời gian điều phối thực sự hay gồm cả chờ trả lời? Nếu cả 4 người không có giờ rảnh chung, tìm lịch nhanh hơn có giúp chốt được buổi học không?” | **Bỏ** giả định rằng tuần nào cũng có thể tìm được lịch phù hợp cho tất cả mọi người. | Chỉ tính thời gian thao tác của người điều phối; ghi riêng thời gian chờ. Giới hạn 4 người và 6 khung giờ ứng viên; cho phép kết luận không có khung chung, đồng thời phân biệt đổi lịch do ghi sai thông tin với việc đột xuất. |
| **#5 — Lập báo giá cho khách (người đi làm)** | “Trong 25 phút/báo giá, mất thời gian vì tìm thông tin hay vì phải chờ kho xác nhận? Nếu bảng giá đã cũ, tổng hợp nhanh hơn có làm báo giá chính xác hơn không?” | **Giữ** nhu cầu đối chiếu giá, tồn kho và giao hàng vì gắn với hạn trả lời khách và số lần phải đính chính.| Tách thời gian tra cứu chủ động khỏi thời gian chờ kho; kiểm tra phiên bản bảng giá và mốc xác nhận tồn kho. Dùng 20 báo giá để kiểm chứng giả định 15 phút tra cứu/báo giá và 3/20 báo giá phải sửa; nhân viên duyệt trước khi gửi. |
| **#6 — Đọc lịch sử đổi trả (người đi làm)** | “Khách phải kể lại vì nhân viên không tìm được thông tin, hay vì lần trước chưa ghi nhận? Nếu dữ liệu thiếu từ đầu, đọc hoặc tóm tắt nhanh hơn có đủ không?” | **Giữ** nhu cầu nắm lịch sử xử lý vì có thể đo thời gian đọc và số lần hỏi trùng.| Chỉ xét ca khách đã liên hệ nhiều lần và có mã đơn để đối chiếu; phân biệt thông tin đã có nhưng chưa tìm thấy với thông tin chưa được ghi. Kiểm chứng dự đoán 18 phút/ca và 3/12 ca hỏi trùng bằng lịch sử hội thoại, đơn hàng và phiếu xử lý; không suy đoán phần lịch sử còn thiếu. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra đủ yêu cầu bài lab trước khi nộp (#1) | Lặp 2 lần/tuần; actor cụ thể; có thể thử với 1 đề, 1 rubric và 1 bản nộp; kiểm được cả thời gian lẫn số mục bỏ sót. | Thiếu mục do không hiểu yêu cầu hay do nhóm chưa làm xong? Bước đối chiếu có thực sự chiếm 20/45 phút không? |
| 2 | Đối soát chi phí phòng trọ (#2) | Gần đời sống; 30 khoản/tháng đủ để thử ở quy mô nhỏ; đo được thời gian và chênh lệch tiền; có phương án Rule rõ ràng để so sánh. | Mất thời gian vì tính toán hay vì thiếu chứng từ? Ba người có thống nhất nguyên tắc chia tiền không? |
| 3 | Chốt lịch học nhóm 4 người (#3) | Lặp hằng tuần; có đầu vào là lịch rảnh; quy trình ngắn; đo được thời gian điều phối và số lần đổi lịch. | Có khung giờ chung thật không? Thành viên đổi lịch vì thông tin sai hay vì việc đột xuất? |

### Problem Card #1 — Kiểm tra đủ yêu cầu bài lab trước khi nộp

| Trường | Nội dung |
|---|---|
| Job Story | Khi còn 1 giờ trước hạn nộp bài lab, tôi muốn biết bản nộp đã đáp ứng đủ các yêu cầu bắt buộc chưa, để nộp đúng cấu trúc và không mất điểm vì thiếu mục. |
| Actor | Sinh viên được giao kiểm tra và nộp bài cho nhóm 4 người; 3 thành viên còn lại chịu ảnh hưởng nếu bài thiếu mục. |
| Thời điểm / bối cảnh | Khoảng 22h–23h, trước hạn nộp 23h59; yêu cầu nằm trong đề, rubric và thông báo bổ sung. Phạm vi thử: 1 bài lab có 10 yêu cầu bắt buộc; chỉ kiểm độ đầy đủ, chưa chấm độ đúng của toàn bộ bài. |
| Quy trình hiện tại (3–7 bước) | 1. Mở đề, rubric, thông báo (5 phút) → 2. Liệt kê 10 yêu cầu bắt buộc (7 phút) → 3. Đối chiếu từng yêu cầu với bản nộp (20 phút) → 4. Đánh dấu mục thiếu và nhờ bổ sung (8 phút thao tác) → 5. Kiểm tên file, định dạng và nộp (5 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: 20/45 phút, khoảng 44% tổng thời gian; phải chuyển qua lại giữa 3 nguồn yêu cầu và bản nộp để tìm bằng chứng cho từng mục. Đây là giả định cần bấm giờ kiểm chứng. |
| Impact (nếu không giải thì sao) | Ước lượng người nộp mất 45 × 2 = 90 phút/tuần. Giả định 2/8 bài còn thiếu ít nhất 1 mục bắt buộc lúc nộp (25%), có thể ảnh hưởng điểm chung của 4 người. Chưa quy đổi thành điểm bị trừ vì chưa có dữ liệu chấm thực tế. |
| Success metric (baseline → target) | Thời gian thao tác của người nộp:** 45 → ≤25 phút/bài. Chất lượng: tỷ lệ bài còn thiếu mục bắt buộc lúc nộp từ giả định 2/8 → 0/8 bài. Cách đo: ghi thời gian từng bước của 8 bài baseline rồi 8 bài thử nghiệm có phạm vi tương đương; ghi riêng thời gian chờ bạn bổ sung. Một thành viên khác đối chiếu độc lập 10 yêu cầu với bản cuối và ghi số mục còn thiếu; không dùng chính đầu ra AI làm chuẩn. |
| Phương án không dùng AI | **No AI:** tạo checklist 10 yêu cầu kèm vị trí bằng chứng, phân công người kiểm trước hạn 2 giờ. **Rule:** kiểm tên file, đuôi file và sự hiện diện của tiêu đề bắt buộc; có tiêu đề chưa chứng minh nội dung đã đáp ứng yêu cầu. Thử checklist trước, chỉ xét AI nếu vẫn mất >25 phút/bài sau 4 bài. |
| Giả thuyết về AI (nếu có) | Nếu bước đối chiếu nội dung vẫn chậm, thử **Workflow** cố định: nhận yêu cầu và bản nộp → gợi ý vị trí đáp ứng/thiếu → người nộp kiểm lại. Mỗi gợi ý phải dẫn tới đoạn yêu cầu và đoạn bài liên quan; AI không tự sửa hoặc tự nộp bài. **Agent** chưa cần vì thứ tự bước đã rõ, không cần tự chọn công cụ hay hành động tiếp theo. |
| Cảm nhận nhanh | **No AI**; **Workflow** là giả thuyết dự phòng nếu checklist và Rule chưa đủ. Chưa chốt dùng AI ở CP2. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 45 phút thao tác/bài × 2 bài/tuần = 90 phút/tuần

[1 Mở 3 nguồn yêu cầu: 5'] → [2 Liệt kê 10 yêu cầu: 7']
→ [3 Đối chiếu yêu cầu với bản nộp: 20'] ← BOTTLENECK
→ [4 Đánh dấu thiếu + nhờ bổ sung: 8'] → [5 Kiểm file + nộp: 5']

Đầu ra: bản nộp cuối cùng và danh sách yêu cầu đã kiểm.
Thời gian chờ bạn sửa/bổ sung được ghi riêng, chưa nằm trong 45 phút.
```

### Problem Card #2 — Đối soát chi phí phòng trọ

| Trường | Nội dung |
|---|---|
| Job Story | Khi chốt tiền phòng trọ cuối tháng, tôi muốn xác định rõ từng người đã trả và còn phải trả bao nhiêu, để chia đúng chi phí và tránh chuyển tiền nhầm. |
| Actor | Một sinh viên tổng hợp sổ chi cho phòng trọ 3 người; mỗi người có thể đã ứng tiền cho các khoản khác nhau. |
| Thời điểm / bối cảnh | Tối cuối tháng, xử lý khoảng 30 khoản với tổng giả định 6.000.000 đồng; có khoản chia đều 3 người và khoản chỉ 2 người sử dụng. Phạm vi thử: 1 phòng, 1 tháng, chỉ đối soát và lập bảng, chưa thực hiện chuyển tiền. |
| Quy trình hiện tại (3–7 bước) | 1. Gom hóa đơn, tin nhắn và xác nhận chuyển tiền (10 phút) → 2. Nhập 30 khoản vào sổ (15 phút) → 3. Đối chiếu khoản trùng, người trả, người sử dụng; hỏi lại 4 khoản chưa rõ (30 phút thao tác) → 4. Tính phần phải chịu và số dư từng người (15 phút) → 5. Gửi bảng và ghi nhận xác nhận (10 phút thao tác). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: 30/80 phút, bằng 37,5% thời gian; thông tin người trả và phạm vi chia tiền thiếu hoặc nằm rải rác. Tính tổng không phải bottleneck được giả định của card này. |
| Impact (nếu không giải thì sao) | Ước lượng mất 80 phút/tháng cho người tổng hợp; 4/30 khoản (13,3%) cần làm rõ, dễ kéo dài việc chốt sổ. Ví dụ rủi ro giả định: một khoản 180.000 đồng bị nhập trùng sẽ làm tổng phân bổ tăng sai 180.000 đồng; đây là tình huống minh họa, chưa phải sự cố đã ghi nhận. |
| Success metric (baseline → target) | Thời gian thao tác: 80 → ≤40 phút/kỳ chốt. Độ đầy đủ: số khoản cần hỏi lại từ 4/30 → ≤1/30. Độ chính xác: chênh lệch giữa tổng tiền phân bổ và tổng chi hợp lệ đã xác nhận = 0 đồng; 30/30 khoản phải đúng người trả, người chịu và quy tắc chia. Cách đo: lấy 1 kỳ baseline và 2 kỳ thử, bấm giờ theo bước, ghi số khoản hỏi lại; 3 người cùng kiểm chứng từ và xác nhận bảng cuối. Với khoản chia không hết, ghi rõ quy tắc phân bổ phần dư 1 đồng. |
| Phương án không dùng AI | **No AI:** thống nhất quy tắc chia, ghi ngay khi chi, mỗi khoản có ngày, số tiền, người trả, người chịu và chứng từ. **Rule:** dùng bảng tính kiểm ô trống, gắn cờ khoản nghi trùng, tính chia và số dư. Không tự xóa khoản bị gắn cờ. Ưu tiên sửa cách ghi đầu vào vì công thức không khôi phục được thông tin chưa ghi. |
| Giả thuyết về AI (nếu có) | Chỉ xét **Workflow** trích xuất ngày, tiền và nội dung từ ảnh hóa đơn nếu nhập liệu vẫn chậm sau khi chuẩn hóa sổ. Người nhập phải đối chiếu ảnh và xác nhận; AI không suy đoán người chịu tiền, không thay đổi quy tắc chia, không chuyển tiền. **Agent** chưa cần vì các phép tính và bước xác nhận đều định sẵn. |
| Cảm nhận nhanh | **Rule**, kết hợp chuẩn hóa quy trình ghi chi; chưa có cơ sở cần AI. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 80 phút thao tác/kỳ chốt, 1 kỳ/tháng

[1 Gom chứng từ: 10'] → [2 Nhập 30 khoản: 15']
→ [3 Đối chiếu + hỏi lại khoản chưa rõ: 30'] ← BOTTLENECK
→ [4 Tính phần chịu + số dư: 15'] → [5 Gửi bảng + ghi xác nhận: 10']

Đầu ra: sổ chi được xác nhận và số tiền từng người cần nhận/trả.
Thời gian chờ bạn cùng phòng trả lời được ghi riêng, chưa nằm trong 80 phút.
```

### Problem Card #3 — Chốt lịch học nhóm 4 người

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhóm 4 người cần học chung trước bài kiểm tra, tôi muốn xác định được một khung giờ đủ người tham dự, để không mất cả buổi nhắn tin mà vẫn chưa chốt được lịch. |
| Actor | Sinh viên điều phối nhóm học 4 người, có thành viên đi làm thêm nên lịch rảnh không giống nhau. |
| Thời điểm / bối cảnh | Tối Chủ nhật, chốt 1 buổi học 90 phút trong tuần tới. Phạm vi chỉ gồm 4 thành viên, 6 khung giờ ứng viên đã thống nhất và một địa điểm cố định; không mở rộng sang tìm phòng hoặc lập kế hoạch học tập. |
| Quy trình hiện tại (3–7 bước) | 1. Gửi đề nghị và 6 khung giờ ứng viên (3 phút) → 2. Đọc, ghi lại phản hồi rời rạc của 4 người (8 phút) → 3. So sánh khung rảnh và hỏi lại phản hồi mơ hồ (15 phút thao tác) → 4. Đề xuất khung phù hợp, lấy xác nhận (6 phút thao tác) → 5. Ghi lịch cuối và nhắc nhóm (3 phút). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: 15/35 phút, khoảng 43% thời gian; phải diễn giải câu như “tối nào cũng được, trừ lúc có ca” rồi kiểm lại khung giờ của từng người. |
| Impact (nếu không giải thì sao) | Giả định người điều phối mất 35 phút/tuần, xử lý khoảng 25 tin nhắn/lần; 2/4 buổi phải đổi lịch sau khi chốt (50%). Chỉ 35 phút là thời gian của người điều phối, không nhân 4 vì chưa đo công sức các thành viên khác. |
| Success metric (baseline → target) | Thời gian điều phối chủ động: 35 → ≤10 phút/lần. Tính ổn định: số buổi phải đổi lịch do thu thập sai/thiếu lịch rảnh từ 2/4 → ≤1/4 buổi; ghi riêng đổi lịch vì việc đột xuất. Cách đo: theo dõi 4 lần baseline và 4 lần thử, bấm giờ thao tác, lưu bảng lịch rảnh và xác nhận của 4 người; ghi nguyên nhân từng lần đổi lịch. Chỉ so thời gian trên các tuần có ít nhất 1 khung chung; nếu không có thì ghi “không có khung phù hợp”, không tính là đã chốt lịch thành công. |
| Phương án không dùng AI | **No AI:** mỗi người đánh dấu 6 khung giờ theo mẫu và xác nhận trước 20h Chủ nhật. **Rule:** lọc khung có đủ 4 người rảnh trong bảng tính; nếu nhiều khung thì ưu tiên khung sớm nhất đã thống nhất. Nếu không có khung chung, người điều phối hỏi lại để đổi tập khung giờ, không tự coi người chưa trả lời là đồng ý. |
| Giả thuyết về AI (nếu có) | Nếu nhóm buộc phải trả lời bằng ngôn ngữ tự nhiên, thử **Workflow** chuyển câu trả lời thành khung giờ để từng người xác nhận rồi mới tìm giao lịch. AI không tự suy đoán lịch cá nhân và không tự gửi lời mời. **Agent** chưa cần vì bài toán chỉ là thu lịch, xác nhận và tìm giao theo thứ tự cố định. |
| Cảm nhận nhanh | **Rule**, sau khi dùng mẫu phản hồi thống nhất; chưa cần Workflow hoặc Agent nếu đầu vào đã rõ. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 35 phút thao tác/lần × 1 lần/tuần = 35 phút/tuần

[1 Gửi 6 khung giờ: 3'] → [2 Đọc + ghi lịch 4 người: 8']
→ [3 So sánh + hỏi lại lịch mơ hồ: 15'] ← BOTTLENECK
→ [4 Đề xuất + lấy xác nhận: 6'] → [5 Ghi lịch + nhắc nhóm: 3']

Đầu ra: 1 lịch học 90 phút được cả 4 người xác nhận, hoặc kết luận chưa có khung chung.
Thời gian chờ phản hồi được ghi riêng, chưa nằm trong 35 phút.
```

### Card muốn pitch nhất

- **Card số:** 1 — Kiểm tra đủ yêu cầu bài lab trước khi nộp.
- **Vì sao:** nhóm dễ hiểu tình huống; phạm vi nhỏ, có thể lấy một đề và một bản nộp để tái hiện ngay trong buổi lab. Nếu giả định đúng, giảm 45 xuống 25 phút giúp người nộp tiết kiệm 40 phút/tuần ở tần suất 2 bài/tuần, đồng thời phải giữ mục tiêu không thiếu yêu cầu bắt buộc.
- **Câu hỏi muốn nhóm phản biện:** “Lần gần nhất bài nhóm bị thiếu mục là khi nào, thiếu gì và bị phát hiện ở bước nào?”; “Một checklist làm từ đầu có giảm thời gian xuống 25 phút mà không cần AI không?”; “Nếu chậm vì chờ bạn hoàn thành nội dung, card này có đang chọn sai bottleneck không?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Cả 3 card: con số cụ thể dễ bị hiểu nhầm là đã có log hoặc khảo sát xác nhận. | Đồng ý. | Ghi rõ toàn bộ số liệu là giả định; từng dòng CP1 có nguồn cần thu thập; không ghi lời phỏng vấn hoặc kết quả khảo sát chưa diễn ra. |
| Card #1: kiểm đủ mục khác với chấm đúng nội dung; có tiêu đề chưa chứng minh đã đáp ứng yêu cầu. | Đồng ý. | Giới hạn ở 10 yêu cầu bắt buộc, đòi vị trí bằng chứng trong bản nộp và có người khác kiểm độc lập; Rule chỉ kiểm được cấu trúc. |
| Card #1: giảm thời gian có thể khiến bỏ sót nhiều hơn; chưa có căn cứ khẳng định cần AI. | Đồng ý. | Thêm metric 0/8 bài thiếu mục bắt buộc; thử checklist trước, chỉ cân nhắc Workflow nếu còn >25 phút/bài sau 4 bài. |
| Card #2: phép cộng đúng không bảo đảm chia đúng người; thiếu thông tin không giải được bằng công thức. | Đồng ý. | Yêu cầu ghi người trả, người chịu và chứng từ; kiểm từng khoản với cả phòng, thêm quy tắc phần dư; chọn chuẩn hóa đầu vào + Rule trước AI. |
| Card #3: thời gian chờ trả lời và không có lịch chung có thể bị nhầm là lỗi tìm lịch. | Đồng ý. | Tách thời gian thao tác khỏi thời gian chờ, thêm trạng thái không có khung chung và phân biệt đổi lịch do thông tin sai với việc đột xuất. |
| Chọn Agent chỉ vì có nhiều nguồn dữ liệu chưa đủ thuyết phục. | Đồng ý. | Cả 3 card đều nêu thứ tự bước cố định; ưu tiên No AI/Rule, chỉ giữ Workflow như giả thuyết có điều kiện. |

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
