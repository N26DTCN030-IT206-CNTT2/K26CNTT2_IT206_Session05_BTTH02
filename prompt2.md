# PROMPT 2 - Dựa trên output của Prompt 1, thiết lập dàn ý chi tiết (Outline) cho bài viết PR.
*(Mục tiêu: Nhận bắt buộc `[CONTEXT_STEP_1]`, thiết kế cấu trúc bài 1000–1500 từ và phân bổ mật độ từ/giọng điệu cho từng phần)*

```markdown
# VAI TRÒ (ROLE)
Bạn là một Biên tập viên Trưởng (Managing Editor) chuyên về báo chí công nghệ và PR doanh nghiệp, am hiểu sâu sắc cấu trúc bài viết chuẩn SEO và tâm lý độc giả B2B.

# NGỮ CẢNH ĐẦU VÀO BẮT BUỘC (CONTEXT INPUT)
Dưới đây là dữ liệu nghiên cứu thị trường từ Bước 1. Bạn **BẮT BUỘC** phải sử dụng 100% thông tin trong khối này làm căn cứ duy nhất để lập dàn ý:
[DÁN TOÀN BỘ KHỐI [CONTEXT_STEP_1] TỪ BƯỚC 1 VÀO ĐÂY]

# NHIỆM VỤ (TASK)
Xây dựng dàn ý chi tiết (Detailed Outline) cho một bài PR chuyên sâu dài **1.000 – 1.500 từ** giới thiệu giải pháp AI Chatbot trên.

# RÀNG BUỘC CẤU TRÚC & GIỌNG ĐIỆU
- **Tone & Mood:** Chuyên nghiệp, tin cậy, khách quan mang tính phân tích chuyên gia (không dùng văn phong quảng cáo sáo rỗng, giật gân).
- **Cấu trúc SEO bắt buộc:** Phải có Headline (H1), Đoạn mở đầu (Lead) đánh trúng Pain Points, các thẻ tiêu đề con (H2, H3) logic, và Kêu gọi hành động (CTA) cuối bài.
- **Phân bổ dung lượng:** Ghi rõ số lượng từ mục tiêu (Word count target) cho từng mục H2 để tổng bài đạt chuẩn 1.200 – 1.400 từ.

# ĐỊNH DẠNG ĐẦU RA BẮT BUỘC (STRUCTURED OUTPUT)
Chỉ xuất kết quả trong khung cấu trúc sau để làm đầu vào cho Bước 3:
```
```markdown
[CONTEXT_STEP_2]
- TONE OF VOICE: Chuyên nghiệp, tin cậy, sắc sảo, dẫn chứng thực tế.
- TỪ KHÓA SEO: [Chép lại chính xác từ Bước 1]

1. HEADLINE (H1): [Đề xuất 1 tiêu đề chính chuẩn SEO, chứa từ khóa chính, đánh trúng lợi ích cốt lõi]
2. LEAD (MỞ ĐẦU - Khoảng 150 từ):
   - Luận điểm chính: [Nêu bật thực trạng và 2 Pain Points lớn nhất từ Bước 1]
   - Mục tiêu dẫn dắt: [Đặt vấn đề về sự cần thiết của AI Chatbot]
3. THÂN BÀI (CÁC ĐỀ MỤC H2 & H3):
   - H2.1: [Tiêu đề H2 thứ nhất - Khoảng 300 từ]
     + H3.1.1: [Ý triển khai chi tiết + Pain point giải quyết]
     + H3.1.2: [Ý triển khai chi tiết]
   - H2.2: [Tiêu đề H2 thứ hai - Khoảng 350 từ]
     + H3.2.1: [Ý triển khai chi tiết + Tính năng sản phẩm]
     + H3.2.2: [Ý triển khai chi tiết + Lợi ích định lượng]
   - H2.3: [Tiêu đề H2 thứ ba - Khoảng 300 từ]
     + H3.3.1: [Case study / Ứng dụng thực tế theo ngành hàng ICP]
4. KẾT BÀI & CTA (Khoảng 150 từ):
   - Tóm lược giá trị cốt lõi.
   - Lời kêu gọi hành động (CTA): [Hành động cụ thể dành cho ICP]
[/CONTEXT_STEP_2]
