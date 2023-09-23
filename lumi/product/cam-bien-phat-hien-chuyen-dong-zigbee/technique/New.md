## **1. Tổng quát**
Mã sản phẩm: LM-MDZ/2.1 (bản dùng nguồn)

- Thiết bị cảm biến chuyển động của Lumi hoạt động bằng công nghệ cảm biến hồng ngoại.
- Thiết bị được sử dụng để kích hoạt các thiết bị khác trong hệ thống, thông qua bộ điều khiển trung tâm.
## **2. Thông số kỹ thuật**

<table><tr><th rowspan="2">Nguồn cấp</th><th></th></tr>
<tr><td>Bản chạy nguồn AC:<br>220V AC ~ 50Hz</td></tr>
<tr><td>Nhiệt độ hoạt động</td><td>0℃ – 50℃</td></tr>
<tr><td>Truyền thông</td><td>Zigbee</td></tr>
<tr><td>Công suất phát Zigbee</td><td>10 dbm</td></tr>
<tr><td rowspan="2">Góc phát hiện chuyển động</td><td>Góc 1: 92⁰</td></tr>
<tr><td>Góc 2: 102⁰</td></tr>
<tr><td>Dải đo ánh sáng</td><td>0 – 10000 lux</td></tr>
<tr><td>Kích thước (Φ x C)</td><td>70 x 27 mm</td></tr>
<tr><td>Khối lượng</td><td>40 gram</td></tr>
</table>
## **3. Lắp đặt thiết bị**
#### **Bước 1: Cấp nguồn thiết bị.**
- Lắp pin cho cảm biến sử dụng nguồn pin:
- Xoay mặt trước ngược chiều kim đồng hồ để mở sản phẩm.
- Lắp pin được cấp kèm vào khay đựng pin trên thiết bị.
- Cấp nguồn cho cảm biến sử dụng nguồn điện 220V AC:
- Xoay mặt trước ngược chiều kim đồng hồ để mở sản phẩm.

**Lưu ý:**
Đối với lắp cảm biến trên trần thạch cao dùng nguồn người dùng khoét lỗ lắp đặt nguồn hợp lí để lắp đặt được cảm biến.
#### **Bước 2: Lắp đặt thiết bị lên vị trí.**
**Lưu ý:**
Trước khi lắp đặt hoàn thiện sản phẩm người dùng cần phải cho thiết bị hoàn thành việc gia nhập mạng trước đó.

- Cố định mặt sau lên vị trí lắp đặt:
- Lắp đặt hoàn thiện sản phẩm lên đúng vị trí

**Lưu ý:**

- Ngàm nhỏ ở mặt sau tương ứng với rãnh nhỏ ở mặt trước. Thiết bị được thiết kế chỉ 1 vị trí có thể xoay ăn khớp giữa mặt trước và mặt sau.
- Đặc biệt đây là thiết bị lắp ở trong nhà khuyến cáo không sử dụng ở ngoài trời.
## **2. Sử dụng thiết bị**
### ***2.1. Phát hiện chuyển động***
- Thiết bị phát hiện chuyển động khi có người di chuyển trong vùng cảm ứng và thông báo về bộ điều khiển trung tâm.
- Phát hiện chuyển động: Đèn chỉ thị sáng xanh, nháy nhanh 2 lần.
- Nếu không có tín hiệu chuyển động: Đèn chỉ thị nháy xanh theo chu kỳ 2s/1 lần.
### ***2.2. Góc quét chuyển động của cảm biến***
Vùng phát hiện chuyển động của cảm biến:

- Vùng phát hiện chuyển động góc 1
- Vùng phát hiện chuyển động góc 2
### ***2.3. Phụ kiện che mắt cảm biến***
Từ tháng 6/2020 cảm biến chuyển động được thiết kế theo mẫu mới có thể gắn thêm phụ kiện để giảm bớt góc quét chuyển động của cảm biến.
### ***2.4. Lựa chọn mức thời gian trễ***
- Thời gian trễ là khoảng thời gian tính từ khi cảm biến bắt đầu không phát hiện thấy chuyển động đến thời điểm cảm biến xác nhận trạng thái và gửi tín hiệu về HC.
- Cảm biến chuyển động có 3 mức thời gian trễ: 30s, 120s, 300s.
- Mặc định ban đầu là 30s.
- Người dùng có thể thay đổi các mức thời gian trễ bằng cách nhấn đúp (2 lần liên tiếp) nút config trên mạch cảm biến để chuyển đổi các mức thời gian trễ được miêu tẳ như bảng dưới.

Cài đặt thời gian trễ

