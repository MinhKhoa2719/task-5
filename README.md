- NodeJS là gì?
- Ưu nhược điểm của node so với các ngôn ngữ back end khác (php, django, golang, ...)
- Cài đặt node thế nào ? ( windows/linux ) -> ưu tiên code trên linux ( wsl2 )
- Demo nhẹ với hello-world ( localhost:3000 )

# NodeJS là gì?
Node.js là 
Một mã nguồn mở
Nodejs có thể thể dễ dàng xử lý nhiều kết nối một cách dễ dàng.
Chạy trên môi trường JavaSript, được xây dựng trên V8 JavaScript engine của Chrome - V8 thực thi mã JavaScript bên ngoài trình duyệt. 
Node.js cho phép thực hiện lập trình bất đồng bộ. Mặc dù tỷ lệ phần trăm các trang web được xây dựng bằng Node.js tương đối thấp (0,4%), nhưng nó đang nhanh chóng trở nên phổ biến hơn giữa các developer.
NHƯỢC ĐIỂM: 
Ít hiệu quả trong việc xử lý tác vụ cần nhiều CPU
Ngôn ngữ JavaScript phát triển khá chậm (và thậm chí một số người còn nói là quá kém), ngay cả khi những khái niệm từ các ngôn ngữ khác được cho là làm việc tốt hơn.
Thiếu sự kiểm duyệt chất lượng các module Nodejs(Hệ sinh thái Nodejs vẫn chưa có một cơ chế kiểm duyệt chất lượng tốt.)

Nhưng Node.js vẫn có một cộng đồng lớn và có hàng tấn các ứng dụng tuyệt vời được viết bởi nó
Node.js là một nền tảng ngày càng phổ biến được xây dựng trên một JavaScript-based runtime rất nhanh: V8.
Vì Node.js được viết bằng JavaScript, nên nó thừa hưởng hầu hết các tính chất của JavaScript 
# Ưu nhược điểm của node so với các ngôn ngữ back end khác (php, django, golang, ...)
- So sánh giữa Node.js vs Golang

Việc lựa chọn giữa Node.js hoặc Go phụ thuộc rất nhiều vào loại phát triển phù hợp với bạn nhất và độ lớn của ứng dụng cần phải mở rộng.

Go chưa có được tất cả các community package hoặc cộng đồng mà Node có, nhưng cú pháp của nó rõ ràng hơn với mô hình concurrency, sử dụng tối đa hiệu suất của CPU và bộ nhớ, và khả năng mở rộng quy mô của nó tốt hơn với tải đồng thời (concurrent loads)

Nếu bạn cần chắc chắn một số package Node.js mà vẫn chưa có sẵn trong Go, và sẽ khó hoặc tốn kém để viết lại trong Go, thì Node có thể là sự lựa chọn khôn ngoan hơn.

- So sánh giữa Node.js vs PHP
PHP và Nodejs khác nhau hoàn toàn về tư tưởng và cả kiến trúc thiết kế.
Trong khi Nodejs xử lý các tác vụ theo kiểu bất đồng bộ. Còn PHP thì tuần tự.
PHP có rất nhiều framework, cộng đồng developer lớn sẽ giúp đỡ bạn khi cần thiết.
Chi phí cho nhân sự cũng như môi trường triển khai ứng dụng thì Nodejs có nhỉnh hơn PHP một chút.
- So sánh giữa Node.js vs Django
Cả hai đều là nguồn mở
Node.js và Django đều miễn phí sử dụng

Để làm việc với Node.js, bạn cần hiểu về lập trình không đồng bộ, phương thức gốc và kiến ​​trúc của Node.
Để làm việc với Django, các phương pháp cần phải được hiểu cũng như các tính năng đi kèm. Một sự hiểu biết đầy đủ về kiến ​​trúc MTV (Dạng mẫu mẫu) cũng cần được hiểu.
Trong khi học Node.js và Django đòi hỏi kiến ​​thức về ngôn ngữ cơ bản của họ, Node giới thiệu một số khái niệm phức tạp gây khó khăn cho người mới bắt đầu so với Django.
Cả hai công cụ có khả năng mở rộng và hiệu suất tuyệt vời. Tuy nhiên, trong khi Django dường như có lợi thế về khả năng mở rộng, Node.js có lợi thế về hiệu suất.
Cả Node.js và Django đều có cộng đồng người dùng lớn
Django là một lựa chọn tuyệt vời khi bạn đang cân nhắc sử dụng cơ sở dữ liệu quan hệ, có bảo mật là ưu tiên hàng đầu trong danh sách và cần nhanh chóng xây dựng ứng dụng. Sử dụng Node.js khi có một ngăn xếp không đồng bộ từ máy chủ, cần hiệu năng tuyệt vời, có ý định xây dựng các tính năng từ đầu và muốn một ứng dụng thực hiện quá trình xử lý phía máy khách.


# Cài đặt node thế nào ? ( windows/linux ) -> ưu tiên code trên linux ( wsl2 )




