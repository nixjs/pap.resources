### **Thông số kỹ thuật**

|Điện áp hoạt động|110 – 240V AC ~ 50/60Hz|
| :- | :- |
|Công suất tiêu thụ|1000W tải trở/200W tải Led (Trên một kênh đầu ra)|
|Truyền thông|Zigbee|
|Công suất phát|10 dbm|
|Khoảng cách giới hạn giữa các thiết bị Zigbee|10m/40m (Khi có vật cản/không có vật cản)|
|Kích thước|47\.5mm x 49mm x 20.4mm|
|Nhiệt độ hoạt động|0 -> 50 độ C|


### **Sơ đồ đấu nối**
![Smiley face]
Đấu nối thiết bị

Khi vừa mới cấp nguồn vào thiết bị đèn Led sẽ nháy hồng 4 lần. Tiếp theo thiết bị sẽ kiểm tra trạng thái ở trong mạng.

- Nếu thiết bị chưa được cấu hình vào mạng: Led nháy đỏ 3 lần sau đó sáng đỏ.
- Nếu thiết bị đã được cấu hình vào mạng và kết nối thành công tới HC: Led nháy hồng 3 lần sau đó sáng xanh.
- Nếu thiết bị đã được cấu hình vào mạng nhưng không thể kết nối tới HC: Led nháy xanh 3 lần sau đó sáng đỏ.
## **Cài đặt điều khiển cho thiết bị**
### **Cho thiết bị gia nhập mạng**
- Người dùng đăng nhập vào app Lumi Life => chọn cài đặt => chọn cài đặt thiết bị => chọn HC => Zigbee => cho thiết bị gia nhập mạng.

(Chi tiết xem [cài đặt thiết bị](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cau_hinh_he_thong/cai_dat_thiet_bi))

- Khi thiết bị gia nhập mạng thành công đèn Led trên vỏ thiết bị sẽ nháy hồng 3 lần.
- Trường hợp thiết bị không gia nhập mạng có thể thiết bị đã được cấu hình, người dùng thực hiện reset thiết bị để quay về chế độ gia nhập mạng.
### **Điều khiển thiết bị trên ứng dụng Lumi Life**
Sau khi thiết bị gia nhập mạng thành công, ta có thể điều khiển bật/tắt thiết bị trên giao diện App Lumi Life.

![Smiley face]
Giao diện icon thiết bị trên App
## **Xóa thông tin mạng Zigbee dưới thiết bị**
Để xóa thông tin mạng Zigbee lưu dưới thiết bị ta thực hiện những bước như sau. Đầu tiên ta xác định công tắc đang đấu với đầu vào Input 1 trên Module và cho công tắc đó về trạng thái tắt.

- Tiếp theo ta tiến hành bật/tắt công tắc ở đầu vào Input 1 5 lần liên tiếp, khoảng thời gian giữa mỗi lần bật/tắt công tắc là 2 giây, sau đó ta sẽ thấy đèn Led trên vỏ thiết bị sẽ nháy hồng 2 lần trong 2 giây sau đó Led sáng hồng.

![Smiley face]

![Smiley face]
Cấp và ngắt nguồn thiết bị 5 lần – mỗi lần cách nhau 2 giây

- Trong vòng 5 giây ngay sau khi đèn Led trên vỏ thiết bị nháy hồng xong, ta tiến hành tắt rồi bật công tắc đấu với Input 1 thêm một lần nữa để xác nhận quá trình xóa thông tin mạng lưu trên thiết bị. Sau khi xóa thành công đèn Led trên vỏ thiết bị sẽ nháy hồng 4 lần và module sẽ quay về chế độ tìm kiếm mạng.

![Smiley face]
Đợi đến khi đèn Led nháy xong – trong vòng 5s sau đó ta tắt/bật công tắc đấu với Input 1 thêm lần nữa

