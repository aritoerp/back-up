# 14\_Phân bổ tiền hàng cho các hóa đơn

**PHÂN BỔ TIỀN HÀNG TRẢ CHO CÁC HÓA ĐƠN**

1. **Chức năng**

Phân bổ tiền hàng cho các hóa đơn được dùng trong trường hợp có theo dõi nợ phải trả theo từng hóa đơn và khi trả tiền cho nhà cung cấp chưa trực tiếp chi hóa đơn nào, sau đó thực hiện phân bổ cho hóa đơn để cấn trừ trực tiếp cho hóa đơn. Nhằm ghi giảm số tiền còn phải thanh toán của hóa đơn khi lên báo cáo.

1. **Các bước thực hiện**

* Vào phân hệ **Mua hàng/ Tiện ích/ Phân bổ tiền hàng trả cho các hóa đơn**

![](<../.gitbook/assets/sb_0 (26).png>)

* Ngày từ/ đến: lọc theo ngày chứng từ thanh toán
* Ngoại tệ: nếu có sử dụng đồng tiền ngoại tệ thì lấy lên nếu không có thể để trắng
* Tài khoản:  lọc theo tài khoản công nợ của hóa đơn cần phân bổ, có thể để trắng.
* Mã khách hàng: nếu muốn lọc 1 mã khách cụ thể thì chương trình sẽ lấy lên các chứng từ có cùng 1 mã đối tượng, có thể để trắng.
* Nhóm khách hàng: nếu mã khách hàng có phân nhóm đối tượng thì phần mềm sẽ lọc các mã đối tượng theo nhóm, có thể để trống.
* Đơn vị: chọn đơn vị cần phân bổ hóa đơn.
* Loại chứng từ: gồm các tùy chọn: chưa phân bổ hết, đã phân bổ hết, tất cả.
* Chọn chưa phân bổ hết: thì chỉ lọc lên các chứng từ thanh toán chưa phân bổ hết cho các hóa đơn.
* Chọn đã phân bổ hết thì hiển thị các chứng từ đã phân bổ hết số tiền trên hóa đơn.
* Chọn tất cả: thì sẽ lọc hết các chứng từ thanh toán bao gồm chưa phân bổ hết và đã phân bổ hết.
* Xử lý có 3 tùy chọn:
* Người dùng tự phân bổ: người dùng tự chọn chứng từ và nhập số tiền muốn phán bổ cho các hóa đơn
* Phân bổ tự động theo ngày và số hóa đơn: chương trình sẽ tự phân bổ các chứng từ thanh toán cho các hóa đơn lần lượt từ trên xuống theo nguyên tắc ngày hóa đơn, số hóa đơn, hóa đơn có ngày nhỏ hơn thì phân bổ trước.
* Phân bổ theo hạn thanh toán và số hóa đơn: chương trình sẽ tự phân bổ các chứng từ thanh toán cho các hóa đơn lần lượt từ trên xuống theo nguyên tắc hạn thanh toán và số hóa đơn, hóa đơn nào có hạn thanh toán trước thì phân bổ trước.
* Nhấn **Đồng ý**

_**Màn hình kết quả lọc**_

![](<../.gitbook/assets/sb_1 (38).png>)

* Màn hình phía trên là Danh sách các chứng từ thanh toán, màn hình phía dưới là danh sách các hóa đơn của các mã khách hàng. Khi bấm vào 1 chứng từ ở trên thì màn hình dưới hiện các hóa đơn có cũng mã khách hàng.
* Đối với loại xử lý tự động thì chương trình sẽ check chọn sẵn các hóa đơn ở màn hình bên dưới cho đủ số tiền phân bổ cho chứng từ thanh toán phía trên.
* Tích chọn các chứng từ thanh toán cần phân bổ.
* Nhấn biểu tượng **Lưu phân bổ** trên màn hình.
* Đối với loại xử lý người dụng tự phân bổ thì đứng tại dòng chứng từ thanh toán cần phân bổ ở phía trên sau đó click vào từng hóa đơn bên dưới muốn phân bổ, chỉ cần check chọn hóa đơn chương trình sẽ tự phân bổ số tiền (được phép sửa lại).
* Nhấn biểu tượng **Lưu phân bổ** trên màn hình.
* Trường hợp đã phân bổ sau đó muốn bỏ phân bổ thì click vào nút **Xóa phân bổ** ở màn hình bên dưới.
