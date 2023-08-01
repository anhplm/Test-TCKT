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

# \[Done] Theo dõi và ghi nhận các khoản phí khi giao dịch ngân hàng

Khi phát sinh khoản phí ở các giao dịch bằng tiền gửi ngân hàng, có thể ghi nhận khoản phí kèm với chứng từ thanh toán để tiện cho việc thao tác và theo dõi của người dùng.

Nghiệp vụ hạch toán phí ngân hàng xảy ra ở trường hợp chuyển thanh toán cho nhà cung cấp hoặc nhận khoản thu từ khách hàng bao gồm phí ngân hàng

## Khai báo hệ thống

Khai báo danh mục phí ngân hàng

Đường dẫn: _**Danh mục/ Ngân hàng/ Phí ngân hàng**_

<figure><img src="../../.gitbook/assets/Phí ngân hàng 01.png" alt=""><figcaption><p>Khai báo danh mục phí ngân hàng</p></figcaption></figure>

## Định khoản

Nợ 64x: Phí ngân hàng

Nợ 133: Thuế GTGT phí ngân hàng

Có 112x: Phí ngân hàng + Thuế&#x20;

## Các bước thực hiện

### Trường hợp 1: Khách hàng chuyển khoản, công ty chịu phí.

#### Định khoản

Nợ 64x/ Có 112x: Phí ngân hàng

Nợ 133/ Có 112x: Thuế GTGT phí ngân hàng

**Bước 1:** Lập giấy báo có theo đường dẫn: _**Tiền gửi/ Nhập liệu/ Giấy báo nợ.**_

**Bước 2:** Sau khi nhập các thông tin trên phiếu, chọn tab **Phí ngân hàng** để khai báo thông tin phí và nhấn **Lưu**.

<figure><img src="../../.gitbook/assets/Phí ngân hàng 02.png" alt=""><figcaption><p>Giấy báo có</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Nhập mã khách hàng: là mã ngân hàng giao dịch.
* Khi nhập Mã chi phí, hệ thống sẽ hiện dữ liệu ở các trường Tài khoản và Thuế suất theo dữ liệu đã khai báo trong danh mục phí ngân hàng.

### Trường hợp 2: Chuyển khoản trả cho nhà cung cấp, công ty chịu phí.

#### Định khoản

Nợ 64x/ Có 112x: Phí ngân hàng

Nợ 133/ Có 112x: Thuế GTGT phí ngân hàng

**Bước 1:** Lập giấy báo nợ theo đường dẫn: _**Tiền gửi/ Nhập liệu/ Giấy báo nợ.**_

**Bước 2:** Sau khi nhập các thông tin trên phiếu, chọn tab **Phí ngân hàng** để khai báo thông tin phí và nhấn **Lưu**.

<figure><img src="../../.gitbook/assets/Phí ngân hàng 03.png" alt=""><figcaption><p>Giấy báo nợ</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Nhập mã nhà cung cấp: là mã ngân hàng giao dịch.
* Khi nhập Mã chi phí, hệ thống sẽ hiện dữ liệu ở các trường Tài khoản và Thuế suất theo dữ liệu đã khai báo trong danh mục phí ngân hàng.