|Ấn đúp nút Config lần 1|Đèn chỉ thị sáng xanh|Thời gian trễ 30s|
| :- | :- | :- |
|Ấn đúp nút Config lần 2|Đèn chỉ thị sáng đỏ|Thời gian trễ 120s|
|Ấn đúp nút Config lần 3|Đèn chỉ thị sáng hồng|Thời gian trễ 300s|
### **2.5. Cảm biến nhiệt độ, độ ẩm và ánh sáng**
- Cảm biến ánh sáng và cảm biến nhiệt độ, độ ẩm của thiết bị giúp thiết bị đo lường được điều kiện thực tế và sự thay đổi của môi trường xung quanh vị trí lắp đặt cảm biến để thông báo tới người sử dụng. Các chỉ số môi trường được hiển thị ở ứng dụng trên điện thoại.
- Chỉ số môi trường về ánh sáng nhiệt độ, độ ẩm của thiết bị cũng có thể dùng làm điều kiện để cài đặt các chế độ Rule tự động tùy theo mục đích người dùng.

**Lưu ý:**
Các thông số môi trường cảm biến sẽ không cập nhật thường xuyên.

|Thông số|Ánh sáng|Nhiệt độ|Độ ẩm|
| :- | :- | :- | :- |
|Thời gian đo|2\.5 phút/lần|5 phút /lần|5 phút /lần|
|Ngưỡng thay đổi|≥ 30 lux|≥ 1⁰C|≥ 5%|
|Thời gian gửi định kỳ|30 phút/lần|30 phút/lần|30 phút/lần|
|Cập nhật khi cảm biến chuyển động thay đổi trạng thái|Cập nhật khi có sự thay đổi giá trị|Không|Không|
## **3. Cài đặt thiết bị trên ứng dụng Lumi Life**
### **3.1. Cho thiết bị gia nhập mạng**
- Để cài đặt thiết bị cảm biến chuyển động bằng ứng dụng trên điện thoại người dùng cần có bộ điều khiển trung tâm HC và đã tạo nhà trên hệ thống.
  - Bước 1: Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.
  - Bước 2: Gia nhập mạng cảm biến chuyển động. Ấn giữ nút Config trong 1s khi đèn chỉ thị nháy xanh 2 lần thì thả tay => Theo dõi trạng thái đèn chỉ thị để kiểm tra tình trạng gia nhập mạng của thiết bị (trong khoảng 40 giây) => Khi thiết bị gia nhập mạng thành công đèn chỉ thị nháy hồng 3 lần.
- Thiết bị gia nhập mạng không thành công đèn chỉ thị sẽ nháy đỏ 3 lần, khi đó người dùng thực hiện reset thiết bị, sau đó thực hiện gia nhập lại thiết bị như trên.
- Lưu ý: Thiết bị cảm biến chuyển động khi gia nhập mạng sẽ có 5 enpoint hiển thị trên ứng dụng: cảm biến chuyển động, cảm biến ánh sáng, cảm biến nhiệt độ, cảm biến độ ẩm, mức pin.

(Chi tiết xem [cài đặt thiết bị](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_thiet_bi))
### ***3.2. Trạng thái thiết bị***
- Sau khi gia nhập mạng thành công, người dùng đặt tên thiết bị cho vào phòng.
- Trong giao diện phòng người dùng chuyển sang tab hiển thị cảm biến để xem trạng thái của cảm biến.
### ***3.3. Cài đặt rule tự động***
- Đối với cảm biến chuyển động người dùng có thể cài đặt Rule tự động bật/tắt thiết bị khác trong nhà hoặc cài đặt các Rule tự động khác theo ý muốn.
- Đầu vào của Rule là cảm biến chuyển động, đầu ra là thiết bị mà người dùng muốn điều khiển bằng cảm biến.
- Người dùng chọn trạng thái thiết bị đầu vào và thiết bị đầu ra phù hợp với nhu cầu sử dụng.

(Chi tiết xem hướng dẫn [cài đặt rule](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_rule)).
### ***3.4. Reset thiết bị***
- Nhấn giữ nút Config trong 5s cho đến khi đèn chỉ thị sáng hồng thì thả tay.
- Đèn chỉ thị nháy hồng 3 lần theo chu kì 1 giây/ lần, thiết bị rời mạng thành công quay lại trạng thái ban đầu.
## **4. Bộ sản phẩm đóng gói**
### ***Loại cảm biến sử dụng nguồn 220V AC***
Hộp đóng gói sản phẩm bao gồm:

- 1 thiết bị cảm biến chuyển động
- 1 bộ hướng dẫn sử dụng
- 1 bộ adapter
- 1 bộ ốc vít lắp đặt
