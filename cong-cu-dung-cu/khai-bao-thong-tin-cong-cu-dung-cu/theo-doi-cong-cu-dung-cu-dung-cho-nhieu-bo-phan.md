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

# Theo dõi công cụ dụng cụ dùng cho nhiều bộ phận

## Mô tả nghiệp vụ

Tài liệu hướng dẫn khai báo các công cụ dùng chung cho nhiều bộ phận với mỗi bộ phận có hệ số phân bổ chi khí khấu hao khác nhau.

## Các bước thực hiện

### Khai báo thông tin CCDC dùng chung

Hướng dẫn khai báo mới một CCDC [tại đây](./).

### Khai báo hệ số phân bổ CCDC

**Bước 1:** Vào màn hình khai báo hệ số phân bổ CCDC theo đường dẫn: _**Công cụ/ Nhập liệu/ Phân bổ công cụ dụng cụ/ Khai báo hệ số phân bổ CCDC.**_

**Bước 2:** Nhập điều kiện lọc là kỳ muốn phân bổ và nhấn **Đồng ý.**

<figure><img src="../../.gitbook/assets/image01081.png" alt=""><figcaption><p>Chọn kỳ khai báo hệ số</p></figcaption></figure>

**Bước 3:** Chọn nút **Thêm** trên thanh công cụ để thêm mới.

**Bước 4:** Nhập các thông tin trên phiếu và nhấn **Lưu.**

<figure><img src="../../.gitbook/assets/hệ số pb CCDC 01.png" alt=""><figcaption><p>Nhập hệ số phân bổ cho bộ phận</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Công cụ: khi nhập mã công cụ, chương trình sẽ hiện các tài khoản phân bổ và chi phí (có thể sửa các tài khoản này).
* Bộ phận công cụ: nhập bộ phận nhận chi phí phân bổ tài sản dùng chung.
* Nhập hệ số tính phân bổ theo bộ phận.

ví dụ:

Công cụ laptop có giá trị phân bổ hằng tháng là 1.000.000đ

Tháng 01/2023, tài sản này có khai báo hệ số phân bổ khấu hao cho 2 bộ phận:

* Bộ phận BH: Hệ số = 6
* Bộ phận KD: Hệ số = 4

Khi tính khấu hao chương trình sẽ thực hiện theo công thức sau:

* Giá trị khấu hao của BH = 1.000.000 x 6 : (6+4) = 600.000đ
* Giá trị khấu hao của KD = 1.000.000 x 4 : (6+4) = 400.000đ

### Chuyển hệ số phân bổ CCDC đã khai báo sang kỳ sau

Trường hợp công cụ sử dụng cho các bộ phận có hệ số phân bổ không thay đổi và phân cho nhiều kỳ, thì chương trình có tính năng chuyển hệ số phân bổ CCDC sang kỳ sau.

**Bước 1:** Tại kỳ đã khai báo hệ số phân bổ, chọn nút chức năng **Sao chép sang kỳ sau.**

<figure><img src="../../.gitbook/assets/hệ số pb CCDC 03.png" alt=""><figcaption><p>Chọn chức năng sao chép sang kỳ sau</p></figcaption></figure>

**Bước 2:** Chọn kỳ cần chuyển hệ số và nhấn **Đồng ý.**

<figure><img src="../../.gitbook/assets/image (204).png" alt=""><figcaption><p>Nhập kỳ cần chuyển</p></figcaption></figure>

**Lưu ý:**

* Khi chuyển hệ số, chương trình sẽ chuyển tất cả hệ số đã khai báo trong tháng của tất cả công cụ. Nếu không muốn chuyển phần hệ số nào, thì vào màn hình khai báo hệ số lọc theo kỳ chuyển đến và xóa dòng đó.
