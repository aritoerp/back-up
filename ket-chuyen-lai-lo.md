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

# Kết chuyển lãi lỗ

## 1. **Khai báo bút toán kết chuyển**

Vào phân hệ **Tổng hợp/ Nhập liệu/ Khai báo bút toán kết chuyển**, nhấn **Thêm** để khai báo các bút toán kết chuyển lãi, lỗ.

_**Nguyên tắc: Tài khoản nhận kết chuyển phải là tài khoản chi tiết nhất.**_

![](<.gitbook/assets/sb_0 (21).png>)

_**Giải thích một số trường:**_

Khai báo trường thông tin chung:

* Số thứ tự: số thứ tự ưu tiên thực hiện trước sau cho các bút toán kết chuyển tự động.
* Loại kết chuyển dùng để xác định tài khoản "Nguồn" và tài khoản "Đích" của bút toán kết chuyển. Chọn loại 3. Kết chuyển lãi lỗ (từ tài khoản 911 sang tài khoản 421), hệ thống tự động xác định lãi hoặc lỗ để hạch toán Nợ/Có tương ứng cho các tài khoản. Lưu ý: nhập tài khoản 911 vào trường **Tài khoản nợ**.
* Tài khoản nợ/Tài khoản có nhập vào các tài khoản kết chuyển và nhận kết chuyển theo đúng hạch toán Nợ/Có khi tạo bút toán.
* Chỉ k/c các ps chi tiết: Nếu chọn thông tin này thì chương trình chỉ kết chuyển các phát sinh có chỉ rõ các trường bộ phận, vụ việc (bên dưới check chọn vào trường bộ phận, vụ việc). Các phát sinh không nhập bộ phận, vụ việc sẽ không kết chuyển.

Khai báo các thông tin ở tab Khác:

* Nếu muốn kết chuyển theo bộ phận, vụ việc, hợp đồng, khế ước, … thì check chọn vào các trường đó.
* Nhấn **Lưu.**

## **2. Chạy bút toán kết chuyển**

Vào phân hệ **Tổng hợp/ Bút toán kết chuyển**

![](<.gitbook/assets/sb_1 (52).png>)

Chọn kỳ/ Năm cần tạo bút toán kết chuyển.

Nhấn **Đồng ý.**

* Màn hình hiện các tài khoản cần tạo bút toán kết chuyển:

![](<.gitbook/assets/sb_2 (15).png>)

* Check chọn các bút toán cần chạy kết chuyển, sau đó nhấn vào nút Kết chuyển trên thanh công cụ. Khi kết chuyển chương trình sẽ tự động sinh ra các phiếu hạch toán kết chuyển vào ngày cuối tháng.
* Trường hợp muốn xóa bút toán kết chuyển thì click vào nút Xóa kết chuyển trên thanh công cụ.
