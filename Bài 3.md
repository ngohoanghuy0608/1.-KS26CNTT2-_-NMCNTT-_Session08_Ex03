# Bài 3
#### Phần1:
## 1. Phân tích bài toán

AI xử lý văn bản bằng cách chia nhỏ nội dung thành các đơn vị gọi là Token. Số Token sử dụng thường ảnh hưởng đến chi phí và thời gian xử lý.

-   Markdown có cú pháp ngắn gọn, dễ đọc, thường ít ký tự định dạng hơn HTML.
    
-   HTML sử dụng nhiều thẻ mở và đóng, khiến dữ liệu có thể dài hơn.
    
-   Văn bản ngắn gọn giúp giảm lượng dữ liệu cần gửi đến AI, nhưng số Token thực tế còn phụ thuộc vào nội dung và bộ mã hóa Token.
## 2. Bảng so sánh Markdown và HTML

| Tiêu chí |Markdown|HTML|
| - | - | -|
|Số ký tự định dạng |Thường ít hơn | Thường nhiều hơn|
|Độ dễ đọc | Dễ đọc, dễ viết |Nhiều thẻ, phức tạp hơn|
|Số Token|Có thể ít hơn|Có thể nhiều hơn|
|Tốc độ xử lý|Có thể nhanh hơn|Phụ thuộc dữ liệu và hệ thống|
|Khả năng tùy chỉnh giao diện|Cơ bản|Linh hoạt hơn|
## 3. Giải pháp cho hệ thống GreenTech

Đề xuất: Sử dụng Markdown làm định dạng dữ liệu mặc định cho chatbot Chuyên gia nông nghiệp AI.

Lý do:

-   Giảm các ký tự định dạng không cần thiết.
    
-   Giúp nhân viên dễ đọc và chỉnh sửa dữ liệu.
    
-   Thuận tiện trình bày tiêu đề, danh sách và bảng hướng dẫn nông nghiệp.
    
-   Có thể giảm chi phí Token nếu nội dung ngắn hơn sau khi mã hóa.
    

HTML chỉ nên sử dụng khi hệ thống cần giao diện phức tạp hoặc các thành phần tùy chỉnh.
