Mã sản phẩm: LM-MDZ/2.0 (Bản Zigbee), LM-MDB (Bản BLE Mesh)

![Smiley face]

- Kết nối không dây: Zigbee/ BLE Mesh
- Phát hiện chuyển động.
- Đo cường độ ánh sáng của môi trường xung quanh.
- Đo mức nhiệt độ, độ ẩm của môi trường xung quanh.
- Cập nhật thường xuyên mức pin của thiết bị lên App Lumi Life.
- Có thể thay đổi độ nhạy/độ trễ của cảm biến.
- Các thành phần của cảm biến có thể làm đầu vào cho Rule (Tùy biến theo nhu cầu người sử dụng).
- Điều khiển trực tiếp với các loại công tắc bật/tắt, module In Out (bản Zigbee) thông qua cài đặt tính năng nâng cao (Binding).
## **Thông số kỹ thuật**

|Điện áp hoạt động|x3 Pin AAA|
| :- | :- |
|Kích thước (Bán kinh x C)|70 x 35mm|
|Truyền thông|Zigbee/ BLE Mesh|
|Công suất phát|10 dbm|
|Khoảng cách giới hạn giữa các thiết bị Zigbee|10m/40m (Khi có vật cản/không có vật cản)|
|Góc quét cảm biến|90 độ|
|Khoảng cách phát hiện chuyển động|6m|
|Dải đo ánh sáng|0 -> 10.000 lux|
|Khối lượng|90 gram|
|Nhiệt độ hoạt động|0 -> 50 độ C|

![Smiley face]
## **Cài đặt điều khiển thiết bị**
### **Cấp nguồn cho thiết bị**
Để cấp nguồn cho thiết bị (thiết bị chưa được lắp pin hoặc cần thay pin mới) người dùng cần thực hiện thao tác mở nắp sản phẩm và lắp pin cấp nguồn cho sản phẩm theo các bước như sau:

- Xoay mặt trước ngược chiều kim đồng hồ để mở sản phẩm.
- Lắp pin được cấp kèm vào khay đựng pin trên thiết bị.
## **Sau khi được cấp nguồn thành công. Ta theo dõi đèn Led ở trên vỏ thiết bị. Nếu thiết bị chưa cấu hình vào mạng – Led nháy đỏ 3 lần, còn nếu thiết bị đã được cấu hình vào mạng – Led nháy hồng 3 lần.**
![Smiley face]
Mở mặt sau của thiết bị

![Smiley face]
Lắp pin mới vào thiết bị

![Smiley face]
Quan sát đèn Led trên vỏ trước của thiết bị
## **NOTE: Nếu như có cảm biến nào trên thiết bị bị lỗi thi đèn Led cũng sẽ hiển thị để thông báo:**
- Cảm biến ánh sáng lỗi: Led sáng đỏ trong 2 giây.
- Cảm biến nhiệt độ/độ ẩm lỗi: Led sáng xanh trong 2 giây.
- Tất cả cảm biến môi trường bị lỗi: Led sáng hồng trong 2 giây.
### **Cho thiết bị gia nhập mạng**
- Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.

(Chi tiết xem [cài đặt thiết bị](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_thiet_bi))

- Sau khi ấn gia nhập mạng trên App, người dùng cũng cần phải nhấn giữ nút Config (Ở mặt sau của sản phẩm) trong vòng 2s đến khi đèn Led nháy xanh 2 lần. Lúc này thiết bị sẽ bắt đầu tìm kiếm mạng của HC và nháy đỏ (8 giây/nháy). Cuối cùng khi thiết bị gia nhập mạng thành công đèn Led sẽ nháy hồng 3 lần.
## **NOTE Trong 1 phút mà thiết bị không tìm được mạng thiết bị sẽ nháy đỏ 3 lần.**
### **Điều khiển thiết bị trên ứng dụng Lumi Life**
Sau khi thiết bị gia nhập mạng thành công, ta sẽ có 5 icon thể hiện cho thiết bị ở trên App Lumi Life bao gồm:

- Chuyển động
- Ánh sáng
- Nhiệt độ
- Độ ẩm
- Mức % pin

![Smiley face]
Giao diện icon thiết bị trên App
### **Cập nhật phát hiện chuyển động**
Khi phát hiện có chuyển động:

