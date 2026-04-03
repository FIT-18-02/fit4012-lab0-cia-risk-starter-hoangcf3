# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Hoàng

**MSSV:** 1871020250

**Lớp/Nhóm:** CNTT18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Bảng điểm sinh viên
- Asset 2:Tài khoản giảng viên
- Asset 3 (nếu có):Cơ sở dữ liệu hệ thống

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Availability (A)
- Sự cố B ->Integrity (I)
- Sự cố C ->Confidentiality (C)

---

## 3. Phân tích sự cố B
- Threat:Người dùng trái phép hoặc giảng viên sửa điểm không đúng quyền.
- Vulnerability:Mật khẩu yếu, không có phân quyền rõ ràng, thiếu log theo dõi, không có xác thực nhiều lớp.
- Mitigation:Bật MFA, phân quyền theo vai trò rõ ràng, ghi log mọi thay đổi điểm, yêu cầu phê duyệt khi sửa điểm.

---

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề liên quan đến Integrity trước vì điểm số bị thay đổi ảnh hưởng trực tiếp đến tính chính xác và uy tín của hệ thống. Sau đó, em sẽ cải thiện hệ thống xác thực và phân quyền để ngăn chặn truy cập trái phép. Việc bổ sung log và cơ chế giám sát cũng rất quan trọng để phát hiện sớm các hành vi bất thường. Cuối cùng, em sẽ nâng cao bảo mật tổng thể để giảm thiểu rủi ro lâu dài.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-A-B-I-C-C}

