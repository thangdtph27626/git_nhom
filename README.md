<p align="center">
 <img width="100px" src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">Sử dụng git làm việc nhóm</h2>
</p>

<div align="center">
 <table >
  <theader>
  <th>
   Nội Dung 
   </th>
   </theader>
  <tbody>
  <td>
   <p>1: github là gì?</p>
   <p>2: tại sao lại sử dụng git làm việc?</p>
   <p>3: cách sử dụng github làm việc nhóm?</p>
   </td>
   </tbody>
   </table>
</div>

# 1: github là gì?

github là một dịch vụ lưu trữ trên web dành cho các dự án có sử dụng hệ thống kiểm soát Git revision

>  thông tin về GIT:

- Là công cụ giúp quản lý source code tổ chức theo dạng dữ liệu phân tán.\
- Giúp đồng bộ source code của team lên 1 server.
- Hỗ trợ các thao tác kiểm tra source code trong quá trình làm việc 

# 2: tại sao lại sử dụng git làm việc?

- Khi làm việc nhóm thì trong team sẽ code chung 1 dự án, và sau mỗi 1 thời gian nhất định thì cần phải thống nhất code  vào 1 project để cho ra 1 sản phẩm cuối cùng.

<div>
  <table>
    <thead>
     <th>Không sử dụng kênh lưu trữ code</th>
       <th>sử dụng các kênh lưu trữ code</th>
    </thead>
      <tbody>
        <tr>
          <td>Không thống nhất về cách triển khai code</td>
          <td>thống nhất về 1 base code chung</td>
        </tr>
        <tr>
          <td>dễ confix khi gộp chung một project</td>
          <td>dễ dàng kéo code về một branch hoặc một máy nhất định</td>
        </tr>
        <tr>
          <td>khó khăn trong việc gộp code</td>
          <td>giảm thiểu các trường hợp config</td>
        </tr>
        <tr>
          <td>...</td>
          <td>...</td>
        </tr>
      </tbody>
    </table>
</div>


# 3: cách sử dụng github làm việc nhóm? 

