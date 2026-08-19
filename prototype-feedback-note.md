# PROTOTYPE FEEDBACK NOTE (CÁ NHÂN FACILITATE)

**Người facilitate:** Kim Mạnh Hưng (MHV: 2A202601679)  
**Vai trò:** Facilitator chính cho các phiên User Testing với 3 testers ngoài nhóm trên 3 Solution Options (A, B, C).  
**Thời gian thực hiện:** Day 18 — Chặng 6 (User Testing & Observation)

---

## 1. THÔNG TIN NGƯỜI THAM GIA TEST (TESTERS NGOÀI NHÓM)

| Tester | Tên / Bối cảnh | Option trọng tâm được thử nghiệm |
| :--- | :--- | :--- |
| **Tester 01** | Khanh | Option C (AI-Led) $\rightarrow$ Option A (User-Led) |
| **Tester 02** | Trung | Option B |
| **Tester 03** | Đức | Tổng hợp trải nghiệm A, B, C |

---

## 2. GHI CHÉP CHI TIẾT CÁC PHIÊN TEST (OBSERVATIONS & FEEDBACK)

### 🟢 Phiên Test 1 — Tester 01 (Khanh)
- **Nhiệm vụ (Task):** Trải nghiệm ghi chú tự động ở Option C (AI-Led), sau đó thử dùng Option A (User-Led) để yêu cầu AI giải thích thuật ngữ khó bôi đen.
- **Hành vi quan sát được (Observed Behaviors):**
  - Nhanh chóng phát hiện ra thẻ ghi chú AI Proactive ở Sidebar phải (Option C), nhưng thể hiện sự ngập ngừng/hoài nghi về tính chính xác và độ liên quan của ghi chú tự động đối với nhu cầu cá nhân.
  - Khi chuyển qua Option A, tester tương tác tích cực với thao tác bôi đen từ khóa để gọi AI, nhưng gặp rào cản nhỏ do độ nhạy của thao tác chọn văn bản trên prototype.
- **Phản hồi nguyên văn & Góp ý từ Tester:**
  - *"Ghi chú AI tự động khá tiện và giải thích dễ hiểu, nhưng hệ thống cần biết người dùng có thực sự cần dùng tới giải thích đó hay không để tránh làm loãng nội dung."*
  - **Cá nhân hóa nội dung:** Cần có cơ chế lưu trữ các giải thích đã tạo và tùy chỉnh độ sâu giải thích theo trình độ/gu học tập (vd: giải thích bằng ví dụ đời sống vs. phân tích kỹ thuật sâu).
  - **Cấu trúc thông tin:** Đề xuất tách thành nhiều thẻ note kiến thức nhỏ (Granular Multi-cards) cho từng khái niệm trên slide thay vì gộp chung vào 1 thẻ tóm tắt duy nhất.

### 🟡 Phiên Test 2 — Tester 02 (Trung)
- **Nhiệm vụ (Task):** Trải nghiệm Option B (Co-Creation) bằng thao tác nối các khối khái niệm để kích hoạt Mini-Quiz và kiểm tra thanh công cụ vẽ trên slide.
- **Hành vi quan sát được (Observed Behaviors):**
  - Thể hiện sự hứng thú cao khi nối 2 ô Guideline và xuất hiện Mini-Quiz gợi mở tư duy.
  - Tỏ ra bối rối ngắn khi phát hiện các công cụ như Bút vẽ / Highlight trên thanh Reader Toolbar chỉ mang tính chất mô phỏng giao diện (Static UI Mockup) chứ chưa tương tác vẽ tự do trên canvas.
- **Phản hồi nguyên văn & Góp ý từ Tester:**
  - *"Ý tưởng AI đóng vai trò Coach đặt câu hỏi gợi mở rất hay, giúp mình phải thực sự suy nghĩ và nhớ bài lâu hơn."*
  - **Thiếu không gian tổng hợp thắc mắc:** AI đã tạo ghi chú bài học nhưng chưa có khu vực riêng để ghi nhận các câu hỏi/thắc mắc cá nhân do người học tự gõ.
  - **Đề xuất UX:** Cần bổ sung một bảng/sổ tay tổng hợp ghi chú nằm ngay bên cạnh slide để theo dõi mạch học tập.

### 🔵 Phiên Test 3 — Tester 03 (Đức)
- **Nhiệm vụ (Task):** Đánh giá và so sánh luồng ghi chú trên cả 3 Option (A, B, C).
- **Hành vi quan sát được (Observed Behaviors):**
  - Tập trung so sánh khu vực Sidebar phải giữa Option B và Option C; có thói quen vừa đọc vừa gõ lại thắc mắc cá nhân để chuẩn bị hỏi giảng viên.
- **Phản hồi nguyên văn & Góp ý từ Tester:**
  - Đồng quan điểm với Tester 02: AI tự tạo note bài học là tốt, nhưng trong lúc đọc slide người học luôn phát sinh thắc mắc riêng. Nếu hệ thống không cung cấp chỗ để gõ và lưu lại các thắc mắc này thì người học vẫn phải dùng app ngoài (Notion/Word).
  - **Đề xuất UX:** Bắt buộc tích hợp một Sidebar/Drawer "Sổ tay cá nhân" tập trung, cho phép lưu trữ song song cả note do AI đề xuất và ghi chú/câu hỏi tự gõ của người học.

---

## 3. ĐÚC KẾT & RÀO CẢN CHÍNH NÊN ĐIỀU CHỈNH (SUMMARY OF KEY FINDINGS)

- **Rào cản về cá nhân hóa & Độ phủ (Need for Granular & Personalized Notes):**  
  Một thẻ AI Note chung chung chưa đáp ứng đủ nhu cầu. Cần chia nhỏ theo từng thuật ngữ và cho phép tùy chỉnh phong cách giải thích (Feynman vs Technical).
- **Khoảng trống về ghi nhận thắc mắc cá nhân (Unmet Need for Personal Q&A):**  
  Các Option hiện tại tập trung nhiều vào việc AI cung cấp kiến thức (Output) mà chưa cho phép người học ghi lại câu hỏi / thắc mắc tự thân trong lúc đọc slide.
- **Mô phỏng công cụ vẽ trên Slide (Prototype Limitation):**  
  Nhu cầu vẽ/khoanh vùng trực tiếp là có thật. Cần làm rõ phạm vi mô phỏng (fidelity scope) để tester không bị ngắt mạch trải nghiệm.
