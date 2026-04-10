# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu điểm sinh viên và thông tin cá nhân liên quan.
- Tài khoản người dùng, cơ sở dữ liệu và máy chủ của hệ thống lưu điểm.

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Kẻ tấn công hoặc người dùng không được phép chỉnh sửa điểm số trong hệ thống.
- Vulnerability:Mật khẩu yếu, phân quyền chưa chặt chẽ hoặc thiếu kiểm tra/xác thực khi cập nhật điểm. 
- Mitigation: Áp dụng xác thực mạnh, phân quyền theo vai trò, ghi log thay đổi điểm và kiểm tra dữ liệu đầu vào.

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn cách xác định tài sản cần bảo vệ trong một hệ thống thông tin. Em cũng phân biệt được ba yếu tố quan trọng là Confidentiality, Integrity và Availability khi phân tích sự cố. Phần khó nhất là xác định chính xác một sự cố thuộc nhóm CIA nào vì có trường hợp ảnh hưởng đến nhiều yếu tố cùng lúc. Khi phân tích an toàn thông tin, cần chú ý xác định đúng mối đe dọa, lỗ hổng và biện pháp giảm thiểu phù hợp. Bài lab cũng giúp em luyện cách suy nghĩ có hệ thống hơn về rủi ro bảo mật.
