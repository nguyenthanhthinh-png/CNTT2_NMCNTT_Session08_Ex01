1\. Hai sai lầm trong tư duy của Nam

Sai lầm 1: Cho rằng Word phù hợp hơn để lưu trữ tài liệu dự án trên GitHub.

\- File Word (.docx) là định dạng Rich Text, chứa cả nội dung và thông tin định dạng như font chữ, màu sắc, bố cục.

\- Git khó so sánh trực tiếp các thay đổi bên trong file .docx vì đây là định dạng tài liệu nhị phân được đóng gói, không phải văn bản thuần túy.

\- Markdown (.md) là văn bản thuần, giúp Git Diff hiển thị rõ dòng nào được thêm, sửa hoặc xóa. GitHub cũng có thể hiển thị nội dung Markdown trực tiếp trên trình duyệt.

Sai lầm 2: Cho rằng Markdown không thể tạo tài liệu chuyên nghiệp.

Markdown hỗ trợ tiêu đề, danh sách, chữ in đậm, liên kết, hình ảnh, bảng và khối mã. Khi hiển thị trên GitHub hoặc công cụ hỗ trợ Markdown, tài liệu vẫn có bố cục rõ ràng, dễ đọc và chuyên nghiệp.

2\. Tại sao Markdown an toàn và nhẹ hơn?

Tiêu chí	Word (.docx)	Markdown (.md)

Bản chất	Tệp tài liệu đóng gói, chứa cấu trúc và định dạng	Văn bản thuần

Dung lượng	Thường lớn hơn do có cấu trúc định dạng và tài nguyên nhúng	Thường nhỏ, dễ lưu trữ

Git Diff	Khó xem trực tiếp thay đổi nội dung	Dễ theo dõi thay đổi theo từng dòng

Khả năng đọc	Thường cần ứng dụng tương thích	Có thể đọc bằng trình soạn thảo văn bản

Khả năng phục hồi	Có thể khó khôi phục nếu cấu trúc tệp bị hỏng	Thường dễ cứu phần văn bản còn nguyên vẹn



