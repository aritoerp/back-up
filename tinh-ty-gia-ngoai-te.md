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

# Tính tỷ giá ngoại tệ

## 1. **Khai báo danh mục tài khoản ngoại tệ**

Khai báo phương pháp tính tỷ giá ghi sổ cho các tài khoản có gốc ngoại tệ để hệ thống tính tỷ giá ghi sổ tự động.

_**Đường dẫn:**_ vào **Danh mục/ Đối tượng/ Hệ thống tài khoản,** Nhấn **Thêm** để tạo tài khoản.

![](<.gitbook/assets/sb_0 (28).png>)

**Giải thích 1 số trường:**

* Tài khoản: mã ký hiệu tài khoản không được bao gồm các ký tự đặc biệt (‘\`\~!@#$%^&\*(),;”<>?/\\,\_, và các ký hiệu đặc biệt khác). Ngoài ra, khi tạo các tài khoản con thì ký hiệu tài khoản con phải bao gồm các ký hiệu của tài khoản mẹ.
* Tài khoản mẹ: là tài khoản cấp trên liền kề của tài khoản đang khai báo. Tài khoản mẹ được dùng để tính toán, cộng dồn giá trị từ các tài khoản con khi lên báo cáo.&#x20;
* Ngoại tệ gốc: khai báo đồng tiền gốc của tài khoản.
* Tài khoản theo dõi công nợ: dùng để theo dõi số dư công nợ chi tiết theo từng đối tượng nợ. Để khai báo được các tài khoản theo dõi công nợ thì phải khai báo trước các tài khoản này tại tham số Danh sách tài khoản công nợ phải thu, Danh sách tài khoản công nợ phải trả
* Tài khoản sổ cái: là tài khoản mẹ cấp lớn nhất, dùng để lên Sổ cái theo qui định. Số liệu tài khoản sổ cái sẽ được kế thừa từ số liệu của các tài khoản con cấp thấp hơn.
* Phương pháp tính tỷ giá ghi sổ nợ: dùng để khai báo cho các tài khoản nợ phải trả gốc ngoại tệ, có tham gia tính toán và tạo bút toán chênh lệch tỷ giá tự động từ hệ thống. Các tài khoản khai báo tại trường thông tin này bao gồm: tài khoản công nợ phải trả, tài khoản tiền vay. Có 4 loại PP tính tggs có:
  1. Không tính chênh lệch
  2. Trung bình tháng
  3. Đích danh
  4. Trung bình di động
* Phương pháp tính tỷ giá ghi sổ có: dùng để khai báo cho các tài khoản tài sản gốc ngoại tệ, có tham gia tính toán và tạo bút toán chênh lệch tỷ giá tự động từ hệ thống. Các tài khoản khai báo tại trường thông tin này bao gồm: tài khoản công nợ phải thu, tài khoản tiền, tạm ứng. Có 4 loại PP tính tggs có:
  1. Không tính chênh lệch
  2. Trung bình tháng
  3. Đích danh
  4. Trung bình di động

_**Lưu ý:**_

* Chỉ được phép hạch toán vào tài khoản con cấp chi tiết nhất, hệ thống không cho phép hạch toán vào tài khoản tổng hợp (tài khoản mẹ).
* Các tài khoản khi đã phát sinh nhập liệu (số dư, chứng từ), nếu muốn sửa/xoá mã tài khoản hoặc mở thêm tài khoản cấp con thì chuyển số dư tài khoản qua 1 tài khoản trung gian rồi tiến hành sửa, xóa, thêm mới tài khoản. Sau khi tạo tài khoản mới xong thì chúng ta tiến hành gộp mã tài khoản trung gian lại với tài khoản cần thêm, sửa, xóa.
* Nhấn **Lưu.**

## &#x20;**2. Khai báo danh mục tiền tệ**

_**Đường dẫn:**_ vào **Danh mục/ Kế toán/ Ngoại tệ**, nhấn **Thêm** để khai báo các đơn vị tiền tệ sẽ được sử dụng trong giao dịch.

![](<.gitbook/assets/sb_1 (42).png>)

* **Tài khoản phát sinh chênh lệch nợ, Tài khoản phát sinh chênh lệch có**: dùng để hạch toán tự động các chênh lệch lãi/lỗ tỷ giá cho các giao dịch ngoại tệ phát sinh trong kỳ.
* Khai báo các thông tin cần thiết
* Nhấn **Lưu.**

## **3. Hạch toán ngoại tệ**

* _**TH: Phát sinh công nợ bằng ngoại tệ**_

Vào phân hệ **Bán hàng**, nhấn **Thêm** mới chứng từ

![](<.gitbook/assets/sb_2 (46).png>)

* Khai báo các thông tin chung: mã khách hàng, mã nhân viên, tài khoản nợ, ngoại tệ, số chứng từ…
* Khai báo thẻ chi tiết: mã sản phẩm, Đvt, mã kho, số lượng, tiền hàng, tài khoản có…
* Khai báo thông tin **Loại tiền** và **Tỷ giá** giao dịch thực tế.
* Nhấn **Lưu.**

Vào phân hệ **Mua hàng,** nhấn **Thêm** để tạo mới chứng từ

![](<.gitbook/assets/sb_3 (10).png>)

* Khai báo các thông tin chung: Mã nhà cung cấp, mã nhân viên, tài khoản có, số chứng từ, ngày chứng từ, ngoại tệ…
* Khai báo thẻ chi tiết: mã sản phẩm, đvt, mã kho, mã vị trí (nếu có), số lượng, giá, thuế (nếu có) …
* Khai báo thông tin **Loại tiền** và **Tỷ giá**.
* Nhấn **Lưu.**
* **TH: Trường hợp phát sinh thu ngoại tệ**
* Vào phân hệ **Tiền\ Phiếu thu tiền mặt (Giấy báo có)**, chọn biểu tượng **Mới** trên thanh công cụ.
* Chọn loại phiếu thu **1 – Thu tiền theo hóa đơn.**

![](<.gitbook/assets/sb_4 (28).png>)

* Tỷ giá (thông tin chung): ghi nhận cho **Tài khoản nợ**, nhập vào theo tỷ giá giao dịch thực tế (tỷ giá mua vào của Ngân hàng mở tài khoản).
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.&#x20;

**Lưu ý:** _nghiệp vụ này có thể phát sinh chênh lệch tỷ giá do tài khoản 111, 112 ghi nhận theo tỷ giá giao dịch thực tế và tài khoản 131 ghi nhận theo tỷ giá ghi sổ, khi 2 tỷ giá này khác nhau sẽ tạo ra chênh lệch lãi hoặc lỗ tỷ giá_.&#x20;

_Thanh toán quy đổi: quy đổi về đồng tiền trên hóa đơn. Trường hợp đồng tiền trên hóa đơn và đồng tiền thanh toán giống nhau thì tiền thanh toán qui đổi sẽ được ngầm định gán bằng tiền thanh toán, còn nếu khác nhau thì phải nhập vào tiền thanh toán qui đổi._

* Chọn loại phiếu thu **2 – Thu theo đối tượng**

![](<.gitbook/assets/sb_5 (1).png>)

* Tỷ giá (thông tin chung): ghi nhận cho **Tài khoản nợ**, nhập vào theo tỷ giá giao dịch thực tế (tỷ giá mua vào của Ngân hàng mở tài khoản).
* Tỷ giá ghi sổ (thẻ Chi tiết): ghi nhận cho **Tài khoản có**, hệ thống tự động tính theo phương pháp tính tỷ giá ghi sổ khai báo tại Danh mục tài khoản sau khi **Lưu** phiếu.
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.&#x20;

_**Lưu ý:**_

* Trường hợp áp dụng tỷ giá ghi sổ theo phương pháp đích danh thì người dùng tự nhập vào trường Tỷ giá gs (ở thẻ Chi tiết).
* Đối với các phương pháp tính tỷ giá ghi sổ khác thì hệ thống tự tính, nếu không muốn hệ thống tự tính thì tích chọn ô Sửa tỷ giá ghi sổ ở cuối màn hình và người dùng tự nhập vào Tỷ giá gs.
* Đối với thanh toán chi tiết theo hóa đơn, chênh lệch tỷ giá sẽ được tạo ra giữa tỷ giá giao dịch thực tế của tài khoản tiền và tỷ giá của hóa đơn được chọn thanh toán trong chi tiết.
* **TH: Trường hợp phát sinh chi ngoại tệ**
* Vào phân hệ **Tiền\ Phiếu chi tiền mặt (Giấy báo nợ)**, chọn biểu tượng **Mới** trên thanh công cụ.
* Chọn loại chứng từ: **1. Chi theo hóa đơn**

![](<.gitbook/assets/sb_6 (6).png>)

* Tỷ giá ghi sổ (thông tin chung): ghi nhận cho **Tài khoản có**, hệ thống tự động tính theo phương pháp tính tỷ giá ghi sổ khai báo tại Danh mục tài khoản sau khi **Lưu** phiếu.
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.&#x20;
* Chọn loại chứng từ: **2. Chi theo đối tượng**

![](<.gitbook/assets/sb_7 (6).png>)

* Tỷ giá ghi sổ (thông tin chung): ghi nhận cho **Tài khoản có**, hệ thống tự động tính theo phương pháp tính tỷ giá ghi sổ khai báo tại Danh mục tài khoản sau khi **Lưu** phiếu.
* Tỷ giá ghi sổ (ở thẻ Chi tiết): ghi nhận cho **Tài khoản nợ**, hệ thống tự động tính theo phương pháp tính tỷ giá ghi sổ khai báo tại Danh mục tài khoản sau khi **Lưu** phiếu.
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.&#x20;

## **4. Chạy tính xử lý cuối kỳ**

Mục đích: tính tỷ giá ghi sổ theo phương pháp trung bình tháng, trung bình di động theo ngày, nhập trước xuất trước và tạo lại bút toán chênh lệch tỷ giá cho các phát sinh trong kỳ (do tỷ giá ghi sổ được tính tại thời điểm lập phiếu có thể chỉ là tỷ giá ghi sổ tạm tính do dữ liệu cập nhật vào hệ thống chưa đầy đủ).

_**Công thức tính tỷ giá ghi sổ:**_

![](<.gitbook/assets/sb_8 (1).png>)

Các phương pháp tính tỷ giá ghi sổ sẽ dựa vào phần khai báo ở danh mục tài khoản.

Đối với phương pháp **trung bình di động (theo ngày):** mỗi lần thực hiện chi ngoại tệ bằng tiền mặt, tiền gửi, chương trình sẽ tự động xác định tỷ giá xuất quỹ trên chứng từ chi tiền. Khi nào có phát sinh sửa chữa, thêm, bớt hoặc xóa các khoản thu, chi ngoại tệ, kế toán sẽ thực hiện chức năng **Tính tỷ giá xuất quỹ**, để chương trình tự động tính lại tỷ giá xuất quỹ cho các chứng từ gốc.

* Vào phân hệ **Tiền mặt** hoặc **Tiền gửi**, chọn chức năng **Tính tỷ giá ghi sổ**.

![](.gitbook/assets/sb_9.png)

Giải thích các trường thông tin:

* Kỳ / Năm Kỳ/năm cần tính tỷ giá ghi sổ và tạo chênh lệch.
* Mã ngoại tệ Mã ngoại tệ cần tính tỷ giá ghi sổ
* **Xử lý Có các tùy chọn**

\- Xem bảng tính tỷ giá ghi sổ: chỉ xem kết quả của bảng tính

\- Chỉ tính tỷ giá ghi sổ: tính kết quả tỷ giá ghi sổ của các tài khoản ngoại tệ lưu vào bảng tính, phương pháp tính dựa vào danh mục tài khoản

\- Chỉ áp tỷ giá vào sổ cái: áp tỷ giá tính được vào sổ cái, có các dạng áp như sau:

* Các chứng từ thu, chi nếu có check Sửa tỷ giá ghi sổ thì không áp lại
* Các chứng từ thu chi có check Tạo chênh lệch tỷ giá ngay, chương trình sẽ áp lại tỷ giá cho các chứng từ này và hạch toán lại theo tỷ giá mới
* Các chứng từ thu chi không có check Tạo chênh lệch tỷ giá ngay, chương trình sẽ không áp lại tỷ giá trên chứng từ, nhưng có hạch toán lại theo tỷ giá ghi sổ mới

\- Xóa tỷ giá đã áp vào sổ cái: chương trình sẽ áp lại hạch toán cũ theo dữ liệu nhập trên chứng từ, chỉ có tác dụng cho các chứng từ không có check Tạo chênh lệch tỷ giá ngay

* **Đơn vị cơ sở**: Màn hình điều kiện lọc cho phép chọn các đơn vị cơ sở mà người sử dụng được phân quyền Mới, hoặc Sửa hoặc Xóa để tính tỷ giá. Nếu để trắng không chọn thì chương trình tự động tính cho tất cả các đơn vị cơ sở được phân quyền.
* Nhấn **nhận** chương trình tự động cập nhật lại tỷ giá xuất quỹ vào các chứng từ gốc có liên quan.

**Màn hình kết quả như sau:**

![](<.gitbook/assets/sb_10 (3).png>)

Đối với **phương pháp trung bình tháng (cuối tháng):** mỗi lần thực hiện chi ngoại tệ bằng tiền mặt, tiền gửi, chương trình sẽ không tự động xác định tỷ giá xuất quỹ trên chứng từ chi tiền. Cuối tháng, kế toán sẽ thực hiện chức năng **Tính tỷ giá xuất quỹ**, để chương trình xử lý chênh lệch tỷ giá cho các chứng từ có liên quan.

* Vào phân hệ **Tiền mặt** hoặc **Tiền gửi**, chọn chức năng **Tính tỷ giá ghi sổ**.

![](<.gitbook/assets/sb_11 (2).png>)

* Chọn **Kỳ tính giá xuất quỹ**.
* Tích chọn loại ngoại tệ cần tính tỷ giá xuất quỹ.
* Nhấn **Đồng ý**, chương trình tự động sinh chứng từ xử lý chênh lệch từ việc tính tỷ giá xuất quỹ.

![](<.gitbook/assets/sb_12 (5).png>)

Trong kỳ, **nếu có các chứng từ người dùng cố định (tức đích danh**) tỷ giá ghi sổ (tích vào ô **Sửa tỷ giá ghi sổ** trên chứng từ) thì các chứng từ này sẽ không tham gia áp tỷ giá ghi sổ tự động và sẽ được loại ra khỏi công thức tính tỷ giá ghi sổ.

Vào phân hệ **Tiền mặt** hoặc **Tiền gửi**, chọn phiếu chi (giấy báo nợ) nhấn bấm vào **tab tỷ giá** và tích chọn vào ô **sửa tỷ giá ghi sổ.**

<figure><img src=".gitbook/assets/sb_13 (2).png" alt=""><figcaption></figcaption></figure>
