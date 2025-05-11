# 📱 Dự án Website Bán Điện Thoại – ASP.NET MVC & Web API

## 📌 Mô tả dự án

Dự án xây dựng website bán điện thoại sử dụng ngôn ngữ lập trình **C#**, áp dụng mô hình **MVC** và tách biệt rõ ràng giữa **frontend** và **backend**. Dự án cung cấp đầy đủ các chức năng quản lý dành cho người quản trị và trải nghiệm mua sắm cơ bản dành cho người dùng.

---

## 🧑‍💻 Vai trò và trách nhiệm

- Thiết kế **cơ sở dữ liệu chuẩn hóa** theo mô hình quan hệ (MySQL).
- Phát triển đầy đủ chức năng **trang quản trị (Admin)**:
  - Thêm, sửa, xóa, cập nhật **sản phẩm** và **danh mục**.
  - Quản lý **đơn hàng**: trạng thái, chi tiết đơn hàng.
  - Quản lý **người dùng**, phân quyền **Admin/User**.
- Tích hợp giao diện quản trị với **API backend** sử dụng ASP.NET Web API.
- Thiết kế giao diện bằng **HTML, CSS, Bootstrap** và tích hợp với ASP.NET MVC.

---

## 🛠️ Công nghệ sử dụng

| Thành phần         | Công nghệ                                      |
|--------------------|------------------------------------------------|
| Ngôn ngữ            | C#, SQL                                       |
| Backend             | ASP.NET Web API                               |
| Frontend            | ASP.NET MVC, HTML, CSS, Bootstrap             |
| Cơ sở dữ liệu       | MySQL                                         |
| IDE & Công cụ       | Visual Studio, Postman, MySQL Workbench       |
| Mô hình kiến trúc   | MVC (Model - View - Controller)               |

---

## 🚀 Hướng dẫn chạy dự án

1. **Clone** dự án về máy:
   ```bash
   git clone https://github.com/N-Q-V/DoAnC-.git
2. API
- Chạy file WebApplication1.sln trong folder WebApplication1 để chạy API
- Cấu hình db, username, password trong appsettings.json
- Chạy update-database
- Paste đường dẫn sau để chạy api https://localhost:44374/api/admin/Categories
3. Call API
- Chạy file CallApi.sln trong folder CallApi để gọi API
- Paste đường dẫn sau để vào giao diện trang chủ https://localhost:44341
4. Tài khoản đăng nhập có sẵn
- TK Admin: username: admin
            password: 123456
- TK User:  username: user01
            password: 123456
