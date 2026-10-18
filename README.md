# [Bài tập] Tạo layout với RWD (Responsive Web Design)

Bài tập thực hành sử dụng thẻ `<div>` và CSS để xây dựng bố cục trang web có khả năng tự động thích ứng co giãn trên mọi kích thước màn hình thiết bị (Desktop, Tablet, Mobile) theo chương trình đào tạo CodeGym.

## 🎯 Mục tiêu
- Luyện tập sử dụng `<div>` và CSS để phân chia và kiểm soát bố cục trang web.
- Hiểu và ứng dụng thành thạo **Responsive Web Design (RWD)** với **Flexbox**, **CSS Grid** và **Media Queries (`@media`)**.
- Bố cục trang web luôn đảm bảo trải nghiệm người dùng tối ưu, không bị vỡ giao diện hay xuất hiện thanh cuộn ngang không mong muốn trên thiết bị di động.

## 📐 Cấu trúc bố cục
Trang web gồm 4 phân vùng chính:
1. **Header (`#header`)**: Logo biểu tượng `🌐 RWD Layout` và phần mô tả ngắn gọn.
2. **Navigation (`#navbar`)**: Thanh menu điều hướng với hiệu ứng hover và active.
3. **Container chính (`#container`)**:
   - **Cột trái (`#left`)**: Sidebar chứa danh mục chính và liên kết tài liệu.
   - **Nội dung chính (`#content`)**: Khối biểu ngữ giới thiệu (Hero Banner) và lưới 4 thẻ thông tin cốt lõi của RWD.
   - **Cột phải (`#right`)**: Sidebar thông báo mới và form đăng ký tư vấn.
4. **Footer (`#footer`)**: Bản quyền và thông tin cuối trang.

## 📱 Khả năng thích ứng đa thiết bị (RWD)
- **Desktop (> 992px)**: Bố cục 3 cột (Trái - Giữa - Phải) dàn ngang mạch lạc, trực quan.
- **Tablet (768px - 992px)**: Cột phải tự động dàn đều bên dưới 2 cột chính.
- **Mobile (<= 768px)**: Toàn bộ thanh menu và 3 cột tự động chuyển thành cột đơn xếp chồng dọc (`width: 100%`), căn chỉnh khoảng cách hợp lý.
