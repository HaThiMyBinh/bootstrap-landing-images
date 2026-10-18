# Landing Page với Bootstrap và Hình Ảnh

Dự án thực hành sử dụng **Bootstrap Containers**, **Grid System**, **Buttons** và **Images** (`img-fluid`) để tạo Landing Page hiện đại và responsive.

## Cấu trúc trang web
- **Banner / Hero Section**:
  - Tự xây dựng trên **Bootstrap 5** bằng các utility classes (`container`, `py-5`, `text-center`, gradient).
  - Có tiêu đề lớn, nội dung giới thiệu, các nút CTA và hình ảnh lớn nổi bật sử dụng `img-fluid`.
- **Giới thiệu**:
  - Một hàng (`row`) gồm 2 cột: hình ảnh minh họa (`img-fluid rounded-4 shadow`) + đoạn mô tả chi tiết sản phẩm/dịch vụ.
- **Danh sách tính năng**:
  - Một hàng (`row`) gồm 4 cột (`col-12 col-md-6 col-lg-3`), mỗi cột hiển thị icon Bootstrap Icons + tiêu đề + mô tả ngắn bọc trong `card`.
- **CTA Section**:
  - Kêu gọi hành động với các nút kích thước lớn (`btn-lg`, `btn-light`).
- **Footer**:
  - Thông tin bản quyền.

## Thử nghiệm Responsive
Mở tệp `index.html` trong trình duyệt web để xem giao diện co giãn tối ưu trên điện thoại di động, máy tính bảng và màn hình máy tính.
