# Hash-Function-with-SHA-256-and-SHA-512
📌 Giới thiệu

Ứng dụng web đơn giản sử dụng Flask kết hợp với Ngrok để triển khai một giao diện cho phép người dùng tải lên tệp tin và chọn thuật toán băm SHA-256 hoặc SHA-512. Ứng dụng sẽ:

Hiển thị kết quả băm gốc.

Tạo một phiên bản đã sửa đổi nhẹ (thêm \n) của file và hiển thị kết quả băm tương ứng.

Cho thấy tính kháng va chạm (collision-resistant) của thuật toán băm: chỉ một thay đổi nhỏ cũng tạo ra mã băm hoàn toàn khác.

🚀 Tính năng nổi bật

✅ Giao diện web đẹp mắt, hỗ trợ cả desktop và mobile.

🔐 Hỗ trợ SHA-256 và SHA-512.

🔁 Hiển thị sự thay đổi mã băm khi dữ liệu bị thay đổi nhẹ.

🌐 Sử dụng Ngrok để truy cập web trên bất kỳ thiết bị nào qua Internet.

🛠️ Cách chạy ứng dụng
1. Cài đặt các thư viện cần thiết
bash
Sao chép
Chỉnh sửa
pip install flask pyngrok
2. Cấu hình Ngrok token
Tạo tài khoản tại https://dashboard.ngrok.com, sau đó lấy token và chèn vào dòng sau trong code:

os.environ["NGROK_AUTH_TOKEN"] = "your-ngrok-token"

3. Chạy ứng dụng

python app.py
Sau khi chạy, bạn sẽ thấy một đường dẫn ngrok hiển thị trong terminal như sau:

📌 Truy cập web tại: https://xxxxx.ngrok.io
🖼️ Giao diện người dùng
📤 Chọn file và thuật toán băm
<img src="./path/to/your/screenshot.png" alt="UI Screenshot" width="600"/>
🔄 Kết quả băm
Hiển thị kết quả băm của file gốc và phiên bản đã được thay đổi nhỏ.

📚 Kỹ thuật sử dụng
Ngôn ngữ: Python 3

Framework: Flask

Tạo cổng public: Ngrok

Thuật toán băm: hashlib SHA-256, SHA-512

📎 Ví dụ đầu ra

Kết quả băm gốc (SHA-256):
a8f5f167f44f4964e6c998dee827110c...

Kết quả băm đã sửa đổi (SHA-256 - thêm một ký tự):
e9d71f5ee7c92d6dc9e92ffdad17b8bd...
📌 Lưu ý
Ứng dụng không lưu trữ bất kỳ tệp tin hoặc dữ liệu người dùng nào.

Chỉ dùng cho mục đích học tập, không dùng trong các hệ thống yêu cầu bảo mật cao.

💡 Đóng góp
Rất hoan nghênh mọi đóng góp! Hãy tạo Pull Request hoặc Issue nếu bạn muốn thêm tính năng hoặc phát hiện lỗi.

📄 Giấy phép
Dự án được phát hành theo giấy phép MIT. Tự do sử dụng, chia sẻ và phát triển.

