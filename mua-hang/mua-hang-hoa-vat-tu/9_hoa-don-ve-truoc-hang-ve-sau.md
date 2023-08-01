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

# \[DONE] Hóa đơn về trước hàng về sau

## Mô tả nghiệp vụ

Nghiệp vụ này xảy ra khi công ty đã nhận được hóa đơn của nhà cung cấp nhưng hàng chưa về nhập kho, khi đó căn cứ vào hóa đơn chứng từ, kế toán sẽ ghi nhận hàng mua đang đi đường. Khi hàng về nhập kho, kế toán làm thủ tục nhập kho và ghi sổ kế toán.

## **Các bước thực hiện**

### **Khi hóa đơn về trước và hàng về trong tháng**

#### Khi nhận hóa đơn

**Bước 1:** Vào phân hệ **Mua hàng/Nhập liệu/Hóa đơn mua vào/Hóa đơn mua hàng trong nước**

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3:** Không tick vào tickbox Phiếu nhập do hàng chưa về, khai các thông tin trên hóa đơn mua.

Định khoản

Nợ TK 151 Hàng mua đang đi trên đường

Nợ TK 1331 Thuế GTGT được khấu trừ của hàng hoá, dịch vụ

Có TK 331 Phải trả cho người bán

<figure><img src="../../.gitbook/assets/Hóa đơn về trước hàng về sau 4 (1).png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: mã nhà cung cấp, tài khoản có, số hóa đơn, ngày hóa đơn, ngày hạch toán, trạng thái,…
* Số hóa đơn; Ký hiệu; Ngày hóa đơn: nhập vào thông tin hóa đơn mua hàng từ nhà cung cấp.
* Khai báo tab Chi tiết: mã hàng, mã kho, số lượng, giá, tiền hàng, tài khoản nợ,…
* Khai báo tab Chi phí (nếu có): mã chi phí, tiền,...
* Khai báo tab Thuế: phục vụ cho việc lên Bảng kê thuế GTGT đầu vào.
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

#### Khi hàng về kho

Nhập hàng về ngay trong tháng, người dùng vào **Hóa đơn mua hàng trong nước** chọn hóa đơn đã nhập trước đó, tick vào tickbox Phiếu nhập, sửa lại định khoản kế toán.

Nợ TK 151 Hàng mua đang đi trên đường **đổi thành** Nợ 152,153,156,... Nguyên liệu, công cụ, hàng hóa.

<figure><img src="../../.gitbook/assets/Hóa đơn về trước hàng về sau 3 (1).png" alt=""><figcaption></figcaption></figure>

### **Khi hóa đơn về trước và hàng về khác tháng**

#### Khi nhận hóa đơn

**Bước 1:** Vào phân hệ **Mua hàng/Nhập liệu/Hóa đơn mua vào/Hóa đơn mua hàng trong nước**

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3:** Khai các thông tin trên hóa đơn mua, có khai báo mã kho đi đường, tick vào phiếu nhập để nhập kho đi đường.

Định khoản

Nợ TK 151 Hàng mua đang đi trên đường

Nợ TK 1331 Thuế GTGT được khấu trừ của hàng hoá, dịch vụ

Có TK 331 Phải trả cho người bán

<figure><img src="../../.gitbook/assets/Hóa đơn về trước hàng về sau.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: mã nhà cung cấp, tài khoản có, số hóa đơn, ngày hóa đơn, ngày hạch toán, trạng thái,…
* Số hóa đơn; Ký hiệu; Ngày hóa đơn: nhập vào thông tin hóa đơn mua hàng từ nhà cung cấp
* Khai báo tab Chi tiết: mã hàng, mã kho, số lượng, giá, tiền hàng, tài khoản nợ,…
* Khai báo tab Chi phí (nếu có): mã chi phí, tiền,...
* Khai báo tab Thuế: phục vụ cho việc lên Bảng kê thuế GTGT đầu vào.
* Nhấn **Lưu**. Chọn biểu tượng In trên thanh công cụ để in chứng từ.

#### Khi hàng về kho

Nhập hàng về khác tháng, người dùng vào **Phiếu xuất điều chuyển** để chuyển hàng từ kho đang đi đường sang kho thực tế, nếu như trước đó hóa đơn mua hàng đã nhập kho đi đường, để ghi nhận tăng số lượng và giá trị tồn kho thực tế.

Nợ TK 152, 156, 611 Nguyên liệu, vật liệu; Hàng hóa; Mua hàng

Có TK 151 Hàng mua đang đi trên đường

**Bước 1:** Vào phân hệ **Kho/Nhập liệu/Xuất kho nội bộ/Phiếu xuất điều chuyển**

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu

**Bước 3**: Chọn loại giao dịch là **Điều chuyển nội bộ** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Hóa đơn về trước hàng về sau 2.png" alt=""><figcaption></figcaption></figure>

* Khai báo thông tin chung: mã kho xuất, mã kho nhập, mã giao dịch, số chứng từ, ngày hạch toán, trạng thái,…
* Khai báo tab Chi tiết: mã sản phẩm, tồn kho, số lượng, giá đích danh, mã kho nhậpt, tài khoản nợ, tài khoản có,…
* Nhấn **Lưu.**
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.
