# 📄 Tổng quan Dự án

Dự án này là một mẫu giao diện web, phù hợp cho doanh nghiệp liên quan đến ẩm thực...

## 🌐 Demo
Truy cập thử: [https://nguyendinhgiabao.github.io/do_an_web/](#)

## 🖼️ Ảnh giao diện
![Trang chủ](img/screenshot_home.png)
![Trang sản phẩm](img/screenshot_shop.png)

## 🗂️ Cấu trúc thư mục

```
do_an_web/
├── index.html
├── about.html
├── css/
├── js/
├── img/
└── ...
```
---

## ✨ Tính năng nổi bật

- **Mẫu website hoàn chỉnh:** Cung cấp sẵn cấu trúc cho website về ẩm thực.
- **Thiết kế responsive:** Hiển thị tốt trên nhiều kích thước màn hình (CSS).
- **Trang có sẵn:** Trang chủ, giới thiệu, blog, cửa hàng, liên hệ, giỏ hàng.
- **Tài nguyên đa phương tiện:** Hình ảnh, font chữ thẩm mỹ.
- **Tính năng tương tác:** JavaScript tạo hiệu ứng, tăng trải nghiệm người dùng.

---

## ⚙️ Yêu cầu hệ thống & Thư viện phụ thuộc

- **Trình duyệt web:** Chrome, Firefox, Safari, v.v.
- **Trình soạn thảo mã nguồn/IDE:** VS Code, Sublime Text, v.v.
- **(Tuỳ chọn) Máy chủ web:** XAMPP, WAMP hoặc máy chủ tĩnh nếu muốn chạy từ server cục bộ (không bắt buộc).

---

## 🚀 Hướng dẫn cài đặt & khởi chạy

1. **Clone repository:**
   ```sh
   git clone https://github.com/nguyendinhgiabao/do_an_web.git
   cd do_an_web
   ```
2. **Mở file index.html:**  
   Chỉ cần mở file `index.html` bằng trình duyệt để xem website.
3. **(Tuỳ chọn) Khởi tạo máy chủ cục bộ:**
   - Cài đặt XAMPP, WAMP hoặc tương đương.
   - Đặt thư mục dự án (`do_an_web`) vào thư mục gốc của máy chủ (ví dụ: `htdocs` nếu dùng XAMPP).
   - Chạy máy chủ.
   - Truy cập qua địa chỉ: `http://localhost/do_an_web/` hoặc tương ứng.

---

## 🛠️ Hướng dẫn tuỳ chỉnh & API

Dự án là template front-end, **không bao gồm backend hay API**.

- **HTML:** Chỉnh sửa nội dung trong các file như `index.html`, `about.html`.
- **CSS:** Tuỳ chỉnh giao diện tại thư mục `css/`.
- **JavaScript:** Thêm/tùy chỉnh chức năng tại thư mục `js/`.

**Ví dụ sử dụng jQuery trong `main.js`:**
```js
$(document).ready(function() {
  console.log("Website loaded!");

  $('.owl-carousel').owlCarousel({
    items: 1,
    loop: true,
    margin: 10,
    nav: true
  });
});
```

### ⚙️ Tuỳ chỉnh giao diện

- **Hình ảnh:** Thay thế trong thư mục `img/`.
- **Font chữ:** Tuỳ chỉnh trong các file CSS.
- **Màu sắc:** Thay đổi mã màu trực tiếp trong CSS.

---

## 🤝 Hướng dẫn đóng góp

1. Fork repository.
2. Tạo nhánh mới cho thay đổi của bạn.
3. Thực hiện chỉnh sửa, cập nhật.
4. Commit với nội dung rõ ràng.
5. Push lên repository của bạn.
6. Tạo Pull Request về repository chính.

---

## 📄 Thông tin bản quyền

Chưa có thông tin về giấy phép. Vui lòng liên hệ chủ sở hữu repository (nguyendinhgiabao) để biết chi tiết.

---

## 🙏 Ghi nhận

Dự án sử dụng các thư viện mã nguồn mở sau:

- **jQuery:** Thao tác DOM.
- **Owl Carousel:** Tạo slider/carousel.
- **Magnific Popup:** Popup ảnh hoặc nội dung.
- **Nice Select:** Tuỳ chỉnh giao diện `<select>`.
- **Slicknav:** Tạo menu responsive.
- **Elegant Icons, Font Awesome:** Bộ biểu tượng.

---
