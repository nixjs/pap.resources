# **1. Tổng quát về cửa cổng thông minh**
Mã sản phẩm: LM-Sx-G

- LM-Sx-G là thiết bị công tắc cửa cổng của Lumi hỗ tợ điều khiển động cơ cửa cổng.
- Thiết kế: mặt kính cường lực chống xước kết hợp viền nhôm nguyên khối.
- Công nghệ: cảm ứng điện dung, giao thức truyền thông không dây Zigbee.
- Phương thức điều khiển: bằng tay, điều khiển từ xa trên ứng dụng Lumi Life thông qua bộ điều khiển trung tâm.
## **2. Thông số kỹ thuật**

<table><tr><th>Điện áp hoạt động</th><th>100 – 240V AC ~ 50/60Hz</th></tr>
<tr><td>Nhiệt độ hoạt động</td><td>0℃ – 50℃</td></tr>
<tr><td>Truyền thông</td><td>Zigbee</td></tr>
<tr><td>Công suất phát Zigbee</td><td>10 dbm</td></tr>
<tr><td>Công suất tiêu thụ không tải</td><td>< 0.5W</td></tr>
<tr><td rowspan="2">Kích thước (D x R x C)</td><td>Hình chữ nhật: 121.5 x 80 x 31.5 mm</td></tr>
<tr><td>Hình vuông: 95 x 95 x 31.5 mm</td></tr>
</table>
## **3. Lắp đặt thiết bị**
Bước 1: Đấu nối dây cho thiết bị.
Sơ đồ đấu nối dây:

Chân L: đấu dây lửa của nguồn điện.
Chân N: đấu dây trung tính của nguồn điện.
Chân C: đấu dây tín hiệu chung (Com) của động cơ cửa cổng.
Chân 1,2: đấu dây điều khiển động cơ.
Bước 2:
Lắp công tắc vào đế âm.
Tháo kính công tắc: sử dụng tuốc nơ vít đặt vào rãnh nhỏ trên viền công tắc và đẩy nhẹ tháo rời mặt kính.Tháo mặt kính công tắc

Lắp công tắc vào đế âm và lắp lại mặt kính:Lắp công tắc vào đế âm tắc

Lưu ý:

- Xếp gọn dây điện trong đế âm để lắp vừa công tắc và tránh bị vít ốc vào dây điện.
- không vít quá chặt sẽ làm công tắc bị cong, vênh mạch cảm ứng của công tắc không tiếp xúc được với mặt kính dẫn đến không bật/tắt được công tắc bằng tay.
## **4. Sử dụng thiết bị**
### **4.1. Điều khiển mở/dừng/đóng cửa cổng**
- Công tắc cửa cổng Lumi có 2 loại: công tắc cửa cổng 1 nút và công tắc cửa cổng 2 nút.
- Công tắc cửa cổng hoạt động ở chế độ nhấn nhả (công tắc bật và trở về trạng thái bật trong khoảng 0.5s).
- Để điều khiển mở/dừng/đóng, người dùng chạm giữ trong khoảng 0.5s vào nút cảm ứng trên công tắc rồi thả tay.

Sử dụng công tắc cổng

Lưu ý:
Điều khiển mở/dừng/đóng cho 1 động cơ cửa cổng thao tác trên cùng 1 nút của công tắc cửa cổng.
### **4.2. Khóa cảm ứng**
Từ 24/2/2020 thiết bị công tắc cửa cổng có chức năng khóa cảm ứng, người dùng sẽ không thể bật/tắt bằng tay được và chỉ có thể điều khiển bằng app Lumi Life.

![Smiley face](Aspose.Words.fb0d615d-4a63-4fcd-8b62-923e9b935a4c.001.png)
Khóa cảm ứng công tắc

Nhấn nhanh nút config 10 lần liên tiếp để khóa và mở khóa cảm ứng.
Khóa cảm ứng – Tất cả led nháy đỏ 5 lần.
Mở khóa cảm ứng – Tất cả led nháy xanh 5 lần.
### **4.3. Thay đổi độ sáng led chỉ thị**
- Led chỉ thị trên công tắc có 2 mức là sáng mạnh hoặc sáng yếu.
- Công tắc trước 24/2/2020, người dùng nhấn giữ nút config 8s và quan sát led chỉ thị thay đổi độ sáng thả tay ra.
- Công tắc từ 24/2/2020 trở đi, người dùng nhấn giữ nút config 5s và quan sát led chỉ thị thay đổi độ sáng thả tay ra.
## **5. Cài đặt điều khiển thiết bị**
### **5.1. Cho thiết bị gia nhập mạng**
- Để cài đặt điều khiển công tắc bằng ứng dụng trên điện thoại người dùng cần có bộ điều khiển trung tâm HC (home controller) và đã tạo nhà trên hệ thống.
- Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.

(Chi tiết xem

[cài đặt thiết bị](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_thiet_bi)

)

- Quan sát đèn chỉ thị trên công tắc nháy hồng 3 lần liên tiếp chu kỳ 1s/1 lần khi gia mạng thành công.
- Trường hợp công tắc không gia nhập mạng có thể công tắc đã được cấu hình, người dùng thực hiện reset thiết bị để quay về chế độ gia nhập mạng.
### **5.2. Điều khiển thiết bị trên ứng dụng Lumi Life**
Sau khi công tắc gia nhập mạng người dùng đặt tên thiết bị và cho vào phòng trong nhà để điều khiển bằng ứng dụng Lumi Life trên điện thoại.Điều khiển công tắc cửa cổng

- Icon sáng thể hiện công tắc đã bật và điều khiển động cơ cửa cổng.
- Icon thiết bị sẽ tự trở về trạng thái tối trong 0.5s.
## **6. Reset thiết bị**
### **6.1. Reset công tắc zigbee 3.0**
Từ 24/02/2020, reset và cho thiết bị ra khỏi mạng người dùng ấn nút config 5 lần liên tiếp.
Nếu thiết bị đang trong mạng thì sau khi reset led chỉ thị của thiết bị sẽ nháy hồng 2 lần liên tiếp báo xóa mạng thành công, sau đó nháy hồng thêm 2 lần liên tiếp lần nữa báo khởi động lại và nháy đỏ 3 lần liên tiếp để trở về chế độ tự động tìm mạng.
### **6.2. Reset công tắc zigbee 1.2**
Reset công tắc zigbee 1.2

Công tắc trước 24/02/2020, reset và cho thiết bị ra khỏi mạng người dùng ấn giữ nút cảm ứng trong 5s, khi led chỉ thị nháy hồng thì thả tay.
Reset thành công, led chỉ thị nháy hồng 3 lần liên tiếp với chu kì 1s/1 lần. Khi đó, thiết bị rời khỏi mạng thành công và nháy đỏ 3 lần liên tiếp quay lại quá trình tự động tìm mạng.
## **7. Bộ sản phẩm đóng gói**
Bộ thiết bị công tắc cửa cổng cửa được đóng hộp bao gồm: 1 bộ công tắc cửa cổng, 2 vít, 1 bộ hướng dẫn sử dụng.Bộ sản phẩm đóng gói
