# 🌟 Dự án Java Web Application

## 📌 Giới thiệu  

dự án này là một ứng dụng web được xây dựng bằng **Jakarta EE** với **JSP** ở frontend và **MySQL** làm database. Dự án sử dụng nhiều thư viện hỗ trợ như **BCrypt** để mã hóa mật khẩu, **Jakarta Mail** để gửi email và **Jackson** để xử lý JSON.

---

## 🚀 Công nghệ sử dụng

- **Backend:** Java (Jakarta EE)  
- **Frontend:** JSP, Bootstrap  
- **Database:** MySQL  

### 📦 Dependencies chính:
- **Bcrypt:** Mã hóa mật khẩu  
- **Jakarta Mail:** Gửi email  
- **Jackson:** Xử lý JSON  
- **SLF4J & Log4j:** Logging  
- **Google API Client:** Giao tiếp với API của Google  
- **JDBI:** tương tác Database   
- **HikariCP:** Quản lý kết nối database hiệu suất cao  

## 📚 Thư viện bên ngoài:
- **Bootstrap:** Framework CSS giúp thiết kế giao diện responsive nhanh chóng  
- **Bootstrap Icons:** Bộ icon mở rộng dành cho Bootstrap  
- **FontAwesome:** Thư viện icon phổ biến với nhiều biểu tượng đa dạng  
- **Animate.css:** Thư viện CSS để tạo hiệu ứng động cho giao diện  
- **SweetAlert2:** Hiển thị popup thông báo đẹp mắt và tùy chỉnh linh hoạt  
- **DataTables:** Plugin jQuery để tạo bảng dữ liệu có sắp xếp, tìm kiếm, phân trang  
- **Chart.js:** Thư viện vẽ biểu đồ trực quan dựa trên canvas  
- **CKEditor:** Trình soạn thảo văn bản WYSIWYG mạnh mẽ  
- **CKBox:** Dịch vụ lưu trữ và quản lý hình ảnh cho CKEditor  
---

## 🛠 Cài đặt và chạy dự án

### **1️⃣ Yêu cầu**
Trước khi bắt đầu, hãy đảm bảo bạn đã cài đặt:
- **JDK 23**  
- **Apache Tomcat** (nếu chạy trên server)  
- **MySQL Server**  
- **Maven** (để quản lý dependencies)

### **2️⃣ Clone repo**
```bash
git clone https://github.com/flourine95/drum_store.git
```

### **3️⃣ Cấu hình database**
- Tạo database trong MySQL:
```sql
CREATE DATABASE your_database_name;
```
- Cấu hình thông tin kết nối trong **`src/main/resources/application.properties`**:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=root
spring.datasource.password=your_password
```

### **4️⃣ Cài đặt dependencies**
Chạy lệnh:
```bash
mvn clean install
```

### **5️⃣ Chạy ứng dụng**
Nếu dùng **Maven**, chạy lệnh:
```bash
mvn tomcat7:run
```
Hoặc deploy lên **Tomcat** và truy cập:
```
http://localhost:8080/
```

---

## 📚 Cấu trúc thư mục

```
📆 your-project
👉💻 src
    👉💻 main
        👉💻 java/com/example
            👉💻 controller
            👉💻 service
            👉💻 model
            👉💻 repository
            👉 Application.java
        👉💻 webapp
            👉💻 WEB-INF
                👉 views (JSP files)
            👉💻 assets (CSS, JS)
    👉💻 test (Unit test)
👉 pom.xml (Khai báo dependencies)
👉 README.md
```

---

## ✅ Các tính năng chính
🔹 Đăng ký / Đăng nhập với mã hóa mật khẩu  
🔹 Gửi email xác nhận qua **Jakarta Mail**  
🔹 Quản lý dữ liệu với **MySQL & JDBI**  
🔹 Logging với **SLF4J & Log4j**  
🔹 REST API hỗ trợ JSON với **Jackson**  

---

## 🤝 Đóng góp
Mọ̣i đóng góp đều được hoan nghênh! Hãy fork repo, tạo pull request hoặc mở issue nếu bạn có ý tưởng cải tiến.

---

## 🐟 License
Dự án này được phát hành theo **MIT License**.

"# drum_store_gradle" 
"# drum_store_gradle" 
