# BasicExample

Cài đặt phụ thuộc Tailwind CSS:
pnpm install
Chạy dự án:
Chạy lệnh phát triển:

pnpm dev

Lệnh này sẽ:

Chạy hugo server từ thư mục gốc 

Đồng thời biên dịch Tailwind CSS theo thời gian thực.

Kiểm tra trang web:
Mở trình duyệt và truy cập http://localhost:1313. Bạn sẽ thấy trang web với nội dung từ content/ và giao diện từ layouts/.

Kiểm tra build (tùy chọn):
Để đảm bảo dự án sẵn sàng triển khai:

pnpm build

Các tệp tĩnh sẽ được tạo trong thư mục public/.

Bước 6: Tùy biến dự án
Bây giờ C:\Users\Administrator\Desktop\Hugo\my-tailwind-project là một dự án Hugo độc lập, bạn có thể tùy biến thoải mái:
Sửa layouts:
Chỉnh sửa các tệp trong layouts/ để thay đổi giao diện. Ví dụ:
layouts\_default\baseof.html: Template chính.

layouts\partials\header.html: Thanh điều hướng.

layouts\index.html: Trang chủ.

Tùy chỉnh Tailwind CSS:
Mở assets\css\main.css để thêm các quy tắc Tailwind tùy chỉnh.

Cập nhật tailwind.config.js nếu cần thêm plugin hoặc tùy chỉnh theme Tailwind.

Chạy pnpm dev-tailwind để xem thay đổi CSS theo thời gian thực:

Triển khai:
Khi sẵn sàng, chạy:

pnpm build