# Báo cáo \_SB

**PHIẾU XUẤT ĐIỀU CHUYỂN KHO**

1. **Hạch toán**

Nợ TK 151 Hàng mua đang đi trên đường

Có TK 152, 155, 156,… Nguyên liệu, vật liệu; Thành phẩm; Hàng hóa,…

1. **Các bước thực hiện**

* Vào phân hệ: Kho/ Nhập liệu/ Phiếu xuất điều chuyển chọn biểu tượng Thêm trên thanh công cụ.

1. Số bước là 1. Điều chuyển 1 bước

* Chọn giao dịch là: NB. Điều chuyển nội bộ

![](<../.gitbook/assets/sb_0 (7).png>)

* Khai báo các thông tin chung: mã kho xuất, diễn giải, ngày chứng từ, trạng thái,…
* Khai báo tab Chi tiết: mã sản phẩm, **Mã kho nhập,** số lượng,...
* Lý do nhập xuất: chọn lý do xuất kho được khai báo ở Danh mục lý do nhập xuất.
* Tài khoản nợ: chương trình ngầm định theo tài khoản được khai báo trong Lý do nhập xuất (nếu có), được phép sửa lại. Trường hợp không muốn tạo bút toán hạch toán trong nghiệp vụ này thì nhập Tài khoản nợ = Tài khoản có.
* Tài khoản có: ngầm định theo mã hàng khai báo ở **Danh mục vật tư, sản phẩm** . Trường hợp muốn sửa lại tài khoản này thì trong Danh mục hàng hóa, vật tư phải tích chọn ô **Sửa tài khoản vật tư**.
* Khai báo thêm File đính kèm ( nếu có).
* Nhấn vào Lưu.
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

1. Số bước là: 2. Điều chuyển 2 bước

* Chọn giao dịch là: NB. Điều chuyển nội bộ

![](<../.gitbook/assets/sb_1 (18).png>)

* Khai báo các thông tin chung: mã kho xuất, diễn giải, ngày chứng từ, trạng thái,…
* Khai báo tab Chi tiết: mã sản phẩm, **Mã kho nhập,** số lượng,...
* Lý do nhập xuất: chọn lý do xuất kho được khai báo ở Danh mục lý do nhập xuất.
* Tài khoản nợ: chương trình ngầm định theo tài khoản được khai báo trong Lý do nhập xuất (nếu có), được phép sửa lại. Trường hợp không muốn tạo bút toán hạch toán trong nghiệp vụ này thì nhập Tài khoản nợ = Tài khoản có.
* Tài khoản có: ngầm định theo mã hàng khai báo ở **Danh mục vật tư, sản phẩm** . Trường hợp muốn sửa lại tài khoản này thì trong Danh mục hàng hóa, vật tư phải tích chọn ô **Sửa tài khoản vật tư**.
* Khai báo thêm File đính kèm ( nếu có).
* Nhấn vào Lưu.
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

**PHIẾU NHẬP KHO ĐIỀU CHUYỂN**

1. **Hạch toán**

Nợ TK 152,155,156,.. Nguyên liệu, vật liệu; Thành phẩm; Hàng hóa;…

Có TK 151 Hàng mua đang đi trên đường

1. **Các bước thực hiện**

* Vào phân hệ: Kho/ Nhập liệu/ Phiếu nhập điều chuyển chọn biểu tượng Sửa trên thanh công cụ, Phiếu nhập điều chuyển được sinh ra tự động từ Phiếu xuất điều chuyển ( 2 bước).

![](../.gitbook/assets/sb_2.png)

* Trạng thái: hệ thống ngầm định = 0. Lập chứng từ khi tự động sinh ra từ Phiếu xuất điều chuyển ( 2 bước), người dùng cẩn phải cập nhật trạng thái mới “Nhập kho”
* Các thông tin khác: cho phép sửa lại (trừ thông tin Giá, Tiền không được phép do được gán tự động theo Giá, Tiền của Phiếu xuất điều chuyển).
* Khai báo thêm File đính kèm ( nếu có).
* Nhấn vào Lưu.
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

**TÍNH GIÁ XUẤT KHO**

Dùng để khai báo các thông tin tùy chọn xử lý khi tính giá xuất hàng tồn kho theo phương pháp của Doanh nghiệp:

Khai báo chung tại màn hình “Cài đặt khi bắt đầu sử dụng hệ thống”

![](<../.gitbook/assets/sb_3 (6).png>)

1. **Tính giá trung bình tháng**
2. _**Chức năng**_

Dùng để khai báo các thông tin tùy chọn xử lý khi tính giá xuất hàng tồn kho theo phương pháp trung bình tháng.

1. _**Các bước thực hiện**_

Vào phân hệ **Kho/Nhập liệu/ Tính giá trung bình**

![](<../.gitbook/assets/sb_4 (8).png>)

