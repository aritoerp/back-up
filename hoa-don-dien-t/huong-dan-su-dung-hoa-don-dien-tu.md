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

# Hướng dẫn sử dụng hóa đơn điện tử

##

##

## 1.      Khai báo tích hợp hóa đơn điện tử

1.1.  Danh mục quyển hóa đơn điện tử

Đường dẫn: Vào phân hệ **Hệ thống/ Kết nối HĐĐT/ Danh mục quyển hóa đơn điện tử**, nhấn **Thêm** để tạo Danh mục quyển mới.

<figure><img src="../.gitbook/assets/sb_1 (57).png" alt=""><figcaption></figcaption></figure>

* Dùng để khai báo quyển hóa đơn, để khi phát hành hóa đơn điện tử sẽ biết được phát hành của quyển nào? mẫu số, ký hiệu và loại hóa đơn là gì?

<figure><img src="../.gitbook/assets/sb_2 (13).png" alt=""><figcaption></figcaption></figure>

* &#x20;**Mã quyển, tên quyển, tên khác**: Do người dùng tự đặt
* **Mẫu số, ký hiệu, loại hóa đơn**:  Là các thông tin theo quy định.
* Nhấn **Lưu.**

_Sang năm tài chính mới thì phải khai thêm quyển chứng từ theo ký hiệu mới_

_1.2._  Danh mục tài khoản hóa đơn điện tử

Đường dẫn: Vào phân hệ **Hệ thống/ Kết nối HĐĐT/ Danh mục tài khoản hóa đơn điện tử**, nhấn **Thêm** để tạo mới chứng từ.&#x20;

<figure><img src="../.gitbook/assets/sb_3 (30).png" alt=""><figcaption></figcaption></figure>

* Dùng để khai báo tài khoản kết nối giữa phần mềm Safebook và phần mềm hóa đơn điện tử của đối tác cung cấp dịch vụ hóa đơn điện tử.

<figure><img src="../.gitbook/assets/sb_4 (1).png" alt=""><figcaption></figcaption></figure>

* **Mã tài khoản, tên tài khoản, tên khác**: Do người dùng tự đặt, cũng có thể đặt mã và tên theo tên của PM của hóa đơn điện tử.
* **Host**: Là đường link kết nối hóa đơn điện tử mà đối tác cung cấp.
* **Tài khoản, mật khẩu**: Là tài khoản và mật khẩu đăng nhập trang HĐĐT do đối tác cung cấp. Riêng đối với đối tác Bkav thì dùng PartnerGUID/PartnerToken (NCC cấp).
* **Tài khoản 2**: Mã số thuế doanh nghiệp (khai báo đối với đối tác HĐ ĐT Cyberbill)
* **Ký hiệu mặc định**: Ký hiệu hóa đơn của doanh nghiệp (khai ở Danh mục quyển Hóa đơn điện tử mục 1.1)
* **Đối tác**: Nhà cung cấp hóa đơn điện tử
* **Trạng thái xác thực**: Trạng thái khi đẩy hóa đơn lên đối tác HĐ ĐT (Chờ ký: đẩy HĐ lên với trạng thái chờ ký (áp dụng cho KH ký bằng token), Xác thực: đẩy HĐ lên và ký (áp dụng cho KH ký bằng HSM), …)
* **Thông tư**: Thông tư 32, thông tư 78 hoặc tự động
*   **Sử dụng USB Token để ký hóa đơn chờ ký**: áp dụng cho nhà cung cấp HĐ ĐT Cyberbill

    &#x20;    \+ Nếu doanh nghiệp dùng USB Token để ký phát hành HĐ ĐT thì tick vào mục này.

    &#x20;    \+ Nếu doanh nghiệp dùng chữ ký Webservice (CKS HSM) thì không tick.
* Nhấn **Lưu**.

1.3.  Khai báo tài khoản sử dụng hóa đơn điện tử

**Đường dẫn**: Vào phân hệ **Hệ thống/ Kết nối HĐĐT/ Khai báo tài khoản sử dụng hóa đơn điện tử**, nhấn **Thêm** để tạo mới chứng từ.

<figure><img src="../.gitbook/assets/sb_5 (6).png" alt=""><figcaption></figcaption></figure>

* Dùng để khai báo user nào được sử dụng tài khoản hóa đơn điện tử đã khai báo ở mục 1.2.

<figure><img src="../.gitbook/assets/sb_6.png" alt=""><figcaption></figcaption></figure>

* &#x20;**Mã tài khoản**: Là tài khoản kết nối hóa đơn điện tử được khai báo ở mục 1.2.
* **Cấp cho đơn vị**: Là đơn vị cơ sở (chi nhánh). Nếu có khai đơn vị thì chỉ được phép phát hành hóa đơn điện tử ở đơn vị được khai báo, nếu để trắng thì được phát hành ở tất cả các đơn vị.
* **Cấp cho người dùng**: Là user sử dụng phần mềm, nếu khai báo user ở trường này thì chỉ user nào có khai báo thì mới phát hành được hóa đơn điện tử. Còn nếu để trống thì tất cả các user của đơn vị (khai báo ở trường Cấp cho đơn vị) đều phát hành được HĐĐT.
* Nhấn **Lưu**.

