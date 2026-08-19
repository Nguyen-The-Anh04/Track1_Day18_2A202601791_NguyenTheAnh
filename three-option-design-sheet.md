# THREE OPTION DESIGN SHEET & HUMAN-AI DECISION MATRIX

**Nhóm:** 3H  
**Case:** Case B — AI Notes: Personal Learning Notes

---

## 1. BẢNG SO SÁNH 3 SOLUTION OPTIONS (A / B / C)

| Thành phần | Option A: User-Led (On-Demand AI Tutor) | Option B: Co-Creation (Interactive Concept Connector) | Option C: AI-Led (Proactive Enriched Notes) |
| :--- | :--- | :--- | :--- |
| **Solution Mechanism** | Giải thích theo yêu cầu: Bôi đen khái niệm khó để nhờ AI dịch sang bối cảnh non-tech. | Tương tác 2 chiều: Nối 2 khái niệm, AI đặt câu hỏi gợi mở suy luận để user tự điền ví dụ. | Tự động enrich: AI tự động quét slide khó, chuẩn bị sẵn thẻ ghi chú giải thích + ví dụ ở sidebar. |
| **User làm gì?** | Bôi đen văn bản $\rightarrow$ Bấm nút Giải thích hoặc Ví dụ trên Toolbar. | Khoanh vùng 2 thuật ngữ $\rightarrow$ Trả lời câu hỏi mini-quiz do AI đưa ra. | Mở slide $\rightarrow$ Đọc thẻ AI soạn sẵn $\rightarrow$ Bấm Lưu vào sổ tay hoặc Sửa. |
| **AI làm gì?** | Chờ lệnh $\rightarrow$ Phân tích đoạn được bôi đen và trả kết quả tại Sidebar. | Phân tích mối liên hệ giữa 2 vùng $\rightarrow$ Đặt câu hỏi gợi mở $\rightarrow$ Lưu note khi user chốt. | Tự động quét slide $\rightarrow$ Bóc tách thuật ngữ $\rightarrow$ Tạo sẵn thẻ Enriched Note. |
| **Trigger** | Thụ động (Chỉ chạy khi User bôi đen & click). | Bán tự động (User khoanh vùng $\rightarrow$ AI khởi chạy thử thách). | Tự động hoàn toàn (Kích hoạt ngay khi mở slide học). |
| **Trade-off chính** | Tốn thao tác chủ động của User nhưng kiểm soát 100%. | Tốn tư duy trả lời câu hỏi nhưng ghi nhớ rất sâu. | Tiết kiệm thời gian tối đa nhưng nguy cơ ảo tưởng chính xác nếu đọc lướt. |

---

## 2. BẢNG NGUYÊN TẮC THIẾT KẾ HUMAN-AI (DECISION TABLE)

| Human-AI Decision | Option A: User-Led | Option B: Co-Creation | Option C: AI-Led |
| :--- | :--- | :--- | :--- |
| **1. Phân chia công việc** | User bôi đen & chọn nút. AI xuất định nghĩa + ví dụ đơn giản. | User nối 2 vùng & trả lời. AI gợi mở câu hỏi & tổng hợp note. | AI tự soạn note bên sidebar. User đọc, sửa nhẹ và bấm lưu. |
| **2. Act / Ask / Don't Act** | Don't Act: AI thụ động hoàn toàn, chỉ chạy khi có lệnh. | Ask: AI đưa câu hỏi gợi mở trước (Ask First) rồi mới tổng hợp. | Act: AI tự động chạy và hiển thị ngay khi mở slide. |
| **3. Capability & Limits** | Tooltip khi rê chuột: "Giải thích đoạn bôi đen bằng ngôn ngữ đơn giản". | Banner hướng dẫn: "Khoanh 2 thuật ngữ để AI tạo thử thách kết nối". | Badge nhãn: "AI Enriched Note (Thử nghiệm)" + Disclaimer footer. |
| **4. Uncertainty & Evidence** | Dẫn chiếu số Slide gốc ("Trích từ Slide 7"). Phản hồi nếu câu quá ngắn. | Hiển thị sơ đồ liên kết visual kèm mức độ tin cậy. Dùng câu hỏi giả định. | Phân cấu trúc [Khái niệm] vs [Ví dụ AI bổ sung]. Đánh nhãn "Ví dụ tham khảo". |
| **5. Control & Recovery** | Nút Thử lại, Đơn giản hơn. Đóng panel hoặc tự nhập chat tự do. | Nút Đổi câu hỏi khác, Xem gợi ý. Bấm Sửa để tự gõ lại. | Nút Chỉnh sửa (Edit), Ẩn thẻ (Dismiss). Tự gõ đè ghi chú cá nhân. |
