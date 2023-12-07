# Attendance-System-Using-Facial-Recognition
Dự án này sử dụng ngôn ngữ Python, nhận diện khuôn mặt bằng OpenCV và được xây dựng bằng giao diện GUI dựa trên thư viện Tkinter.
## Các bước thực hiện
- Cài đặt thư viện: các thư viện cần thiết cho dự án nằm trong file requirements.txt 
```
pip install -r requirements.txt
```
- Chạy tệp main.py ```python main.py```, sau đó sẽ hiện ra giao diện sau:
<picture>
![image](https://github.com/ledanhan/Attendance-System-Using-Facial-Recognition/assets/111650057/0470eb92-55a4-4935-b6c0-1d77aa9f9362)
</picture>

- Nhập ID, tên, chức vụ tương ứng và nhấn nút "Chụp ảnh". Dự án này sử dụng thuật toán Haar Cascade để phát hiện khuôn mặt. Sau khi nhấn nút sẽ hiện ra một khung camera để thu thập dữ liệu khuôn mặt. Camera sẽ chụp lại 30 tấm hình và lưu vào folder "TrainingImage".
  <picture>
  ![image](https://github.com/ledanhan/Attendance-System-Using-Facial-Recognition/assets/111650057/27f1d1cc-378c-429a-9610-71d74c3b8e42)
  </picture> 

- Sau khi giao diện hiện thông báo "Ảnh đã được chụp cho ID:  " thì nhấp vào nút "Lưu thông tin" để lưu lại thông tin cá nhân phục vụ cho việc chấm công. Trước khi có thể lưu thông tin, hệ thống hiện ra một cửa sổ nhập mật khẩu nhằm tăng độ bảo mật.
  <picture>
  ![image](https://github.com/ledanhan/Attendance-System-Using-Facial-Recognition/assets/111650057/5eab83f7-33d4-4c33-a706-ffd95d60f8bf)
  </picture> 

- Chấm công: sau khi nhấp vào nút "Chấm công", hệ thống sẽ mở ra một khung camera để nhận diện khuôn mặt của người chấm công và thực hiện việc chấm công cho người đó. Nhấn phím "q" để tắt khung camera chấm công.
  
- Sau khi thoát khỏi khung camera, giao diện sẽ hiện lên thông tin của người đã chấm công (bao gồm ID, HỌ TÊN, CHỨC VỤ, NGÀY và THỜI GIAN) và lưu thông tin chấm công của người đó vào file excel trong folder "Attendance" theo từng ngày.
  <picture>
  ![image](https://github.com/ledanhan/Attendance-System-Using-Facial-Recognition/assets/111650057/84c45086-bfe1-4b5e-acc2-c982c6e8f0fc)
  </picture> 

- Nhấp vào nút "Thoát" để tắt giao diện. 
