Yêu cầu:
- Sản phẩm phục vụ cho các của hàng tạp hóa nhỏ lẻ có thể quản lý sản phẩm, giá cả đầu ra , đầu vào
- Quản lý chi tiêu của cửa hàng
- Sản phẩm có thể chạy được trên 2 môi trường web và android có thể đồng bộ cho nhau nhưng không kêt nối quả internet mà chỉ sử dụng mạng local.
Mô hình:
- Có 2 sản phẩm đuợc làm theo thứ tự:
    + Web: được làm trên Spring Boot Framework xây dựng hệ thống RestAPI phía server và Angular Framework phía client sử dụng hệ quản trị cơ sở dữ liệu MySql để lưu trữ dữ liệu.
    + Android App: được xây trên Android Native.
- Cả server web và client đều nằm trên 1 máy tính là máy người dùng sử dụng. Bản android sẽ là bản di động  và được đồng bộ với bản web qua kết nối chung wifi hoặc qua cable.
