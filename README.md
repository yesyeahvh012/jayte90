# jayte90
Hướng dẫn cách tạo VPS trên Azure với ổ cứng thấp (Smalldisk) nhanh và đơn giản nhằm tiết kiệm chi phí sử dụng VPS.
Bước 1 : Đăng nhập vào tài khoản Azure tại : https://portal.azure.com
Bước 2 : Truy cập vào đường dẫn : https://tinyurl.com/jayte90 để vào trang tạo VPS của Azure
Bước 3 : Điền các thông tin và chọn cấu hình cho VPS :
- Chọn Subscription nếu có nhiều thì chọn Subscription tương ứng cần tạo.
- Resource Group : Bấm Creat new và điền thông tin vào.
- Location : Chọn Vùng đặt máy chủ VPS.
- Admin Username : Điền vào tên người dùng VPS.
- Admin Password : Điền pass người dùng VPS.
- Dns Label Prefix :  Dòng này để nguyên không cần điền gì vào hết nhé.
- Vm Name : Đánh tên VPS mà bạn muốn đặt.
- Window OS Version : Chọn bản Window Server Smalldisk bạn muốn cài đặt.
-Vm Size : Chọn cấu hình cho VPS cần tạo, thông tin cấu hình xem bảng bên dưới :
Instance	     vCPU(s)        RAM     Temporary Disk       Price / Hour
B1S	             1	         1 GiB	     4 GiB	            $0.0104/hour
B1MS	           1	         2 GiB	     4 GiB	            $0.0207/hour
B2S	             2	         4 GiB	     8 GiB	            $0.0416/hour
B2MS	           2	         8 GiB	     16 GiB	            $0.0832/hour
B4MS             4	         16 GiB	     32 GiB	            $0.166/hour
B8MS	           8	         32 GiB	     64 GiB	            $0.333/hour
- Location : Dòng này để nguyên không cần điền gì vào hết nhé.
Sau khi điền và chọn các option xong xuôi thì các bạn bấm tích chọn "I agree to the terms and conditions stated above"
và bấm Purchase để tiến hành tạo VPS.
Bạn nào có yêu cầu thêm cấu hình nào khác ngoài các cấu hình trên thì inbox mình hoặc comment bên dưới,
mình sẽ update khi có time rảnh.
Chi tiết các cấu hình có thể tham khảo ở trang chủ Azure :
https://azure.microsoft.com/en-us/pricing/details/virtual-machines/windows/
