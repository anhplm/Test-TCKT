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

# Nhập kho thành phẩm theo lệnh sản xuất

## Mô tả nghiệp vụ

Bán thành phẩm hoặc sản phẩm sau khi sản xuất hoặc thuê gia công ngoài xong sẽ được nhập vào kho để ghi nhận tăng hàng tồn kho. Các phiếu nhập kho thành phẩm cũng là cơ sở để tính giá thành cho sản phẩm.

## Định khoản

Nợ TK 154, 155,… Giá trị bán thành phẩm, thành phẩm nhập kho

Có TK 154 Chi phí sản xuất kinh doanh dở dang

## Các bước thực hiện

Phiếu nhập kho thành phẩm được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu nhập kho theo đường dẫn: _**Kho/ Nhập liệu/ Nhập kho nội bộ/ Phiếu nhập kho**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Kế thừa dữ liệu từ **Lệnh sản xuất** sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Kế thừa từ LSX.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Kế thừa từ LSX 2.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (191).png" alt=""><figcaption><p>Màn hình Phiếu nhập kho đã kế thừa dữ liệu</p></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng nhập kho sản xuất theo khách hàng trên đơn hàng cần sản xuất, theo phân xưởng hoặc theo mã đối tượng chung của doanh nghiệp.
* Thông tin vật tư: Chỉ cần nhập thông tin vật tư, kho và số lượng. Giá sẽ tự động áp khi thực hiện tính giá thành trên phần mềm. (Xem cách thiết lập tính giá thành [tại đây](../../gia-thanh/cach-set-up-tinh-gia-thanh-va-kiem-tra-gia-thanh.md))
* Lý do nhập: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người nhập kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản có. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản có. Chương trình cho phép khai báo lý do nhập và tài khoản có mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thiet-lap-su-dung-chung-tu-so-lieu-bao-cao/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* File đính kèm: Chương trình cho phép người dùng đính kèm file thuộc nhiều định dạng khác nhau.&#x20;

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.

