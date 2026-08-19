# Track1_Day18_2A202601791_NguyenTheAnh

## I. THÔNG TIN CÁ NHÂN VÀ NHÓM

- **Mã học viên (MHV):** 2A202601791
- **Họ và tên:** Nguyễn Thế Anh
- **Tên nhóm:** 3H
- **Case đã chọn:** Case B — AI Notes: Personal Learning Notes

### Thành viên trong nhóm:
1. **Cao Hữu Phúc** (MHV: 2A202601283) — Facilitator Option A
2. **Kim Mạnh Hưng** (MHV: 2A202601679) — Facilitator Option B
3. **Nguyễn Thế Anh** (MHV: 2A202601791) — Facilitator Option C

---

## II. HYPOTHESIS PROBLEM (BẢN CHỐT DAY 18)

> "Khi quay lại bài học để ôn thi hoặc làm bài tập (đặc biệt với các slide khó/chứa nội dung kỹ thuật), học viên (Learner) gặp khó khăn trong việc hiểu sâu, kết nối các khái niệm và hình dung cách áp dụng kiến thức vào thực tế, vì họ dễ quên định nghĩa và thiếu các ví dụ giải thích theo ngữ cảnh phù hợp, dẫn đến tốn quá nhiều thời gian ôn tập và phải tự tra cứu rải rác ngoài internet hoặc hỏi AI nhiều lần."

---

## III. THREE SOLUTION OPTIONS (MÔ TẢ CÁC OPTION)

### Option A: User-Led (On-Demand AI Tutor)
**Mô tả:** Học viên hoàn toàn chủ động bôi đen khái niệm khó trên slide và chọn nút Giải thích / Ví dụ trên Toolbar nổi. AI chỉ phản hồi đoạn được chọn dưới dạng ngôn ngữ đơn giản + 1 ví dụ đời sống.

**Link Prototype:** [`option-a.html`](option-a.html)

### Option B: Co-Creation (Interactive Concept Connector)
**Mô tả:** Học viên dùng công cụ khoanh vùng nối 2 khái niệm khó trên slide. AI đóng vai trò Coach, tạo câu hỏi thử thách suy luận ngắn (Mini-quiz) để người học tự trả lời trước khi chốt lưu thành note.

**Link Prototype:** [`option-b.html`](option-b.html)

### Option C: AI-Led (Proactive Enriched Notes)
**Mô tả:** AI tự động quét slide khó ngay khi mở, trích xuất thuật ngữ chuyên ngành và soạn sẵn thẻ ghi chú dịch thuật ngữ + ví dụ ở Panel bên phải. Học viên kiểm tra và bấm Lưu vào sổ tay hoặc Chỉnh sửa.

**Link Prototype:** [`option-c.html`](option-c.html)

---

## IV. ĐÓNG GÓP CỦA TÔI TRONG NHÓM

### Trách nhiệm Option:
Phụ trách chính thiết kế và kiểm thử **Option C (AI-Led: Proactive Enriched Notes)**.

### Đóng góp Shared Context/Content:
- Tổng hợp bài học mẫu (*Design the Experiment - Slide 7*) làm dữ liệu thử nghiệm chuẩn cho cả 3 Options.
- Phối hợp xây dựng bảng phân định **Agency & Control** giữa người học và AI.
- Quy định cơ chế **Recovery** khi AI đưa ra phản hồi quá chung chung hoặc mờ nghĩa.

### Facilitation & Observation:
- Trực tiếp facilitate phiên User Testing với 1 tester ngoài nhóm.
- Ghi nhận Feedback Note và tổng hợp vào Group Synthesis.

## V-B. PROTOTYPE FEEDBACK (CHẶNG 6) - TỔNG HỢP TESTER

### Tester 01
- **Nhận xét chung:** Sản phẩm ấn tượng, tuy nhiên thiếu tổng hợp các note lại để giải thích (từ cả 3 option)
- **Chi tiết:** Tính năng highlight, khoanh vùng vẫn mới là tượng trưng thôi

### Tester 02
- **Nhận xét chung:** Sản phẩm tạo ra độ mới mẻ vừa học vừa chơi, có phần ghi chú chi tiết bên cạnh mỗi slide bài học để hiểu rõ hơn nội dung
- **Chi tiết:** Tuy nhiên tính năng highlight chưa hoạt động thực sự

### Tester 03
- **Nhận xét Option C (AI-Led):** AI có ghi chú note bài học nhưng chưa tổng hợp lại note thắc mắc của người dùng. Cần bổ sung tính năng tổng hợp note bên cạnh.
- **Nhận xét chung:** Nên bổ sung thêm nhiều thẻ note trên 1 slide

### Tổng hợp Feedback Chung:
1. Cần bổ sung tính năng **tổng hợp các note** lại để giải thích (từ cả 3 option)
2. Tính năng **highlight, khoanh vùng** cần hoạt động thực sự, không chỉ là tượng trưng
3. **Option C:** AI cần tổng hợp cả note thắc mắc của người dùng, không chỉ ghi chú bài học
4. Cần bổ sung **nhiều thẻ note trên 1 slide**
5. Cần đánh nhãn cảnh báo rõ ràng khi AI tóm tắt tài liệu chuyên ngành (Expectations vs. Capabilities)

---

## VI. AI SUPPORT LOG

Chi tiết việc sử dụng AI trong suốt quá trình suy luận, phản biện và chuẩn hóa báo cáo được ghi nhận tại [`ai-support-log.md`](ai-support-log.md).

---

## VII. CẤU TRÚC DỰ ÁN

```
├── index.html              # Trang chủ - chọn Option A/B/C
├── option-a.html           # Option A: User-Led (On-Demand AI Tutor)
├── option-b.html           # Option B: Co-Creation (Interactive Concept Connector)
├── option-c.html           # Option C: AI-Led (Proactive Enriched Notes)
├── gallery.html            # Gallery tổng hợp 7 ảnh
├── README.md               # Tài liệu dự án
├── ai-support-log.md       # Log sử dụng AI
├── three-option-design-sheet.md
├── prototype-link.md
├── prototype-feedback-note.md
├── group-feedback-synthesis.md
├── interview/
│   ├── notes.md
│   └── recording.m4a
└── [7 ảnh PNG screenshots]
```

---

## VIII. TRẠNG THÁI BÀI

| Hạng mục | Trạng thái |
|----------|-----------|
| Case | Case B — AI Notes |
| Problem Hypothesis | Chưa validated |
| Conversation Guide | Đã chỉnh sau luyện phỏng vấn |
| Interview Record cá nhân | Đã thực hiện |
| Practice Reflection | Đã hoàn thành |
| AI Support Log | Đã khai báo |
| Prototype 3 Options | Đã hoàn thành |
| User Testing (Chặng 6) | Đã thực hiện |
| Feedback Synthesis | Đã tổng hợp |

---

*© 2024 VLearn Team - Track 1 Day 18 - Human-AI Design*
