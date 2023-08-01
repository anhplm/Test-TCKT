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

# \[DONE] Chuyển vật tư hàng hóa giữa các kho nội bộ

## Mô tả nghiệp vụ

Doanh nghiệp có nhiều kho hàng, cần luân chuyển giữa các kho nhằm đáp ứng nhu cầu xuất sản xuất, xuất bán kịp thời hàng mua không về kịp, người dùng sử dụng phiếu xuất điều chuyển để luân chuyển hàng hóa giữa hai kho.

## Định khoản

Nợ TK 152, 155, 156,... Nguyên liệu, vật liệu; Thành phẩm; Hàng hóa,…

Có TK 152, 155, 156,… Nguyên liệu, vật liệu; Thành phẩm; Hàng hóa,…

## **Các bước thực hiện**

Phiếu xuất điều chuyển có hai loại điều chuyển:

* Điều chuyển 1 bước: Điều chuyển không cần xác nhận của bên nhập (1 bước xử lý cả phần xuất và nhập kho). Khi dùng loại này khi lưu chương trình sẽ tự động tăng số lượng ở kho nhập bằng đúng số lượng xuất tại kho xuất.
* Điều chuyển 2 bước: Điều chuyển cần xác nhận của bên nhập (Bước 1 là kho xuất xuất hàng, bước 2 là kho nhập xác nhận số lượng nhập hàng). Khi dùng loại này chương trình sẽ tạo tự động một phiếu nhập điều chuyển ở kho nhập, phiếu nhập tạo tự động ở trạng thái lập chứng từ, thủ kho nhập xác nhận số lượng sau khi nhận đủ hàng thì chuyển trạng thái thành nhập kho, lúc này sẽ tăng số lượng ở kho nhập. Số lượng hàng nhập kho có thể khác với số lượng xuất kho.

#### Phiếu xuất điều chuyển 1 bước

**Bước 1**: Vào phiếu xuất kho theo đường dẫn: _**Kho/ Nhập liệu/Xuất kho nội bộ/ Phiếu xuất điều chuyển**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn số bước là **Điều chuyển 1 bước** và loại giao dịch là **Điều chuyển nội bộ** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Phiếu xuất điều chuyển.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng xuất kho hủy hàng theo mã đối tượng chung của doanh nghiệp.
* Khai báo các thông tin chung: mã kho xuất, diễn giải, ngày chứng từ, trạng thái,…
* Khai báo tab Chi tiết: Mã sản phẩm, **Mã kho nhập,** số lượng,...
* Lý do nhập xuất: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người xuất kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản nợ. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản nợ. Chương trình cho phép khai báo lý do xuất và tài khoản nợ mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* Khai báo thêm File đính kèm ( nếu có).

**Bước 4**: Nhấn vào **Lưu** để lưu phiếu.

**Bước 5**: Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

#### Phiếu xuất điều chuyển 2 bước

**Bước 1, 2, 3, 4, 5:** Bên xuất thực hiện các thao tác tạo phiếu xuất điều chuyển 2 bước tương tự như điều chuyển 1 bước. Lưu ý số bước chọn là **2. Điều chuyển 2 bước.**

<figure><img src="../../.gitbook/assets/Phiếu xuất điều chuyển 2.png" alt=""><figcaption></figcaption></figure>

**Bước 6**: Kho nhập vào phiếu nhập kho theo đường dẫn: _**Kho/ Nhập liệu/Nhập kho nội bộ/ Phiếu nhập điều chuyển,**_ kiểm tra và sửa lại thông tin về sản phẩm, số lượng, ngày nhập (nếu có) và chuyển trạng thái thành nhập kho, bấm lưu để ghi nhận tăng kho.

<figure><img src="../../.gitbook/assets/Phiếu xuất điều chuyển 3.png" alt=""><figcaption></figcaption></figure>

Lưu ý:

* Khi phiếu nhập đã chuyển trạng thái thì không sửa/ xóa phiếu xuất được.

### Báo cáo theo dõi tình hình nhập - xuất điều chuyển

Trong trường hợp doanh nghiệp sử dụng quy trình điều chuyển 2 bước, cần theo dõi quá trình tiếp nhận tại kho nhập và đối chiếu. Báo cáo theo dõi tình hình nhập - xuất điều chuyển sẽ hỗ trợ người dùng biết được phần điều chuyển đã được nhập kho hay chưa, nhập lúc nào, số lượng bao nhiêu. Khi có chênh lệch về số lượng thì yêu cầu giải trình để xử lý (VD trong quá trình vận chuyển có rơi vỡ, hư hỏng,...)

Đường dẫn: _**Kho/ Báo cáo/ Tình hình nhập - xuất kho/ Báo cáo tình hình nhập, xuất điều chuyển**_

<figure><img src="../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>
