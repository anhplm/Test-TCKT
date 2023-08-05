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

# Xử lý tất toán hóa đơn phải trả

## Mô tả nghiệp vụ

Chức năng này nhằm mục đích giải quyết tình trạng treo công nợ theo hóa đơn mà trên thực tế các hóa đơn này không còn phải trả. Thường áp dụng khi hóa đơn còn 1 số tiền lẻ nhỏ mà nhà cung cấp không thu nữa.

Chức năng Tất toán sẽ lọc ra các Hóa đơn mua hàng còn dư nợ, sau khi tất toán xong thì chương trình sẽ xử lý giảm công nợ của hóa đơn tương ứng, đồng thời xử lý giảm công nợ theo nhà cung cấp.

## Hạch toán

Nợ TK 331 Phải trả người bán

Có TK 711,... Doanh thu khác

## Các bước thực hiện

### Tất toán hóa đơn

**Bước 1:** Lọc các hóa đơn muốn tất toán theo đường dẫn: _**Kế toán/ Mua hàng/ Tiện ích/ Tất toán hóa đơn**_

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải trả 02.png" alt=""><figcaption><p>Nhập điều kiện lọc hóa đơn cần tất toán</p></figcaption></figure>

Nhập các điều kiện lọc chi tiết khác như Mã khách hàng, số c/từ,… ở tab Chi tiết và tab Khác (nếu có). Ở trường Tất toán chọn loại Chưa tất toán để lọc các hóa đơn chưa tất toán.

**Bước 2:** Xử lý tất toán hóa đơn

Sau khi nhấn Đồng ý ở màn hình lọc, chương trình sẽ hiện danh sách các hóa đơn còn dư nợ.

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải trả 03 (1).png" alt=""><figcaption><p>Các bước tất toán</p></figcaption></figure>

**Các lưu ý:**

* Sau khi nhấn tất toán, chương trình sẽ tự sinh 1 bút toán tất toán hạch toán N331/C711. Tài khoản ghi nhận lãi khi tất toán được khai báo tại _**Hệ thống/ Tham số tùy chọn/ Kế toán**_

<figure><img src="../../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

* Ngày chứng từ của phiếu tất toán theo ngày tất toán trên điều kiện lọc.

### Bỏ tất toán hóa đơn

**Bước 1:** Lọc các hóa đơn cần bỏ tất toán theo đường dẫn: _**Kế toán/ Mua hàng/ Tiện ích/ Tất toán hóa đơn**_

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải trả 04.png" alt=""><figcaption><p>Nhập điều kiện lọc hóa đơn cần tất toán</p></figcaption></figure>

Nhập Ngày tất toán là ngày chứng từ của phiếu tất toán.

Ở trường Tất toán chọn loại Đã tất toán sử dụng tính năng này để lọc các hóa đơn đã tất toán.

**Bước 2:** Xử lý bỏ tất toán hóa đơn

Sau khi nhấn Đồng ý ở màn hình lọc, chương trình sẽ hiện ra danh sách các hóa đơn đã tất toán bằng tính năng này.

<figure><img src="../../.gitbook/assets/Xử lý tất toán phải trả 05.png" alt=""><figcaption><p>Các bước bỏ tất toán</p></figcaption></figure>