* Tạo phiếu xuất chênh lệch trong trường hợp vật tư không xuất trong kỳ: Chọn Có: tiền chênh lệch khi tính giá xuất (nếu có) sẽ được tạo một chứng từ riêng nếu trong kỳ tính giá không có bất kỳ chứng từ xuất kho nào để cấn trừ.&#x20;
* Cập nhật giá: Tính và cập nhật giá vào kho
* Giá cho từng kho: giá xuất hàng tồn kho sẽ được tính theo từng kho ( mỗi kho 1 giá)
* Giá chung: giá xuất hàng tồn kho sẽ được tính theo tất cả các kho ( tất cả các kho sẽ có chung 1 giá)

Lưu ý: hệ thống ngầm định tuỳ chọn _**Giá cho từng kho**_ theo qui định, người dùng có thể sửa lại cách tính tuỳ vào yêu cầu đặc thù tại mỗi Doanh nghiệp.

1. **Tính giá nhập trước xuất trước**
2. _**Chức năng**_

Dùng để khai báo các thông tin tùy chọn xử lý khi tính giá xuất hàng tồn kho theo phương pháp Tính giá nhập trước xuất trước.

1. _**Các bước thực hiện**_

Vào phân hệ **Kho/Nhập liệu/ Tính giá nhật trước xuất trước**

![](<../.gitbook/assets/sb_5 (4).png>)

* Kỳ/năm : nhập vào kỳ cần tính giá
* Mã vật tư/ mã kho: cho phép lọc các đối tượng cần tính
* Cập nhật giá: Tính và cập nhật giá vào kho
* Xem kết quả: Xem kết quả phiếu xuất được lập.

1. **Tính giá đích danh**

Khách hàng check vào ô đích danh trên chứng từ và nhập giá vào trường “giá tồn”.

![](<../.gitbook/assets/sb_6 (7).png>)

1. **Tính giá trung bình di động**
2. _**Chức năng**_

Dùng để khai báo các thông tin tùy chọn xử lý khi tính giá xuất hàng tồn kho theo phương pháp trung bình di động.

1. _**Các bước thực hiện**_

* Khai báo chung tại màn hình “Cài đặt khi bắt đầu sử dụng hệ thống”

1. _**Công thức tính:**_

Giá xuất hàng tồn kho = (Giá trị tồn kho đầu ngày + Giá trị nhập kho trong ngày) / (Số lượng tồn kho đầu ngày + Số lượng nhập kho trong ngày)

![](<../.gitbook/assets/sb_7 (1).png>)

* Tạo phiếu xuất chênh lệch trong trường hợp vật tư không xuất trong kỳ: Chọn Có: tiền chênh lệch khi tính giá xuất (nếu có) sẽ được tạo một chứng từ riêng nếu trong kỳ tính giá không có bất kỳ chứng từ xuất kho nào để cấn trừ.&#x20;
* Cập nhật giá: Tính và cập nhật giá vào kho
* Giá cho từng kho: giá xuất hàng tồn kho sẽ được tính theo từng kho ( mỗi kho 1 giá)

**KIỂM KÊ KHO**

Vào phân hệ: **Tồn kho/ Nhập liệu/ Kiểm kê**

![](../.gitbook/assets/sb_8.png)

Các bước thực hiện:

Bước 1: Tạo Phiếu yêu cầu kiểm kê

Khi có nhu cầu kiểm kê vật tư để biết được tình trạng tồn kho thực tế thì bước đầu tiên phải cập nhật yêu cầu kiểm kê ![](<../.gitbook/assets/sb_9 (1).png>)

* Ngày kiểm kê: Ngày yêu cầu kiểm kê
* Đơn vị: Mã đơn vị cần kiểm kê
* Mã kho: Kiểm trên trên kho nào
* Mã vị trí: Kiểm kê theo mã vị trí
* Mã lô: Kiểm kê theo mã lô hàng
* Diễn giải: Nhập nội dung nhu cầu kiểm kê Trạng thái Kiểm kê hoặc lập chứng từ

Bước 2: Cập nhật kiểm kê

Lọc phiếu yêu cầu kiểm kê cần kiểm

![](../.gitbook/assets/sb_10.png)

Sau khi chọn phiếu yêu cầu chương trình sẽ hiển thị lên nội dung kiểm kê của kho đó, cho biết tình trạng tồn kho thực tế là bao nhiêu

![](<../.gitbook/assets/sb_11 (1).png>)

* Mã kho: Kho được kiểm kê
* Mã vật tư: Danh sách những vật tư được kiểm kê trong kho
* Đvt gốc: Đvt của vật tư được khai báo trong danh mục hàng hóa, vật tư
* Mã vị trí: Mã vị khí kho hàng nếu vị trí có theo dõi tồn kho
* Mã lô: Mã lô hàng nếu lô có theo dõi tồn kho
* Tồn kho thực tế: Số liệu tồn kho thực tế từ dữ liệu nhập xuất trong phần mềm
* Đvt: Đơn vị tính khi kiểm kê, 1 mã vật tư có thể có nhiều đvt
* Sl kiểm kế: Số lượng kiểm kê thực tế, người dùng tự gõ
* Số lượng (Theo dvt gốc): Số lượng sau khi được kiểm kê chương trình sẽ tự động quy
* đổi về đvt gốc