> link đăng kí git hub [tại đây](https://github.com/)


### bước 1: tải git về máy tính

bạn có thể tải [tại đây](https://git-scm.com/downloads)

sau khi tải xong bạn cài đặt git trên máy

> sau khi cài đặt máy bạn sẽ có git bash và git UI trên máy tính 

![image](https://user-images.githubusercontent.com/109157942/194497481-c3195ff7-7adb-4d95-92c3-1f030bc54cbf.png)

bước 1: tạo một repository lưu trữ code của cả nhóm hoặc cá nhân 

![image](https://user-images.githubusercontent.com/109157942/194495534-eb1f1daf-0f3a-4bb4-a61f-67084acd2acb.png)

hoặc

![image](https://user-images.githubusercontent.com/109157942/194495696-451b8e2f-2e90-4a19-b8eb-d6376417b8a2.png)

![image](https://user-images.githubusercontent.com/109157942/194496262-15d22b80-f227-4c63-85c2-3731a37c26e1.png)

sau khi tạo xong bạn bấm nút create repository

### bước 2: tạo một một dự án 

> lưu ý: bạn phải cấu hình email, password trên máy tính hoặc cài đặt ssh trên máy tính của mình [tại đây](https://thangdtph27626.github.io/Git_And_GitHub.github.io/)

![image](https://user-images.githubusercontent.com/109157942/194497736-f95d28e8-b6a2-4ca6-a54c-c338dca9c962.png)

### bước 3: đẩy dự án lên git hub

- bạn tìm vào nơi lưu trữ dự án trên máy click chuột phải chọn git bash 

- thực hiện các câu lệnh sau khi thực hiện bước 1 trên git bash 

vd:

![image](https://user-images.githubusercontent.com/109157942/194498202-ba5821e9-4f6a-4dde-af94-c7c2a459beeb.png)

> lưu ý:
 - git add 
    bạn có thể add toàn bộ dự án bằng câu lệnh( git add .) hoặc từng file một bằng ( git add  tenfile )

### bước 4: add các thành viên vào dự án 

cài đặt >  Collaborators > add people 

bạn thự hiện tìm kiếm và add các thành viên trong nhóm

### bước 5 : thực hiện clone dự án về máy 

git clone link-du-an

1: lấy link dự án 

![image](https://user-images.githubusercontent.com/109157942/194499665-a74ff7d1-9bf4-4efa-be78-28ac1199feff.png)

2: bạn có thể chọn tải file zip hoặc thự hiện git clone như sau 

![image](https://user-images.githubusercontent.com/109157942/194499880-05974934-8def-43d5-b39d-a7cffd83da7f.png)

Và đây là thư mục được kéo từ trên git về máy của bạn và code trên project này nhé.

![image](https://user-images.githubusercontent.com/109157942/194499954-61ce5061-4a32-44eb-95d2-fe7fb0b590f4.png)

### bước 6: mỗi thành viên tạo một branch cho riêng mình 

![image](https://user-images.githubusercontent.com/109157942/194500173-3bee5b85-38f4-4f7b-a980-da5838fa32cd.png)

chọn main > view branch > new Branch 

hoặc bạn có thể thự hiện bằng câu lệnh sau 

git checkout -b "tên branch"

![image](https://user-images.githubusercontent.com/109157942/194500577-0c44cde2-7b4c-493d-8543-eaf5a1ad5bf0.png)


### bước 7: sau khi code xong mỗi thành viên sẽ đẩy code lên nhánh của mình 

bạn có thể tải sourcetree để quản lí dự án [tại đây](https://www.sourcetreeapp.com/)

> lưu ý nếu dự án của bạn dùng ssh thì bạn sẽ thực hiện cài đặt sau: tools -> options -> openSSH -> chọn lưu lưu id_rsa trên máy -> ok
![image](https://user-images.githubusercontent.com/109157942/194501209-df911f85-d884-4752-b784-4517dd92e140.png)

click những file cần đẩy lên dự án unstaged files hoặc loại bỏ file cần đẩy lên  staged files

commit những thay đổi của bạn và bấm commit > push dự án lên nhánh 

![image](https://user-images.githubusercontent.com/109157942/195606112-6cbe6125-6f1d-4af8-8bfb-1b5aed059b19.png)


sau khi push lên nhánh bạn lên github để tạo một pull resquest

pull resquest > new pull resquest > chọn nhánh > create pull resquest

![image](https://user-images.githubusercontent.com/109157942/194502421-3ee6181d-df8e-4e84-877e-f34d0f834ce9.png)

tại đây viết những chức năng hay nhứng thay đổi  và chọn create pull resquest 

leader của dụ án sẽ merger vào nhánh


![image](https://user-images.githubusercontent.com/109157942/194503055-56ff13cd-09b1-4c78-998b-5433bcd2d985.png)
![image](https://user-images.githubusercontent.com/109157942/194503092-f25c92bd-1ac1-4319-a0a4-fa0577372232.png)

Sau đó bạn có thể comment hay đặt tên commit như mình mong muốn. Rồi nhấn Confirm merge.

![image](https://user-images.githubusercontent.com/109157942/194503200-914280f7-6770-40f2-addf-6ccd5b7704ec.png)

> lưu ý 

mỗi một ngày bạn nên pull code ở nhánh chính và thự hiện fetch trước mỗi lần pull 
bạn phải commit mỗi lần push code lên 

![image](https://user-images.githubusercontent.com/109157942/194504044-98ac22df-5f49-4f1e-a034-0f05f3fc6426.png)

> lưu ý bạn có thể đẩy code lên nhánh của cá nhân lên bằng các câu lệnh sau 

git add . (đẩy tất cả các file lên) hoặc git add tenFile

git commit -M "commit"

git push


> Luồng cơ bản để thực hiện git nhóm mà mình đã đúc kết ra được. Các bạn có thể tham khảo qua nhé


![image](https://user-images.githubusercontent.com/109157942/194503640-41ee1b27-dcbb-44d0-bcf3-026917e2f676.png)







