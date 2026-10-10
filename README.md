# 📺 YouTube Multiview

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live_Demo-mymy123765.github.io-red?logo=youtube)](https://mymy123765.github.io)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen.svg)](#)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-purple.svg)](#)
[![Mobile Friendly](https://img.shields.io/badge/Responsive-Mobile_%26_Desktop-orange.svg)](#)

> **YouTube Multiview** là ứng dụng web gọn nhẹ, hiệu năng cao giúp bạn xem đồng thời **2, 3 hoặc 4 video / livestream YouTube** trên cùng một màn hình — với bố cục linh hoạt, modal thêm stream nhanh và phím tắt tiện lợi.

🔗 **Trải nghiệm trực tiếp tại:** [https://mymy123765.github.io](https://mymy123765.github.io)

---

## ✨ Tính năng nổi bật

- **Chọn số lượng stream**: Hiển thị **2, 3 hoặc 4** stream cùng lúc qua thanh điều khiển Streams trên toolbar.
- **Hai chế độ bố cục (Layout)**:
  - **Equal** — Chia đều không gian cho tất cả các stream.
  - **Main** — Một stream chính chiếm ưu thế, các stream phụ xếp cột bên cạnh.
  - *(Layout selector ẩn tự động khi chỉ có 2 streams.)*
- **Thêm stream qua Modal**: Click vào ô trống bất kỳ → hộp thoại mở ra để dán link hoặc ID video.
- **Hỗ trợ đa dạng định dạng link**:
  - `https://www.youtube.com/watch?v=ID`
  - `https://youtu.be/ID`
  - `https://www.youtube.com/shorts/ID`
  - `https://www.youtube.com/live/ID`
  - `https://www.youtube.com/embed/ID`
  - Hoặc trực tiếp nhập **ID video (11 ký tự)**.
- **Xóa stream nhanh**: Nút `×` xuất hiện khi hover góc trên phải của từng panel.
- **Bố cục thích ứng (Responsive)**:
  - Desktop: CSS Grid tối ưu từng kiểu bố cục.
  - Mobile: Chuyển sang flex column, 16:9 aspect-ratio, cuộn mượt mà.
  - Hỗ trợ tai thỏ / Dynamic Island qua `env(safe-area-inset)`.
- **Chế độ toàn màn hình (Fullscreen)**: Toolbar ẩn, workspace mở rộng tối đa; nút "Thoát toàn màn hình" hiện ở góc dưới phải.
- **Điều khiển âm thanh đồng bộ**: Mute/Unmute toàn bộ stream cùng lúc qua YouTube Iframe API (`postMessage`).
- **PWA Ready**: Có `site.webmanifest` — có thể cài đặt như ứng dụng trên điện thoại / máy tính.
- **Zero Dependencies**: 100% Vanilla HTML, CSS và JavaScript thuần — tải tức thì, không framework.

---

## ⌨️ Phím tắt nhanh (Keyboard Shortcuts)

| Phím tắt | Chức năng |
| :---: | :--- |
| <kbd>F</kbd> | Bật / tắt chế độ toàn màn hình (Fullscreen) |
| <kbd>M</kbd> | Mute / Unmute tất cả các stream đang phát |
| <kbd>Esc</kbd> | Đóng modal Add Stream **hoặc** thoát toàn màn hình |

*(Phím tắt tự động bị tạm tắt khi bạn đang gõ trong ô nhập liệu của modal.)*

---

## 🗂️ Bố cục lưới (Grid Layouts)

| Số stream | Equal | Main |
| :---: | :--- | :--- |
| **2** | 2 cột ngang bằng nhau (layout duy nhất) | — |
| **3** | 2 trên + 1 giữa dưới | 1 lớn trái + 2 nhỏ xếp phải |
| **4** | Lưới 2×2 | 1 lớn trái + 3 nhỏ xếp phải |

---

## 🚀 Hướng dẫn sử dụng

1. Truy cập [https://mymy123765.github.io](https://mymy123765.github.io).
2. Chọn số lượng stream (**2 / 3 / 4**) trên thanh toolbar.
3. Chọn kiểu bố cục (**Equal** hoặc **Main**) nếu dùng 3–4 streams.
4. Click vào ô trống → Dán URL YouTube hoặc ID video → nhấn **Add Stream**.
5. Bấm nút `×` (hover vào panel) để xóa stream bất kỳ.
6. Nhấn <kbd>F</kbd> để vào toàn màn hình, <kbd>M</kbd> để mute/unmute tất cả, <kbd>Esc</kbd> để thoát modal hoặc fullscreen.

---

## 🛠️ Công nghệ xây dựng

- **HTML5**: Semantic HTML, SEO meta tags, Open Graph, PWA Manifest.
- **CSS3**: CSS Grid (multi-area layouts), Flexbox, CSS Custom Properties, `env(safe-area-inset)`, `100dvh`.
- **JavaScript (ES6+)**: Vanilla JS, DOM manipulation, YouTube Iframe API (`postMessage`), `URL` API, Fullscreen API.
- **Deployment**: GitHub Pages (zero-build, static).

---

## 📁 Cấu trúc dự án

```
mymy123765.github.io/
├── index.html        # Toàn bộ ứng dụng (HTML + CSS + JS, single-file)
├── favicon.svg       # Icon SVG
├── site.webmanifest  # PWA manifest
├── robots.txt        # SEO robots
├── sitemap.xml       # SEO sitemap
└── README.md
```

---

## 📄 Bản quyền (License)

Dự án được phân phối dưới giấy phép [MIT License](LICENSE). Tự do sử dụng, chỉnh sửa và phân phối.
