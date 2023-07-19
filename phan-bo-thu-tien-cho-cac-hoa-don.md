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

# Phân bổ thu tiền cho các hóa đơn

## 1.      Chức năng

Phân bổ hóa đơn được dùng trong trường hợp thu tiền theo khách hàng chưa trực tiếp cho hóa đơn nào, sau đó thực hiện phân bổ cho hóa đơn để cấn trừ trực tiếp cho hóa đơn. Chức năng này chỉ lọc ra Phiếu thu nào có Loại là Thu theo khách hàng để phân bổ.

## 2.      Các bước thực hiện

* Vào phân hệ **Bán hàng\ Tiện ích\ Phân bổ thu tiền cho các hoá đơn.**&#x20;

<figure><img src=".gitbook/assets/sb_2 (35).png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin trên mà hình điều kiện lọc

Giải thích các trường màn hình điều kiện lọc

&#x20;         \+       Ngày từ/ đến Lọc theo ngày của phiếu thu.

&#x20;         \+        Mã ngoại tệ Lọc chứng từ thanh toán theo ngoại tệ, để trống chương trình sẽ lấy hết tất cả ngoại tệ.

&#x20;         \+        Mã khách hàng Lọc chứng từ thanh toán của khách hàng chỉ định, để trắng chương trình sẽ lấy của tất cả khách hàng.

&#x20;         \+        Tài khoản Lọc chứng từ thanh toán của theo tài khoản, để trắng chương trình sẽ lấy của tất cả tài khoản.

&#x20;        \+        Xử lý Có 3 tùy chọn:

\- Phân bổ tự động theo ngày hoá đơn, số hoá đơn: chương trình sẽ tự bổ các hóa đơn cho các phiếu thu lần lượt từ trên xuống dưới theo nguyên tắc ngày hóa đơn, số hóa đơn.

\- Phân bổ tự động theo hạn thanh toán, số hoá đơn: chương trình sẽ tự bổ các hóa đơn cho các phiếu thu lần lượt từ trên xuống dưới theo nguyên tắc hạn thanh toán, số hóa đơn.

\- Người dùng tự phân bổ: người dùng tự chọn phiếu thu nào sẽ phân bổ cho hóa đơn nào.

<figure><img src=".gitbook/assets/sb_3 (16).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/sb_4 (19).png" alt=""><figcaption></figcaption></figure>
