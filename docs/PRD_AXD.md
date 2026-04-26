# Product Requirements Document (PRD)
## Sản phẩm: AXD – Hệ thống quản lý file dữ liệu

### 1. Giới thiệu
AXD là nền tảng quản lý, lưu trữ và chia sẻ tài liệu cho doanh nghiệp, lấy cảm hứng từ Google Drive, Dropbox nhưng tối ưu cho môi trường nội bộ, bảo mật và phân quyền linh hoạt.

### 2. Mục tiêu sản phẩm
- Quản lý, lưu trữ, phân loại, tìm kiếm, chia sẻ tài liệu nội bộ hiệu quả
- Đảm bảo bảo mật, kiểm soát truy cập, dễ sử dụng, mở rộng linh hoạt

### 3. Đối tượng sử dụng
- Nhân viên doanh nghiệp
- Quản trị viên hệ thống

### 4. Tính năng cốt lõi
1. Đăng nhập/Đăng xuất (SSO, email/password)
2. Upload/download nhiều định dạng file
3. Tổ chức file theo thư mục, tag
4. Phân quyền chi tiết (user, nhóm, vai trò)
5. Chia sẻ nội bộ (link, user, group)
6. Tìm kiếm tài liệu nhanh
7. Lịch sử thao tác, nhật ký hệ thống
8. Quản lý tài khoản, phân quyền
9. Giao diện web responsive, tối giản

### 5. Yêu cầu phi chức năng
- Bảo mật: xác thực, phân quyền, mã hóa dữ liệu
- Hiệu năng: đáp ứng 100 user đồng thời
- Khả năng mở rộng, backup định kỳ, log đầy đủ
- Đảm bảo vận hành trên Windows Server/Cloud

### 6. Luồng sử dụng chính
1. Người dùng đăng nhập, vào dashboard
2. Tạo thư mục/tải file lên
3. Phân quyền truy cập tài liệu/thư mục
4. Tìm kiếm, xem, tải, chỉnh sửa, xóa tài liệu
5. Chia sẻ file/thư mục cho đồng nghiệp
6. Quản trị viên quản lý tài khoản, kiểm tra nhật ký hệ thống

### 7. Tiêu chí nghiệm thu
- Đầy đủ tính năng MVP: Auth, lưu trữ, chia sẻ, phân quyền, tìm kiếm
- Upload/download thành công nhiều định dạng file
- Phân quyền hoạt động đúng
- Tìm kiếm nhanh, chính xác
- Giao diện dễ dùng, audit log minh bạch

### 8. Phạm vi MVP
- Chỉ bao gồm các tính năng nêu trên, loại bỏ các tính năng nâng cao (mobile app, sync đa nền tảng, chia sẻ ngoài tổ chức...)
- Ưu tiên hoàn thiện quy trình quản lý tài liệu nội bộ hiệu quả

---
Tài liệu này là cơ sở để SA và Dev Lead tiếp tục đặc tả kiến trúc, thiết kế và phát triển sản phẩm AXD.