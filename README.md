# 🚀 NhatHoang | Elite Developer Portfolio

Chào mừng đến với mã nguồn Portfolio cá nhân của mình! Đây là một dự án web tĩnh (Single-page HTML) được thiết kế với phong cách **Cyber / Glassmorphism**, mang đậm dấu ấn cá nhân và tối ưu hóa trải nghiệm người dùng.

🌐 **Live Demo:** [https://nhatdz.tech](https://nhatdz.tech)

---

## ✨ Tính Năng Nổi Bật

Dự án không chỉ là một trang giới thiệu thông thường mà còn tích hợp nhiều kỹ thuật front-end nâng cao:

- **Giao diện Cyber / Glassmorphism:** Sử dụng CSS hiện đại, hiệu ứng kính mờ (backdrop-filter) kết hợp với các dải màu gradient rực rỡ.
- **Đồ họa & Hiệu ứng (WebGL / Canvas):**
  - Nền Shader WebGL tương tác theo chuột (Noise, Wave, Chromatic Aberration).
  - Hệ thống hạt (Bubbles) và con rồng SVG bơi theo con trỏ chuột.
  - Hiệu ứng chữ Glitch, custom cursor mượt mà.
- **Terminal Tương Tác:** Một cửa sổ command-line ngay trên web cho phép gõ lệnh thật (vd: `whoami`, `theme`, `matrix`, `snake`, `help`).
- **Command Palette:** Bấm `Ctrl + K` để mở bảng tìm kiếm và điều hướng nhanh (giống VS Code).
- **Music Player Tích Hợp:**
  - Trình phát nhạc tự viết với Visualizer (sóng nhạc) chạy bằng Web Audio API.
  - Thanh tua (seek bar) và âm lượng (volume) hỗ trợ kéo thả mượt mà trên cả PC và Mobile.
- **Tối Ưu Hiệu Năng (Adaptive Performance):** Tự động đo FPS, nếu phát hiện máy yếu sẽ tự động tắt các hiệu ứng nặng (WebGL, cursor) để đảm bảo không bị lag.
- **Tính Năng Phụ:** Mini game Snake, Konami Easter Egg (Matrix mode), Live GitHub Activity, Visitor Counter, Theme Switcher (4 chủ đề màu).

---

## 🛠 Công Nghệ Sử Dụng

Dự án được viết **100% bằng Vanilla (thuần)** để tối ưu tốc độ và dung lượng, không sử dụng framework cồng kềnh:
- **HTML5 / CSS3:** Grid, Flexbox, CSS Variables, Keyframe Animations.
- **JavaScript (ES6+):** Xử lý logic, DOM manipulation, Intersection Observer.
- **WebGL / Canvas API:** Vẽ nền shader và visualizer.
- **Web Audio API:** Xử lý âm thanh cho trình phát nhạc.
- **API Bên Thứ 3:** GitHub API (fetch repos), CounterAPI (lượt truy cập), iTunes API (preview nhạc).

---

## 🚀 Hướng Dẫn Cài Đặt & Chạy Thử

Vì là dự án web tĩnh 1 file, việc chạy thử cực kỳ đơn giản:
Mở file index.html:

Bác có thể click đúp chuột vào file index.html để mở bằng trình duyệt.

Hoặc sử dụng Extension Live Server trên VS Code để chạy với môi trường localhost (khuyến nghị, để tránh lỗi CORS khi gọi API nhạc).

(Lưu ý: Một số tính năng fetch API có thể bị chặn nếu chạy trực tiếp bằng file:// mà không qua server).

🕹️ Cách Trải Nghiệm Nhanh
Mở trang web.

Bấm Ctrl + K (hoặc Cmd + K trên Mac) để mở Command Palette.

Gõ help vào ô Terminal ở phần Header để xem danh sách lệnh.

Thử đổi Theme bằng các nút tròn ở góc trên bên phải.

Bấm nút "Play Snake Game" ở gần cuối trang để giải trí.

👤 Tác Giả
NhatHoang (NhatDz)

GitHub: @nhat2907

Discord: 7c3z

1. **Clone repo này về máy:**
   ```bash
   git clone https://github.com/nhat2907/portfolio.git