- Nếu thiết bị đã được cấu hình vào mạng:
**Pin < 20%: Led nháy xanh 5 lần
Pin > 20%: Led nháy xanh 1 lần – phát hiện có chuyển động liên tục. Nháy xanh 2 lần – khi cảm biến đang từ trạng thái không chuyển động -> có chuyển động.**
------------------------------------------------------------------------------------------------------------------------------------------------------------
- Nếu thiết bị chưa được cấu hình vào mạng:
**Pin < 20%: Led nháy đỏ 5 lần
Pin > 20%: Led nháy đỏ 1 lần – phát hiện có chuyển động liên tục. Nháy đỏ 2 lần – khi cảm biến đang từ trạng thái không chuyển động -> có chuyển động.**
--------------------------------------------------------------------------------------------------------------------------------------------------------
![Smiley face]
Icon trên App khi phát hiện có chuyển động/không có chuyển động
### **Cập nhật thông tin môi trường**
- Cảm biến ánh sáng: Cứ 30 giây thiết bị sẽ thức dậy và đo cường độ ánh sáng xung quanh, nếu có sự thay đổi lớn hơn hoặc nhỏ hơn 10 lux thì sẽ gửi thông tin mới lên cho HC.
- Cảm biến nhiệt độ: Nhiệt cứ thay đổi 1 độ C thì thiết bị sẽ gửi lên HC.
- Cảm biến độ ẩm: Độ ẩm cứ thay đổi 5% thì thiết bị sẽ gửi lên HC.
## **Ngoài ra mặc định cứ 30p là thiết bị sẽ gửi toàn bộ thông tin môi trường lên. Nếu như người dùng muốn lấy luôn mọi thông tin của cảm biến tại thời điểm đó thì có thể nhấn 1 lần nút Config (Với điều kiện thiết bị đang ở trong mạng)**
![Smiley face]
Nhấn 1 lần nút Config để cập nhật mọi thông tin của thiết bị.

Sau khi ấn nút Config:

- Nếu thiết bị đã được cấu hình vào mạng:
**Pin < 20%: Led nháy xanh 5 lần.
Pin > 20%: Led nháy xanh 1 lần.**
---------------------------------
- Nếu thiết bị chưa được cấu hình vào mạng:
**Pin < 20%: Led nháy đỏ 5 lần.
Pin > 20%: Led nháy đỏ 1 lần.**
-------------------------------
## **Reset thiết bị**
Nếu không quét được thiết bị vào mạng người dùng nên thử tiến hành reset thiết bị. Để reset thiết bị, ta thực hiện những bước như sau. Đầu tiên ta cần mở vỏ ở mặt sau của sản phẩm, sau đó nhấn giữ nút Config trong vòng 5 giây đến khi Led sáng hồng thì thả tay.

![Smiley face]
Mở mặt sau của thiết bị

![Smiley face]
Nhấn giữ nút config trong 5 giây

Khi thiết bị được reset (hoặc tự xóa khỏi mạng) thành công thì đèn Led trên vỏ thiết bị sẽ nháy hồng 2 lần.

![Smiley face]
Led trên vỏ thiết bị nháy hồng 2 lần thông báo reset thành công
## <a name="cài-đặt-các-chế-độ-hoạt-động--chức-năng-nâng-cao-cho-sản-phẩm"></a>[**#](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cam_bien/pir_zigbee_v2#c%C3%A0i-%C4%91%E1%BA%B7t-c%C3%A1c-ch%E1%BA%BF-%C4%91%E1%BB%99-ho%E1%BA%A1t-%C4%91%E1%BB%99ng--ch%E1%BB%A9c-n%C4%83ng-n%C3%A2ng-cao-cho-s%E1%BA%A3n-ph%E1%BA%A9m)**Cài đặt các chế độ hoạt động & chức năng nâng cao cho sản phẩm**
### <a name="cấu-hình-điều-khiển-trực-tiếp-thiết-bị-khác-binding-group"></a>[**#](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cam_bien/pir_zigbee_v2#c%E1%BA%A5u-h%C3%ACnh-%C4%91i%E1%BB%81u-khi%E1%BB%83n-tr%E1%BB%B1c-ti%E1%BA%BFp-thi%E1%BA%BFt-b%E1%BB%8B-kh%C3%A1c-binding-group)**Cấu hình điều khiển trực tiếp thiết bị khác (Binding Group)**
Một trong những ứng dụng phổ biến nhất của cảm biến chuyển động đó là khi phát hiện chuyển động – bật điện, khi hết chuyển động – tắt điện (Ứng dụng ở vị trí hiên nhà, nhà vệ sinh…). Thông thường ta có thể tạo rule cho những ứng dụng này, tuy nhiên để tối giản cho hoạt động rule trên HC đồng thời với những ứng dụng đơn giản như này, thiết bị vẫn có thể tự động hoạt động mà không cần tới HC. Vậy nên Lumi đã phát triển thêm tính năng Binding (Nhóm trực tiếp dưới thiết bị), với chức năng này sau khi cảm biến gia nhập mạng thành công sẽ có thể gửi trực tiếp trạng thái của cảm biến tới các dòng thiết bị [công tắc Zigbee](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cong_tac/cong_tac_cam_ung), [module In Out Zigbee](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/module/2in_2out_zigbee)