Bước 3: Xử lý chênh lệch số liệu kiểm kê

Khai báo màn hình: Xử lý chênh lệch số liệu kiểm kê

![](../.gitbook/assets/sb_12.png)

* Ngày kiểm kê: Ngày xử lý số liệu kiểm kê
* Tk hàng thừa chờ xử lý: Tài khoản có để hạch toán chứng từ xử lý khi
* kiểm kê tồn kho thừa so với thực tế

**NHẬP TỰ ĐỘNG THÀNH PHẨM TỪ HÓA ĐƠN**

Vào phân hệ**: Tồn kho/ Tiện ích/ Nhập tự động thành phẩm từ hóa đơn**

* Tính năng nhập kho

![](../.gitbook/assets/sb_13.png)

Sau khi kế toán xuất hóa đơn bán hàng, bộ phận kho khi tính giá thành thay vì phải nhập tay phiếu nhập kho thành phẩm từ sản xuất thì tiện ích này hổ trợ tạo phiếu nhập kho tự động từ hóa đơn. Ngày của phiếu nhập là ngày của hóa đơn.

Lưu ý: để dùng được chức năng này thì khi khai báo danh mục vật tư phải nhập đúng loại vật từ là 51 – thành phẩm

**XUẤT TỰ ĐỘNG NGUYÊN VẬT LIỆU**

Vào phân hệ : Tồn kho/ Tiện ích/ Xuất tự động nguyên vật liệu

Khi kế toán đã khai báo định mức NVL ở phân hệ giá thành, thay vì phải làm phiếu xuất kho NVL thủ công thì chức năng cho phép người dùng tạo tự động phiếu xuất kho NVL dựa vào định mức đã khai báo. Tiện ích này nhằm giảm thiếu khá nhiều thời gian nhập liệu vì đôi khi 1 sản phẩm có định mức của rất nhiều vật tư phải làm phiếu xuất kho nhiều dòng.

![](../.gitbook/assets/sb_14.png)

* Ngày từ/ đến: Khoản thời gian cần tạo phiếu xuất kho tự động, ngày của phiếu
* xuất kho sẽ mặc định lấy ngày của phiếu nhập kho thành phẩm
* trong kỳ
* Đơn vị: Mã đơn vị cần tạo phiếu xuất kho
* Mã khách hàng: Tạo phiếu xuất cho khách hàng nào
* Quyển/ Số ct: Quyển chứng từ của phiếu xuất kho
* Tạo: Nếu chọn tạo thì chương trình sẽ tạo phiếu xuất kho tự động/ xóa thì sẽ xóa phiếu xuất kho tự động vừa tạo

**BÁO CÁO TỒN KHO**

Vào Phân hệ : Báo cáo / Tồn kho / Báo cáo tồn kho

Báo cáo thể hiện số tồn kho của tại ngày xem báo cáo, thể hiện số tồn chi tiết theo Mã hàng – Mã kho, mỗi mã hàng tồn kho bao nhiêu kho thì hiện bấy nhiêu dòng. Các tùy chọn trên điều kiện lọc tương tự báo cáo Tổng hợp nhập xuất tồn theo đối tượng.

![](../.gitbook/assets/sb_15.png)

![](../.gitbook/assets/sb_16.png)

**BÁO CÁO XUẤT NHẬP TỒN KHO**

Đường dẫn: Báo cáo / Tồn kho / Tổng hợp nhập xuất tồn theo kho

Báo cáo thể hiện số cân đối tồn kho: Tồn đầu, Số lượng nhập, Số lượng xuất, Tồn cuối trong khoảng từ ngày đến ngày xem báo cáo, thể hiện số liệu chi tiết theo Mã hàng – Mã kho, báo cáo nhóm theo từng kho, mỗi mã hàng phát sinh bao nhiêu kho thì hiện bấy nhiêu dòng. Các tùy chọn trên điều kiện lọc tương tự báo cáo Tổng hợp nhập xuất tồn theo đối tượng.

![](../.gitbook/assets/sb_17.png)

![](../.gitbook/assets/sb_18.png)

**BÁO CÁO KIỂM KÊ**

Đường dẫn: Báo cáo/ Kho/ Báo cáo kiểm kê

Mục đích của báo cáo này thể hiện cho biết số lượng kiểm kê của từng mặt hàng ở từng kho là bao nhiêu, từ đó đưa ra quyết định luân chuyển hàng tồn kho hợp lý nhầm tránh tổn thất về hàng hóa, vật tư, tiết kiệm chi phí lưu kho và dự trù được lượng vốn lưu động cho hàng tồn kho này.

![](../.gitbook/assets/sb_19.png)

![](../.gitbook/assets/sb_20.png)
