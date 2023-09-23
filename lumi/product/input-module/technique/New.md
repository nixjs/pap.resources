## **1. Tổng quan của Module Input**
- Mã sản phẩm: LM-INPUT
- Thiết bị LM-INPUT của Lumi giúp các thiết bị cảm biến hãng khác trở thành một thiết bị trong hệ thống nhà thông minh Lumi. Khi đó, các thiết bị cảm biến có thể gửi thông tin trạng thái lên bộ điều khiển trung tâm để theo dõi hoặc thiết lập thành đầu vào các rule tự động một cách dễ dàng.
- Sản phẩm hỗ trợ chuyển đổi tín hiệu từ các cảm biến không tích hợp Zigbee nhưng có đầu ra drycontact hoặc wet contact vào bộ điều khiển trung tâm của Lumi. Các thiết bị, giải pháp tích hợp vào nhà thông minh Lumi thông qua Input Module có thể kể đến như: Khóa vân tay, Cảm biến hàng rào, Cảm biến khói, Cảm biến khí ga, Cảm biến CO, Cảm biến chuyển động… .
## **2. Thông số kỹ thuật**

|Nguồn cấp|9 -24V DC/ 1A|
| :- | :- |
|Nhiệt độ hoạt động|0℃ – 50℃|
|Truyền thông|Zigbee|
|Công suất phát zigbee|10 dbm|
|Số kênh đầu vào|4|
|Kích thước (D x R x C)|80 x 80 x 20 mm|
|Khối lượng|200 gram|
## **2. Lắp đặt thiết bị**
Cấp nguồn cho thiết bị:

Cấp nguồn thiết bị

Người dùng cấp nguồn điện 9 – 24V DC vào chân 12V và GND.

Lưu ý:
Thiết bị LM-Input sử dụng điện 1 chiều nên cần sử dụng nguồn điện hợp lý, tránh cháy nổ.

Chân 12V: đấu dây dương (+) nguồn điện DC.

Chân GND: đấu dây âm (-) nguồn điện DC.

Chân IN1- : đấu với Chân COM của cảm biến.

Chân IN1+ : đấu chân NC hoặc NO của cảm biến.

NO: tiếp điếp thường mở.

NC: tiếp điểm thường đóng.

Các đầu vào IN 2,3,4 đấu tương tự như IN 1.

Chân RS485 không đấu dây, chân này sử dụng với chức năng khác.
## **2. Cài đặt thiết bị**
### **2.1. Cho thiết bị gia nhập mạng**
- Để cài đặt sử dụng thiết bị trên app Lumi Life người dùng cần có bộ điều khiển trung tâm HC (home controller) và đã tạo nhà trên hệ thống.
- Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.
- Quan sát nếu thiết bị gia nhập mạng thành công led Zigbee nháy hồng 3 lần liên tiếp.
- Trường hợp không thấy thiết bị xuất hiện trên app, người dụng thực hiện reset thiết bị để quay về chế độ tìm mạng.

Lưu ý: Khi gia nhập mạng, input module sẽ có 4 enpoint tương ứng với 4 đầu vào độc lập.
### **2.2. Sử dụng thiết bị trên ứng dụng Lumi Life**
Người dùng đăng nhập vào ứng dụng Lumi Life, quan sát icon của thiết bị để biết trạng thái hoạt động của cảm biến đang kết nối với Input Module:

- Icon sáng: cảm biến bật (cảm biến phát hiện chuyển động, phát hiện có khói, khí gas, …).
  Icon tối: cảm biến tắt (cảm biến không phát hiện thấy đối tượng).
- Người dùng dựa theo trạng thái hoạt động của thiết bị để cài đặt chế độ tự động phù hợp trong phần Rule, với thiết bị đầu vào là Input Module.
- Cài đặt Rule tự động với Input module

Lưu ý: Biểu tượng thiết bị trong hình là mặc định, quý khách hàng có thể thay đổi theo tùy ý mục đích sử dụng.
## **3. Reset thiết bị**
- Để reset thiết bị, người dùng sử dụng vật cứng, cách điện nhấn giữ nút reset trong 5s thì thả tay.
- Led Zigbee nháy hồng 3 lần trong 2s. Thiết bị reset thành công, nháy đỏ 3 lần. Khi đó, thiết bị quay lại quá trình tự động tìm mạng.
## **4. Bộ đóng gói sản phẩm**
Hộp đóng gói sản phẩm bao gồm:

- 1 bộ Input Module
- 1 bộ Connector
- 1 bộ hướng dẫn sử dụng.
