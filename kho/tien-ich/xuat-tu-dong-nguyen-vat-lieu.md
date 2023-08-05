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

# Xuất tự động nguyên vật liệu

## Mô tả nghiệp vụ

Chức năng này hỗ trợ việc tự động tạo phiếu xuất kho nguyên vật liệu sản xuất dựa vào số lượng thành phẩm nhập kho và định mức nguyên vật liệu.

## Các bước thực hiện

### Khai báo định mức nguyên vật liệu

Đường dẫn: _**Kế toán/ Giá thành/ Nhập liệu/ Định mức nguyên vật liệu**_

Xem chi tiết cách lập định mức [tại đây](../../gia-thanh/khai-bao-dinh-muc-nguyen-vat-lieu.md).

### Nhập kho thành phẩm

Thành phẩm nhập kho có thể lập từng phiếu [tại đây](../nhap-kho/nhap-kho.md) hoặc [tự sinh từ hóa đơn bán hàng](nhap-tu-dong-thanh-pham-tu-hoa-don.md).

### Xuất tự động nguyên vật liệu

Truy cập chức năng tại đường dẫn _**Kho/ Tiện ích/ Xuất tự động nguyên vật liệu**_

<figure><img src="../../.gitbook/assets/image (103).png" alt=""><figcaption><p>Nhập thông tin tạo phiếu</p></figcaption></figure>

Sau khi chạy tạo Xuất tự động nguyên vật liệu, hệ thống sẽ tự sinh ra các phiếu xuất nguyên vật liệu dựa trên định mức nguyên vật liệu của thành phẩm phiếu nhập.

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

**Các lưu ý:**

* Mã kho xuất nguyên vật liệu được khai báo trong định mức nguyên vật liệu.
* Tài khoản Nợ được khai báo trong danh mục vật tư.
* Hệ thống cho phép khai báo cách thức tạo phiếu xuất tại _**Hệ thống/ Khai báo tham số/ Tồn kho**_
  * Trường hợp mỗi phiếu nhập thành phẩm tạo ra một phiếu xuất NVL tương ứng thì sẽ chọn giá trị là **Theo phiếu nhập.**&#x20;
  * Trường hợp nhiều phiếu nhập trong cùng 1 ngày tạo thành 1 phiếu xuất thì chọn **Theo ngày nhập.** Đây là giá trị mặc định của chương trình.
  * Trường hợp người dùng muốn mỗi ngày - một sản phẩm sẽ tạo ra 1 phiếu xuất thì chọn giá trị **Theo ngày nhập - sản phẩm**.

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

* Hệ thống cho khai báo rã nguyên vật liệu theo 1 cấp hay rã tới cấp cuối cùng. Xem ví dụ sau:

<figure><img src="../../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

Khai báo tại _**Hệ thống/ Khai báo tham số/ Giá thành:**_

<figure><img src="../../.gitbook/assets/image (1) (2).png" alt=""><figcaption></figcaption></figure>
