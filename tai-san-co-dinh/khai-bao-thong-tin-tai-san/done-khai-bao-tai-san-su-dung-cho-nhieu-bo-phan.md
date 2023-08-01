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

# \[DONE] Khai báo tài sản sử dụng cho nhiều bộ phận

Tài liệu hướng dẫn khai báo các tài sản dùng chung cho nhiều bộ phận với mỗi bộ phận có hệ số phân bổ chi khí khấu hao khác nhau.

## Các bước thực hiện

## Khai báo thông tin TSCĐ dùng chung

Hướng dẫn khai  báo mới một TSCĐ [tại đây](mua-va-khai-bao-thong-tin-tai-san-tren-hoa-don-mua-tai-san-co-dinh.md)

### Khai báo hệ số phân bổ khấu hao TSCĐ

**Bước 1:** Vào màn hình khai báo hệ số khấu hao TSCĐ theo đường dẫn: _**Tài sản/ Nhập liệu/ Tính khấu hao TSCĐ/ Khai báo hệ số phân bổ khấu hao TSCĐ**_

**Bước 2:** Nhập điều kiện lọc là kỳ muốn phân bổ và nhấn **Đồng ý.**

<figure><img src="../../.gitbook/assets/image (97).png" alt=""><figcaption><p>Nhập kỳ muốn phân bổ</p></figcaption></figure>

**Bước 3:** Chọn nút **Thêm** trên thanh công cụ để thêm mới khai báo.

**Bước 4:** Nhập các thông tin trên phiếu và nhấn **Lưu.**

<figure><img src="../../.gitbook/assets/hệ số pb TSCĐ 01.png" alt=""><figcaption><p>Nhập hệ số phân bổ cho bộ phận</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Tài sản: khi nhập mã tài sản, chương trình sẽ hiện các tài khoản khấu hao và chi phí (có thể sửa các tài khoản này).
* Bộ phận tài sản: nhập bộ phận nhận chi phí khấu hao tài sản dùng chung
* Nhập hệ số tính khấu hao theo bộ phận.

Ví dụ:

Tài sản Xe xúc đất: giá trị khấu hao hằng tháng là 12.500.000đ

Tháng 01/2023, tài sản này có khai báo hệ số phân bổ khấu hao cho 2 bộ phận:

* Bộ phận DA1: Hệ số = 3
* Bộ phận DA2: Hệ số = 2

Khi tính khấu hao chương trình sẽ thực hiện theo công thức sau:

* Giá trị khấu hao của DA1 = 12.500.000 x 3 : (3+2) = 7.500.000đ
* Giá trị khấu hao của DA2 = 12.500.000 x 2 : (3+2) = 5.000.000đ

### Chuyển hệ số phân bổ TSCĐ đã khai báo sang kỳ sau

Trường hợp tài sản sử dụng cho các bộ phận có hệ số phân bổ khấu hao không thay đổi và phân cho nhiều kỳ, thì chương trình có tính năng chuyển hệ số phân bổ TSCĐ sang kỳ sau.

**Bước 1:** Tại kỳ đã khai báo hệ số phân bổ, chọn nút chức năng **Sao chép sang kỳ sau.**

<figure><img src="../../.gitbook/assets/hệ số pb TSCĐ 03.png" alt=""><figcaption><p>Chọn chức năng sao chép sang kỳ sau</p></figcaption></figure>

**Bước 2:** Chọn kỳ cần chuyển hệ số và nhấn **Đồng ý.**

<figure><img src="../../.gitbook/assets/image104.png" alt=""><figcaption><p>Nhập kỳ chuyển hệ số đến</p></figcaption></figure>

