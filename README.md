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

```text
MVC
├── Model       -> Xử lý dữ liệu
├── View        -> Giao diện người dùng
└── Controller  -> Xử lý logic
---

📂 Cấu trúc thư mục
Website_tintuc/
├── app/                 # Chứa Controller, Model, Middleware
├── bootstrap/          # Khởi động framework Laravel
├── config/             # File cấu hình hệ thống
├── database/           # Migration, Seeder, Factory
├── lang/en/            # File ngôn ngữ tiếng Anh
├── public/             # Thư mục chạy web, chứa index.php, css, js, images
├── resources/          # View Blade, file giao diện, assets gốc
├── routes/             # Khai báo route web, api
├── storage/            # Log, cache, upload file
├── tests/              # Unit Test / Feature Test

├── .editorconfig       # Chuẩn format code
├── .env.example        # File cấu hình mẫu môi trường
├── .gitattributes      # Cấu hình Git attributes
├── .gitignore          # File bỏ qua khi push GitHub
├── README.md           # Tài liệu dự án
├── artisan             # Command line Laravel
├── composer.json       # Khai báo package PHP
├── composer.lock       # Phiên bản package đã cài
├── package.json        # Package frontend npm
└── phpunit.xml         # Cấu hình kiểm thử PHPUnit

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
