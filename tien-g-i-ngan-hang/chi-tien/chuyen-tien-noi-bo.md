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

# \[Done] Chuyển tiền giữa các tài khoản ngân hàng

## Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ chuyển tiền từ tài khoản của ngân hàng này sang tài khoản của ngân hàng khác của đơn vị. Hệ thống sẽ tự động sinh Giấy báo có hạch toán đối với tài khoản thụ hưởng, giúp giảm thiểu việc nhập liệu.

## Định khoản

Nợ TK 112 Chi tiết theo tài khoản thụ hưởng

Có TK 112 Chi tiết theo tài khoản chuyển tiền

## Các bước thực hiện

**Bước 1:** Vào đường dẫn _**Tiền mặt/ Nhập liệu/ Giấy báo nợ**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo mới phiếu

**Bước 3:** Chọn Loại phiếu thu: 5**. Chuyển giữa các ngân hàng.** Nhập các thông tin và nhấn **Lưu**

<figure><img src="../../.gitbook/assets/Chuyển tiền nội bộ.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: địa chỉ, người nộp tiền, diễn giải, tài khoản nợ, số chứng từ, ngày hạch toán, trạng thái,…
* Khai báo thẻ Chi tiết: mã đối tượng,số tiền thanh toán,…

Chương trình tự sinh Giấy báo có (phân hệ tiền gửi) có các thông tin tương tự như Giấy báo nợ.

Giấy báo có sẽ không được sửa xóa, muốn điều chỉnh thông tin người dùng điều chỉnh ở giấy báo nợ, chương trình  sẽ cập nhật lại thông tin chứng từ tự sinh này**.**

<figure><img src="../../.gitbook/assets/Chuyển tiền nội bộ 2.png" alt=""><figcaption><p>Giấy báo có tự sinh</p></figcaption></figure>

