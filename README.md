# TRÀ MỘC · AEGIS PROTOCOL — Độc Quyền: Quyền Lực & Cái Giá

Game kết hợp **Đấu Trường Chiến Đấu Không Gian 5 Người Chơi (5-Player Star Formation PvP & Bot Simulation)** cùng **Mô Phỏng Kinh Tế & Bài Học Triết Học Mác – Lênin**.
Nhóm 4 · Học phần Triết học Mác – Lênin (2026).

Một game trình duyệt thuần HTML/CSS/JavaScript: **không build, không server bắt buộc, hỗ trợ WebRTC P2P qua PeerJS**.
Mở `index.html` là chơi ngay.

---

## Cốt truyện & Bối cảnh: 5 Tàu Cướp Phá Lẫn Nhau

Năm 2124, trên **Liên bang Vành đai** — một nền văn minh sống trong các trạm không gian và vành quỹ đạo:
Trên hải trình vận tải nguyên liệu trà Mộc thủy canh thượng hạng và tinh dầu sinh thái lượng tử, phi thuyền chuyên dụng **Aegis-7** của Tập đoàn Trà Mộc bất ngờ gặp bão thiên thạch dữ dội và phải hạ cánh khẩn cấp xuống một hành tinh hoang phế ngoài rìa Ngân Hà.

Lớp vỏ tàu nứt toác, các container trà quý rò rỉ bức xạ sinh thái đã kích hoạt hệ thống radar tầm xa của **4 chiến hạm vũ trang thuộc các tập đoàn đối thủ và hải tặc không gian**:
1. **Chuỗi Trà Vương:** Tuần tra hạm vũ trang bọc thép hạng nặng.
2. **Phương Nam Agri:** Tuần dương hạm laser kiểm soát chuỗi cung ứng.
3. **Nova-Valkyrie:** Phi thuyền xung kích tốc độ cao của lính đánh thuê.
4. **Cartel Vành Đai:** Đoàn tàu cướp phá hỏa lực pháo plasma tàn bạo.

Bạn chỉ huy **Robot Bảo An UNIT-07** trên soái hạm Trà Mộc (trang bị súng Plasma Blaster và Khiên Năng Lượng 200/200 HP). Nhiệm vụ của bạn là giải mã các câu hỏi tri thức Triết học Mác – Lênin để nạp đạn Plasma, bắn phá khiên chắn và đẩy lùi hỏa lực của 4 chiến hạm đối thủ qua 3 khu vực chiến trường (`Kho Hàng`, `Lò Phản Ứng`, `Cầu Tàu`), đồng thời đưa ra 36 quyết định chiến lược để xây dựng thương hiệu Trà Mộc, giải mã bản chất của Độc Quyền và kích hoạt cột Hải Đăng Cứu Hộ S.O.S!

Luận đề của game:

> Quá trình tích tụ và tập trung tư bản tất yếu sinh ra độc quyền.
> Mỗi lựa chọn trên thương trường và chiến trường sinh tồn đều đi kèm cái giá phải trả.

---

## Cơ chế Đấu Trường Ngôi Sao 5 Tàu (Star Formation Arena)

- **Đội hình 5 Tàu Chiến Tinh Vân:**
  - **Trung tâm bên trái:** Thẻ bài Robot Unit-07 đại diện cho chiến hạm Trà Mộc với Khiên Sinh Thái 200/200 HP, hiệu ứng nạp đạn Plasma, cảnh báo khiên nguy cấp và tự động sửa chữa.
  - **4 Pod Chiến Hạm Đối Thủ:** Bố trí hình cánh cung sao (Star Formation) đại diện cho 4 thế lực: *Chuỗi Trà Vương*, *Phương Nam Agri*, *Nova-Valkyrie*, và *Cartel Vành Đai* (mỗi tàu 200/200 HP với thanh HP thời gian thực).
- **Hệ Thống Khóa Mục Tiêu & Pháo Kích Chéo (Crossfire):**
  - Nhấp chuột trực tiếp vào bất kỳ chiến hạm đối thủ nào để khóa tâm ngắm mục tiêu.
  - Trả lời đúng: Robot Unit-07 bắn chùm tia Plasma xuyên giáp gây -40 HP cho mục tiêu được chọn.
  - Trả lời sai: Hệ thống phản lực chập mạch, trừ -25 HP khiên tự thân.
  - Mô phỏng Bot AI & WebRTC Multiplayer: 4 tàu đối thủ liên tục pháo kích chéo lẫn nhau (-20 HP đến -40 HP) và bắn phá người chơi trong thời gian thực.
  - Khiên về 0 HP: Tàu chuyển sang trạng thái SỬA CHỮA / NẠP KHIÊN và tự động hồi sinh phục hồi 200/200 HP sau thời gian chờ.

---

## Hướng dẫn chơi

1. Mở trực tiếp file `index.html` bằng trình duyệt (Chrome, Edge, Firefox, Safari).
2. Chọn **Chế độ Chơi Đơn (AI Bots)** hoặc **Tạo Phòng / Tham Gia Phòng (P2P Multiplayer 5 người)**.
3. Đọc cốt truyện dẫn nhập, giải mã các câu hỏi tri thức để nạp đạn bắn phá chiến hạm đối thủ, đưa ra lựa chọn kinh tế và mở khóa 6 đại kết cục!
