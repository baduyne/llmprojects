# Part 1. Clone the Repo

## 1. Cài đặt Git (nếu chưa có)

- Truy cập https://git-scm.com/downloads/mac 
- Cài đặt Homebrew.
- Open Terminal (Applications > Utilities > Terminal) dán

-   `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` 
- Cài đặt Git `$ brew install git` 

## 2. Điều hướng đến thư mục dự án

Nếu bạn có một thư mục riêng cho các dự án, hãy điều hướng đến đó bằng lệnh cd: 

cd ~/Documents/Projects

Nếu chưa có thư mục dự án, hãy tạo một thư mục mới:

mkdir ~/Documents/Projects

## 3. Clone Repository

Nhập lệnh sau vào Terminal (trong thư mục Projects):

`git clone https://github.com/tam1511/llmprojects.git`

Lệnh này sẽ tạo một thư mục mới có tên llmprojects bên trong thư mục Projects và tải mã nguồn về.

Đi vào thư mục dự án: cd llmprojects

thư mục llmprojects sẽ là thư mục gốc của dự án

# Part 2. Install Anaconda environment

## 1. Tải và cài đặt Anaconda

Tải Anaconda từ: https://docs.anaconda.com/anaconda/install/mac-os/

Chạy trình cài đặt và làm theo hướng dẫn. Lưu ý rằng Anaconda chiếm vài GB dung lượng và quá trình cài đặt có thể mất thời gian.

## 2. Thiết lập môi trường

Mở Terminal mới (Applications > Utilities > Terminal)

Điều hướng đến "thư mục gốc của dự án" bằng lệnh:

`cd ~/Documents/Projects/llmprojects`

Sau đó, dùng lệnh `ls` để kiểm tra xem bạn có thể thấy các thư mục con hay không

Tiếp theo, tạo môi trường bằng lệnh:

`conda env create -f environment.yml`

Chờ trong vài phút để tất cả các gói được cài đặt – trong một số trường hợp, nếu bạn chưa sử dụng Anaconda trước đây, quá trình này có thể mất 20-30 phút, thậm chí lâu hơn tùy thuộc vào kết nối Internet của bạn.

Bây giờ, bạn đã xây dựng thành công một môi trường AI cách ly và chuyên dụng cho việc phát triển LLMs, chạy vector datastores và nhiều ứng dụng khác. Để kích hoạt môi trường này, hãy dùng lệnh:

`conda activate llms`

## 3. Bắt đầu với Vscode 

Nhập lênh `code .` để bắt đầu













