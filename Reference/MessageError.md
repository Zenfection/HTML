# ![icons8-road_closure.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-20-19-50-icons8-road_closure.png) Message Error <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/22-20-49-37-22-12-04-09-06-00-18-00-html5.gif" title="" alt="html5" width="50">

Khi trình duyệt gửi tín hiệu về `Web server`, đôi khi sẽ xuất hiện lỗi, chẳng hạn như `404 Not Found`.

Và rất nhiều lỗi mà `HTML` báo về, dưới đây là tổng hợp các lỗi mà bạn có thể tham khảo : 

![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png)

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/27-22-18-28-icons8-information.png" title="" alt="icons8-information.png" width="40"> 1xx: Information

| ![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png) Message | Description                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| 100 Continue                                                                                                                        | `server` nhận `request headers` và `client` sẽ tiến hành gửi `request` đó           |
| 101 Switching Protocols                                                                                                             | Yêu cầu `server` chuyển đổi **giao thức** (`protocols`)                             |
| 103 Checkpoint                                                                                                                      | Được sử dụng trong đề xuất có thể tiếp tục yêu cầu `PUT` *hoặc* `POST` đã bị huỷ bỏ |

---

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/27-22-17-39-icons8-system_information.png" title="" alt="icons8-system_information.png" width="40"> 2xx: Successful

| ![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png) Message | Description                                                                                                           |
| ----------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| 200 OK                                                                                                                              | `Request` thành công (*phản hồi thành công `HTTP request`*)                                                           |
| 201 Created                                                                                                                         | `Request` được thực hiện và `resource` mới đã được tạo                                                                |
| 202 Accept                                                                                                                          | `Request` được chấp nhận xử lý (*quá trình xử lý chưa hoàn thành*)                                                    |
| 203 Non-Authoritative Information                                                                                                   | `Request` được xử lý thành công nhưng trả lại thông tin từ một `source` khác                                          |
| 204 No Content                                                                                                                      | `Request` được xử lý thành công nhưng không trả về nội dung nào                                                       |
| 205 Reset Content                                                                                                                   | `Request` được xử lý thành công nhưng không trả về nội dung nào, và `request` được yêu cầu đặt chế độ `document view` |
| 206 Partial Content                                                                                                                 | `server` phân phối một phần `resource` do phạm vi `header` gửi bởi `client`                                           |

---

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/27-22-19-05-icons8-train_track.png" title="" alt="icons8-train_track.png" width="40"> 3xx: Redirection

| ![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png) Message | Description                                                                               |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 300 Multiple Choices                                                                                                                | Một danh sách `link`, người dùng có thể chọn `link` và tới đó (*tối đa `5` link *)        |
| 301 Moved Permanently                                                                                                               | Trang yêu cầu chuyển qua `URL` mới                                                        |
| 302 Found                                                                                                                           | Trang yêu cầu **tạm thời** chuyển qua `URL` **mới**                                       |
| 303 See Other                                                                                                                       | Trang yêu cầu có thể tìm thấy dưới một `URL` **khác**                                     |
| 304 Not Modified                                                                                                                    | Chỉ ra trang yêu cầu chưa sửa đổi kể từ lần `request` cuối cùng                           |
| 306 Switch Proxy                                                                                                                    |                                                                                           |
| 307 Temporary                                                                                                                       | Trang yêu cầu đã tạm thời chuyển sang `URL` **mới**                                       |
| 308 Resume Incomplete                                                                                                               | Được sử dụng trong đề xuất `request proposal` để yêu cầu `PUT` *hoặc* `POST` đã bị huỷ bỏ |

---

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/27-22-19-26-icons8-error_cloud.png" title="" alt="icons8-error_cloud.png" width="40"> 4xx: Client Error

| ![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png) Message | Description                                                                                                       |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| 400 Bad Request                                                                                                                     | Không thể thực hiện do cú pháp sai                                                                                |
| 401 Unauthorized                                                                                                                    | `Request` đúng nhưng `server` từ chối phản hồi<br>Dùng khi có thể xác thực nhưng thất bại hoặc chưa được cung cấp |
| 402 Payment Required                                                                                                                |                                                                                                                   |
| 403 Forbidden                                                                                                                       | `Request` đúng nhưng `server` từ chối phản hồi                                                                    |
| 404 Not Found                                                                                                                       | Trang yêu cầu có thể không tìm thấy *hoặc* có thể không khả dụng nữa                                              |
| 405 Method Not Allowed                                                                                                              | `Request` được tạo bằng một trang sử dụng phương thức `request` không hỗ trợ trên trang                           |
| 406 Not Acceptable                                                                                                                  | `server` có                                                                                                       |
| 407 Proxy Authentication                                                                                                            |                                                                                                                   |
| 408 Request Timeout                                                                                                                 |                                                                                                                   |
| 409 Conflict                                                                                                                        |                                                                                                                   |
| 410 Gone                                                                                                                            |                                                                                                                   |
| 411 Length Required                                                                                                                 |                                                                                                                   |
| 412 Precodition Failed                                                                                                              |                                                                                                                   |
| 413 Request Entity Too Large                                                                                                        |                                                                                                                   |
| 414 Request-URI Too Long                                                                                                            |                                                                                                                   |
| 415 Unsupported Media Type                                                                                                          |                                                                                                                   |
| 416 Requested Range Not Satisfiable                                                                                                 |                                                                                                                   |
| 417 Expectation Failed                                                                                                              |                                                                                                                   |

---

## <img src="https://raw.githubusercontent.com/Zenfection/Image/master/2021/06/27-22-20-16-icons8-smart_home_error.png" title="" alt="icons8-smart_home_error.png" width="40"> 5xx: Server Error

| ![icons8-messaging.png](https://raw.githubusercontent.com/Zenfection/Image/master/2021/07/01-21-00-10-icons8-messaging.png) Message | Description |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| 500 Internal Server Error                                                                                                           |             |
| 501 Not Implemented                                                                                                                 |             |
| 502 Bad Gateway                                                                                                                     |             |
| 503 Service Unavailable                                                                                                             |             |
| 504 Gateway Timeout                                                                                                                 |             |
| 505 HTTP Version Not Supported                                                                                                      |             |
| 511 Network Authentication Required                                                                                                 |             |
