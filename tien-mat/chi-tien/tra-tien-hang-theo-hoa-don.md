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

# \[DONE] Trả tiền hàng theo hóa đơn

## Mô tả nghiệp vụ

Khi người dùng có theo dõi chi tiết công nợ theo hoá đơn mua hàng, cần thanh toán tiền và cấn trừ đích danh cho hoá đơn đang còn công nợ thì dùng chức năng này.

## Định khoản

Nợ TK 331 Phải trả cho người bán

Có TK 111 Tiền mặt (1111, 1112)

## Các bước thực hiện

**Bước 1:** Vào đường dẫn **Tiền mặt/ Nhập liệu/ Phiếu chi**

**Bước 2:** Trên thanh công cụ nhấn **Thêm** để tạo mới chứng từ

**Bước 3:** Chọn Loại phiếu chi **1. Chi theo hoá đơn.** Nhập thông tin và nhấn **Lưu**

Có thể chọn từng hoá đơn hoặc chọn đồng loạt nhiều hoá đơn, chương trình tự gắn nhiều dòng trên chi tiết phiếu.

<figure><img src="../../.gitbook/assets/image (75).png" alt=""><figcaption><p>Phiếu chi tiền</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Phiếu chi tiền</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Khai báo các thông tin chung: địa chỉ, người nhận tiền, diễn giải, tài khoản nợ, số chứng từ, ngày hạch toán, trạng thái,…
* Khai báo thẻ Chi tiết : mã đối tượng, tài khoản có, số tiền thanh toán, loại hóa đơn, id hóa đơn, số HĐ, Ngày HĐ…
* Khi nhấn lưu, hệ thống tự động cấn trừ công nợ giữa phiếu chi tiền và hoá đơn

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.
