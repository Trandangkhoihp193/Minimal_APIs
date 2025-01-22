# Minimal API với ASP.NET Core và MongoDB

## Giới thiệu
Dự án này là một ứng dụng Minimal API được xây dựng bằng **ASP.NET Core** và sử dụng **Entity Framework Core** với cơ sở dữ liệu In-Memory. API được thiết kế để quản lý danh sách công việc (To-Do List) với các chức năng CRUD cơ bản.

### **Công nghệ sử dụng**
- **ASP.NET Core**: Tạo và quản lý các API endpoint.
- **Entity Framework Core**: Tích hợp cơ sở dữ liệu và xử lý ORM.
- **In-Memory Database**: Lưu trữ dữ liệu tạm thời để thử nghiệm.
- **Swagger UI**: Giao diện hỗ trợ kiểm tra và thử nghiệm API.

---

## Các chức năng đã triển khai
API hỗ trợ các endpoint sau:
1. **GET /todoitems**: Lấy danh sách tất cả các công việc.
2. **GET /todoitems/complete**: Lấy danh sách các công việc đã hoàn thành.
3. **GET /todoitems/{id}**: Lấy thông tin chi tiết của một công việc dựa trên ID.
4. **POST /todoitems**: Thêm một công việc mới vào danh sách.
5. **PUT /todoitems/{id}**: Cập nhật thông tin của một công việc theo ID.
6. **DELETE /todoitems/{id}**: Xóa một công việc dựa trên ID.

---

## Kết quả

### **Tóm tắt kết quả đạt được**
Dự án Minimal API được triển khai thành công với các kết quả nổi bật:
- **Tích hợp thành công cơ sở dữ liệu In-Memory**: Lưu trữ và quản lý dữ liệu công việc (To-Do items) một cách tạm thời.
- **Triển khai đầy đủ các phương thức CRUD**:
  - Lấy danh sách công việc (GET).
  - Thêm công việc mới (POST).
  - Lấy thông tin chi tiết một công việc theo ID (GET).
  - Cập nhật công việc (PUT).
  - Xóa công việc (DELETE).
- **Swagger UI**: Được tích hợp để thử nghiệm và kiểm tra trực tiếp các API trong trình duyệt.

---

### **Các phương thức API**

#### **1. GET: Lấy danh sách toàn bộ công việc**
- **Mô tả**: Truy vấn và trả về danh sách tất cả công việc hiện có trong cơ sở dữ liệu.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/cc5b5eff-a332-4e34-b2d3-889a4f3c80c2" />

---

#### **2. POST: Thêm công việc mới**
- **Mô tả**: Thêm một công việc mới vào cơ sở dữ liệu với các thông tin do người dùng cung cấp.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/b55263a8-0010-4c6d-8a4c-e55e2c24cd47" />

---

#### **3. GET: Lấy thông tin chi tiết một công việc**
- **Mô tả**: Truy vấn và trả về thông tin chi tiết của một công việc dựa trên ID được cung cấp.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/48833b4a-aa61-4272-9a02-0abae520736f" />

---

#### **4. PUT: Cập nhật thông tin công việc**
- **Mô tả**: Cập nhật thông tin của một công việc đã tồn tại trong cơ sở dữ liệu dựa trên ID.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/46b4dbc7-f6f7-4506-acee-d75d86e28b59" />

---

#### **5. DELETE: Xóa một công việc**
- **Mô tả**: Xóa một công việc khỏi cơ sở dữ liệu dựa trên ID được cung cấp.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/4d4771a4-3e54-4757-a753-fc3a7ab6c358" />

---
  #### **6. GET: Lấy những công việc đã hoàn thành**
- **Mô tả**: Lấy những công việc đã hoàn thành dựa trên dữ liệu.
- **Ảnh minh họa**:
  <img width="1280" alt="Image" src="https://github.com/user-attachments/assets/d5d2c6d2-f295-45ad-a286-df3df85ccae8" />

---

## Kết luận
### Những gì đã làm được:
- Tạo một Minimal API hoàn chỉnh với ASP.NET Core.
- Tích hợp cơ sở dữ liệu In-Memory để lưu trữ dữ liệu.
- Thử nghiệm và đảm bảo tất cả endpoint hoạt động đúng.

### Cải tiến trong tương lai:
- Chuyển sang sử dụng cơ sở dữ liệu thực như SQL Server hoặc MongoDB.
- Thêm kiểm tra và xác thực dữ liệu đầu vào.
- Phát triển thêm tính năng như phân trang và lọc dữ liệu.