![Smiley face]
Cảm biến điều khiển công tắc, module thông qua Rule của HC

![Smiley face]
Cơ chế hoạt động của nhóm Binding
## **NOTE: Các thiết bị phải nằm trong cùng một hệ thống mạng Zigbee (Nằm trong cùng HC/LC) thì mới có thể cấu hình Binding với nhau.**
Để cấu hình nhóm Binding ta thực hiện những bước sau đây:

- Bước 1: Cho cảm biến vào chế độ cấu hình
  Bấm nhanh 10 lần nút Config ở mặt sau sản phẩm. Lúc này cảm biến chuyển động sẽ trở thành thiết bị khởi tạo (Init) và Led trên thiết bị sẽ nháy hồng một lần.

![Smiley face]
Nhấn nhanh nút Config 10 lần

- Bước 2: Thêm công tắc, module Zigbee vào nhóm Binding của cảm biến
  Tiếp theo người dùng tiến hành thao tác cho các thiết bị Zigbee khác vào chế độ Binding ([Binding công tắc](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cong_tac/cong_tac_cam_ung#nh%C3%B3m-thi%E1%BA%BFt-b%E1%BB%8B), [Binding module In Out](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/module/2in_2out_zigbee#c%C3%A0i-%C4%91%E1%BA%B7t-nh%C3%B3m-thi%E1%BA%BFt-b%E1%BB%8B-binding)). Khi cảm biến chuyển động Zigbee đã mở chế độ Binding, các thiết bị công tắc, module vào chế độ Binding sau thì sẽ tự động thực hiện nhóm với cảm biến. Mỗi khi có thiết bị mới nhóm thành công với cảm biến, Led trên cảm biến sẽ nháy hồng 3 lần.

![Smiley face]

- Bước 3: Hoàn thành cấu hình
  Sau khi cấu hình xong người dùng có thể nhấn một lần nút Config trên cảm biến hoặc đợi hết 1 phút mà không có thêm thiết bị mới vào, đèn Led sẽ nháy hồng 3 lần sau đó cảm biến tự động thoát ra khỏi chế độ cấu hình Binding.
## **NOTE**
- Cảm biến chỉ có một vai trò duy nhất trong nhóm Binding đó là thiết bị khởi tạo – Init.
- Chỉ nên cấu hình tối đa là 5 thiết bị trong một nhóm Binding.
- Tại một thời điểm chỉ nên cấu hình Binding cho một cảm biến chuyển động, sau khi cấu hình xong cần phải thoát khỏi chế độ cấu hình Binding, để tránh bị cấu hình nhầm các thiết bị của nhóm Binding khác.
- Xóa nhóm: Để xóa nhóm ta chỉ cần bấm 10 lần nút Config ở trên cảm biến, nếu như cảm biến chưa có nhóm Binding nào thì sẽ tiếp tục cấu hình mới còn đối với cả biến đã có nhóm Binding rồi thì nhóm do nó khởi tạo sẽ bị xóa toàn bộ (Bởi cảm biến là thiết bị khởi tạo – Init, nên khi nó bị xóa ra khỏi nhóm thì mọi thiết bị khác cũng bị xóa theo) sau đó cảm biến lại về chế độ cấu hình nhóm Binding mới. Còn nếu muốn xóa riêng lẻ từng thiết bị ra khỏi nhóm Binding ta có thể thực hiện bước xóa trên từng thiết bị riêng lẻ ([Xóa nhóm Binding công tắc cảm ứng](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cong_tac/cong_tac_cam_ung#nh%C3%B3m-thi%E1%BA%BFt-b%E1%BB%8B), [Xóa nhóm Binding module In Out](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cong_tac/cong_tac_cam_ung#nh%C3%B3m-thi%E1%BA%BFt-b%E1%BB%8B)).
### **Thay đổi thời gian độ trễ của cảm biến (Thao tác dưới thiết bị)**
Tính từ lúc cảm biến phát hiện có chuyển động sau bao nhiêu lâu mà không phát hiện thêm có chuyển động nào khác thì cảm biến sẽ báo về là không có chuyển động. Ngoài ra người dùng có thể cài đặt linh hoạt hơn mức độ trễ (Từ 10 -> 3600 giây) thông qua chức năng cài đặt nâng cao trên App Lumi Life

![Smiley face]
### **Cài đặt tính năng nâng cao cho cảm biến (Thao tác trên App Lumi Life)**
## [**Người dùng có thể cài đặt độ trễ, độ nhạy và những chức năng nâng cao cho cảm biến trên App Lumi Life. Chi tiết có thể xem tại đây**](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cai_dat_chuc_nang_nang_cao/cam_bien_nang_cao_zigbee)
## **Lắp đặt và hoàn thiện sản phẩm**
**Bước 1: Cấp nguồn thiết bị.
Xoay mặt trước ngược chiều kim đồng hồ để mở sản phẩm.
Lắp pin được cấp kèm vào khay đựng pin trên thiết bị.**
-------------------------------------------------------
![Smiley face]
Lắp pin mới vào thiết bị
**Bước 2: Lắp đặt thiết bị lên vị trí.
NOTE: Trước khi lắp đặt hoàn thiện sản phẩm người dùng cần phải cho thiết bị hoàn thành việc gia nhập mạng trước đó.**
----------------------------------------------------------------------------------------------------------------------
- Cố định mặt sau lên vị trí lắp đặt:
## **Thiết bị thiết kế với 2 tùy chọn: cố định bằng băng dính 2 mặt hoặc cố định bằng vít nở.**
![Smiley face]

- Lắp đặt hoàn thiện sản phẩm lên đúng vị trí:
## **Đặt mặt trước thiết bị sao cho các ngàm của mặt sau trùng với các rãnh ngàm của mặt trước, sau đó xoay mặt trước theo chiều cùng kim đồng hồ để các ngàm ăn khớp vào rãnh.**
![Smiley face]
## **NOTE: Ngàm nhỏ ở mặt sau tương ứng với rãnh nhỏ ở mặt trước. Thiết bị được thiết kế chỉ 1 vị trí có thể xoay ăn khớp giữa mặt trước và mặt sau.**
### <a name="lưu-ý-khi-lắp-đặt-sản-phẩm"></a>[**#](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cam_bien/pir_zigbee_v2#l%C6%B0u-%C3%BD-khi-l%E1%BA%AFp-%C4%91%E1%BA%B7t-s%E1%BA%A3n-ph%E1%BA%A9m)**Lưu ý khi lắp đặt sản phẩm**
![Smiley face]
Lắp mặt trước sản phẩm -> Lắp đặt mặt cảm biến trước để hoàn thiện
## **NOTE: Đây là thiết bị lắp ở trong nhà không khuyến khích lắp đặt, sử dụng ngoài trời**
### <a name="phụ-kiện-che-mắt-cảm-biến"></a>[**#](https://support.lumi.vn/docs/hdsd/thiet_bi/thiet_bi_zigbee/cam_bien/pir_zigbee_v2#ph%E1%BB%A5-ki%E1%BB%87n-che-m%E1%BA%AFt-c%E1%BA%A3m-bi%E1%BA%BFn)**Phụ kiện che mắt cảm biến**
Sản phẩm sẽ được đóng gói kèm 2 phụ kiện mắt che cảm biến để có thể linh hoạt theo nhu cầu sử dụng của người dùng.

![Smiley face]
Phụ kiện che mắt cảm biến
### **Vùng cảm ứng của thiết bị**
Với khoảng cách trên, khi người sử dụng đi vào vùng cảm ứng của thiết bị, thiết bị sẽ cảm ứng tốt nhất. Nếu thiết bị không phát hiện người sử dụng trong vùng cảm ứng, hãy liên hệ với Đại lý mua hàng để được hỗ trợ tốt nhất

![Smiley face]

[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.001.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.002.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.003.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.004.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.005.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.006.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.007.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.008.png
[Smiley face]: Aspose.Words.8d6cffd1-b77f-46ad-8a8f-f5240b840580.009.png
