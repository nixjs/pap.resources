## **1. Tổng quát**
- Mã sản phẩm: LM-DSZ/2.1
- Thiết bị cảm biến cửa là thiết bị của Lumi dùng để phát hiện đóng/mở cửa, làm điều kiện kích hoạt các thiết bị khác trong hệ thống, thông qua bộ điều khiển trung tâm, đồng thời cảnh báo trên ứng dụng Lumi Life.
## **2. Thông số kỹ thuật**

<table><tr><th><b>Nguồn cấp</b></th><th>Pin CR2477: 3.3V 1A</th></tr>
<tr><td><b>Nhiệt độ hoạt động</b></td><td>0℃ – 50℃</td></tr>
<tr><td><b>Truyền thông</b></td><td>Zigbee</td></tr>
<tr><td><b>Công suất phát Zigbee</b></td><td>10 dbm</td></tr>
<tr><td rowspan="2"><b>Kích thước</b></td><td>Phần cảm biến: 36 x 36 x 15 mm (D x R xC)</td></tr>
<tr><td>Nam châm: 36 x 10 x 15 mm (D x R xC)</td></tr>
<tr><td><b>Dải đo ánh sáng</b></td><td>0 – 10000 lux</td></tr>
<tr><td><b>Khối lượng</b></td><td>29 gram</td></tr>
</table>
## **3. Lắp đặt thiết bị**
Bước 1: Cấp nguồn thiết bị

- Dùng tuốc nơ vít mở mặt sau của thiết bị.
- Lắp pin được cấp kèm theo hộp đựng sản phẩm.
- Sau khi được cấp nguồn, đèn chỉ thị sẽ nháy đỏ 3 lần trong thời gian 3s.

Bước 2: Lắp đặt thiết bị.
**Lưu ý:** Trước khi lắp đặt hoàn thiện sản phẩm người dùng cần phải cho thiết bị hoàn thành việc gia nhập mạng trước đó.

- Cố định mặt sau của thiết bị lên vị trí lắp đặt:Thiết bị cảm biến cửa được thiết kế với 2 tùy chọn:
- Cố định lên vị trí lắp đặt bằng băng dính 2 mặt gắn sẵn trên nắp sau thiết bị.
- Cố định lên vị trí lắp đặt bằng bộ vít nở (được cấp kèm theo sản phẩm).

**Lưu ý:**

- Băng dính chỉ sử dụng ở những bề mặt sạch, phẳng như kính và nhựa. Còn những bề mặt đặc trưng khác khuyến cáo người dùng nên sử dụng vít nở để đảm bảo độ chắc chắn của thiết bị lên bề mặt.
- Lắp đặt hoàn thiện sản phẩm lên vị trí lắp đặt:
- Sau khi cố định mặt sau vào đúng vị trí lắp đặt, quý khách hàng tiếp tục gắn mặt trước cảm biến vào vị trí mặt sau đã lắp đặt để hoàn thiện sản phẩm.
- Người dùng nên lắp nam châm vào lề cửa, cảm biến cửa vào cánh cửa và khoảng cách giữa nam châm và cảm biến cửa gần hơn 2cm.
- Để đảm bảo cảm biến cửa hoạt động chính xác lắp rãnh khuyết ở cảm biến trùng với rãnh khuyết trên nam châm.
- Xem chi tiết cách lắp đặt TẠI ĐÂY.
## **4. Sử dụng thiết bị**
### ***4.1. Phát hiện đóng/mở cửa***
- Thiết bị phát hiện trạng thái đóng/mở cửa tại vị trí được lắp đặt, thông báo về bộ điều khiển trung tâm và được hiển thị trên ứng dụng.
- Phát hiện có sự kiện đóng/mở cửa: led chỉ thị nháy xanh 2 lần.
- Trường hợp cảm biến chưa được gia nhập mạng khi thay đổi trang thái đóng/mở cửa led chỉ thị nháy mà đỏ 2 lần.
- Thiết bị thông báo pin yếu: Đèn chỉ thị nháy đỏ nhanh 5 lần sau khi thay đổi trạng thái đóng/mở cửa.
### ***4.2. Cảm biến nhiệt độ, độ ẩm và ánh sáng***
- Cảm biến ánh sáng và cảm biến nhiệt độ, độ ẩm của thiết bị giúp thiết bị đo lường được điều kiện thực tế và sự thay đổi của môi trường xung quanh vị trí lắp đặt cảm biến để thông báo tới người sử dụng.
- Các chỉ số môi trường được hiển thị ở ứng dụng trên điện thoại.
- Chỉ số môi trường về ánh sáng nhiệt độ, độ ẩm của thiết bị cũng có thể dùng làm điều kiện để cài đặt các chế độ Rule tự động tùy theo mục đích người dùng.

