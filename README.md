# 📰 Web Tin Tức - Laravel News Website

## 📌 Giới thiệu

**Web Tin Tức** là dự án website tin tức được xây dựng bằng **Laravel Framework** theo mô hình **MVC (Model - View - Controller)**.  
Hệ thống cho phép người dùng xem tin tức, phân loại bài viết theo danh mục và quản trị nội dung thông qua trang admin.
---
## 🚀 Công nghệ sử dụng

- PHP
- Laravel
- MySQL
- HTML / CSS / JavaScript
- Bootstrap
- Blade Template Engine
---
## 🏗️ Mô hình hệ thống
Dự án được xây dựng theo mô hình:
MVC
├── Model       -> Xử lý dữ liệu
├── View        -> Giao diện người dùng
└── Controller  -> Xử lý logic
---
📂 Cấu trúc thư mục
Webtintuclaravel/
├── app/                 # Chứa Controller, Model, Middleware
├── bootstrap/           # Khởi động framework Laravel
├── config/              # File cấu hình hệ thống
├── database/            # Migration, Seeder, Factory
├── lang/en/             # File ngôn ngữ tiếng Anh
├── public/              # Thư mục public chạy website
├── resources/           # View Blade, CSS, JS, assets
├── routes/              # Định tuyến web, api
├── storage/             # Log, cache, upload
├── tests/               # Kiểm thử hệ thống

├── .editorconfig        # Chuẩn định dạng code
├── .env.example         # File cấu hình mẫu
├── .gitattributes       # Cấu hình Git
├── .gitignore           # File bỏ qua khi push GitHub
├── artisan              # Công cụ dòng lệnh Laravel
├── composer.json        # Danh sách package PHP
├── composer.lock        # Phiên bản package đã cài
├── package.json         # Package frontend npm
├── phpunit.xml          # Cấu hình PHPUnit
├── README.md            # File mô tả dự án
└── webtintuc.sql        # File cơ sở dữ liệu MySQL

⚙️ Chức năng chính
👤 Người dùng
 • Xem danh sách tin tức
 • Xem chi tiết bài viết
 • Tìm kiếm bài viết
 • Xem tin theo danh mục

🔐 Quản trị viên
 • Đăng nhập hệ thống
 • Thêm bài viết
 • Sửa bài viết
 • Xóa bài viết
 • Quản lý danh mục
 • Quản lý tài khoản
⸻
🗄️ Cơ sở dữ liệu
Các bảng chính:
 • users
 • tintuc
 • danhmuc
 • comments
📌 Ưu điểm dự án
 • Xây dựng theo chuẩn Laravel MVC
 • Code rõ ràng, dễ nâng cấp
 • Bảo mật tốt
 • Dễ quản lý dữ liệu
 • Giao diện thân thiện
⸻
📚 Kiến thức áp dụng
 • Laravel Routing
 • Controller
 • Model Eloquent ORM
 • Blade Template
 • Authentication
 • CRUD MySQL
