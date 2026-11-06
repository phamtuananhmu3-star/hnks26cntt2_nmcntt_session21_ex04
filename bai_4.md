 **BÀI 4 : ĐÁNH GIÁ CÔNG CỤ HỖ TRỢ XỬ LÝ LỖI LẬP TRÌNH**


---

## 1. Bảng so sánh Ưu/Nhược điểm giữa Google Search và AI Assistant (Sự cố: Xung đột cổng - Port Conflict)

| Tiêu chí | Google Search (Tìm kiếm trên StackOverflow / GitHub Issues) | AI Assistant (ChatGPT, Gemini, Claude...) |
| :--- | :--- | :--- |
| **Độ chính xác** | **Cao (Thực tế):** Các giải pháp do lập trình viên thực tế trải qua và kiểm chứng, có thể áp dụng trực tiếp mã lệnh chuẩn xác. | **Khá (Logic ngôn ngữ):** Đưa ra câu trả lời rất nhanh và dễ hiểu, nhưng đôi khi áp dụng vào máy cá nhân vẫn có thể phát sinh lỗi phụ thuộc môi trường. |
| **Tính cập nhật** | **Phụ thuộc thời gian đăng:** Các bài viết cũ từ 5-10 năm trước có thể đã lỗi thời, đòi hỏi phải lọc kỹ các bài viết gần đây. | **Cập nhật tốt:** Có khả năng tổng hợp kiến thức từ nhiều tài liệu kỹ thuật mới, tuy nhiên cần kiểm chứng lại với tài liệu gốc (Official Docs). |
| **Khả năng giải thích** | **Thấp - Trung bình:** Chỉ cung cấp sẵn đoạn code hoặc các bước sửa lỗi thô, người dùng tự đọc hiểu và tự xâu chuỗi vấn đề. | **Rất cao (Interactive):** Giải thích chi tiết nguyên nhân gốc rễ bằng ngôn ngữ tự nhiên, cho phép hỏi lại liên tục nếu chưa hiểu từng dòng lệnh. |
| **Rủi ro (Hallucination)** | **Thấp:** Dữ liệu hiển thị là bài viết nguyên bản từ cộng đồng, không có hiện tượng tự bịa ra thông tin. | **Có rủi ro (Ảo giác AI):** Có thể tự tin sinh ra các câu lệnh, tham số cấu hình hoặc tên tiến trình **không có thật** nếu người dùng hỏi chung chung. |

---

## 2. Lựa chọn: Trường hợp nào bắt buộc phải dùng Google Search để đảm bảo an toàn cho máy tính?

* **Lựa chọn:** Bắt buộc phải ưu tiên sử dụng **Google Search** (kết hợp tra cứu tài liệu chính thức - Official Docs) trong các trường hợp:
  1. **Khi thực hiện các lệnh can thiệp hệ thống sâu / thao tác hủy diệt dữ liệu:** Ví dụ như các lệnh xóa phân vùng ổ cứng, chỉnh sửa Registry hệ điều hành Windows, hoặc thiết lập cấu hình mạng lõi có nguy cơ làm sập hệ thống (mất kết nối mạng toàn bộ).
  2. **Khi đối mặt với các lỗ hổng bảo mật hoặc mã độc (Malware/Ransomware):** Cần tìm kiếm bản vá bảo mật chính thống từ trang chủ của nhà sản xuất phần mềm thay vì tin tưởng hoàn toàn vào các đoạn mã lệnh do AI tự biên soạn để vá lỗi.
