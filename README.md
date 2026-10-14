# BÁO CÁO BÀI TẬP: ƯỚC LƯỢNG PRODUCT BACKLOG CHO NỀN TẢNG BÁN HÀNG QUA LIVESTREAM

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Kiểm tra dữ liệu trước khi ước lượng

Sau khi đọc kỹ các User Story và Acceptance Criteria của LS01 và LS03 (so sánh với LS02 làm Reference Story), tôi tiến hành đánh giá mức độ rõ ràng của từng yêu cầu như sau:

- LS01: Đủ rõ. Tiêu đề không được để trống và trạng thái hiển thị 'Sắp diễn ra' trước giờ bắt đầu đã được quy định rạch ròi, không có điểm mơ hồ ảnh hưởng đến phạm vi.
- LS03: Cần làm rõ. Quy chế xử lý khi có hai khách hàng đặt cùng một sản phẩm cuối cùng cần được Product Owner chốt lại cụ thể để đội ngũ không bị lúng túng trong quá trình hiện thực hóa logic trừ tồn kho.

| Mã Story | Đủ rõ | Cần làm rõ | Thông tin/câu hỏi còn thiếu |
| --- | --- | --- | --- |
| LS01 | [x] | [ ] | Không có câu hỏi thêm. |
| LS03 | [ ] | [x] | Khi hai khách cùng đặt món cuối cùng thì hệ thống phân định đơn nào thành công, đơn nào nhận thông báo hết hàng ra sao? |

## Nhiệm vụ 2: Phân tích Planning Poker và chốt Story Point

Dựa trên kết quả vòng Planning Poker mô phỏng, tôi phân tích các mức độ chênh lệch phiếu giữa các thành viên và đưa ra mức Story Point cuối cùng dựa trên sự so sánh tương đối với Reference Story LS02 (được gán cố định 3 SP).

- LS01: Phiếu chênh lệch ở mức 3 và 5 SP. Nguyên nhân do một thành viên đánh giá phần xử lý thời gian bắt đầu và trạng thái phiên phức tạp hơn một chút, nhưng nhìn chung phạm vi tương đương LS02 nên chốt 3 SP.
- LS03: Phiếu chênh lệch từ 5 đến 8 SP do rủi ro đồng thời khi nhiều khách đặt sát nhau và logic giảm/hoàn tồn kho cần đội ngũ cẩn trọng. Do tính chất phức tạp cao hơn LS02, nhóm chốt mức 5 SP sau khi đã có thông tin làm rõ từ PO.

| Mã Story | Mức ưu tiên | Kết quả phiếu | SP cuối cùng | Lý do ngắn |
| --- | --- | --- | --- | --- |
| LS01 | 1 | 3 - 3 - 5 - 3 | 3 | Phạm vi tương đương LS02 (Reference Story); xử lý thời gian đơn giản và không phát sinh rủi ro ẩn. |
| LS02 | 2 | 3 - 3 - 3 - 3 | 3 | Reference Story; các phiếu đã trùng nhau. |
| LS03 | 3 | 5 - 8 - 8 - 5 | 5 | Phức tạp hơn LS02 do có logic kiểm tra tồn kho đồng thời và cập nhật tăng giảm, tuy nhiên quy mô vẫn trong tầm kiểm soát. |

## Nhiệm vụ 3: Phát hiện cách hiểu sai

Đề xuất cố định '1 Story Point = 4 giờ' cho mọi User Story là hoàn toàn sai lầm và đi ngược lại bản chất của Agile. Story Point thật ra đo lường độ phức tạp, khối lượng công việc tổng thể và mức độ rủi ro dựa trên sự so sánh tương đối giữa các User Story chứ không phải là thước đo thời gian tuyệt đối.

Thay vì quy đổi cứng nhắc sang giờ công, nhóm phát triển sử dụng Velocity (tốc độ hoàn thành tổng số Story Point qua các Sprint trước) để dự báo khối lượng công việc có thể cam kết cho Sprint tiếp theo một cách linh hoạt và thực tế hơn.

- Việc cố định thời gian cho Story Point sẽ làm mất đi ý nghĩa của ước lượng tương đối và gây áp lực sai lệch khi độ khó thực tế của từng task khác nhau.
- Velocity giúp team tự điều chỉnh năng suất dựa trên dữ liệu lịch sử thực tế của các Sprint.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
