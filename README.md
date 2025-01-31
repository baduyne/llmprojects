# llmprojects

## 1. Cài đặt Ollama

1. Tải xuống và cài đặt Ollama từ https://ollama.com.
📌 Lưu ý: Trên PC, bạn có thể cần quyền admin để cài đặt thành công.

2. Mở giao diện dòng lệnh:
Trên Windows: Nhấn Win + R, gõ cmd, rồi nhấn Enter.
Trên Mac: Mở Terminal (Applications > Utilities > Terminal).

4. Chạy mô hình:
Run `ollama run llama3.2` , đối với máy yếu hơn `ollama run llama3.2:1b`
🚫 Tránh sử dụng mô hình mới nhất `llama3.3` của Meta vì nó có 70B tham số, quá lớn với hầu hết máy tính cá nhân!

Nếu không hoạt động, thử chạy máy chủ: Trên Windows (Powershell) hoặc Mac (Terminal): `ollama serve`  
Sau đó thử lại bước 3.
