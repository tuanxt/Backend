# Backend
1. Cài đặt Git:
Trước tiên, bạn cần cài đặt Git. Tùy vào hệ điều hành của bạn, bạn có thể cài đặt Git theo hướng dẫn sau:

Windows: Tải về và cài đặt Git từ https://git-scm.com/download/win
macOS: Tải về và cài đặt Git từ https://git-scm.com/download/mac hoặc sử dụng Homebrew brew install git
Linux: Cài đặt Git thông qua trình quản lý gói của hệ điều hành, ví dụ: sudo apt-get install git (Ubuntu/Debian) hoặc sudo yum install git (Fedora/CentOS)

2. Thiết lập Git:
Sau khi cài đặt Git, thiết lập tên người dùng và địa chỉ email của bạn:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

3. Tạo một kho lưu trữ (repository) mới:
git init

Lệnh này sẽ tạo một thư mục .git mới trong thư mục hiện tại, trong đó chứa tất cả thông tin về kho lưu trữ của bạn.
4. Sao chép (clone) một kho lưu trữ:
git clone <repository_url>

Thay thế <repository_url> bằng địa chỉ URL của kho lưu trữ mà bạn muốn sao chép.
5. Thêm tệp vào kho lưu trữ:
git add <file>

Thay <file> bằng tên tệp bạn muốn thêm vào kho lưu trữ. Sử dụng git add . để thêm tất cả các tệp trong thư mục hiện tại vào kho lưu trữ.



