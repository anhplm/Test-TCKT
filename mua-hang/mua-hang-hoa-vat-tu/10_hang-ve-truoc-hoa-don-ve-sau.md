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

# \[DONE] Hàng về trước hóa đơn về sau

## Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ hàng về trước, để đảm bảo công tác kế toán phản ánh trung thực và phù hợp với thực tế phát sinh thì kế toán sẽ hạch toán hàng về trước hóa đơn về sau.

## **Các bước thực hiện**

### Tạo phiếu nhập kho hàng hóa về

**Bước 1:** Vào phân hệ **Mua hàng/Nhập liệu/Hóa đơn mua vào/Hóa đơn mua hàng trong nước**&#x20;

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3:** Khai các thông tin trên hóa đơn mua và không tích chọn **hóa đơn** (do hóa đơn về sau)

Hạch toán:

* Nợ 152, 156,.. Vật tư, hàng hóa
* Có 3388 Phải trả khác

<figure><img src="../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

### Xử lý hóa đơn về

#### Hóa đơn về cùng tháng với phiếu nhập

Người dùng vào **Hóa đơn mua hàng trong nước** đã nhập ở bước trên tick vào tickbox Hóa đơn, sửa lại tài khoản có từ 3388 về 3311, cập nhật lại giá, tiền theo hóa đơn và bổ sung thêm số hóa đơn, ngày hóa đơn GTGT đồng thời kê khai thuế bên tab **Thuế.**

<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

#### Hóa đơn về khác tháng với phiếu nhập và không có chênh lệch về giá trị so với khi nhập kho

**Bước 1:** Vào phân hệ _**Tổng hợp/Nhập liệu/Hạch toán/Phiếu kế toán**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu

Hạch toán

N3388 Phải trả khác

Nợ 133 Thuế GTGT đầu ra

Có 331 Phải trả người bán

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

Tab thuế

<figure><img src="../../.gitbook/assets/Hàng về trước hóa đơn về sau 4.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin như: số hóa đơn, ngày hóa đơn, thuế suất, mã nhà cung cấp,...&#x20;

**Bước 3**: Nhấn **Lưu**

#### Hóa đơn về khác tháng với phiếu nhập và không có chênh lệch về giá trị so với khi nhập kho

**Bước 1, 2, 3** tương tự như khi không có chênh lệch.

**Bước 4**: Tạo phiếu [Giảm giá hàng mua](13\_giam-gia-hang-mua-da-nhap-kho.md), chọn loại "Giảm giá" giá nhập kho > giá hóa đơn, loại "Tăng giá" nếu giá nhập kho < giá hóa đơn.

Hạch toán

* Nợ 152, 156 (Phần chênh lệch)
* Có 331

