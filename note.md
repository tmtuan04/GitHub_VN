# Terms - Danh từ

**Repository** (Repo): Tiếng anh là cái kho, nhưng trong lập trình, nó là thư mục dự án của chúng ta. Hiện tại thư mục dự án của chúng ta là GITHUB_VN
=> Đây là một Repo

**Branch** (Cành): Cành mặc định luôn là master (hình như bây giờ đổi tên thành main), ví dụ trên một dự án có nhiều chức năng khác nhau, mỗi chức năng sẽ được chia ra một branch => Tổng hợp các brach để hoàn thành dự án đó.

**Conflict**: Xung đột

**Local**: tất cả những gì trên máy tính của ta (hình ảnh, file, ...) => local

**Remote**: ngược lại của local, nó k nằm ở máy ta mà nằm ở một server nào đó

# Commands - Lệnh

- *git init*: Dễ hiểu là dự án của chúng ta sẽ sử dụng được git khi ta gõ dòng lệnh này (trên cmd trong VSCODE - Ctrl + J)
=> Git tạo ra một Repo mới cho dự án hiện tại
=> Dự án của chúng ta sẽ trở thành một git


- *git status*: Cho ta thấy được trạng thái của dự án của mình, những thay đổi trong dự án..


- *git add*: CHUẨN BỊ lưu lại thời điểm hiện tại của dự án
=> git add + tên file để CHUẨN BỊ lưu lại file đó
=> CHUẨN BỊ lưu lại tất cả file: *git add .*


- *git reset*: ngược lại của git add .


- *git commit*: muốn chính thức lưu, lệnh này rất đặc biệt => cần ghi chú lại một chi tiết trước khi lưu, chi tiết này thường cho biết quá trình của dự án hoặc ta đang làm một tính năng gì
=> **git commit -m 'initial commit'**: thường là ghi chú đầu tiên => đánh dấu thời điểm đầu tiên (bắt đầu) trong dự án


- *git log*: muốn xem lại thời điểm ta đã lưu
    - Dòng đầu là id
    - +0700 là múi giờ


- *git log --oneline*: xem gọn trên một dòng


- *git checkout *id*: nếu muốn quay trở lại một thời điểm

- *git checkout {branch name}*: quay trở lại về thời điểm hiện tại, ngoài ra cũng mang tác dụng là đổi branch

- *git branch*: kiểm tra cành hiện tại

- *git checkout -b (tên branch)*: tạo một branch mới

- *git merge {tên branch}*: gộm branch kia vào branch hiện tại, khi ta thay đổi branch quay lại master thì file contact bị mất vì nó được tạo ở branch dev => Cần gộp branch lại

- *git branch -d {tên branch}* : xoá branch

- *git push + {link} + {tên branch}*: đẩy lên local repo lên remote repo

- *git remote add + {link}*: đặt tên cho link

- *git push*: khi đã clone về thì k cần link mà push lên luôn

- *git push -u origin + {tên branch}*: đẩy branch từ local lên remote

- *git clone + {repo url}*: 

- *git fetch origin*: lấy branch từ remote về local

- *git checkout -b {tên branch} + origin/{tên branch}*

- *git pull*: kéo về thay đổi vừa pull trên github