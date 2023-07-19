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

# Kết nối hóa đơn đầu vào

Hóa đơn đầu vào là hóa đơn điện tử được hiểu là các hóa đơn đơn mua hàng hóa, dịch vụ phục cho nhu cầu sản xuất kinh doanh hoặc hoạt động của doanh nghiệp được lập dưới dạng hóa đơn điện tử. Là phần mềm lưu trữ, cũng như tự động kiểm tra tính hợp lệ của hóa đơn. Giúp tránh rủi ro hóa đơn bị sai sót hoặc giả. Không cần lưu trữ HĐĐT ở dạng giấy mà có thể lưu trữ hóa đơn điện tử dưới dạng điện tử (định dạng XML) khi sử dụng phần mềm HĐĐT đầu vào. Ngay khi hóa đơn được tạo lập trên phần mềm thì dữ liệu đã được lưu trên hệ thống

Phần mềm sẽ cung cấp cho KH AritoID và mail nhận hóa đơn ((có gắn đuôi @dochoadon.com).

<figure><img src=".gitbook/assets/sb_h1.png" alt=""><figcaption></figcaption></figure>

Khi tích chuột vào Hóa đơn đầu vào thì sẽ hiện ra màn hình như sau:

<figure><img src=".gitbook/assets/sb_h2.png" alt=""><figcaption></figcaption></figure>

## 1.      Phân hệ “Công ty” là thông tin mà hóa đơn dựa vào để check tín hợp lệ

Nếu doanh nghiệp muốn thông tin mặc định hóa đơn thay đổi, có thể vào mục Công ty để thay đổi thông tin.

_Lưu ý:_

Chỉ được thay đổi thông tin về mã số thuế, Tên công ty, Địa chỉ. Nếu thay đổi các trường khác (Email nhận HĐ, ĐƠn vị, ID …) thì khi xảy ra lỗi thì Phần mềm không chịu trách nhiệm.

<figure><img src=".gitbook/assets/sb_h3.png" alt=""><figcaption></figcaption></figure>

## 2.      Phân hệ “Hộp thư” sẽ là nơi lưu trữ các mail được gửi đến và nơi lưu trữ này với thời hạn 10 năm.

Thiết lập mail để gửi hóa đơn là để phục vụ cho việc gửi hóa đơn điện tử đã phát hành tới khách hàng. Khi kế toán sử dụng chức năng gửi hóa đơn, chương trình sẽ thực hiện gửi từ địa chỉ email được thiết lập. Phần mềm cung cấp hòm mail tiếp nhận hóa đơn điện tử tập trung – hóa đơn đầu vào được lưu trữ nhất quán (có gắn đuôi @dochoadon.com).

Có 2 cách để tạo hóa đơn đầu vào:

*   Khách hàng sẽ gửi mail và Pwd về email mới thiết lập trong đó phải đính kèm 1 file PDF và 1 file XML để phần mềm đọc được file và duyệt để đưa lên (Quan trọng phải có file XML).

    Thông báo với các đối tác về email mới và báo khách hàng khi xuất hóa đơn thì gửi vào email mới này. Mỗi khi có email hóa đơn mới, thì chương trình sẽ hiển thị thông báo.
* Kết nối với trang tổng cục thuế ([https://hoadondientu.gdt.gov.vn/](https://hoadondientu.gdt.gov.vn/)):

<figure><img src=".gitbook/assets/sb_h4.png" alt=""><figcaption></figcaption></figure>

**Bước 1:** Khách hàng phải có tài khoản để đăng nhập vào trang tổng cục thuế

**Bước 2:** Phần mềm Arito sẽ liên hệ và xử lý lấy dữ liệu về Phần mềm ở phân hệ Hộp Thư. Thời gian xử lý sao lưu dữ liệu về phần mềm theo yêu cầu của khách hàng ít nhất 1 ngày. vd: backup 1 ngày/ lần, 3 ngày/ lần, hoặc 7 ngày/ lần.

_**Lưu ý**_**:** Nếu Quý khách đã chọn kết nối trực tiếp từ tổng cục thuế, thì doanh nghiệp không cần phải gửi thực hiện thao tác gửi mail nữa (tránh trường hợp hao phí số lượng hóa đơn).

<figure><img src=".gitbook/assets/sb_h5.png" alt=""><figcaption></figcaption></figure>

Trường hợp sau này DN muốn kết xuất lại file PDF hay XML để quyết toán thuế, họ có thể dễ dàng vào đây để tải lại.

_**Lưu ý:**_&#x20;

Vì đây là phần mềm lưu trữ và check tính hợp lệ của hóa đơn, NÊN khi mail được gửi vào hệ thống phải luôn có 2 file đi kèm là file dữ liệu hóa đơn XML và bản thể hiện của hóa đơn PDF để phải có đủ link tra cứu và mã tra cứu của NCC HĐĐT. Và hóa đơn điện tử hợp pháp phải có nội dung trong file PDF trùng với các dữ liệu có trong file XML từ thông tin đơn vị bán hàng, tên công ty, mã số thuế … Khi gửi mail thì chương trình đồng bộ lấy dữ liệu từ mail ra màn hình hóa đơn.

Trường hợp KH không thể cung cấp được file XML ở cả 2 trường hợp trên, ARITO sẽ đưa ra giải pháp:

Xin user – pass của trang thuế KH, để hệ thống có thể vào thực hiện lệnh và backup định kỳ 3-7 ngày / 1 lần (nhưng nếu khi vào tài khoản thuế của KH vẫn không có file XML để tải về, thì thông báo cho KH làm việc lại với NCC).

## 3.      Phân hệ “Hóa đơn” sẽ là nơi tập kết các hóa đơn từ mail, để check tính hợp lệ

Sau khi nhận file hóa đơn trên từ hộp thư email, phần mềm tự động phân tích – kiểm tra hóa đơn điện tử đầu vào đã đúng thông tin, kiểm tra thông tin doanh nghiệp với tổng cục thuế báo sai khi phát hiện lỗi.

Đây là hóa đơn hợp lệ:

<figure><img src=".gitbook/assets/sb_h6.png" alt=""><figcaption></figcaption></figure>

Tự động lấy dữ liệu, lưu trữ và kiểm tra tính xác thực của hóa đơn từ địa chỉ mail nhận hóa đơn, hợp lệ à duyệt.

<figure><img src=".gitbook/assets/sb_h7.png" alt=""><figcaption></figcaption></figure>

Phần mềm mặc định tích chọn đồng ý với các thông tin của người bán và người mua.

Hóa đơn này đang báo địa chỉ bên mua (KH) đang có sai sót so với thông tin đã nhập ban đầu. Trường hợp KH đồng ý với địa chỉ xuất hóa đơn này, thì sẽ bấm duyệt.

<figure><img src=".gitbook/assets/sb_h8.png" alt=""><figcaption></figcaption></figure>

&#x20;Chọn tích vào nút Áp dụng cho tất cả các hóa đơn sau này. Nếu tick vào thì sau này, địa chỉ hóa đơn xuất dư Việt Nam phần mềm cũng sẽ tự hiểu là đúng ở lần sau.

Nút tích Tự động duyệt nếu không có thông tin lỗi: Phần mềm tự động check tính hợp lệ của hóa đơn không xảy ra lỗi thì Phần mềm tự động duyệt hóa đơn đó.

* _Tạo chứng từ mới (Chuyển đổi vào phần mềm kế toán)_

Chỉ những hóa đơn ở trạng thái đã duyệt mới tạo được hóa đơn mua hàng trong nước hoặc hóa đơn mua hàng dịch vụ.

1\. Chọn Hóa đơn muốn lập chứng từ _(có thể chọn cùng lúc nhiều Hóa đơn để lập chứng từ hàng loạt bằng cách giữ phím **Ctrl**)._

2\. Nhấn **Lập chứng từ**, chọn loại chứng từ cần lập:

<figure><img src=".gitbook/assets/sb_h9.png" alt=""><figcaption></figcaption></figure>

Trường hợp là hóa đơn mua hàng (trong nước hoặc nhập khẩu) nhập kho, người dùng chỉ thao tác nhập chi tiết, hệ thống sẽ tự kiểm tra tổng tiền và số lượng.

<figure><img src=".gitbook/assets/sb_h10.png" alt=""><figcaption></figcaption></figure>

&#x20;Khách hàng khai báo các thông tin giống với hóa đơn mua hàng của phân hệ kế toán gồm các thông tin chung và các thông tin ở thẻ chi tiết. Nếu như chưa có mã đối tượng hay mã vật tư thì chúng ta tiến hành thêm mới.

Phần mềm tự động hạch toán nếu là hóa đơn mua dịch vụ. Tương tự hóa đơn mua hàng trong nước thì cũng khai báo các thông tin chung và các thông tin thẻ chi tiết. Nếu chưa có mã thì thêm mới.

_Lưu ý_: Chỉ những hóa đơn duyệt thành công mới được link vào Safebooks (giao diện sẽ hiện trạng thái “Về chờ duyệt”).

* Nếu danh mục của Safebooks đã có sẵn và khớp với hóa đơn, HDDV sẽ tự nhảy.
* Nếu muốn tạo phiếu chi luôn từ đây, thì mình tick vào ô chi tiền trên màn hình chứng từ.
* Ngoài ra trong phân hệ hóa đơn còn có các tiện ích như sau:

<figure><img src=".gitbook/assets/sb_h11.png" alt=""><figcaption></figcaption></figure>

* Chức năng lấy dữ liệu từ hóa đơn mới: Khi phần mềm lấy dữ liệu được từ hộp thư mà chưa hiển thị trên hóa đơn thì chúng ta dùng chức năng này để cập nhật lại hóa đơn.
* Chức năng lấy lại dữ liệu hóa đơn: Khi cập nhật dữ liệu từ hộp thư thành công nhưng lại bị ẩn không hiển thị thì chúng ta dùng chức năng này.
* Chức năng tải từ tổng cục thuế: khi mình lấy dữ liệu về nhưng chưa hiển thị ở phần hóa đơn thì chúng ta thực hiện chức năng này. Sau đó, chọn ngày để tải dữ liệu về hóa đơn rồi nhấn Đồng ý để lấy dữ liệu từ tổng cục thuế về phân hệ hóa đơn.

<figure><img src=".gitbook/assets/sb_h12.png" alt=""><figcaption></figcaption></figure>

* &#x20;Chức năng cập nhật trạng thái: Lấy dữ liệu và đã hiển thị trong phân hệ hóa đơn, nhưng thanh trạng thái hiển thị trạng thái “nháp” hoặc để trống thì chúng ta thực hiện chức năng này để cập nhật lại trạng thái.&#x20;

## 4.      Phân hệ bảng kê hóa đơn

Bảng kế hóa đơn là một chứng từ quan trọng, giúp thực hiện kê khai hàng hoá dịch vụ mua vào.]

<figure><img src=".gitbook/assets/sb_h13.png" alt=""><figcaption></figcaption></figure>

* Vào bảng kê hóa đơn
* Khai báo các thông tin điều kiện lọc như đơn vị, ngày từ/ đến của hóa đơn, ngày tạo (từ/ đến), chọn mẫu báo cáo (theo misa, Smart Pro, mẫu chuẩn) tùy theo mong muốn của khách hàng.
* Nhấn Đồng ý.

_Màn hình kết quả như sau:_

<figure><img src=".gitbook/assets/sb_h14.png" alt=""><figcaption></figcaption></figure>

Khách hàng muốn kết xuất ra bảng excel thì nhấn kết xuất dữ liệu trên màn hình.

