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

# \[DONE] Tính giá xuất kho theo phương pháp thực tế đích danh

Phương pháp tính giá xuất kho đích danh được áp dụng dựa trên giá trị thực tế của từng nhập hàng hóa mua vào, từng lần nhập sản xuất hàng hóa thành phẩm.

## Các bước thực hiện

### Khai báo phương pháp tính giá&#x20;

Chương trình cho phép khai báo phương pháp tính giá theo đơn vị cơ sở hoặc vật tư, chọn giá đích danh, khi tính giá trung bình sẽ loại những mã hàng tính giá đích danh khỏi công thức tính nếu doanh nghiệp áp dụng cả hai cách tính giá. Xem cách khai báo [tại đây](done-khai-bao-phuong-phap-tinh-gia.md).

### Nhập liệu phát sinh xuất kho

**Cách 1:** Người dùng chủ động tick đích danh và nhập giá xuất.

Các phát sinh xuất kho ở các loại chứng từ như Phiếu xuất kho, Phiếu xuất điều chuyển, Hoá đơn bán hàng, Phiếu xuất trả lại NCC,…

<figure><img src="../../.gitbook/assets/giá đích danh 2.png" alt=""><figcaption></figcaption></figure>

**Cách 2:** Chọn phiếu nhập đích danh khi nhập liệu

**Bước 1:** Sau khi nhập mã sản phẩm người dùng bấm xem phiếu nhập, chọn chứng từ nhập kho, chương trình sẽ tự gán giá vốn.

<figure><img src="../../.gitbook/assets/giá đích danh 3.png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Sau khi chọn được phiếu nhập giá vốn, người dùng khai báo các thông tin liên quan và bấm lưu

<figure><img src="../../.gitbook/assets/giá đích danh 4.png" alt=""><figcaption></figcaption></figure>

**Lưu ý:**

* Để áp dụng cách 2, người dùng cần khai báo tham số tại đường dẫn _**Hệ thống/ Khai báo tham số/ Tồn kho**_

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

* Các phiếu nhập còn tồn trước khi sử dụng chương trình (tồn theo phiếu nhập đầu kỳ), người dùng tạo các phiếu nhập kho mã giao dịch Nhập khác để hệ thống cập nhật và lưu giá trị khi chọn phiếu nhập.

### Kiểm tra giá tồn kho

_Đường dẫn: **Kho/ Báo cáo/ Báo cáo tồn kho/Thẻ kho, sổ chi tiết vật tư**_

<figure><img src="../../.gitbook/assets/giá đích danh 5.png" alt=""><figcaption></figcaption></figure>

