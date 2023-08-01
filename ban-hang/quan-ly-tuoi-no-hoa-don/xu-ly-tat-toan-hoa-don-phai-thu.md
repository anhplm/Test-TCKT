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

# \[DONE] Xử lý tất toán hóa đơn phải thu

## Mô tả

Chức năng này nhằm mục đích giải quyết tất toán đối với những hoá đơn còn công nợ nhưng không truy thu nữa. Thường áp dụng trong trường hợp hóa đơn còn 1 số tiền nhỏ lẻ không thu nữa.

Chức năng Tất toán sẽ lọc ra các Hóa đơn bán hàng còn dư nợ, sau khi tất toán xong thì chương trình sẽ chuyển trạng thái hoá đơn thành tất toán, phần công nợ còn lại sẽ sinh bút toán hạch toán tự động, đồng thời xử lý giảm công nợ theo khách hàng.

## Hạch toán

Nợ TK 811 Chi phí khác

Có TK 131 Phải thu của khách hàng

## Các bước thực hiện

### Tất toán hóa đơn

**Bước 1:** Lọc các hóa đơn muốn tất toán theo đường dẫn: _**Kế toán/ Bán hàng/ Tiện ích/ Tất toán hóa đơn**_

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải thu 02.png" alt=""><figcaption><p>Nhập điều kiện lọc hóa đơn cần tất toán</p></figcaption></figure>

* Nhập Ngày tất toán là ngày chứng từ của phiếu tất toán.
* Ở trường Tất toán chọn loại Chưa tất toán để lọc các hóa đơn chưa tất toán.

**Bước 2:** Xử lý tất toán hóa đơn

Sau khi nhấn Đồng ý ở màn hình lọc, chương trình sẽ hiện ra danh sách các hóa đơn còn dư nợ.

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải thu 03.png" alt=""><figcaption><p>Các bước tất toán</p></figcaption></figure>

**Các lưu ý:**

* Sau khi nhấn tất toán, chương trình sẽ tự sinh 1 bút toán tất toán hạch toán N811/C131. Tài khoản ghi nhận lỗ khi tất toán được khai báo tại _**Hệ thống/ Tham số tùy chọn/ Kế toán**_

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải thu 01.png" alt=""><figcaption><p>Khai báo tham số </p></figcaption></figure>

### Bỏ tất toán hóa đơn

**Bước 1:** Lọc các hóa đơn cần bỏ tất toán theo đường dẫn: _**Kế toán/ Bán hàng/ Tiện ích/ Tất toán hóa đơn**_

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải thu 04.png" alt=""><figcaption><p>Nhập điều kiện lọc hóa đơn cần bỏ tất toán</p></figcaption></figure>

* Nhập Ngày tất toán là ngày chứng từ của phiếu tất toán.
* Ở trường Tất toán chọn loại Đã tất toán sử dụng tính năng này để lọc các hóa đơn đã tất toán.

**Bước 2:** Xử lý bỏ tất toán hóa đơn

Sau khi nhấn Đồng ý ở màn hình lọc, chương trình sẽ hiện ra danh sách các hóa đơn đã tất toán bằng tính năng này.

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải thu 05.png" alt=""><figcaption><p>Các bước bỏ tất toán</p></figcaption></figure>
