# AI SUPPORT LOG

*Nhật ký tương tác và phản ánh việc sử dụng AI của học viên Kim Mạnh Hưng (MHV: 2A202601679) trong suốt quá trình thực hiện bài tập Day 18.*

---

### 1. AI đã giúp tôi ở đâu?
- **Brainstorming ý tưởng:** AI đã cùng thảo luận và phản biện để mở rộng 3 tùy chọn giải pháp (Options A/B/C) từ ý tưởng thô của nhóm, làm nổi bật sự khác biệt về vai trò phân chia công việc giữa Người và AI.
- **Xây dựng UI Prototype:** AI hỗ trợ đắc lực trong việc viết và tối ưu hóa mã nguồn HTML/Tailwind CSS để tạo ra bản Micro-Prototype tương tác tích hợp cả 3 options trên cùng một giao diện, giả lập sát với ứng dụng VLearn thực tế.
- **Gợi ý kịch bản thử nghiệm:** Hỗ trợ chuẩn bị các câu hỏi dẫn dắt khách quan cho facilitator sử dụng trong các phiên User Testing ngoài nhóm.

### 2. AI sai, hời hợt hoặc làm các options giống nhau ở đâu?
- **Trùng lặp cơ chế (Overlap mechanisms):** Ở những lượt prompt đầu tiên, AI đề xuất các option rất hời hợt, chủ yếu chỉ khác nhau ở cách hiển thị giao diện (màu sắc, vị trí nút bấm) chứ chưa phân biệt rõ ràng về mặt bản chất cơ chế tương tác (Role split).
- **Thiếu chiều sâu về Recovery:** AI không tự đề xuất được các kịch bản xử lý lỗi hoặc cách người dùng lấy lại quyền kiểm soát (Control & Recovery) khi AI đưa ra kết quả không như ý muốn (hallucination) mà chỉ đưa ra các nút đóng/mở cơ bản.

### 3. Tôi đã tự sửa hoặc quyết định lại điều gì?
- **Phân tách rạch ròi cơ chế tương tác:** Quyết định quy hoạch lại toàn bộ sơ đồ tương tác: Option A là thụ động hoàn toàn (Don't Act), Option B là đối thoại hai chiều (Ask First), và Option C là chủ động hoàn toàn (Proactive Act).
- **Tự hoàn thiện mã nguồn Prototype:** Chỉnh sửa sâu vào phần Javascript của file HTML để xây dựng tính năng đường nối động SVG (Option B), tạo trình soạn thảo chỉnh sửa trực tiếp (Option C), và đặc biệt là lập trình hệ thống **Sổ tay cá nhân (Notebook Drawer)** lưu trữ thực tế trên LocalStorage để giải quyết triệt để phản hồi từ các tester.
- **Tự biên soạn Feedback thực tế:** Tuyệt đối không để AI tự bịa ra phản hồi của tester; toàn bộ nội dung trong tài liệu kiểm thử đều được chắt lọc từ quan sát thực tế trong 3 phiên test với Khanh, Trung và Đức.
