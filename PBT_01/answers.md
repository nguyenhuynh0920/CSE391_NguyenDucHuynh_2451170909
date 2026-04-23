#### Câu A1 (Nguồn: 01_introduction_html_universe.md 1.1 Kiến trúc Client-Server, 1.2 HTTP, 1.3 Browser Rendering.)
1. Thứ tự ít nhất 5 bước khi gõ https://shopee.vn:
   - DNS lookup: Trình duyệt tra cứu địa chỉ IP của shopee.vn từ DNS server.
   - TCP connection: Thiết lập kết nối TCP với server.
   - HTTP request: Gửi GET request đến server.
   - Server processing: Server xử lý request, trả về HTML/CSS/JS.
   - Browser rendering: Parse HTML, load CSS/JS, render trang.
2. Trong DevTools của Chrome, tab Network cho thấy thông tin:
   - Mã trạng thái: Cho biết yêu cầu thành công (200) hay thất bại (404, 500).
   - Tổng thời gian: Thời gian để trang web tải hoàn tất.
   - Loại tệp: Phân biệt giữa file HTML, CSS, JavaScript hay hình ảnh.
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/85e69e03-6156-4331-9aba-87c8189b6a06" />

#### Câu A2 (Nguồn: 04_visible_part_html.md)
- Trang web bị đánh giá SEO thấp vì:
  + dùng `<div class="header">` thay vì `<header>` cho phần đầu trang.
  + dùng `<div class="menu">` thay vì `<nav>` cho phần điều hướng.
  + dùng `<div class="main">` thay vì `<main>` cho phần nội dung chính.
  + dùng `<div class ="product">` thay vì `<article>` cho phần sản phẩm.
  + dùng `<div class="footer">` thay vì `<footer>` cho phần chân trang.
  
  => Google không hiểu cấu trúc.

  #### Câu A3
[ Hộp 1 ] (div: là các phần tử khối => bắt đầu trên một dòng mới)
Text A Text B (span chiếm vừa đủ chiều ngang của nội dung, không làm ngắt dòng)
[ Hộp 2 ]
Text C Text D (text D in đậm(strong))
[ Hộp 3 ]

#### Câu A4
   <thead>: tiêu đề cột
      
   <tbody></tbody>: dữ liệu chính

   <tfoot>: tổng kết
      
Lý do không nên dùng table để tạo layout cho trang web:
1. Không phải thẻ semantic => Google không hiểu cấu trúc.
2. Khó responsive(table khó co giãn linh hoạt theo màn hình)
3. Ảnh hưởng đến SEO (Screenreader sẽ hiểu nhầm là bảng dữ liệu)


