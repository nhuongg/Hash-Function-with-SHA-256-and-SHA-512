# Hash-Function-with-SHA-256-and-SHA-512
📌 Giới thiệu
---
Ứng dụng web đơn giản sử dụng Flask kết hợp với Ngrok để triển khai một giao diện cho phép người dùng tải lên tệp tin và chọn thuật toán băm SHA-256 hoặc SHA-512. Ứng dụng sẽ:

Hiển thị kết quả băm gốc.

Tạo một phiên bản đã sửa đổi nhẹ (thêm \n) của file và hiển thị kết quả băm tương ứng.

Cho thấy tính kháng va chạm (collision-resistant) của thuật toán băm: chỉ một thay đổi nhỏ cũng tạo ra mã băm hoàn toàn khác.

🚀 Tính năng nổi bật
---
✅ Giao diện web đẹp mắt, hỗ trợ cả desktop và mobile.
<p align="center">  
   <img src="Băm SHA256, 512/Ảnh chụp màn hình (88).png" alt="Ảnh minh họa" width="850" height="480">  
</p>  

🔐 Hỗ trợ SHA-256 và SHA-512.

🔁 Hiển thị sự thay đổi mã băm khi dữ liệu bị thay đổi nhẹ.

🌐 Sử dụng Ngrok để truy cập web trên bất kỳ thiết bị nào qua Internet.

🛠️ Cách chạy code
1. Cấu hình Ngrok token
Tạo tài khoản tại https://dashboard.ngrok.com, sau đó lấy token và chèn vào dòng sau trong code:
os.environ["NGROK_AUTH_TOKEN"] = "your-ngrok-token"
<p align="center">  
   <img src="Băm SHA256, 512/screenshot_1748694058.png" alt="Ảnh minh họa" width="350" height="180">  
</p>  
<p align="center">  
   <img src="Băm SHA256, 512/screenshot_1748694856.png" alt="Ảnh minh họa" width="550" height="280">  
</p> 

2. Tạo file Notebook

   Mở trang web Colab và tạo file Notebook mới

3. Cài thư viện

   Gõ dòng lệnh tải thư viện:

   !pip install pycryptodome

   !pip install flask pyngrok pycryptodome

   -> Bấm nút chạy để tải thư viện.
   
4. Chạy code

   Dán code vô file Notebook rồi chạy

   Sau khi chạy, bạn sẽ thấy một đường dẫn ngrok hiển thị trong terminal như sau:

📌 Truy cập web tại: NgrokTunnel: "https://xxx-xx-xx-xx-xxx.ngrok-free.app - http://localhost:5000"
Bấm vào link để truy cập

5. Sử dụng chương trình

   Chọn file muốn băm
<p align="center">  
   <img src="Băm SHA256, 512/screenshot_1748693355.png" alt="Ảnh minh họa" width="450" height="280">  
</p>  

   Chọn SHA-256 hoặc SHA-512
<p align="center">  
   <img src="Băm SHA256, 512/screenshot_1748693013.png" alt="Ảnh minh họa" width="450" height="280">  
</p>  

   Kết quả
<p align="center">  
   <img src="Băm SHA256, 512/screenshot_1748693214.png" alt="Ảnh minh họa" width="650" height="480">  
</p>  

📚 Kỹ thuật sử dụng
---
Ngôn ngữ: Python 3

Framework: Flask

Tạo cổng public: Ngrok

Thuật toán băm: hashlib SHA-256, SHA-512

📌 Lưu ý
---
Ứng dụng không lưu trữ bất kỳ tệp tin hoặc dữ liệu người dùng nào.

Chỉ dùng cho mục đích học tập, không dùng trong các hệ thống yêu cầu bảo mật cao.

💡 Đóng góp
---
Rất hoan nghênh mọi đóng góp! Hãy tạo Pull Request hoặc Issue nếu bạn muốn thêm tính năng hoặc phát hiện lỗi.

📄 Người sở hữu
---
Nguyễn Văn Hưởng - Gmail: yuukiasuma12@gmail.com

