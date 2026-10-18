# [Thực hành] Tạo bố cục cơ bản (Basic Layout)

Bài thực hành thiết kế bố cục (layout) cho một trang web sử dụng thẻ `<div>` và các thuộc tính CSS cơ bản theo giáo trình CodeGym.

## Cấu trúc các phân vùng chính:
- **`#main`**: Phân vùng chứa toàn bộ nội dung của trang, căn giữa màn hình với `margin: 0 auto`.
- **`#head`**: Phân vùng chứa logo và banner đầu trang.
- **`#head-link`**: Phân vùng chứa thanh điều hướng / liên kết đầu trang.
- **`#left`**: Phân vùng chứa cột menu bên trái, thiết lập `float: left;` và `min-height: 400px;`.
- **`#content`**: Phân vùng nội dung chính ở giữa với các khối tin tức và slide.
- **`#right`**: Phân vùng thông tin phụ bên phải, lịch, bản đồ, tiến độ (`float: right;`).
- **`#footer`**: Phân vùng chân trang, sử dụng `clear: both;` để ngắt dòng bên dưới các khối float.

## Công nghệ sử dụng:
- HTML5 (Thẻ phân đoạn `<div>`)
- CSS3 (Box Model, Float, Clear, Flexbox Menu)
