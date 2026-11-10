# 50 năm THPT Phú Nhuận — Không gian cúp 3D

Trang trưng bày tĩnh cho dấu mốc 1976–2026. Mô hình cúp tự xoay, kéo để xem quanh, phóng to và dừng chuyển động. Có 14 nội dung giải nghĩa logo, bố cục thích ứng điện thoại và hỗ trợ giảm chuyển động.

Chạy tại thư mục này: `py -m http.server 8765`, mở http://localhost:8765.

- `assets/cup.glb`: mô hình cúp bản 02 dựng từ tư liệu TVC; tỷ lệ và kích thước là ước lượng.
- `app.js`: 14 nội dung được nhận diện từ Noi dung.jpg.
- `style.css`: nền xanh, vàng, dải lụa và quỹ đạo ánh sáng.
- `assets/model-viewer.min.js`: Google model-viewer 4.1.0, Apache-2.0. https://modelviewer.dev/

GitHub Actions tự triển khai GitHub Pages khi có thay đổi ở nhánh main. Không cần khóa API. Trang chỉ bao gồm tài nguyên hiển thị; không công khai video và file AI gốc.
