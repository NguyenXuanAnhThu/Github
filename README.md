# Github
[1. Cách thức hoạt động của Github](cachthuc)

[2. Một số khái niệm](khainiem)
   [a. Add](add)
   
   [b. Remove](remove)
   
   [c. Commit](commit)
   
   [d. Push](push)
   
   [e. Pull](pull)
   
   [f. Fetch](fetch)
   
   [g. Clone](clone)
   
   [h. Fork](fork)
   
   [i. Star](star)
   
   [k. Watch](watch)
   
[3. Các bước để Setting up Git](setting)

[4. Các bước để Generate and add SSH key](generate)

[5. Các bước để Caching -your GitHub password in Git](caching)

<a name"cachthuc"></a>
1. Cách thức hoạt động của Github:

   Làm việc với Github nói riêng và Git nói chung có hai workflow chính đó là local workflow và sever workflow.

   Có thể làm mọi thay đổi source code ở local workflow, sau khi thay đổi xong -> commit nhưng những thay đổi đó lên server và bản lên server là bản phải hoàn chỉnh một tính năng nào đó, hoặc fix bug xong, test xong hoặc bản đó phãi chạy được. **Không được commit code dở dang, chưa qua test lên responsitory server sẽ làm ảnh hưởng đến các thành viên khác**, ngược lại bạn có thể làm điều đó ở responsitory local.

<a name"khainiem"></a>
2. Một số khái niệm:

   <a name"add"></a>
   a. Add:
   
      Add file đã thay đổi vào stage. Để thực hiện *ADD* ta sử dụng câu lệnh sau:
      
       Git add README.md để ADD vào file README.md 

   <a name"remove"></a>
   b. Remove:
   
   