NOTE: Sau khi xóa thông tin mạng dưới thiết bị, thiết bị sẽ out khỏi mạng Zigbee của HC, lúc này người dùng không thể điều khiển trên App. Tuy nhiên những thông tin cấu hình chế độ hoạt động, cấu hình tên, phòng… của thiết bị trên App Lumi Life vẫn sẽ được lưu lại, để khi người dùng ấn gia nhập mạng trên App thì thiết bị có thể vào lại mạng mà không cần cấu hình lại
## **Reset thiết bị**
Để reset thiết bị, ta thực hiện những bước như sau, nhấn liên tiếp 5 lần nút config ở mặt sau trên vỏ sản phẩm. Reset thành công đèn Led trên vỏ thiết bị sẽ nháy hồng 2 lần để thông báo reset thành công. Sau khi reset tất cả cấu hình nâng cao cũng như thông tin mạng được lưu trên thiết bị sẽ bị xóa và thiết bị sẽ quay trở về cài đặt như lúc ban đầu.

![Smiley face]
Ấn 5 lần nút Config để reset thiết bị

NOTE: Sau khi Reset tất cả thông tin mạng cũng như cấu hình hoạt động của thiết bị sẽ bị xóa hoàn toàn
## **Cài đặt nhóm thiết bị (Binding)**
Để cài đặt những nhóm đảo chiều thiết bị Zigbee thì ngoài tính năng cài đặt nhóm thiết bị ở trên App Lumi Life thì ta còn có thể cài đặt tính năng nhóm thiết bị (binding) ở ngay trên module, lúc này module In Out có thể đồng bộ trực tiếp trạng thái với các module In Out và công tắc Zigbee khác mà không cần thông qua HC.

Để cài đặt tính năng binding ta thực hiện các bước như bên dưới đây

Thao tác cài đặt:

- Bước 1: Cho module vào chế độ cài đặt: Nhấn giữ nút Config ở trên vỏ sản phẩm trong 10 giây cho đến khi Led nháy hồng 2 lần (Xác nhận đã vào chế độ cài đặt) thì thả tay.
- Bước 2: Chọn kênh cần cho vào nhóm: Tiếp theo người dùng lựa chọn kênh cần cài đặt. Để chọn kênh 1 – người dùng nhấn nhanh nút Config 1 lần, để chọn kênh 2 – người dùng nhấn nhanh Config 2 lần.
- Bước 3: Thêm các thiết bị khác vào nhóm Binding: Ta thực hiện lại bước 1&2 ở trên đối với những thiết bị khác (Module In Out, công tắc cảm ứng…)
- Bước 4: Xác nhận hoàn thành việc cài đặt: Sau khi hoàn thành việc cài đặt và đã cho toàn bộ các thiết bị cần cài đặt vào cùng một nhóm Binding, người dùng nhấn nhanh 2 lần nút Config hoặc đợi hết 60 giây thì thiết bị sẽ tự động thoát ra khỏi chế độ cài đặt.

Thao tác xóa module ra khỏi nhóm Binding:
Người dùng thực hiện lại bước 1&2 giống như thao tác cài đặt nhóm đã nêu ở trên. Nếu như kênh được lựa chọn đã từng được cài đặt vào một nhóm binding thì việc thực hiện đến bước 2 này sẽ là xóa thông tin của nhóm cũ và tiếp tục cấu hình cho kênh tương ứng vào một nhóm mới.
Ngoài ra thiết bị đầu tiên được cho vào chế độ cài đặt Binding thì sẽ tính là thiết bị khởi tạo (Init) nếu như ta thao tác xóa thiết bị Init ra khỏi nhóm thì toàn bộ cấu hình của nhóm đó sẽ bị xóa theo, còn với những thiết bị vào nhóm sau thiết bị khởi tạo (Init) nếu bị xóa thì cũng không làm ảnh hưởng gì đến cấu hình chung.
NOTE:

