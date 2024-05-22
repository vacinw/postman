# Sử dụng Postman để Kiểm Thử API trên [JSONPlaceholder](https://jsonplaceholder.typicode.com/)

## 1. Giới thiệu về Postman

Postman là một công cụ mạnh mẽ giúp phát triển và kiểm thử API một cách dễ dàng và hiệu quả. Với giao diện người dùng đồ họa trực quan, Postman cho phép bạn tạo, gửi và kiểm tra các yêu cầu HTTP và HTTPS một cách thuận tiện.

### Các tính năng chính của Postman:

- **Gửi yêu cầu HTTP:** Hỗ trợ các phương thức GET, POST, PUT, DELETE để tương tác với API.
- **Quản lý yêu cầu:** Tổ chức và quản lý các yêu cầu trong các bộ sưu tập (Collections).
- **Sử dụng biến:** Sử dụng biến để tái sử dụng giá trị trong nhiều yêu cầu khác nhau, giúp tiết kiệm thời gian và giảm thiểu lỗi.
- **Tạo và chạy kịch bản kiểm thử tự động:** Viết và thực thi các kịch bản kiểm thử để kiểm tra tính năng và hiệu suất của API.
- **Phân tích phản hồi:** Kiểm tra và phân tích các phản hồi từ API để đảm bảo tính chính xác và hiệu quả.

## 2. Sử dụng Collections và Variables

### Collections:

- **Tạo Collection:** Bạn có thể tạo một Collection với tên gọi "Rest API basics: CRUD, test and variables".
- **Yêu cầu cụ thể:** Tạo các yêu cầu với các phương thức cụ thể như GET, POST, PUT, DELETE để kiểm thử các chức năng cơ bản của API.

### Variables:

- **Tạo biến `base_url`:** Định nghĩa biến `base_url` với địa chỉ của API (ví dụ: `https://jsonplaceholder.typicode.com/`) và sử dụng biến này trong các yêu cầu để dễ dàng quản lý và thay đổi khi cần thiết.

## 3. Kiểm thử API cơ bản

### Các yêu cầu HTTP:

#### GET, POST, PUT, DELETE:

- **GET:** Lấy dữ liệu từ server.
- **POST:** Gửi dữ liệu mới lên server.
- **PUT:** Cập nhật dữ liệu đã có trên server.
- **DELETE:** Xóa dữ liệu trên server.

### Dữ liệu trả về:

#### GET:

- **Status:** 200 OK (Lấy dữ liệu thành công)
- **Time:** 174ms (Thời gian phản hồi)
- **Size:** 1.33 KB (Dung lượng dữ liệu)

#### POST:

- **Status:** 201 Created (Gửi dữ liệu thành công)
- **Time:** 1726ms (Thời gian phản hồi)
- **Size:** 1.36 KB (Dung lượng dữ liệu)

#### PUT:

- **Status:** 200 OK (Cập nhật dữ liệu thành công)
- **Time:** 279ms (Thời gian phản hồi)
- **Size:** 1.25 KB (Dung lượng dữ liệu)

#### DELETE:

- **Status:** 200 OK (Xóa dữ liệu thành công)
- **Time:** 264ms (Thời gian phản hồi)
- **Size:** 1.06 KB (Dung lượng dữ liệu)

## 4. Run Test

Postman cho phép bạn chạy các kịch bản kiểm thử tự động và hiển thị kết quả chi tiết:

- **Test Pass/Fail:** Hiển thị số lượng test đã pass và số lượng test failed.
- **Thời gian chạy:** Tổng thời gian chạy các test case.

Việc sử dụng Postman không chỉ giúp kiểm thử API một cách hiệu quả mà còn nâng cao năng suất và độ chính xác trong quá trình phát triển phần mềm. Các tính năng đa dạng và linh hoạt của Postman là công cụ không thể thiếu cho các lập trình viên và tester trong quá trình làm việc với API.
