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

# \[DONE] Khai báo tích hợp hóa đơn điện tử

Hóa đơn điện tử là phân hệ hỗ trợ người dùng đẩy dữ liệu từ phần mềm kế toán lên hệ thống hóa đơn điện tử và thực hiện các tác vụ liên quan.

Để sử dụng được tính năng này cần khai báo tích hợp với các nhà cung cấp HDDT. Phần mềm kế toán ARITO hiện đang kết nối với BKAV, Viettel, VNPT, Cyberbill, Hilo, Softdream, M-Invoice, Vin,...

## Các bước khai báo

### Danh mục quyển hóa đơn điện tử

Dùng để khai báo quyển hóa đơn, để khi phát hành hóa đơn điện tử sẽ biết được phát hành của quyển nào, mẫu số, ký hiệu và loại hóa đơn là gì?

Đường dẫn: _**Hệ thống/ Kết nối HĐĐT/ Danh mục quyển hóa đơn điện tử**_

<figure><img src=".gitbook/assets/Khai báo hóa đơn điện tử 1.png" alt=""><figcaption></figcaption></figure>

Các thông tin khai báo quyển hóa đơn điện tử theo nguyên tắc của TT78:

* **Mẫu số**: Khai báo theo mẫu số đã đăng ký HDDT với cơ quan thuế (1 - Hóa đơn GTGT, 2 - Hóa đơn bán hàng, 6 - Phiếu xuất kho kiêm vận chuyển nội bộ và hàng gửi bán).
* **Ký hiệu**: Khai báo theo ký hiệu đã đăng ký với cơ quan thuế, trong đó lưu ý:
  * C: là ký hiệu có mã cơ quan thuế (không có mã cơ quan thuế là K).
  * 23: 2 số cuối của năm phát hành hóa đơn.
  * T: quyển sử dụng cho hóa đơn điện tử/N: quyển sử dụng cho phiếu xuất kho kiêm vận chuyển nội bộ.
  * AR: là ký tự tự do, do nhu cầu quản lý mà doanh nghiệp có thể tự đặt.
* **Loại hóa đơn**: Khai báo khác nhau đối với các nhà cung cấp HDDT:
  * **BKAV**: Lấy theo ký tự thứ 3 trong ký hiệu.
  * **Các nhà cung cấp khác** **(Viettel, VNPT, Cyberbill, M-Invoice, Hilo, SoftDream, Vin,...)**: Khai báo theo mẫu số.

**Lưu ý**: Sang năm mới, thì phải khai báo thêm quyển với ký hiệu mới. Ví dụ với mã quyển trên C23TAR, hiện tại là năm 2023, sang năm 2024 mới người dùng sẽ khai báo là C24TAR.

### Danh mục tài khoản hóa đơn điện tử

Chức năng này dùng để khai báo tài khoản kết nối giữa phần mềm kế toán và phần mềm hóa đơn điện tử.

Đường dẫn: _**Hệ thống/ Kết nối HĐĐT/ Danh mục tài khoản hóa đơn điện tử**_

<figure><img src=".gitbook/assets/Khai báo hóa đơn điện tử 2.png" alt=""><figcaption></figcaption></figure>

Các thông tin cần khai báo:

* Mã tài khoản, tên tài khoản, tên khác: Do người dùng tự đặt, cũng có thể đặt mã và tên theo tên của PM của hóa đơn điện tử.
* Host: Là đường link kết nối hóa đơn điện tử mà đối tác cung cấp. Host của 1 số nhà cung cấp HĐĐT như sau:
  * **BKAV**: [https://ws.ehoadon.vn/WSPublicEHoaDon.asmx](https://ws.ehoadon.vn/WSPublicEHoaDon.asmx)
  * **Viettel**: [https://api-vinvoice.viettel.vn/services/einvoiceapplication/api/InvoiceAPI](https://api-vinvoice.viettel.vn/services/einvoiceapplication/api/InvoiceAPI)
  * **Cyberbill**: [https://ws1.cyberbill.vn/](https://ws1.cyberbill.vn/)
  * **Softdreams (Easy invoice)**: Host chính là link đăng nhập hệ thống HĐĐT của công ty.
  * **VNPT**: Host chính là link đăng nhập hệ thống HĐĐT của công ty.
  * **HILO**: Host chính là link đăng nhập hệ thống HĐĐT của công ty.
  * **Vin**: Host chính là link đăng nhập hệ thống HĐĐT của công ty.
* Tài khoản/ Mật khẩu: Là tài khoản và mật khẩu đăng nhập trang HĐĐT do đối tác cung cấp. Riêng đối với đối tác Bkav thì dùng PartnerGUID/PartnerToken do BKAV cấp.
* Tài khoản 2: Mã số thuế doanh nghiệp (khai báo đối với đối tác HĐ ĐT Cyberbill, Hilo, VNPT).
* Ký hiệu mặc định: Ký hiệu hóa đơn của doanh nghiệp (Đã khai ở Danh mục quyển Hóa đơn điện tử).
* Đối tác: chọn nhà cung cấp hoá đơn điện tử (VD: Viettel, BKAV, HILO...)
* Trạng thái xác thực: Trạng thái khi đẩy hóa đơn lên đối tác HĐĐT
  * Chờ ký: đẩy HĐ lên với trạng thái chờ ký, áp dụng cho trường hợp ký bằng token.
  * Xác thực: đẩy HĐ lên và ký, áp dụng cho KH ký bằng HSM.
* Sử dụng USB Token để ký thì tick vào ô vuông, nếu sử dụng chữ ký số HSM thì không cần tick vào.

### Khai báo sử dụng tài khoản hóa đơn điện tử

Chức năng này dùng để khai báo đơn vị và user sử dụng tài khoản hóa đơn điện tử đã được khai báo.

Đường dẫn: _**Hệ thống/ Kết nối HĐĐT/ Khai báo tài khoản sử dụng hóa đơn điện tử**_

<figure><img src=".gitbook/assets/Khai báo hóa đơn điện tử 3.png" alt=""><figcaption></figcaption></figure>

Giải thích các trường thông tin:

* Mã tài khoản: Là tài khoản kết nối hóa đơn điện tử được khai báo ở mục 2.
* Cấp cho đơn vị: Là đơn vị cơ sở (chi nhánh). Nếu có khai đơn vị thì chỉ được phép phát hành hóa đơn điện tử ở đơn vị được khai báo, nếu để trắng thì được phát hành ở tất cả các đơn vị.
* Cấp cho người dùng: Là user sử dụng phần mềm, nếu khai báo user ở trường này thì chỉ user nào có khai báo thì mới phát hành được hóa đơn điện tử. Còn nếu để trống thì tất cả các user của đơn vị (khai báo ở trường Cấp cho đơn vị) đều phát hành được HĐĐT.
