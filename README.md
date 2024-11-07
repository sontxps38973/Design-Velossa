# Design-Velossa Tutorial
Chào mừng đến với kho thiết kế của Velossa.
Để chuẩn bị cho dự hãy cài extension của github, và nodejs
- [Tải extension của githun: GIT](https://git-scm.com/downloads/win)
- [Tải và cài nodejs](https://nodejs.org/en/download/prebuilt-installer)


Nếu đã hoàn tất tải và cài đặt hãy bắt đầu dự án
Mở thư mục nơi cần lưu dự án -> chuột phải -> GitBash here
- Clone dự án:
```bash
git clone https://github.com/sontxps38973/Design-Velossa.git


Dự án sẽ xuất hiện trong thư mục
Sử dụng termiral trong VSCODE để thực hiện
Bước đầu tiên khi truy cập một dự án. Hãy kiểm tra nhánh của mình. Chỉ code ở trong nhánh của mình
- Kiểm tra nhánh hiện tại
```bash
git branch

- Truy cập nhánh của bản thân
```bash
git checkout tên-nhánh-của-mình

*Lưu ý chỉ code ở trong nhánh của mình. Không động chạm gì đến nhánh main và developer
bởi nhánh main dùng để backup
Khi xóa nhánh main thì hãy chắc chắn rằng không đứng ở nhánh main
- Xóa nhánh main
```bash
git branch -d main

Sau khi hoàn thành tất cả các bước trên. Bạn đã sẵn sàng để bắt đầu dự án
Lưu ý quan trọng : Mỗi khi mở máy lên. Bước đầu tiên hãy fectching để đến code mới nhất
- Fetch
```bash
git fetch

Nếu có các cập nhật từ nhánh khác. Merge vào nhánh của mình
- Merge
```bash 
git merge tên-nhánh-của-mình/tên nhánh khác

Khi đã hoàn thành chức năng/nhiệm vụ của mình hãy commit để người khác thấy được thay đổi
- ADD
```bash
git add .

- Commit
git commit -m "Nội dung đã thực hiện"



### Đó là toàn bộ những câu lệnh cần dùng khi thực hiện dự án. Mọi thăc mắc hay sai sót gì hãy liên hệ Trịnh Xuân Sơn để được hỗ trợ và tư vấn