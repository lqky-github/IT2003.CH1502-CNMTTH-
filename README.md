# IT2003.CH1502-CNMTTH-
Công nghệ mạng và truyền thông hiện đại

# PHẦN 3: DEMO DUAL STACK
 ## (Sử dụng chương trình PacketTracer 7)
 https://www.youtube.com/watch?v=Vcqz16YZ_TU
 
 #### Kịch bản
 https://github.com/lqky-github/IT2003.CH1502-CNMTTH-/blob/main/Kich%20ban%20DualStack.txt
 
Dù giao thức IPv6 có thể giải quyết được vấn đề thiếu hụt địa chỉ IP và mang nhiều ưu điểm nổi bật khi so sánh với IPv4 nhưng trong một thời gian nữa, IPv6 cũng chưa thể thay thế được hoàn toàn IPv4. Trong thời gian quá độ này, nhiều giải pháp đã được đưa ra để hệ thống mạng chạy IPv4 tồn tại song song với hệ thống mạng chạy IPv6.
Để giải quyết vần đề tồn tại nêu trên nhóm đề xuất sử dụng cơ chế Dual – Stack
 	Trong giải pháp này, một thiết bị sẽ chạy đồng thời cả IPv4 và IPv6. Giao thức IPv4 sẽ được sử dụng để giao tiếp với các thực thể IPv4 và giao thức IPv6 sẽ được sử dụng để giao tiếp với các thực thể IPv6; bổ sung, chuyển đổi IPv4 qua IPv6 để các thiết bị trong mạng sử dụng IPv4 và IPv6 có thể giao tiếp nhau. Cụ thể như sau:
 
## Kịch bản như sau:
### Bước 1: Thiết lập mạng chỉ sử dụng IPv4
-	Thiết lập mạng như hình vẽ (Giả lập bước đầu mạng chỉ có PC0 và Sever0 sử dụng IPv4).
-	Cấu hình địa chỉ IPv4 cho các thiết bị.
### Bước 2: Chạy lệnh kiểm tra
-	Chạy chương trình và xác định xem một gói dữ liệu mạng có thể được phân phối đến một địa chỉ mà không có lỗi hay không.
-	Đo độ trễ giữa hai thiết bị trên mạng.
-	Kiểm tra lỗi mạng, kiểm tra 2 thiết bị trong mạng; tình trạng kết nối, thông với nhau.
### Bước 3: Nâng cấp, bổ sung và thiết lập mạng vừa sử dụng IPv4 và IPv6
-	Thiết lập mạng như hình vẽ, trong đó có:
 	PC0, Sever0 sử dụng IPV4
 	PC1, PC2, Server1 sử dụng IPv6
-	Cấu hình địa chỉ IPv6 cho các thiết bị liên quan
### Bước 4: Thực hiện kiểm tra giống Bước 2
### Bước 5: Thực hiện Cơ chế Dual Stack
### Bước 6: Thực hiện kiểm tra giống Bước 2
### Bước 7: Thống kê, báo cáo

# PHẦN 4: DEMO DUAL STACK
 ## (Sử dụng chương trình GNS3)
 
 ### (Phần cuối tài liệu)
 https://github.com/lqky-github/IT2003.CH1502-CNMTTH-/blob/main/6_Cao%20hoc%20-%20Khoa%2015.2(2020)%20-%20Nho%CC%81m%2016%20-%20De%20cuong%20IPV6(09-4-2021).pdf
 

 
 
 
 

 