**Lưu ý:** Các thông số môi trường cảm biến sẽ không cập nhật thường xuyên.

|Thông số|Ánh sáng|Nhiệt độ|Độ ẩm|
| :- | :- | :- | :- |
|Thời gian đo|2\.5 phút/lần|5 phút /lần|5 phút /lần|
|Ngưỡng thay đổi|≥ 30 lux|≥ 1⁰C|≥ 5%|
|Thời gian gửi định kỳ|30 phút/lần|30 phút/lần|30 phút/lần|
|Cập nhật khi cảm biến cửa thay đổi trạng thái|Không|Không|Không|
## **5. Cài đặt thiết bị trên ứng dụng Lumi Life**
### ***5.1. Cho thiết bị gia nhập mạng***
Để cài đặt thiết bị cảm biến cửa bằng ứng dụng trên điện thoại người dùng cần có bộ điều khiển trung tâm HC và đã tạo nhà trên hệ thống.

- Bước 1: Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.
- Bước 2: Gia nhập mạng cảm biến cửa.
- Ấn giữ nút Config trong 1s khi đèn chỉ thị nháy xanh 2 lần thì thả tay => Theo dõi trạng thái đèn chỉ thị để kiểm tra tình trạng gia nhập mạng của thiết bị (trong khoảng 40 giây) => Khi thiết bị gia nhập mạng thành công đèn chỉ thị nháy hồng 3 lần.
- Thiết bị gia nhập mạng không thành công đèn chỉ thị sẽ nháy đỏ 3 lần khi đó người dùng thực hiện reset thiết bị, sau đó thực hiện gia nhập lại thiết bị như trên.

Lưu ý: Thiết bị cảm biến cửa khi gia nhập mạng sẽ có 5 enpoint hiển thị trên ứng dụng: cảm biến cửa, cảm biến ánh sáng, cảm biến nhiệt độ, cảm biến độ ẩm, mức pin.

(Chi tiết xem [cài đặt thiết bị](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_thiet_bi))
### ***5.2. Trạng thái thiết bị***
Sau khi gia nhập mạng thành công, người dùng đặt tên thiết bị cho vào phòng.
Trong giao diện phòng người dùng chuyển sang tab hiển thị cảm biến để xem trạng thái của cảm biến.

- Icon cảm biến sáng: phát hiện có chuyển động.
- Icon cảm biến tối: không có chuyển động.
### ***5.3. Cài đặt rule tự động***
- Đối với cảm cửa người dùng có thể cài đặt Rule tự động bật/tắt thiết bị khác trong nhà hoặc cài đặt các Rule tự động khác theo ý muốn.
- Đầu vào của Rule là cảm biến cửa, đầu ra là thiết bị mà người dùng muốn điều khiển bằng cảm biến.
- Người dùng chọn trạng thái thiết bị đầu vào và thiết bị đầu ra phù hợp với nhu cầu sử dụng.

(Chi tiết xem hướng dẫn [cài đặt rule](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_rule)).
## ***5.4. Reset thiết bị***
- Nhấn giữ nút Config trong 5s cho đến khi đèn chỉ thị sáng hồng thì thả tay.
- Đèn chỉ thị nháy hồng 3 lần theo chu kì 1 giây/ lần, thiết bị rời mạng thành công quay lại trạng thái ban đầu.ị
## **7. Bộ sản phầm đóng gói**
Hộp đóng gói sản phẩm bao gồm: 1 bộ cảm biến cửa, 1 bộ hướng dẫn sử dụng, 1 pin CR2477, 1 bộ ốc vít lắp đặt.
