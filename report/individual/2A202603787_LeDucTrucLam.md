# Báo cáo cá nhân — 2A202603787_LeDucTrucLam

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Lê Đức Trúc Lâm
- MSSV: 2A202603787
- Email trường (không bắt buộc, repo có thể để public): 26ai.lamldt@vinuni.edu.au
- Tên nhóm: A3
- Link repo nhóm: https://github.com/HoangQuan23112004/K5-L3B-Day02-A3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính               | Job Story: Khi… tôi muốn… để…                                                                                                                                                                | Ai chịu ảnh hưởng?     | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                          |
|--:|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|----------------------------------------------------------------------------------------------------|
| 1 | Tốn thời gian           | Khi kiểm tra hệ thống mạng, tôi cần giải pháp tổng hợp chung về tình trạng hệ thống (các cổng mạng, thiết lập IP, etc.) để không phải kiểm tra từng thiết bị (có thể kiểm tra sau)           | SysAdmin               | Các lần kiểm tra thiết bị (chạy command) tốn 10-15 phút                                            |
| 2 | Tốn thời gian           | Khi máy tính các nhân viên gặp sự cố, tôi cần phân cấp các sự cố để xếp lịch ưu tiên xử lý tuỳ theo mức độ ảnh hưởng và loại sự cố                                                           | SysAdmin, nhân viên    | 1 số sự cố gây gián đoạn công việc bị xử lý chậm                                                   |
| 3 | Pain từ người khác      | Các nhân viên mới cần hướng dẫn kỹ thuật cô đọng, dễ hiểu để tự xử lý mà không cần viết ticket lên SysAdmin                                                                                  | Nhân viên              | Nhiều ticket được viết để xử lý các lỗi nhỏ, khiến sự cố lớn hơn bị chậm trễ                       |
| 4 | Lặp lại                 | Khi ban lãnh đạo yêu cầu tổng hợp tình trạng phần mềm bản quyền, tôi cần có danh sách tổng hợp tự động tình trạng cho toàn bộ máy tính để không phải check từng máy                          | SysAdmin, ban lãnh đạo | Mỗi lần kiểm tra tốn 5-10 phút, ảnh hưởng công việc nhân viên                                      |
| 5 | Tốn thời gian           | Khi xảy ra sự cố hệ thống, tôi cần một bản báo cáo ngắn gọn về những gì đã xảy ra kèm log để bàn quy trình xử lý với các SysAdmin khác                                                       | SysAdmin, team         | Khi xảy ra sự cố phải kiểm tra log bằng tay, rất tốn thời gian và làm chậm trễ quá trình xử lý     |
| 6 | Cần đọc nhiều thông tin | Khi lỗ hổng bảo mật mới được công bố rộng rãi, tôi muốn một bản tóm tắt đối chiếu trực tiếp các lỗ hổng đó với hạ tầng hiện tại của công ty, để nhận biết ngay thiết bị nào đang gặp rủi ro. | SysAdmin, công ty      | Tốn 3 tiếng kể từ lúc nhận được cảnh báo bảo mật cho đến khi xác định được ảnh hưởng trong công ty |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Sau khi tham khảo AI, tôi quyết định giữ lại gợi ý #6 "Hỗ trợ tổng hợp thông tin về lỗ hổng bảo mật". Trong khi đó, ý về "buộc nhân viên điền các thông tin cụ thể vào ticket" chỉ cần thiết kế lại giao diện điền ticket và không cần AI hỗ trợ, nên gợi ý này không được chọn.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                             | Vì sao chọn                                                  | Điều còn chưa chắc                                 |
|-----:|-----------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------|
|    1 | Phân loại sự cố thiết bị nhân viên (#2)             | Pain nhiều người, ảnh hưởng đến công việc                    | Cần tiêu chí rõ ràng về mức độ cấp thiết của sự cố |
|    2 | Tổng hợp lỗ hổng bảo mật đối chiếu với công ty (#6) | Impact lớn đến công ty, gây ảnh hưởng tới bảo mật tài nguyên | Quá trình tổng hợp liệu có sai sót?                |
|    3 | Tổng hợp tình trạng mạng (#1)                       | Tốn thời gian, impact lớn đến vận hành công việc             | Nếu có vấn đề, nên highlight như thế nào?          |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                                          |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Job Story                                 | Khi máy tính các nhân viên gặp sự cố, tôi cần phân cấp các sự cố để xếp lịch ưu tiên xử lý tuỳ theo mức độ ảnh hưởng                                                              |
| Actor                                     | SysAdmin, nhân viên                                                                                                                                                               |
| Thời điểm / bối cảnh                      | Khi nhân viên gặp sự cố và gửi ticket lên bộ phận SysAdmin                                                                                                                        |
| Quy trình hiện tại (3–7 bước)             | 1. Nhân viên viết ticket lên SysAdmin · 2. SysAdmin tiếp nhận và phân loại sự cố và mức ưu tiên · 3. Team dựa trên mức ưu tiên để sắp lịch xử lý · 4. Nhân viên được hỗ trợ xử lý |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2: Việc sắp xếp tốn nhiều thời gian và làm chậm trễ quá trình xử lý sự cố                                                                                                    |
| Impact (nếu không giải thì sao)           | Các sự cố nghiêm trọng như không vào được mạng, máy tính không chạy bị giải quyết chậm, ảnh hưởng đến công việc                                                                   |
| Success metric (baseline → target)        | Các sự cố nghiệm trọng được giải quyết nhanh, giảm downtime đến tối đa 20-30 phút                                                                                                 |
| Phương án không dùng AI                   | Để nhân viên tự đặt mức độ cấp thiết tuỳ theo việc sự cố có gây ảnh hưởng đến công việc không: dễ bị lạm dụng để ưu tiên các lỗi nhỏ, ảnh hưởng đến sự cố cần uư tiên thực sự.    |
| Giả thuyết về AI (nếu có)                 | AI tổng hợp và phân loại mức ưu tiên cho các ticket dựa trên tiêu chỉ được đặt sẵn, giúp SysAdmin chủ động xếp lịch xử lý 1 cách hợp lý                                           |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                          |



Quy trình nháp hiện tại:

```text
1. Nhân viên viết ticket lên SysAdmin (5')
2. SysAdmin tiếp nhận và phân loại sự cố và mức ưu tiên (5'/ticket)
3. Team dựa trên mức ưu tiên để sắp lịch xử lý (5'/ticket)
4. Nhân viên được hỗ trợ xử lý (thời gian tuỳ theo từng sự cố)
```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                                                                                                            |
|-------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Job Story                                 | Khi các tổ chức an ninh mạng công bố danh sách lỗ hổng bảo mật mới, tôi muốn một bản tóm tắt đối chiếu trực tiếp các lỗ hổng đó với hạ tầng hiện tại của công ty, để nhận biết ngay thiết bị nào đang gặp rủi ro.                                                   |
| Actor                                     | SysAdmin, Công ty                                                                                                                                                                                                                                                   |
| Thời điểm / bối cảnh                      | Khi lỗ hổng bảo mật được công bố                                                                                                                                                                                                                                    |
| Quy trình hiện tại (3–7 bước)             | 1. Nhận và nghiên cứu thông tin về lỗ hổng bảo mật · 2. Kiểm tra và ghi lại các thiết bị trong công ty có thể bị ảnh hưởng · 3. Đối chiếu và ghi chép những rủi ro ảnh hưởng đến hạ tầng công ty · 4. Dựa theo hướng dẫn khắc phục của nhà sản xuất để xử lý lỗ hổng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3: Quá trình kiểm tra thiết bị bị kéo dài (có thể lên đến 3-4 tiếng)                                                                                                                                                                                        |
| Impact (nếu không giải thì sao)           | Lỗ hổng bảo mật không được vá kịp thời, tạo cơ hội cho hacker xâm nhập làm lộ lọt thông tin hoặc gây tê liệt hệ thống, ảnh hưởng đến hoạt động công ty                                                                                                              |
| Success metric (baseline → target)        | Thời gian kể từ khi lỗ hổng được phát hiện đến khi được khắc phục phải 1-2 tiếng trở xuống                                                                                                                                                                          |
| Phương án không dùng AI                   | Có kế hoạch xử lý trước và khắc phục hậu quả nếu lỗ hổng bị khai thác - Không phù hợp với lỗ hổng Zero-day bị khai thác ngay ngày đầu phát hiện, "phòng bệnh hơn chữa bệnh"                                                                                         |
| Giả thuyết về AI (nếu có)                 | Tổng hợp nhanh những thiết bị bị ảnh hưởng và cách khắc phục dựa trên tài liệu được cho sẵn (giới hạn chỉ tài liệu về lỗ hổng đó và danh sách thiết bị của công ty)                                                                                                 |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                                                                                                            |

Quy trình nháp hiện tại:

```text
1. Nhận và nghiên cứu thông tin về lỗ hổng bảo mật (40')
2. Kiểm tra và ghi lại các thiết bị trong công ty có thể bị ảnh hưởng (45'-60')
3. Đối chiếu và ghi chép những rủi ro ảnh hưởng đến hạ tầng công ty (60')
4. Dựa theo hướng dẫn khắc phục của nhà sản xuất để xử lý lỗ hổng (40'-60')
```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                                                                         |
|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Job Story                                 | Khi kiểm tra hệ thống mạng, tôi cần giải pháp tổng hợp chung về tình trạng hệ thống (các cổng mạng, thiết lập IP, etc.) để không phải kiểm tra từng thiết bị (có thể kiểm tra sau)                                               |
| Actor                                     | SysAdmin                                                                                                                                                                                                                         |
| Thời điểm / bối cảnh                      | Hẵng ngày vào mỗi buổi sáng                                                                                                                                                                                                      |
| Quy trình hiện tại (3–7 bước)             | 1. Login vào từng thiết bị · 2. Chạy command để kiểm tra status và tạo log · 3. Ghi chép lại tình trạng và vấn đề (nếu có) dựa trên log · 4. Tổng hợp thành báo cáo để gửi cấp trên (nếu được yêu cầu) và khắc phục lỗi (nếu có) |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1 và 2: Quá trình đăng nhập và chạy command tạo log có thể mất 10 phút / thiết bị. Ghi chép mất thêm 5 phút / thiết bị nữa                                                                                                  |
| Impact (nếu không giải thì sao)           | 15 phút cho 1 thiết bị được kiểm tra. Nếu công ty có 50 thiết bị, con số sẽ rất lớn.                                                                                                                                             |
| Success metric (baseline → target)        | Thời gian kiểm tra rút ngắn còn bình quên 5 phút / thiết bị (chưa kể thời gian viết report)                                                                                                                                      |
| Phương án không dùng AI                   | Tuyển thêm nhân viên SysAdmin kiểm tra nhiều thiết bị 1 lúc - Tốn tiền, có yếu tố con người có thể sai sót khi kiểm tra                                                                                                          |
| Giả thuyết về AI (nếu có)                 | Tự thu thập status và log từ thiết bị và tổng hợp thành 1 báo cáo chung dễ đọc về tình trạng, với highlight về các vấn đề nếu có, hỗ trợ SysAdmin viết báo cáo và khắc phục sự cố                                                |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                                                                         |

Quy trình nháp hiện tại:

```text
1. Login vào từng thiết bị (5'/thiết bị)
2. Chạy command để kiểm tra status và tạo log (5'/thiết bị)
3. Ghi chép lại tình trạng và vấn đề (nếu có) dựa trên log (10'/thiết bị)
4. Tổng hợp thành báo cáo để gửi cấp trên (nếu được yêu cầu) (20-30') và khắc phục lỗi (nếu có) (5-10' tuỳ lỗi)
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Tình huống hay gặp trong công sở, có impact lớn đến vận hành công việc
- Câu hỏi muốn nhóm phản biện: Có những tiêu chí cụ thể nào để xác định mức độ ưu tiên của các sự cố kỹ thuật?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                        | Đồng ý? | Đã sửa gì                                                                       |
|-----------------------------------------------------------|---------|---------------------------------------------------------------------------------|
| Card #1: Success metric không có con số đảm bảo cụ thể    | Có      | Thêm con số downtime tối đa cho phép (20 đến 30 phút)                           |
| Card #1: Để AI tự xử lý xếp lịch là quá rủi ro            | Có      | Xoá cơ chế tự xếp lích, để SysAdmin tự sắp xếp theo gợi ý của AI                |
| Card #2: Bottleneck quá rộng, không rõ ràng               | Có      | Tập trung vào quá trình tốn thời gian nhất: rà soát thiết bị có thể dính lỗ hổng |
| Card #2: AI thiếu đầu vào quan trọng (danh sách thiết bị) | Có      | Thêm giới hạn về danh sách thiết bị tại công ty                                 |


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                                       | Kết quả / ảnh hưởng tới bài nhóm                                     |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| Pitch Problem Card         | Tôi lựa chọn các vấn đề của một quản trị viên hệ thống (System Administrator), một công việc đòi hỏi việc kiểm tra và giám sát liên tục các thiết bị | Giới thiệu cho nhóm về 1 trong những lĩnh vực AI ứng dụng mới thú vị |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Sử dụng AI để phân tích hình ảnh động tác, liệu có ảnh hưởng gì đến quyền riêng tư không?                                        |                                                                      |
| Nhận phản biện             | Câu hỏi tôi nhận được: Tiêu chí cấp thiết là gì? Có bao nhiêu ticket/tuần và bao nhiêu ticket bị phân loại lại?                                      | Tôi đã sửa gì:                                                       |
| Gom cluster / cây OST      |                                                                                                                                                      |                                                                      |
| Chọn candidate problem     |                                                                                                                                                      |                                                                      |
| Kiểm chứng / research      |                                                                                                                                                      |                                                                      |
| Quy trình nhóm             |                                                                                                                                                      |                                                                      |
| Problem Statement          |                                                                                                                                                      |                                                                      |
| Mức can thiệp AI           |                                                                                                                                                      |                                                                      |
| Quyết định                 |                                                                                                                                                      |                                                                      |

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
