---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Xác thực hóa đơn điều chỉnh

_**Bước 1: Nhập hóa đơn điều chỉnh**_

* Vào chọn các chứng từ điều chỉnh tiền trên phần mềm để nhập liệu **(Hóa đơn điều chỉnh giá hàng bán; Hóa đơn dịch vụ trả lại, giảm giá…)**
* Vào phân hệ **Mua hàng/ Hóa đơn Điều chỉnh giá hàng bán,** nhấn **Thêm** để tạo chứng từ mới.
* Chọn loại hóa đơn: **1. Giảm giá, 2. Tăng giá**

<figure><img src=".gitbook/assets/sb_1 (25).png" alt=""><figcaption></figcaption></figure>

* Điều chỉnh cho hóa đơn nào thì kế thừa số liệu từ hóa đơn đó. Mỗi chứng từ điều chỉnh chỉ được điều chỉnh cho 1 hóa đơn.
* Khi nhập liệu, chứng từ điều chỉnh phải được kế thừa số liệu từ các hoá đơn đã được phát hành trước đó (tức Tình trạng = 2 – Đã xác thực) và chỉ được phép kế thừa từ một hoá đơn. Hệ thống sẽ cảnh báo và không phát hành đối với các chứng từ nhập liệu không chỉ rõ cho hoá đơn đã xác thực nào.
* Nhấn **Lưu**

_**Bước 2: Xác thực hóa đơn điều chỉnh**_

* Vào phân hệ **Bán hàng/ Xác thực hóa đơn điện tử**

<figure><img src=".gitbook/assets/sb_2 (43).png" alt=""><figcaption></figcaption></figure>

* Xử lý: xác thực hóa đơn điều chỉnh tiền
* Lọc ngày chứng từ cần phát hành
* Chọn loại chứng từ cần phát hành. Bao gồm các loại chứng từ được phép phát hành hoá đơn điện tử điều chỉnh sau: (GG1: hóa đơn điều chỉnh giảm giá hàng bán, TL2: hóa đơn dịch vụ trả lại/ giảm giá)
* Mã quyển: chọn mã cần phát hành hóa đơn
* Nhấn **Nhận.**&#x20;

Màn hình kết quả lọc:&#x20;

<figure><img src=".gitbook/assets/sb_3 (18).png" alt=""><figcaption></figcaption></figure>

* Tích chọn hóa đơn cần xác thực rồi nhấn biểu tượng xác thực HDDT và đợi đến khi chương trình thông báo hoàn thành:

<figure><img src=".gitbook/assets/sb_4 (12).png" alt=""><figcaption></figcaption></figure>

* Sau khi phát hành xong, trạng thái HĐĐT của hóa đơn gốc sẽ chuyển sang trạng thái Điều chỉnh. Để xem lịch sử điều chỉnh của hóa đơn thì tại hóa đơn gốc vào tab HĐĐT click vào nút Chứng từ thay thế/điều chỉnh.

<figure><img src=".gitbook/assets/sb_5 (10).png" alt=""><figcaption></figcaption></figure>

* Hóa đơn gốc trên trang tra cứu HĐĐT của đối tác cũng sẽ chuyển sang trạng thái Điều chỉnh. Diễn giải trên hóa đơn điều chỉnh sẽ tự động ghi rõ điều chỉnh cho hóa đơn nào.
