Để cập nhật thay đổi của bạn lên GitHub, bạn sẽ cần làm việc qua một số bước sử dụng Git từ dòng lệnh. Đảm bảo bạn đã cài đặt Git trên máy tính của mình. Dưới đây là các bước cơ bản để thực hiện việc này:

### Bước 1: Mở Terminal hoặc Command Prompt
Khởi động terminal (Linux hoặc macOS) hoặc command prompt/PowerShell (Windows).

### Bước 2: Đi tới Thư mục Dự án
Chuyển đến thư mục chứa dự án của bạn sử dụng lệnh `cd`:
```bash
cd path/to/your/project
```

### Bước 3: Kiểm tra Trạng thái
Trước khi thêm các thay đổi, bạn có thể kiểm tra trạng thái hiện tại của các tệp đã thay đổi:
```bash
git status
```
Lệnh này sẽ cho bạn biết những tệp nào đã được thay đổi, được thêm vào, hoặc chưa được theo dõi.

### Bước 4: Thêm Tệp vào Khu vực Staging
Để thêm tất cả các thay đổi (bao gồm tệp mới, thay đổi tệp hiện tại, xóa tệp):
```bash
git add .
```
Hoặc, bạn có thể chỉ thêm các tệp cụ thể:
```bash
git add file1 file2
```

### Bước 5: Commit Thay đổi
Sau khi thêm các tệp vào khu vực staging, bạn sẽ cần commit chúng:
```bash
git commit -m "Your commit message here"
```
Nội dung commit nên mô tả rõ ràng các thay đổi bạn đã thực hiện.

### Bước 6: Đẩy (Push) Thay đổi lên GitHub
Sau khi đã commit các thay đổi của bạn, bạn cần đẩy chúng lên GitHub:
```bash
git push origin main
```
Thay thế `main` bằng tên nhánh bạn đang làm việc nếu khác. Nếu đây là lần đầu tiên bạn push, Git có thể yêu cầu bạn xác thực danh tính của mình.

### Bước 7: Kiểm tra trên GitHub
Sau khi đã đẩy, bạn có thể vào GitHub để xem các thay đổi của mình đã được cập nhật lên repository trực tuyến.

### Lưu ý
- Nếu bạn đang làm việc cùng người khác, hãy đảm bảo rằng bạn đã kéo (pull) các thay đổi mới nhất từ repository trước khi push các thay đổi của mình:
  ```bash
  git pull origin main
  ```
- Nếu có xung đột, bạn cần giải quyết chúng trước khi hoàn thành push.

Bằng cách thực hiện các bước trên, bạn có thể dễ dàng cập nhật và đồng bộ các thay đổi của mình với repository trên GitHub.