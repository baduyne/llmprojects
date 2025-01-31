# llmprojects

## 1. Cài đặt Ollama

1. Tải xuống và cài đặt Ollama từ https://ollama.com
   
📌 Lưu ý: Trên PC, bạn có thể cần quyền admin để cài đặt thành công.

2. Mở giao diện dòng lệnh:
   
Trên Windows: Nhấn Win + R, gõ cmd, rồi nhấn Enter.
Trên Mac: Mở Terminal (Applications > Utilities > Terminal).

3. Chạy mô hình:
   
Run `ollama run llama3.2` , đối với máy yếu hơn `ollama run llama3.2:1b`
🚫 Tránh sử dụng mô hình mới nhất `llama3.3` của Meta vì nó có 70B tham số, quá lớn với hầu hết máy tính cá nhân!

Nếu không hoạt động, thử chạy máy chủ: Trên Windows (Powershell) hoặc Mac (Terminal): `ollama serve`  
Sau đó thử lại bước 3.

## 2. Setup Environment

Mình sử dụng nền tảng Anaconda để thiết lập môi trường làm việc. Đây là một công cụ mạnh mẽ giúp tạo ra một môi trường data science hoàn chỉnh.

Lợi ích của Anaconda: 
✅ Đảm bảo bạn sử dụng đúng phiên bản Python
✅ Tất cả các gói thư viện đều tương thích, ngay cả khi hệ thống của chúng ta khác nhau
✅ Ổn định và đáng tin cậy sau khi thiết lập xong

Lưu ý: Quá trình cài đặt có thể mất thời gian và Dung lượng ổ cứng yêu cầu khá lớn (5GB+)

Dù mất công ban đầu, nhưng Anaconda giúp bạn tránh được rất nhiều lỗi về môi trường sau này!

### 2.1 Clone Repository
Bước này giúp bạn có một bản sao mã nguồn trên máy tính của mình.

1. Cài đặt Git (nếu chưa có)
   
   Tải Git từ: https://git-scm.com/download/win
   
   Chạy trình cài đặt và làm theo hướng dẫn, sử dụng tùy chọn mặc định (chỉ cần nhấn OK nhiều lần!)
   
2. Mở Command Prompt
   
   Nhấn `Win + R`, gõ `cmd`, sau đó nhấn `Enter`
   
3. Điều hướng đến thư mục dự án
   
   Nếu bạn có một thư mục riêng cho các dự án, hãy điều hướng đến đó bằng lệnh cd:
   `cd C:\Users\YourUsername\Projects`
   
   Thay "YourUsername" bằng tên người dùng Windows thực tế của bạn.
   Nếu chưa có thư mục dự án, hãy tạo một thư mục mới:
   `mkdir C:\Users\YourUsername\Projects`
   
   `cd C:\Users\YourUsername\Projects`
4. Clone Repository
   
   Nhập lệnh sau vào Command Prompt (trong thư mục Projects):
   `git clone https://github.com/tam1511/llmprojects.git`
   
   Lệnh này sẽ tạo một thư mục mới có tên llmprojects bên trong thư mục Projects và tải mã nguồn về.
   
   Đi vào thư mục dự án:
   `cd llmprojects`
   
   thư mục llmprojects sẽ là thư mục gốc của dự án

### 2.2 Install Anaconda environment

1. Tải và cài đặt Anaconda
   
Tải Anaconda từ: https://docs.anaconda.com/anaconda/install/windows/

Chạy trình cài đặt và làm theo hướng dẫn. Lưu ý rằng Anaconda chiếm vài GB dung lượng và quá trình cài đặt có thể mất thời gian.

2. Thiết lập môi trường
   
Mở Anaconda Prompt:

Tìm kiếm Anaconda Prompt trong Start Menu và mở nó.

Điều hướng đến thư mục gốc của dự án:

Nhập lệnh sau, thay YourUsername bằng tên thực của bạn: `cd C:\Users\YourUsername\Projects\llmprojects`

3. Kích hoạt môi trường
   
Sau khi cài đặt hoàn tất, kích hoạt môi trường mới bằng lệnh: `conda activate llms`

   
