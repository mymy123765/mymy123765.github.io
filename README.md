# 📺 YouTube Multiview

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live_Demo-mymy123765.github.io-red?logo=youtube)](https://mymy123765.github.io)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen.svg)](#)
[![Mobile Friendly](https://img.shields.io/badge/Responsive-Mobile_%26_Desktop-orange.svg)](#)

> **YouTube Multiview** là ứng dụng web gọn nhẹ, hiệu năng cao giúp bạn xem đồng thời tối đa **4 video hoặc livestream YouTube** trên cùng một màn hình với khả năng tự động canh chỉnh bố cục và hỗ trợ phím tắt tiện lợi.

🔗 **Trải nghiệm trực tiếp tại:** [https://mymy123765.github.io](https://mymy123765.github.io)

---

## ✨ Tính năng nổi bật

- **Xem đa luồng linh hoạt**: Tùy chỉnh hiển thị từ **1 đến 4 video** cùng lúc, phù hợp theo dõi giải đấu Esports, tin tức nhiều góc máy, podcast hoặc livestream.
- **Bố cục thích ứng (Responsive Grid)**:
  - Tự động sắp xếp lưới tối ưu trên Desktop (1x1, 2x1, 2x2).
  - Tối ưu cho thiết bị di động (Mobile dọc cuộn mượt mà, Mobile ngang tràn viền).
  - Tương thích tốt với tai thỏ / Dynamic Island qua `env(safe-area-inset)`.
- **Hỗ trợ đa dạng định dạng link**:
  - `https://www.youtube.com/watch?v=ID`
  - `https://youtu.be/ID`
  - `https://www.youtube.com/shorts/ID`
  - `https://www.youtube.com/live/ID`
  - `https://www.youtube.com/embed/ID`
  - Hoặc trực tiếp nhập **ID video (11 ký tự)**.
- **Chế độ toàn màn hình (Fullscreen)**: Mở rộng tối đa không gian xem, ẩn thanh điều hướng.
- **Điều khiển âm thanh đồng bộ**: Bật/tắt tiếng nhanh cho tất cả luồng phát thông qua YouTube Iframe API.
- **Zero Dependencies**: 100% Vanilla HTML, CSS và JavaScript thuần — tải trang tức thì, không sử dụng framework nặng nề.

---

## ⌨️ Phím tắt nhanh (Keyboard Shortcuts)

Để thao tác nhanh khi không tiện dùng chuột:

| Phím tắt | Chức năng |
| :---: | :--- |
| <kbd>H</kbd> | Ẩn / hiện thanh bảng điều khiển (Header Controls) |
| <kbd>F</kbd> | Bật / tắt chế độ toàn màn hình (Fullscreen) |
| <kbd>M</kbd> | Bật / tắt tiếng tất cả các video đang phát |
| <kbd>Enter</kbd> | Tải ngay Multiview khi đang gõ liên kết trong ô nhập |
| <kbd>Esc</kbd> | Thoát chế độ toàn màn hình |

*(Lưu ý: Các phím tắt đơn ký tự sẽ tạm tắt khi bạn đang tập trung gõ văn bản trong các ô nhập URL).*

---

## 🚀 Hướng dẫn sử dụng

1. Truy cập [https://mymy123765.github.io](https://mymy123765.github.io).
2. Dán các đường dẫn YouTube bạn muốn xem vào các ô **Video 1, 2, 3, 4**.
3. Chọn số lượng khung phát mong muốn (hoặc để mặc định 4).
4. Nhấn **"Tải Multiview"** (hoặc bấm <kbd>Enter</kbd>).
5. Bấm vào nút `×` ở từng góc video để xóa nhanh luồng phát đó.

---

## 🛠️ Công nghệ xây dựng

- **HTML5**: Cấu trúc ngữ nghĩa (Semantic HTML) & hỗ trợ SEO.
- **CSS3**: CSS Grid, Flexbox, CSS Custom Properties, Safe Area Insets.
- **JavaScript (ES6+)**: Xử lý DOM, Regular Expression phân tích URL, YouTube Iframe API `postMessage`.
- **Deployment**: GitHub Pages.

---

## 📄 Bản quyền (License)

Dự án được phân phối dưới giấy phép [MIT License](LICENSE). Tự do sử dụng, chỉnh sửa và phân phối.
