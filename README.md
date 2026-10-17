# E-commerce UI Improvement

**Môn học:** Phát triển ứng dụng WEB/TMĐT  
**Giảng viên:** TS Nguyễn Mạnh Tuấn – tuannm@ueh.edu.vn

## 1. Giới thiệu

Dự án xây dựng giao diện thương mại điện tử bằng HTML5 và CSS3, tham khảo website Lazada Việt Nam. Khu vực được cải tiến là tìm kiếm và lọc sản phẩm, nhằm giúp người dùng quan sát các tiêu chí lọc rõ ràng hơn và dễ nhận biết thao tác tiếp theo.

## 2. Website tham khảo

- **Tên website:** Lazada Việt Nam
- **URL:** https://www.lazada.vn/
- **Khu vực đã khảo sát:** Trang tìm kiếm sản phẩm, bộ lọc và danh sách sản phẩm.

## 3. Chức năng

- Hiển thị thanh tìm kiếm sản phẩm.
- Hiển thị các nhóm bộ lọc gồm khoảng giá, thương hiệu, màu sắc và kích cỡ.
- Hiển thị 4 sản phẩm mẫu với hình ảnh, tên và giá.
- Có nút “Áp dụng bộ lọc” và “Xóa lựa chọn” để minh họa thao tác.
- Bố cục đáp ứng nhiều kích thước màn hình, gồm máy tính và điện thoại.

**Giới hạn:** Đây là giao diện tĩnh. Nút “Áp dụng bộ lọc” chưa thực hiện lọc dữ liệu sản phẩm.

## 4. Công nghệ

- HTML5
- CSS3

## 5. Cách chạy

1. Giải nén thư mục dự án.
2. Giữ `index.html` và `style.css` trong cùng thư mục.
3. Mở file `index.html` bằng trình duyệt web.
4. Cần có kết nối Internet để tải hình ảnh mẫu từ Unsplash.

## 6. Cải tiến đã thực hiện

Qua quá trình chạy thử giao diện, nhận thấy khu vực bộ lọc ban đầu chưa có nút xác nhận sau khi người dùng lựa chọn các tiêu chí. Vì vậy, giao diện được bổ sung nút “Áp dụng bộ lọc” và nút “Xóa lựa chọn”.

Phần HTML sử dụng thẻ `button` để tạo các nút thao tác. Phần CSS sử dụng Flexbox để bố trí các nút trên cùng một hàng, đồng thời sử dụng media query để điều chỉnh bố cục trên màn hình điện thoại.

Các nút hiện mới thể hiện giao diện; chức năng lọc sản phẩm thực tế chưa được triển khai.

## 7. Hỗ trợ từ AI

ChatGPT được sử dụng để tham khảo phương án bố cục, giải thích các thành phần HTML/CSS và hỗ trợ xác định cách bổ sung nút lọc. Mã nguồn và giao diện được kiểm tra bằng cách mở trang HTML trên trình duyệt. Các thay đổi được đối chiếu với kết quả hiển thị thực tế trước khi hoàn thiện.

Phần mã nguồn được sử dụng và điều chỉnh theo yêu cầu của bài tập.