# 🚗 TrafficX - Hệ thống giám sát giao thông thông minh

> **TrafficX** là hệ thống giám sát giao thông hiện đại, giúp nhận diện phương tiện vi phạm, cung cấp thông tin chi tiết và hỗ trợ ChatBot tư vấn nhanh về Luật giao thông Việt Nam.

---

## 🌟 Tính năng nổi bật

✅ **Nhận diện phương tiện vi phạm** theo thời gian thực với công nghệ AI.  
✅ **Tìm kiếm nhanh thông tin xe vi phạm** bằng biển số xe.  
✅ **ChatBot AI** hỗ trợ hỏi đáp tức thì về Luật giao thông Việt Nam.  
✅ **Giao diện trực quan**, dễ sử dụng trên cả desktop và mobile.  
✅ **Tích hợp API mở rộng**, dễ dàng kết nối với các hệ thống khác.  

---

## 🛠️ Hướng dẫn cài đặt Frontend trên Windows

> **Yêu cầu hệ thống:** Windows 10/11, RAM tối thiểu 4GB, Node.js v16+.

### 📌 1️⃣ Cài đặt **Visual Studio Code**

- Tải và cài đặt VS Code tại: [🔗 VS Code](https://code.visualstudio.com/)
- Đề xuất các extensions hữu ích:
  - `Vetur` hoặc `Vue Language Features` (hỗ trợ Vue.js)
  - `ESLint` (hỗ trợ kiểm tra mã nguồn)
  - `Prettier` (định dạng mã nguồn tự động)

### 📌 2️⃣ Cài đặt **Node.js**

- Tải và cài đặt tại: [🔗 Node.js](https://nodejs.org/)
- Kiểm tra cài đặt thành công:
  ```sh
  node -v   # Kiểm tra phiên bản Node.js
  npm -v    # Kiểm tra phiên bản NPM
  ```

### 📌 3️⃣ Đăng ký tài khoản **Grod** và lấy API Key

- Truy cập: [🔗 Grod](https://grod.com/)
- Đăng ký tài khoản và lấy **GROD_API_KEY**
- Lưu trữ API Key cẩn thận, **tránh chia sẻ công khai**.

### 📌 4️⃣ Clone repository từ GitHub

```sh
git clone https://github.com/MinhPhambk/TrafficX_Frontend.git
```

### 📌 5️⃣ Truy cập vào thư mục dự án

```sh
cd TrafficX_Frontend
```

### 📌 6️⃣ Cấu hình biến môi trường `.env`

- Mở file `.env` trong thư mục dự án.
- Cập nhật giá trị API Key:
  ```env
  GROD_API_KEY=your_api_key_here
  ```
- **Lưu ý:** Nếu chưa có file `.env`, hãy tạo một file mới.

### 📌 7️⃣ Cài đặt các dependencies

```sh
npm install
```

### 📌 8️⃣ Chạy dự án ở chế độ phát triển

```sh
npm run dev
```

### 📌 9️⃣ Truy cập giao diện web

- Mở trình duyệt và truy cập:  
  🖥️ **[http://localhost:5173](http://localhost:5173)**  
- Nếu gặp lỗi, thử chạy lại với quyền **Administrator**.

---

## 🚀 Hỗ trợ & Liên hệ

📧 Email: [phamngocminh1230@gmail.com](mailto:phamngocminh1230@gmail.com)  
🐞 Báo lỗi: [🔗 Issues trên GitHub](https://github.com/MinhPhambk/TrafficX_Frontend/issues)  

🎯 **TrafficX - Công nghệ giao thông thông minh, an toàn hơn mỗi ngày!**