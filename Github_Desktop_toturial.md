#Hướng dẫn sử dụng GitHub với GitHub Desktop
## Mục lục
[1.Nguyên tắc hoạt động] (#1)

[2.Đăng ký tài khoản GitHub] (#2)

[3.Download & cài đặt GitHub Desktop] (#3)

[4.Chạy GitHub Desktop] (#4)

[5.Làm việc với GitHub Desktop] (#5)

<a name="1"></a>
### 1.Nguyên tắc hoạt động
Để làm việc với GitHub bạn cần:
- 1.Đăng ký một tài khoản GitHub và tạo một Repository (GitHub Repository).
- 2.Cài đặt GitHub Desktop, một công cụ trực quan quản lý Local Repository (Kho chứa dữ liệu địa phương).
- 3.Cấu hình để có thể đồng bộ hóa dữ liệu bằng GitHub Desktop lên Repository server.
Hãy xem hình minh họa dưới đây:
<img src="http://i.imgur.com/B4aP0FX.png" />

<a name="2"></a>
### 2.Đăng ký tài khoản GitHub
Trước hết bạn cần phải đăng ký miễn phí một tài khoản GitHub. Bạn có thể vào trang chủ của GitHut tại:
- https://github.com

<img src="http://i.imgur.com/lDIRnIj.png" />

<a name="3"></a>
### 3.Download & cài đặt GitHub Desktop
GitHub Desktop về bản chất là một công cụ trực quan cho phép bạn quản lý Local Repository trên máy tính của bạn.
Để download GitHub Desktop bạn vào địa chỉ:
- https://windows.github.com/

<img src="http://i.imgur.com/QOWaO0C.png" />

Sau khi download bạn tiến hành cài đặt như bình thường.

<a name="4"></a>
### 4.Chạy GitHub Desktop
#### a. Vào phần cài đặt chọn Options
<img src="http://i.imgur.com/4RJYn3P.png" />

#### b.Add acount
Bạn có thể dùng tài khoản cá nhân hoặc tài khoản doanh nghiệp tùy theo nhu cầu.
<img src="http://i.imgur.com/uAKTU83.png" />

#### c.Các tùy chọn trong Options
<img src="http://i.imgur.com/6jYTxTA.png" />

- 1.Add acount: thêm hoặc xóa tài khoản cá nhân hoặc tài khoản doanh nghiệp của bạn.
- 2.Cấu hình git:username, gmail.
- 3.Clone path:đường dẫn mặc định để tạo và clone repositories mới.
- 4.Shell mặc định:chọn git shell mà bạn thích.
- 5.Privacy:sử dụng dữ liệu ẩn danh.

<a name="5"></a>
### 5.Làm việc với GitHub Desktop
#### a.Thêm và sao lưu repositories
Thêm những repositories đã có từ máy của bạn lên github desktop hoặc sao lưu chúng sử dụng tài khoản github.
##### I.Thêm repositories từ máy của bạn lên github desktop
- 1.Trên góc trên bên trái bấm vào kí tự +
- 2.Đường dẫn đến file git, nếu bạn nhớ dường dẫn thì đánh vào đây.
- 3.Nếu bạn không nhớ đường dẫn thì chọn browse để mở thư mục chứa file git cần thêm vào.
- 4.Chọn file git để thêm vào (trước đó tôi đã tạo repositories demo)
- Cuối cùng bấm vào `Add repository`

<img src="http://i.imgur.com/vCc7Uwr.png" />

##### II.Sao lưu  repositories
- 1.Trên góc trên bên trái bấm vào kí tự +
- 2.Chọn clone
- 3.Chọn acount của bạn
- 4.Chọn Repository bạn muốn clone
- Cuối cùng click vào Clone REPOSITORY.

<img src="http://i.imgur.com/y6H6paN.png" />

#### b.Thực hiện thay đổi tại 1 nhánh.
##### I.Tạo nhánh cho công việc của bạn.
Nếu bạn có quyền cộng tác với 1 repository nào đó, bạn có thể tạo 1 nhánh của nhánh mặc định để có thể tùy ý thay đổi 
theo ý mình 1 cách an toàn .Sau đó bạn có thể gửi những thay đổi đấy tới người quản trị.
<img src="http://i.imgur.com/5l0wMI7.png" />

##### II.Commit và xem lại những thay đổi tới project.
Trước đó tôi tạo ra các file để tạo ra sự thay đổi.
- Bạn có thể thêm tất cả sự thay đổi của tất cả các file với 1 lần commit
<img src="http://i.imgur.com/j4TsEi6.png" />

- Hoặc có thể thêm tất cử sự thay đổi của 1 hoặc nhiều file với 1 lần commit bằng cách tích vào những file đấy.
<img src="http://i.imgur.com/5QD1iqs.png" />

- Nếu trong 1 file có nhiều sự thay đổi mà bạn không muốn commit hết thì bạn có thể nhấn `Ctrl` + `chuột trái`
vào những dòng thay đổi bạn muốn commit
<img src="http://i.imgur.com/IUJNxu2.png" />

- Sau khi đã hài lòng về những thay đổi bạn có thể commit nó lên và đặt tên cho nó.
<img src="http://i.imgur.com/eG9N9vc.png" />

#### c.Làm việc trên repository từ xa
Khi bạn có những thay đổi ở máy của bạn, bạn có thể update chúng lên repository từ xa, nó là 1 server nơi lưu trữ code của bạn.

##### I.Tạo file mới
- Đầu tiên clone repository ta muốn thêm file.
- Thêm các file mới vào repository, bằng cách thêm file vào đường dẫn thư mục đã clone.

- GitHub ngay lập tức phát hiện ra các thay đổi, nhập thông tin ghi chú (Comment) và nhấn Commit dữ liệu.
<img src="http://i.imgur.com/oSvvuFO.png" />

- Cuối cùng là publish lên cho mọi người xem.
- Bạn mở github server để kiểm tra file đã được publish lên chưa.
<img src="http://i.imgur.com/mGDGTO9.png" />

##### II.Update lại những file đã tồn tại
- Sau khi clone repository về thì mở thư mục chứa đường dẫn repository và chỉnh sửa file.
<img src="http://i.imgur.com/eGpyVvB.png" />

- Nhập thông tin ghi chú (Comment) và nhấn Commit dữ liệu.
<img src="http://i.imgur.com/GlXFrXi.png" />

- Sau đó bạn bấm vào biểu tượng sync để đồng bộ.
- Bạn mở github server để kiểm tra file đã được đồng bộ chưa.
<img src="http://i.imgur.com/H370BoO.png" />
