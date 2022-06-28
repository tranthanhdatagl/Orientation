# **Chapter 01**
## Cơ chế hoạt động của internet
- Khi ta truy cập một trang web, thiết bị (máy tính, laptop, ipad, điện thoại) của ta sẽ gửi một yêu cầu thông qua đường dẫn (cáp quang, sóng wifi) đến máy chủ -> khi yêu cầu đến máy chủ, máy chủ sẽ truy xuất và trả kết quả chính xác yêu cầu cho thiết bị của ta. 
## Giải thích về protocol của HTTP/HTTPS
- HTTP là giao thức chuẩn internet mà cho phép web client và web server có thể liên lạc và hiểu được nhau.
- HTTPS là giao thức HTTP nhưng tích hợp thêm chứng chỉ bảo mật SSL nhằm mã hóa các thông điệp giao tiếp để tăng tính bảo mật. HTTPS an toàn và bảo mật hơn HTTP.
## Cơ chế hoạt động của browser và sự khác nhau giữa các browser
- Web browser sẽ gửi và nhận dữ liệu đến và từ các phần khác của web. Thông tin nhận được hiển thị trong của sổ trình duyệt của ta. Các web browser có giao diện người dùng, nơi mà ta có thể thao tác (nhấp, cuộn và điều hướng) xung quanh các trang web. Để gửi và nhận dữ liệu, các web browser có phần phụ trợ (máy chủ, cơ sở dữ liệu, ứng dụng) gửi yêu cầu của ta qua internet và mang dữ liệu nhận được trở lại cho ta để ta có thể kết nối và tương tác với các trang web muốn truy cập.

|Trình duyệt    | Ưu điểm          |           Nhược điểm    |
|:---------------:|:-----------------------:| :-----------------------:|
|**Google Chorme**  | Đồng bộ các cài đặt từ thiết bị cũ sang thiết bị mới, tốc độ duyệt web và tải về nhanh, cảnh báo người dùng và ngăn chặn các trang web có nội dung không rõ ràng - độc hại             |Tiêu hao nhiều dung lượng RAM khi mở nhiều tab, đóng tab không có cảnh báo nên sẽ dễ mất các dữ liệu quan trọng, xuất hiện nhiều quảng cáo                   |
|**FireFox**  | Khi đóng tab sẽ xuất hiện thông báo cho người dùng biết để tránh tình trạng mất dữ liệu quan trọng, ngăn chặn các trang web không rõ nguồn gốc          |Đôi khi xuất hiện nhiều quảng cáo gây khó chịu và khi mở nhiều tab cùng lúc khiến dung lượng RAM bị ngốn nghiêm trọng                   |
|**Edge**  | Giao diện thiết kế đẹp, ảnh nền phong cảnh sắc nét đa dạng, tính năng Read Aloud sẽ đọc mọi thứ trên trang web (giúp người có thị lực kém, mỏi mắt hoặc lười đọc có thể nghe)          |Xuất hiện nhiều tin tức trong và ngoài nước có thể khiến người dùng khó chịu, công cụ tìm kiếm mặc định là Bing nếu quen mới Google thì cần phải chuyển đổi trong Cài đặt (điều này sẽ gây sự bất tiện), không cảnh báo khi đóng tab                  |
|**Opera**  | Tốc độ duyệt web và tải về nhanh, cho phép đồng bộ hóa dữ liệu bằng tài khoản Opera, có chế độ tiết kiệm pin cho Laptop (nếu Laptop không mang theo sạc mà đang có việc cần sử dụng trình duyệt thì chế độ này sẽ rất phù hợp), tích hợp công cụ chặn quảng cáo, công cụ quy đổi tiền tệ     | Không có dịch vụ hỗ trợ khách hàng với tính năng Opera VPN            |
|**Safari**  | Tốc độ truy cập trang web và tải về nhanh, có thể đồng bộ và lưu trữ dữ liệu trên các thiết bị Apple của ta, cải thiện tuổi thọ pin của các thiết bị Apple      | Đóng tab không có thông báo nên sẽ dễ mất dữ liệu quan trọng, chỉ tương thích với các thiết bị Apple      |
## Cơ chế hoạt động của DNS - Domain
- Nhập tên miền vào trình duyệt (Chorme, Safari, FireFox,...) -> Trình duyệt sẽ gửi yêu cầu đến máy chủ DNS -> máy chủ DNS sẽ tìm xem địa chỉ IP tương ứng với tên miền đã nhập -> sau khi lấy địa chỉ IP, trình duyệt sẽ yêu cầu đến máy chủ có IP tương ứng -> khi máy chủ có IP tương ứng ấy nhận được yêu cầu truy cập một trang web cụ thể nào đó -> dữ liệu sẽ truyền đi thông qua cáp quang hoặc sóng của tháp viễn thông truyền đến thiết bị của ta.   
## Giải thích về hosting server
- Hosting server là một loại máy chủ lưu trữ chứa các trang web, dữ liệu, ứng dụng và dịch vụ. Hosting server là máy chủ Internet có thể truy cập từ xa với đầy đủ chức năng và tài nguyên của máy chủ Web. Để đảm bảo khả năng truy cập trang web, hosting server luôn được bật và kết nối với Internet. Hosting server hay còn được gọi là Web hosting server.


