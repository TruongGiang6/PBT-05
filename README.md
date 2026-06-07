# PBT-05 - CSS RESPONSIVE & SCSS — Responsive Design, Media Queries, Sass

Dự án này chứa các bài tập thực hành và câu trả lời lý thuyết về CSS nâng cao, tập trung vào thiết kế web đáp ứng (Responsive), hiệu ứng chuyển động (Animations) và bộ tiền xử lý SCSS.

📁 Cấu trúc thư mục
``` text
PBT-05/
├── screenshots/
├── scss/
│   ├── _components.scss
│   ├── _mixins.scss
│   ├── _variables.scss
│   └── style.scss
├── answers.md
├── animations.html
├── animations.css
├── responsive.html
├── responsive.css
└── README.md
```

* screenshots/: Chứa các hình ảnh kết quả của bài tập trên các kích thước màn hình khác nhau.
* scss/: Thư mục chứa mã nguồn SCSS được tổ chức theo kiến trúc phân mảnh (partials):
  * _variables.scss: Lưu trữ các biến cấu hình (màu sắc, font chữ, breakpoint...).
  * _mixins.scss: Chứa các mixin (đoạn code CSS dùng chung, có thể tái sử dụng).
  * _components.scss: Chứa style riêng cho từng thành phần giao diện (nút bấm, card, form...).
  * style.scss: File SCSS chính dùng để import các partials ở trên và biên dịch ra file CSS cuối cùng.
* answers.md: Câu trả lời cho các câu hỏi lý thuyết về Responsive, Animations và cách hoạt động của SCSS.
* animations.html & animations.css: Bài tập thực hành tạo hiệu ứng chuyển động (`@keyframes`, `transition`, `transform`).
* responsive.html & responsive.css: Bài tập thực hành thiết kế giao diện tương thích đa thiết bị sử dụng Media Queries (`@media`).

👤 Thông tin sinh viên

* Họ và tên: Vũ Trường Giang
* MSV: 2451170885
* Trường: Đại học Thủy Lợi (TLU)


🚀 Cách xem dự án

Mở trực tiếp các tệp .html trong trình duyệt web để xem kết quả. Đối với phần Responsive, hãy thử co giãn cửa sổ trình duyệt hoặc dùng phím F12 (DevTools) để kiểm tra giao diện trên điện thoại/máy tính bảng.