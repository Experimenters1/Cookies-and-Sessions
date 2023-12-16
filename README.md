# Cookies-and-Sessions
## [Cookies and Sessions](https://web.stanford.edu/~ouster/cgi-bin/cs142-fall10/lecture.php?topic=cookie) <br><br>
## [Session and state management in ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/app-state?view=aspnetcore-8.0) <br><br>

![image](https://github.com/Experimenters1/Cookies-and-Sessions/assets/64000769/b0c835da-b2c5-47bc-8709-962444b25c5d) <br><br>


![image](https://github.com/Experimenters1/Cookies-and-Sessions/assets/64000769/47d57bb5-51c4-44d9-ad39-220c7174d254) <br><br>

![image](https://github.com/Experimenters1/Cookies-and-Sessions/assets/64000769/0c0f3625-d580-4bfe-a949-493c7c75f2ad) <br><br>

![image](https://github.com/Experimenters1/Cookies-and-Sessions/assets/64000769/6e4f7d72-dc13-4d57-8c66-402f169dbc8f) <br><br>



**Session và Cookie** là hai khái niệm quan trọng trong lĩnh vực phát triển web và giữ trạng thái **(state)** của người dùng trên trang web. Dưới đây là sự khác nhau giữa **Session và Cookie** cũng như cách chúng kết hợp với nhau: <br><br>


### 1.Session (Phiên làm việc): <br><br>

+) Khái niệm: Một **session** là một cách để lưu trữ thông tin trạng thái giữa các **request** từ một người dùng trong khoảng thời gian mà họ duy trì kết nối với trang web. Thông thường, mỗi người dùng sẽ có một **session** duy nhất. <br><br>

+) Lưu trữ dữ liệu: Dữ liệu **session** thường được lưu trữ trên server và có thể chứa thông tin như biến phiên, thông tin đăng nhập, và các thông tin trạng thái khác.<br><br>

+) Định danh phiên: Một số phiên bản của **session** được định danh thông qua một **session ID**, mà thường được lưu trữ trong một **cookie**.<br><br>

### 2.Cookie:

+) Khái niệm: **Cookie** là một phần nhỏ dữ liệu được lưu trữ trên máy tính của người dùng, thường được sử dụng để lưu trữ thông tin về người dùng và trạng thái của họ trên trang web.<br><br>

+) Lưu trữ dữ liệu: **Cookie** có thể lưu trữ các thông tin như định danh phiên, ngôn ngữ ưa thích, thông tin giỏ hàng, và các thiết lập cá nhân khác. <br><br>

+) Định danh phiên: Một **cookie** có thể được sử dụng để lưu trữ một **session ID**, giúp xác định một phiên làm việc cụ thể.<br><br>

### 3.Kết hợp Session và Cookie:

 +) Thông thường, **session và cookie** thường được kết hợp để duy trì trạng thái của người dùng qua các request và giữa các phiên làm việc.<br><br>

 +) Một **session ID** thường được lưu trữ trong một **cookie** để xác định phiên làm việc cụ thể của người dùng. Khi người dùng gửi một **request mới, session ID** này được gửi đến **server** để xác định **session** tương ứng và khôi phục thông tin trạng thái. <br><br>

 +) **Cookie** cũng có thể được sử dụng để lưu trữ các thông tin khác không liên quan đến **session**, như thiết lập ngôn ngữ, tùy chọn cá nhân, v.v. <br><br>

Tóm lại, **session** thường được sử dụng để lưu trữ thông tin trạng thái trên **server**, trong khi **cookie** thường được sử dụng để lưu trữ thông tin trên máy tính của người dùng. Kết hợp cả hai giúp duy trì trạng thái của người dùng một cách linh hoạt và an toàn.<br><br> 

