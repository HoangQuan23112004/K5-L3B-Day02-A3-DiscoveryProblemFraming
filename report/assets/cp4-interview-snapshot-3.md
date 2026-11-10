# CP4 — Interview snapshot 3

- Nhóm: A3
- Problem: Kiểm tra đủ yêu cầu bài lab trước khi nộp
- Người phỏng vấn: Đinh Hoài Nam

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò) | Trợ giảng (TA), thường xuyên review bài nộp của sinh viên |
| Thời gian và cách hỏi | 10:00 ngày 10/11/2026, nhắn tin qua Zalo |
| Lần gần nhất gặp vấn đề | Chiều 09/11/2026, khi chấm một loạt Pull Request của sinh viên |
| Câu nói nguyên văn | "Mỗi lần chấm bài mình phát mệt. Bài thì quên file ảnh screenshot terminal, bài thì sai quy tắc đặt tên branch (ví dụ `task/sv01...`), lại phải comment bắt các bạn sửa lại từng tí." |
| Workaround hiện tại | TA đã viết sẵn một bash script ngắn kiểm cấu trúc, gửi cho lớp và dặn chạy trước khi push. Theo ước tính của TA, khoảng 80% sinh viên không chạy script này |
| Mất bao lâu, bao lần | TA mất 3–5 phút/bài chỉ để kiểm cấu trúc file và format, thay vì chấm logic. Sinh viên bị trả bài mất thêm khoảng 15 phút để sửa và push lại |
| Tín hiệu phản bác | Một công cụ kiểm cấu trúc **đã tồn tại** (script của TA) nhưng phần lớn sinh viên không dùng. Vậy chỗ thiếu không phải công cụ kiểm, mà là việc kiểm đang phụ thuộc vào việc sinh viên tự nhớ chạy |
| Insight | Các lỗi TA gặp (thiếu file ảnh, sai tên branch) đều có đúng/sai rõ ràng, kiểm được bằng Rule. Cách kiểm phải tự chạy hoặc bắt buộc tại thời điểm commit/push, không dựa vào việc sinh viên tự nguyện bấm chạy. Đây là nhận định của người phỏng vấn, chưa được TA xác nhận |