## 2.      Phát hành hóa đơn điện tử

2.1.  Phát hành hóa đơn mới

_**Bước 1**: Tạo lập hóa đơn mới trên phần mềm_

Vào phân hệ **Bán hàng/ Hóa đơn bán hàng** (nếu bán hàng hóa) hoặc **Hóa đơn dịch vụ** (nếu bán dịch vụ), nhấn **Thêm** để tạo chứng từ mới.

* Chọn loại hóa đơn là tích chọn vào hóa đơn và phiếu xuất

<figure><img src="../.gitbook/assets/sb_7.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: mã khách, mã giao dịch, tài khoản tiền thu, ngày hạch toán, trạng thái, ngày hóa đơn, số hóa đơn, …
* Khai báo thẻ Chi tiết: mã hàng, mã kho, số lượng, giá bán, tài khoản doanh thu, tài khoản vật tư, tài khoản giá vốn, giá vốn, tiền vốn, …
* Tab hóa đơn điện tử phải để ở trạng thái: đang phát hành

<figure><img src="../.gitbook/assets/sb_8 (3).png" alt=""><figcaption></figcaption></figure>

* Chọn phương thức thanh toán: tiền mặt/ chuyển khoản, đối từ công nợ, …
* Nhấn **Lưu**

_**Bước 2**: Xác thực hóa đơn điện tử_

**Xác thực ngay trên hóa đơn** (dùng cho xác thực từng hóa đơn):  nhấn nút **Phát hành HĐĐT** trên màn hình.

<figure><img src="../.gitbook/assets/sb_9 (3).png" alt=""><figcaption></figcaption></figure>

*   &#x20;Mẫu hoá đơn/Ký hiệu hoá đơn/Số hoá đơn: sau khi phát hành hoá đơn điện tử thành công, hệ thống sẽ tự động cập nhật cho các trường thông tin này.

    **Vào màn hình Xác thực hóa đơn điện tử (dùng để xác thực nhiều hóa đơn cùng lúc)**
* Vào phân hệ _**Bán hàng/ Nhập liệu/ Xác thực hóa đơn điện tử.**_

<figure><img src="../.gitbook/assets/sb_10 (4).png" alt=""><figcaption></figcaption></figure>

Gõ các thông tin ở điều kiện lọc:

* Xử lý: chọn loại xác thực hóa đơn mới (xác thực hóa đơn điều chỉnh tiền, thay thế hóa đơn đã xác thực, hủy hóa đơn đã xác thực)
* Ngày c/từ (từ/ đến): chọn ngày để xác thực hóa đơn
* Loại chứng từ: Chọn loại chứng từ cần phát hành. Bao gồm các loại chứng từ được phép phát hành hoá đơn điện tử mới sau (HD1: Hóa đơn bán, HD2: Hóa đơn dịch vụ, PX2: Phiếu xuất điều chuyển, TL2: hóa đơn dịch vụ trả lại/ giảm giá, TL5: Phiếu xuất trả lại NCC, TL6: hóa đơn dịch vụ trả lại NCC)
* Mã quyển: Chọn mã quyển hoá đơn cần phát hành
* Trạng thái xác thực: chờ phát hành
* Nhấn Đồng ý.

Màn hình kết quả lọc:

<figure><img src="../.gitbook/assets/sb_11 (4).png" alt=""><figcaption></figcaption></figure>

* Xem nội dung hoá đơn trước khi phát hành: chọn chứng từ cần xem và nhấn vào biểu tượng In trên thanh công cụ. Khuyến nghị người dùng sử dụng tính năng này nhằm hạn chế sai sót (nếu có).
* Phát hành hoá đơn điện tử: chọn các chứng từ cần phát hành, nhấn vào biểu tượng Xác thực hóa đơn điện tử trên thanh công cụ và đợi phần mềm thông báo chương trình đã thực hiện xong.

<figure><img src="../.gitbook/assets/sb_12 (4).png" alt=""><figcaption></figcaption></figure>

* Sau khi phát hành xong hàng loạt hóa đơn, chương trình sẽ cập nhật các thông tin _Số hóa đơn, ký hiệu_ và _mẫu hóa đơn_ vào tab HĐĐT của hóa đơn trên phần mềm, đồng thời trường _trạng thái HĐĐT_ sẽ được chuyển sang trạng thái _Chờ ký hoặc Xác thực_ tùy vào Trạng thái xác thực đã chọn ở mục 1. Nếu chờ ký sẽ thực hiện thêm bước ký hóa đơn.

**Ký từng hóa đơn**: view từng hóa đơn cần ký và chọn nút Ký HĐĐT

<figure><img src="../.gitbook/assets/sb_13 (1).png" alt=""><figcaption></figcaption></figure>

**Ký nhiều hóa đơn cùng lúc**: “_Nợ phải thu/ Hóa đơn điện tử/ Khởi tạo, xác thực và thay thế hóa đơn điện tử” và chọn trạng thái xác thực là chờ ký_

* Sau đó tick chọn các hóa đơn cần ký và chọn nút Ký hóa đơn và hóa đơn sau khi ký sẽ chuyển về trạng thái Xác thực

<figure><img src="../.gitbook/assets/sb_15 (1).png" alt=""><figcaption></figcaption></figure>

