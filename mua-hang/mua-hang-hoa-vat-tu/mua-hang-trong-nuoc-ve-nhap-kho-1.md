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

# \[DONE] Mua hàng trong nước trả tiền ngay

## **Mô tả nghiệp vụ**

Khi mua hàng về nhập kho mà thanh toán ngay cho nhà cung cấp, thì thực hiện thao tác này.

Về mặt xử lý trên phần mềm, vẫn đi qua tài khoản công nợ trung gian và hỗ trợ tính năng tạo phiếu chi ngay từ hóa đơn.

## **Định khoản**

Nợ TK 152, 156: Giá trị hàng nhập kho

Nợ TK 133: Tiền thuế GTGT

**Hóa đơn**

Nợ TK 152, 153, 156, 611: Nguyên liệu, vật liệu; Hàng hóa; Mua hàng

Nợ TK 133: Thuế GTGT được khấu trừ của hàng hoá, dịch vụ

Có TK 331: Phải trả cho người bán

**Phiếu chi/ Báo nợ tạo ngay**

Nợ TK 331: Phải trả cho người bán

Có TK 111, 112: Tiền mặt, tiền gửi ngân hàng

## **Các bước thực hiện**

**Bước 1:** Lập hóa đơn mua hàng trong nước theo đường dẫn: _**Mua hàng/ Hóa đơn mua vào/ Hóa đơn mua hàng trong nước.**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo 1 chứng từ mới.

**Bước 3:** Nhập các thông tin trên hóa đơn và tick chọn nút **Chi tiền.**

<figure><img src="../../.gitbook/assets/mua hàng trong nước 01.png" alt=""><figcaption><p>Hóa đơn mua trong nước</p></figcaption></figure>

* Khai báo các thông tin chung: mã nhà cung cấp, tài khoản có, số hóa đơn, ngày hóa đơn, ngày hạch toán, trạng thái,…
* Số hóa đơn; Ký hiệu; Ngày hóa đơn: nhập vào thông tin hóa đơn mua hàng từ nhà cung cấp.
* Khai báo tab Chi tiết: mã hàng, mã kho, số lượng, giá, tiền hàng, tài khoản nợ,…
* Khai báo tab Chi phí (nếu có): mã chi phí, tiền,...
* Khai báo tab Thuế: phục vụ cho việc lên Bảng kê thuế GTGT đầu vào.
* Khi check vào Chi tiền, chương trình hiện ra tab Thông tin thanh toán mặc định, cho phép người dùng lựa chọn lại.

**Bước 4:** Vào tab **Chứng từ thanh toán** nhập các thông tin để tạo chứng từ thanh toán ngay và nhấn **Lưu.**

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

**Bước 5:** In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.

<figure><img src="../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>
