# AI Usage Log

## 1. Công cụ AI

- Tên công cụ: ChatGPT
- Mục đích: Hỗ trợ học tập và phát triển giao diện HTML5/CSS3.

## 2. Mục đích sử dụng

- Tham khảo phương án bố cục cho khu vực tìm kiếm và lọc sản phẩm.
- Tìm hiểu cách tổ chức các thành phần HTML.
- Tìm hiểu cách sử dụng CSS để bố trí nút và thiết kế giao diện responsive.
- Hỗ trợ xác định và giải thích lỗi hoặc điểm chưa thuận tiện trong giao diện.

## 3. Prompt đã sử dụng

**Prompt 1 – Đề xuất thiết kế:**

“Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Hãy đề xuất bố cục giao diện tìm kiếm, nhóm bộ lọc, danh sách sản phẩm, thành phần HTML, cách tổ chức CSS, responsive và các điểm cần kiểm tra về khả năng sử dụng. Trước tiên chỉ giải thích phương án thiết kế, chưa tạo toàn bộ mã nguồn.”

**Prompt 2 – Xây dựng giao diện:**

“Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3, có tối thiểu 4 sản phẩm mẫu, hình ảnh, tên, giá, nút thao tác và bố cục phù hợp với máy tính và điện thoại. Tách CSS thành file riêng và không sử dụng backend hoặc cơ sở dữ liệu.”

**Prompt 3 – Hỗ trợ cải tiến:**

“Sau khi chạy thử giao diện, tôi nhận thấy khu vực bộ lọc chưa có nút xác nhận. Hãy hướng dẫn cách thêm nút áp dụng bộ lọc bằng HTML và CSS, đồng thời giải thích vai trò của các thành phần được sửa.”

## 4. Kết quả AI đề xuất

AI đề xuất bố cục gồm thanh tìm kiếm ở phía trên, các nhóm bộ lọc khoảng giá, thương hiệu, màu sắc và kích cỡ, cùng danh sách bốn sản phẩm mẫu. Giao diện sử dụng HTML5 để tổ chức nội dung và CSS3 để thiết kế, bố trí thành phần và điều chỉnh theo kích thước màn hình.

## 5. Kiểm tra và điều chỉnh

Trong quá trình chạy thử, nhận thấy cần bổ sung nút “Áp dụng bộ lọc” để người dùng nhận biết bước tiếp theo sau khi lựa chọn tiêu chí. Giao diện được điều chỉnh bằng cách thêm thành phần HTML `button` và định dạng nút trong CSS.

Kết quả hiển thị được kiểm tra trên trình duyệt. Nút áp dụng hiện mới là thành phần giao diện, chưa thực hiện lọc dữ liệu. Các giới hạn này được ghi rõ để tránh nhầm lẫn giữa giao diện và chức năng thực tế.

## 6. Phần tôi hiểu và có thể giải thích

- `form`: nhóm các trường nhập và lựa chọn trong khu vực bộ lọc.
- `button`: tạo nút thao tác trên giao diện.
- `class`: liên kết phần tử HTML với quy tắc CSS tương ứng.
- `display: flex`: sắp xếp các nút trên cùng một hàng.
- `gap`: tạo khoảng cách giữa các nút.
- `:hover`: thay đổi cách hiển thị khi rê chuột lên nút.
- `@media`: áp dụng quy tắc CSS theo kích thước màn hình.

HTML và CSS chỉ tạo cấu trúc và hình thức giao diện; muốn lọc dữ liệu thực tế khi nhấn nút cần bổ sung JavaScript hoặc backend.