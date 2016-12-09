# Github
[1. Cách thức hoạt động của Github](cachthuc)

[2. Một số khái niệm](khainiem)

   [a. Add](add)
   
   [b. Commit](commit)
   
   [c. Push](push)
   
   [d. Pull](pull)
   
   [e. Fetch](fetch)
   
   [f. Clone](clone)
   
   [g. Fork](fork)
     
[3. Các bước để Setting up Git](setting)

[4. Các bước để Generate and add SSH key](generate)

<a name"cachthuc"></a>
##1. Cách thức hoạt động của Github:

   Làm việc với Github nói riêng và Git nói chung có hai workflow chính đó là local workflow và sever workflow.

   Có thể làm mọi thay đổi source code ở local workflow, sau khi thay đổi xong -> commit nhưng những thay đổi đó lên server và bản lên server là bản phải hoàn chỉnh một tính năng nào đó, hoặc fix bug xong, test xong hoặc bản đó phãi chạy được. **Không được commit code dở dang, chưa qua test lên responsitory server sẽ làm ảnh hưởng đến các thành viên khác**, ngược lại bạn có thể làm điều đó ở responsitory local.

<a name"khainiem"></a>
##2. Một số khái niệm:

   <a name"add"></a>
   a. Add: Add file đã thay đổi vào stage. Để thực hiện *ADD* ta sử dụng câu lệnh sau:
      
       Git add README.md để ADD vào file README.md 

   <a name"commit"></a>
   b. Commit: Ghi lại trạng thái thay đổi tại máy local 
   
       Git Commit
       
   <a name"push"></a>
   c. Push: Đẩy những thay đổi từ máy trạm lên sever.
   
       Git Push
       
   <a name"pull"></a>
   d. Pull: Đồng bộ trạng thái từ sever về máy trạm.
   
       Git Pull
   
   <a name"fetch"></a>
   e. Fetch: Hủy tất cả thay đổi và **commit** cục bộ, lấy về (*fetch*) lịch sử gần đây nhất từ máy chủ và trỏ nhánh master cục bộ vào nó.
   
      Git Fetch
      
   <a name"Clone"></a>
   f. Clone: Sao chép một **responsitory** 
   
      Git Clone
      
   <a name"fork"></a>
   g. Fork: Một người dùng khác copy một bản **responsitory** về kho của họ.

<a name"setting"></a>
##3. Các bước để Setting up Git:

   -Cài đặt tại:  https://desktop.github.com/
   
   -Cài đặt bình thường, yêu cầu phải có .NET 4.5
   
<a name"generate"></a>
##4.  Các bước để Generate and add SSH key:

   a. Generate a new SSH key:
   
   -Mở Git Bash
    
   -Nhập email của bạn: `$ ssh-keygen -t rsa -b 4096 -C"your_email@example.com"`
    
   -Enter a file in which to save the key `(/Users/you/.ssh/id_sra)`: Pres Enter
   
   -Nếu nhập passphrase thì nhớ pass
   
   b. Add  SSH key:
   
   -Truy cập vào đường dẫn: https://github.com/settings/ssh 
   
   -Sau đó đặt tên cho file là **Title** và dán nội dung vừa copy vào ô **Key**
   
   -Lúc này có thể **commit** mà không cần username hay password.