- Tại mỗi một thời điểm chỉ nên cài đặt một nhóm Binding.
- Cấu hình nhóm tối đa là 5 nút trong một nhóm và không thể cấu hình nhóm cho những nút nằm trên cùng một thiết bị.
## **Cài đặt tính năng nâng cao cho sản phẩm**
(Đang cập nhật…)
## **Cài đặt các chế độ hoạt động cho sản phẩm**
### **Cài đặt tín hiệu đầu vào của thiết bị (Input Mode)**
[Cách cài đặt tín hiệu đầu vào của thiết bị (Input Mode) trên App Lumi Life xem chi tiết tại đây](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cai_dat_chuc_nang_nang_cao/in_out_zigbee/module_in_out_che_do_hoat_dong#c%C3%A0i-%C4%91%E1%BA%B7t-t%C3%ADn-hi%E1%BB%87u-%C4%91%E1%BA%A7u-v%C3%A0o-c%E1%BB%A7a-thi%E1%BA%BFt-b%E1%BB%8B-input-mode)
Ta có thể cấu hình nhận dạng tín hiệu đầu vào của module (Module sẽ nhận tín hiệu từ công tắc dạng nhấn giữ, dạng nhấn nhả hay là cứ có thay đổi trạng thái công tắc là sẽ cập nhật lên App). Ta có những cách cấu hình như sau:
Bước 1: Người dùng nhấn giữ nút config thiết bị trong 3 giây đến khi Led trên vỏ thiết bị nháy xanh 2 lần thì thả tay ra – lúc này Led trên vỏ thiết bị sẽ chuyển sang sáng hồng thông báo đã vào chế độ cho phép cài đặt.

![Smiley face]
Giữ 3 giây – Led nháy xanh 2 lần

Bước 2: Ta tiến hành cài đặt cho kênh đầu vào tương ứng (VD muốn cài đặt cho kênh 1 thì sẽ tiến hành bấm công tắc đấu vào kênh 1 theo những thao tác như bên dưới và quan sát Led trên vỏ thiết bị).

- Bật/tắt 1 lần: Cài đặt cho kênh đầu vào ở chế độ Toggle Switch – Led nháy hồng 1 lần (Ở chế độ này khi tín hiệu đầu vào là ON thì đầu ra cũng được ON – bật lên, khi tín hiệu đầu vào là OFF thì đầu ra cũng được OFF – tắt đi. Tín hiệu giữa đầu vào và đầu ra là đồng nhất).
- Bật/tắt 2 lần: Cài đặt cho kênh đầu vào ở chế độ Any Change – Led nháy hồng 2 lần (Ở chế độ này cứ khi nào tín hiệu đầu vào thay đổi trạng thái thì đầu ra cũng thay đổi trạng thái theo – không cần quan tâm là có cùng là một trạng thái ON/OFF hay không).
- Bật/tắt 3 lần: Cài đặt cho kênh đầu vào ở chế độ Momentary Switch – Led nháy hồng 3 lần (Ở chế độ này dành cho loại công tắc không giữ trạng thái, VD như nút nhấn chuông cửa… cứ một lượt nhấn và giữ nút trong khoảng 2 -> 7 giây sau đó nhả tay ra là đầu ra sẽ thay đổi trạng thái một lần. Ngoài ra mỗi một lượt thao tác như vậy sẽ tính là một trạng thái nhấn giữ gửi lên App).

![Smiley face]

NOTE: Trước khi vào bước 2 này ta phải cho công tắc đầu vào về trạng thái tắt hoặc nếu như công tắc đầu vào đang ở trạng thái bật thì sẽ tiến hành tắt đi -> sau đó Bật/Tắt theo số lần như trên.
Bước 3: Bấm một lần nút Config ở mặt sau của vỏ sản phẩm hoặc đợi hết 15 giây mà không thao tác gì thêm thì Led trên vỏ thiết bị sẽ nháy xanh 2 lần thông báo hoàn thành việc cài đặt và tự động thoát chế độ. Nếu cài đặt thất bại Led trên vỏ thiết bị sẽ nháy đỏ 2 lần.

![Smiley face]
Bấm thêm 1 lần nút Config để kết thúc việc cấu hình – Led trên thiết bị nháy xanh 2 lần
### **Cài đặt tín hiệu đầu ra của thiết bị (Output Mode)**
[Cách cài đặt tín hiệu đầu ra của thiết bị (Output Mode) trên App Lumi Life xem chi tiết tại đây](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cai_dat_chuc_nang_nang_cao/in_out_zigbee/module_in_out_che_do_hoat_dong#c%C3%A0i-%C4%91%E1%BA%B7t-t%C3%ADn-hi%E1%BB%87u-%C4%91%E1%BA%A7u-ra-c%E1%BB%A7a-thi%E1%BA%BFt-b%E1%BB%8B-output-mode)

Người dùng có thể cài đặt chế độ cho những thiết bị ở đầu ra với những chế độ như sau:

- Chế độ bật/tắt thông thường
- Chế độ Auto Off: Khi thiết bị được bật lên thì sau bao lâu thiết bị sẽ tự động được tắt đi (VD: Ứng dụng cho hẹn giờ bình nóng lạnh…)
- Chế độ Auto On: Khi thiết bị được tắt đi thì sau bao lâu thiết bị sẽ tự động được bật lên.

![Smiley face]
Chế độ Auto On & Auto Off

- Chế độ Delay Off: VD đèn đang sáng và nhận được tín hiệu yêu cầu tắt từ đầu vào nhưng phải một lúc sau đèn mới tắt đi.
- Chế độ Delay On: VD đèn đang tắt và nhận được tín hiệu yêu cầu bật từ đầu vào nhưng phải một lúc sau đèn mới bật lên.

![Smiley face]
Chế độ Auto On & Auto Off

NOTE: Chức năng này chỉ có thể cấu hình trên App. Không hỗ trợ thao tác cấu hình dưới thiết bị.
### **Cài đặt trạng thái của đầu ra khi được cấp lại nguồn (Power Mode)**
[Cách cài đặt trạng thái của đầu ra khi được cấp lại nguồn (Power Mode) trên App Lumi Life xem chi tiết tại đây](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cai_dat_chuc_nang_nang_cao/in_out_zigbee/module_in_out_che_do_hoat_dong#c%C3%A0i-%C4%91%E1%BA%B7t-tr%E1%BA%A1ng-th%C3%A1i-c%E1%BB%A7a-%C4%91%E1%BA%A7u-ra-khi-%C4%91%C6%B0%E1%BB%A3c-c%E1%BA%A5p-l%E1%BA%A1i-ngu%E1%BB%93n-power-mode)

Khi module bị mất điện sau đó được cấp lại nguồn thì ta có thể cài đặt trạng thái cho đầu ra (Output) của module khi được khởi động lại nguồn. Có tất cả 3 chế độ:

- Mặc định tắt (Default Off): Khi module được cấp lại nguồn thì đầu ra của module sẽ vào luôn trạng thái tắt.
- Mặc định bật (Default On): Khi module được cấp lại nguồn thì đầu ra của module sẽ vào luôn trạng thái bật.
- Lấy lại trạng thái cũ: Khi module được cấp lại nguồn thì đầu ra của module sẽ lấy lại trạng thái cũ trước khi bị mất điện.

Để cài đặt ta thực hiện các bước dưới đây:
Bước 1: Người dùng nhấn giữ nút config thiết bị trong 5 giây đến khi Led trên vỏ thiết bị nháy đỏ 2 lần thì thả tay ra – lúc này Led trên vỏ thiết bị sẽ chuyển sang sáng hồng thông báo đã vào chế độ cho phép cài đặt

![Smiley face]
Giữ 5 giây – Led nháy đỏ 2 lần

Bước 2: Ta tiến hành cài đặt cho kênh đầu ra tương ứng (VD muốn cài đặt cho kênh 1 thì sẽ tiến hành bấm công tắc đấu vào kênh 1 theo những thao tác như bên dưới và quan sát Led trên vỏ thiết bị).

- Bật/tắt 1 lần: Cài đặt cho kênh đầu ra ở chế độ Mặc định tắt – Led nháy hồng 1 lần.
- Bật/tắt 2 lần: Cài đặt cho kênh đầu ra ở chế độ Lấy lại trạng thái cũ – Led nháy hồng 2 lần.
- Bật/tắt 3 lần: Cài đặt cho kênh đầu ra ở chế độ Mặc định bật – Led nháy hồng 3 lần.

![Smiley face]

NOTE: Trước khi vào bước 2 này ta phải cho công tắc đầu vào về trạng thái tắt hoặc nếu như công tắc đầu vào đang ở trạng thái bật thì sẽ tiến hành tắt đi -> sau đó Bật/Tắt theo số lần như trên.
Bước 3: Bấm một lần nút Config ở mặt sau của vỏ sản phẩm hoặc đợi hết 15 giây mà không thao tác gì thêm thì Led trên vỏ thiết bị sẽ nháy xanh 2 lần thông báo hoàn thành việc cài đặt và tự động thoát chế độ. Nếu cài đặt thất bại Led trên vỏ thiết bị sẽ nháy đỏ 2 lần.

![Smiley face]
Bấm thêm 1 lần nút Config để kết thúc việc cấu hình – Led trên thiết bị nháy xanh 2 lần
### **Cài đặt cho phép liên kết đầu vào – đầu ra (Link-Unlink)**
[Cách cài đặt cho phép liên kết đầu vào – đầu ra (Link-Unlink) trên App Lumi Life xem chi tiết tại đây](https://support.lumi.vn/docs/hdsd/ung_dung_lumi_life/cai_dat_chuc_nang_nang_cao/in_out_zigbee/module_in_out_che_do_hoat_dong#c%C3%A0i-%C4%91%E1%BA%B7t-cho-ph%C3%A9p-li%C3%AAn-k%E1%BA%BFt-%C4%91%E1%BA%A7u-v%C3%A0o---%C4%91%E1%BA%A7u-ra-link-unlink)

Nếu như người dùng không muốn sự thay đổi của công tắc đầu vào làm ảnh hưởng tới trạng thái của thiết bị điện đầu ra thì có thể tiến hành thao tác Un-Map ở trên App Lumi Life. Lúc này trạng thái của thiết bị trên App Lumi Life sẽ lấy theo trạng thái của đầu ra Output, còn đầu vào Input tuy không thể điều khiển thiết bị ở đầu ra Output nhưng vẫn có thể gửi các sự kiện lên cho App Lumi Life (VD: Sự kiện nhấn 1 lần, nhấn 2 lần, nhấn giữ).

NOTE: Chức năng này chỉ có thể cấu hình trên App. Không hỗ trợ thao tác cấu hình dưới thiết bị.
## **Lắp đặt hoàn thiện sản phẩm**
Bước 1: Kết nối thiết bị với công tắc cơ và nguồn điện trong nhà

![Smiley face]

Bước 2: Đặt thiết bị vào bên trong đế âm rồi ốp mặt công tắc ra ngoài

![Smiley face]

Bước 3: Siết ốc và hoàn thiện lắp đặt sản phẩm

![Smiley face]

[Smiley face]: Aspose.Words.f382dfbb-cdc2-401e-a871-91894c893711.001.png
[Smiley face]: Aspose.Words.f382dfbb-cdc2-401e-a871-91894c893711.002.png
[Smiley face]: Aspose.Words.f382dfbb-cdc2-401e-a871-91894c893711.003.png
[Smiley face]: Aspose.Words.f382dfbb-cdc2-401e-a871-91894c893711.004.png
