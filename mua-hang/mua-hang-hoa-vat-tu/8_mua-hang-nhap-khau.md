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

# \[DONE] Mua hàng nhập khẩu

## **Mô tả nghiệp vụ**

Khi mua hàng từ nhà cung cấp nước ngoài, người dùng sử dụng hóa đơn mua hàng nhập khẩu. Chứng từ này có các nghiệp vụ đặc thù riêng của hàng nhập khẩu.

## **Định khoản**

**Hạch toán giá trị hàng nhập mua**:&#x20;

Nợ TK 152, 156, 611 Nguyên liệu, vật liệu; Hàng hóa; Mua hàng&#x20;

Có TK 331 Phải trả cho người bán&#x20;

**Hạch toán thuế nhập khẩu**:&#x20;

Nợ TK 152, 156, 611 Nguyên liệu, vật liệu; Hàng hóa; Mua hàng&#x20;

Có TK 3333 Thuế nhập khẩu&#x20;

**Hạch toán thuế tiêu thụ đặc biệt (nếu có):**&#x20;

Nợ TK 152, 156, 611 Nguyên liệu, vật liệu; Hàng hóa; Mua hàng&#x20;

Có TK 3332 Thuế tiêu thụ đặc biệt&#x20;

**Hạch toán thuế giá trị gia tăng:**&#x20;

Nợ TK 13312 Thuế GTGT được khấu trừ của hàng nhập khẩu&#x20;

Có TK 33312 Thuế GTGT phải nộp hàng nhập khẩu

## **Các bước thực hiện**

**Bước 1:** Lập hóa đơn mua hàng nhập khẩu theo đường dẫn: _**Mua hàng/ Nhập liệu/ Hóa đơn mua vào/ Hóa đơn mua hàng nhập khẩu.**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo 1 chứng từ mới.

**Bước 3:** Nhập các thông tin trên hóa đơn và bấm lưu để lưu lại chứng từ.

Ngoài ra có thể kế thừa thông tin từ đơn hàng đã lập (hướng dẫn thao tác kế thừa [tại đây](../lap-don-hang-mua-trong-nuoc/duyet-don-hang-1.md))

<figure><img src="../../.gitbook/assets/nhập khẩu 01.png" alt=""><figcaption><p>Hóa đơn mua nhập khẩu</p></figcaption></figure>

* Khai báo các thông tin chung: Mã nhà cung cấp, tài khoản có 331, số chứng từ, ngày hạch toán, trạng thái,…
* Số hóa đơn; Ký hiệu; Ngày hóa đơn: Nhập vào thông tin hóa đơn mua hàng từ nhà cung cấp.
* Khai báo tab Chi tiết: Mã hàng, mã kho, số lượng, giá, tiền hàng, tài khoản nợ, ... Lưu ý đối với các loại thuế trên hóa đơn nhập khẩu như sau:
  * Tiền tính thuế nhập khẩu ngoại tệ/ Tiền tính thuế nhập khẩu (VND): nhập vào giá trị tiền hàng dùng để tính thuế nhập khẩu theo quy định (bao gồm cả các chi phí vận chuyển, bảo hiểm).
  * Mã thuế nhập khẩu, mã thuế GTGT: được ngầm định theo vật tư, khai báo trong **Danh mục hàng hóa, vật tư** và được phép sửa lại.
  * Thuế nhập khẩu: được ngầm định = Tiền tính thuế nhập khẩu x Thuế suất thuế nhập khẩu.
  * Thuế tiêu thụ đặc biệt: được ngầm định = (Tiền tính thuế nhập khẩu + Thuế nhập khẩu) x Thuế suất thuế tiêu thụ đặc biệt.
  * Thuế giá trị gia tăng: được ngầm định = (Tiền tính thuế nhập khẩu + Thuế nhập khẩu + Thuế tiêu thụ đặc biệt) x Thuế suất thuế GTGT.
* Khai báo tab Chi phí (nếu có): mã chi phí, tiền,... Xem cách thức phân bổ chi phí mua hàng [tại đây](cach-thiet-lap-tieu-thuc-phan-bo-chi-phi-va-huong-dan-phan-bo-chi-phi-mua-hang.md).
* Khai báo tab Thuế: phục vụ cho việc lên Bảng kê thuế GTGT đầu vào.
