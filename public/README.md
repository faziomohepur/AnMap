# Taxi Điện Rạch Giá

## Trạng thái tạm thời

Landing page hiện là một file tĩnh duy nhất: `index.html`, không dùng framework hoặc build tool.

## Trình tự cấu trúc trang

1. **Thẻ `head`**
	- Khai báo HTML5, ngôn ngữ tiếng Việt và bảng mã UTF-8.
	- Dùng viewport responsive: `width=device-width`, `initial-scale=1`, `viewport-fit=cover`.
	- Đặt màu giao diện trình duyệt và tiêu đề thương hiệu `Taxi Điện Rạch Giá`.
	- CSS được viết nội tuyến trong thẻ `style`, gồm biến màu, bố cục desktop/mobile, giới hạn chiều rộng ảnh và chống tràn ngang.

2. **Header và điều hướng**
	- Hiển thị thương hiệu Taxi Điện RG.
	- Các liên kết điều hướng đến trang chủ, dịch vụ, bảng giá, đội xe và liên hệ.
	- Số gọi/Zalo hiện dùng: `0852 755 227`.

3. **Hero và đặt xe**
	- Giới thiệu dịch vụ, các lợi ích và form đặt xe.
	- Form chuyển nội dung đặt xe sang Zalo của số `0852 755 227`.

4. **Dịch vụ và đội xe**
	- Hiển thị các loại dịch vụ taxi, xe điện và xe xăng 4–7 chỗ.
	- Khôi phục lại toàn bộ ảnh xe JPEG base64 từ file origin để giao diện không bị trống. Ảnh vẫn nằm trong `index.html` theo đúng bản gốc.

5. **Bảng giá**
	- Taxi điện 4 chỗ: `13.000đ/km`.
	- Taxi điện 7 chỗ: `15.000đ/km`.
	- Mức giá ghi chú áp dụng cho chuyến gần trong nội ô Rạch Giá; giá thực tế tùy lộ trình và thời điểm.

6. **Chính sách**
	- Chính sách bảo mật thông tin khách hàng.
	- Các phương thức thanh toán.
	- Quy định hủy chuyến và phụ phí khi tài xế đã đến hoặc đã di chuyển.

7. **Footer và nút liên hệ nổi**
	- Footer hiển thị khu vực hoạt động, thông tin dịch vụ, thanh toán và số liên hệ mới.
	- Nút gọi và Zalo cố định dưới màn hình, có tính đến vùng an toàn trên thiết bị di động.

## Ghi chú tiếp theo

- Bổ sung ảnh JPG/JPEG đã nén vào `./assets/img` và thay các placeholder bằng đường dẫn cục bộ.
- Kiểm tra trực tiếp trên trình duyệt ở các kích thước mobile phổ biến để tinh chỉnh thêm nếu cần.