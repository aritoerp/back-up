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

# Phân bổ chi phí bán hàng

## **Phân bổ chi phí bán hàng, QLDN, chi phí khác**

Cho phép lập chứng từ phân bổ chi phí bán hàng, quản lý doanh nghiệpvào tài khoản kết quả kinh doanh, tài khoản chi phí chờ kết chuyển khác và chi phí khác cho các công trình, đơn hàng, hợp đồng, đơn vị nhằm xác định được chi phí, lãi lỗ thực tế cho công trình, đơn hàng, hợp đồng, đơn vị.

## **1. Khai báo các bút toán phân bổ tự động**

* _**Đường dẫn**_: Vào phân hệ **Tổng hợp/ Nhập liệu/ Khai báo các bút toán phân bổ**, nhấn **Thêm** để khai báo bút toán.

![](.gitbook/assets/sb_0.png)

**Giải thích một số trường thông tin**:

* Số thứ tự: số thứ tự ưu tiên thực hiện trước sau cho các bút toán phân bổ.
* Loại phân bổ:

Nếu loại phân bổ là 1- Từ tài khoản có sang tài khoản nợ thì kết quả của bút toán sẽ là Ghi Nợ tài khoản nhận phân bổ (tài khoản đích) và ghi Có tài khoản phân bổ (tài khoản nguồn).

Nếu loại phân bổ là 2- Từ tài khoản nợ sang tài khoản có thì kết quả của bút toán sẽ là ghi nợ tài khoản phân bổ (tài khoản nguồn)/ ghi có tài khoản nhận phân bổ (tài khoản đích).

* Tài khoản phân bổ: Số hiệu tài khoản nguồn trong bút toán phân bổ. Tài khoản này có thể khai báo là tài khoản tổng hợp hoặc chi tiết. Tuy nhiên, khi thực hiện, chương trình sẽ chỉ thực hiện phân bổ từ những tài khoản chi tiết thuộc tài khoản tổng hợp.

_**Khai báo tab thông tin chi tiết**_

* Tài khoản nhận phân bổ/Mã vụ việc/Bộ phận/Hợp đồng: nhập các đối tượng nhận phân bổ. Trường **Tài khoản nhận phân bổ** là bắt buộc nhập, riêng các trường khác là không bắt buộc (tuỳ theo yêu cầu nghiệp vụ).
* Danh sách tài khoản nợ/Danh sách tài khoản có: nhập vào các tài khoản cần lấy số phát sinh làm hệ số phân bổ (nếu muốn hệ số tính tự động). Nếu để trắng thì khi thực hiện bút toán phân bổ, người dùng phải tự cập nhập hệ số phân bổ cho các đối tượng nhận phân bổ.
* Riêng cột **Cộng/Trừ** là để xác định dấu của số phát sinh (tức cộng vào hay trừ đi khi tính tổng hệ số từ các cặp định khoản).

_**Khai báo tab khác**_

* Bao gồm các lựa chọn:

1. **Chỉ phân bổ trực tiếp cho các đối tượng khai báo**: nếu chọn loại này thì chương trình chỉ lấy phát sinh của các bộ phận/vụ việc trực tiếp (Bộ phận/Vụ việc có khai báo ở tab Chi tiết) mang đi phân bổ.
2. **Chỉ phân bổ các đối tượng trung gian**: nếu chọn loại này thì chương trình chỉ lấy phát sinh của các bộ phận/vụ việc gián tiếp (bộ phận/vụ việc không có khai báo ở tab Chi tiết) mang đi phân bổ.
3. **Phân bổ cả đối tượng trực tiếp và trung gian**: chương trình lấy cả phát sinh của các bộ phận/vụ việc trực tiếp và gián tiếp mang đi phân bổ.

* Bộ phận/Vụ việc Nếu có check chọn bộ phận/vụ việc thì chương trình sẽ lấy phát sinh của các bộ phận, vụ việc được chọn để mang đi phân bổ. Nếu để trắng thì chương trình sẽ lấy tất cả phát sinh của tài khoản phân bổ để mang đi phân bổ.

![](<.gitbook/assets/sb_1 (61).png>)

* Nhấn **Lưu**.

## **2. Thực hiện bút toán phân bổ**

_**Đường dẫn**_**:** Vào phân hệ **Tổng hợp/ Bút toán tự động cuối kỳ/ Bút toán phân bổ tự động.**

**Màn hình điều kiện lọc:**

<figure><img src=".gitbook/assets/sb_2 (41).png" alt=""><figcaption></figcaption></figure>

* Chọn kỳ/năm cần tạo bút toán phân bổ.&#x20;
* Nhấn **Đồng ý.**

Màn hình hiện các tài khoản cần tạo bút toán phân bổ:

![](<.gitbook/assets/sb_3 (31).png>)

* Nút **Tính hệ số phân bổ**: dùng để tính hệ số phân bổ tự động cho các tài khoản phân bổ có khai báo tiêu chí tính hệ số phân bổ tự động dựa vào các tài khoản khác. Thường thì hệ số sẽ do người dùng tự ghi. Nếu phần mềm tự động tính phân bổ nó sẽ dựa vào các chỉ tiêu mã vụ việc, bộ phân để phân bổ số tiền.
* Nút Sửa **hệ số phân bổ**: dùng để kiểm tra, sửa lại hệ số sau khi hệ thống tự động tính hoặc người dùng tự nhập hệ số (trường hợp không tính tự động).
* **Nút Phân bổ**: tạo các bút toán phân bổ tự động cuối kỳ cho các tài khoản được chọn. Lưu ý: chỉ thực hiện sau khi đã tính hoặc nhập hệ số đầy đủ.
* Nút **Xoá phân bổ**: xoá các bút toán phân bổ đã được tạo trước đó.
* **In** chứng từ hạch toán (lưu sổ): vào phân hệ **Tổng hơp/ Bút toán tự động cuối kỳ/ In các bút toán tự động.**

![](<.gitbook/assets/sb_4 (30).png>)
