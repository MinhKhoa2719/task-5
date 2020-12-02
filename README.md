- NodeJS là gì?19851498498
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


- Để download NodeJS bạn cần truy cập vào địa chỉ dưới đây
https://nodejs.org/en/download/

![1](https://user-images.githubusercontent.com/54676091/92732692-fe995500-f3a0-11ea-981e-e0a39c527a0f.png)

Rồi next cho tới bước cuối

![2](https://user-images.githubusercontent.com/54676091/92732778-1b358d00-f3a1-11ea-821b-9a58ab7cdcf4.png)

- Kiểm tra và cấu hình

kiểm tra lại kết quả cài đặt và cấu hình NodeJS.
Mở cửa sổ CMD và thực thi các lệnh sau để kiểm tra phiên bản của NodeJS và NPM

- node -v
 
- npm -v


.

![3](https://user-images.githubusercontent.com/54676091/92733082-72d3f880-f3a1-11ea-8660-e2b858e9ee67.png)

.
Sau khi cài đặt xong chúng ta sẽ thực hành bài học đầu tiên "hello-world ( localhost:3000 )"

# 1/ Trước bạn cần tạo một thư mục có tên MyProject, hoặc một tên nào đó mà bạn muốn


![1](https://user-images.githubusercontent.com/54676091/92733339-c7777380-f3a1-11ea-9bdf-1e08d72374a1.png)


# 2/ Mở cửa sổ CMD và CD tới thư mục mà bạn vừa tạo ra. Sau đó chạy lệnh sau để NPM khởi tạo project cho bạn

- npm init

![4](https://user-images.githubusercontent.com/54676091/92733594-00afe380-f3a2-11ea-981c-c4702256354e.png)

.

nhấn Enter cho tới khi hoàn thành

![7](https://user-images.githubusercontent.com/54676091/92733968-52f10480-f3a2-11ea-92f5-d9c28de65c2a.png)

=> Một tập tin có tên package.json đã được tạo ra trên project của bạn.

![9](https://user-images.githubusercontent.com/54676091/92734071-6bf9b580-f3a2-11ea-9a5a-b20fc745b5fa.png)


Có một vài gói (package) thư viện cần thiết cho project của bạn, và bạn cần phải cài đặt nó với sự hỗ trợ của NPM:


*Express
Express.js (Hoặc đơn giản là Express) là một Web Application Framework cho NodeJS. Cung cấp bộ tính năng mạnh mẽ cho các ứng dụng web và mobile.
*Ejs
EJS là viết tắt của "Embedded JavaScript templating", đây là một thư viện, được sử dụng để phân tích các tập tin ejs, và tạo ra HTML trả về cho client (Trình duyệt).

# 3/ ta dùng lệnh 
- npm install express ejs

.
![10](https://user-images.githubusercontent.com/54676091/92734561-d9a5e180-f3a2-11ea-966c-42508719d2ff.png)
- Sau khi cài đặt xong, bạn có thể nhìn thấy các thay đổi trên project của bạn:

![11](https://user-images.githubusercontent.com/54676091/92734703-fa6e3700-f3a2-11ea-8a8c-9c96352df2a4.png)

.

# 4/ Tạo cấu trúc cho dự án


Bây giờ chúng ta sẽ mở project này bằng một công cụ trực quan hơn, ở đây tôi sử dụng trình soạn thảo Atom
(https://atom.io/ và tải về)

B1 : mở Atom lên
- vào File chọn Add Project Folder
sau đó chọn vào Project đã tạo khi nãy

.
OK, Project đã được mở trên Atom:

![32](https://user-images.githubusercontent.com/54676091/92736843-d27fd300-f3a4-11ea-9f67-7a585aaa44b5.png)


.
- Trên project tạo 2 thư mục con là public & views:
public: Là thư mục để chứa tất cả các tập tin mà người dùng có thể truy cập vào được, chẳng hạn image, video,..
views: Website của bạn sẽ có rất nhiều trang (page), chẳng hạn trang chủ, trang đăng nhập,... Thư mục này là nơi chứa tất cả các trang của bạn.


![24](https://user-images.githubusercontent.com/54676091/92737267-2f7b8900-f3a5-11ea-8cdd-1b3db927862e.png)

.


Trong thư mục views chúng ta tạo 2 tập tin:
homePage.ejs
testPage.ejs

![72](https://user-images.githubusercontent.com/54676091/92737750-9a2cc480-f3a5-11ea-9c05-d84524041741.png)


.
![111](https://user-images.githubusercontent.com/54676091/92737966-bf213780-f3a5-11ea-8726-1c9cf81f6d52.png)


.
Tiếp theo, tạo một file có tên index.js, và nhập vào nội dung cho file này. Đây là file cấu hình cho project của bạn:


![222](https://user-images.githubusercontent.com/54676091/92738048-d4966180-f3a5-11ea-829f-f4a2c7ad3b00.png)




nhập vào file index.js

![333](https://user-images.githubusercontent.com/54676091/92738263-fe4f8880-f3a5-11ea-9be6-774c2f19208b.png)





![444](https://user-images.githubusercontent.com/54676091/92738423-20490b00-f3a6-11ea-98ab-38ee450afc0f.png)

# 4- Chạy Application Server
Mở cửa sổ CMD, và CD vào thư mục project của bạn. Và thực hiện lệnh lệnh dưới đây để triển khai (deploy) ứng dụng của bạn.

- node index.js

![555](https://user-images.githubusercontent.com/54676091/92738582-44a4e780-f3a6-11ea-9b5c-797877958f9c.png)


- Lệnh ở trên sẽ khởi động Web Application Server, và triển khai ứng dụng của bạn lên Web Server này. Lúc này nó đã sẵn sàng phục vụ yêu cầu gửi đến từ client.


![999](https://user-images.githubusercontent.com/54676091/92739634-4b802a00-f3a7-11ea-9d96-c88e521c4d4b.png)


Chú ý: Không đóng cửa sổ CMD, vì Application Serser của bạn đang được chạy. Mở trình duyệt và truy cập vào đường dẫn:
http://localhost:3000/
http://localhost:3000/test

![000](https://user-images.githubusercontent.com/54676091/92739708-5dfa6380-f3a7-11ea-9d6f-1f98803d8553.png)




Điều gì diễn ra tại Server khi người dùng truy cập địa chỉ ở trên?

![09](https://user-images.githubusercontent.com/54676091/92739769-6ce11600-f3a7-11ea-91c8-a27c5cb1a0e1.png)





Kết 
![777](https://user-images.githubusercontent.com/54676091/92741360-ba11b780-f3a8-11ea-890c-3d0426eb2074.png)




























