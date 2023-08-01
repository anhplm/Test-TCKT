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

# \[DONE] Điều chỉnh tăng giá trị tài sản cố định

## Mô tả nghiệp vụ

Dùng để điều chỉnh giá trị TSCĐ (nếu có) trong các trường hợp như: đánh giá lại tài sản, lắp ráp thêm...

Khi điều chỉnh tăng, phần giá trị tăng sẽ được cộng thêm vào giá trị còn lại của tài sản và phân bổ cho số kỳ khấu hao còn lại.

## Định khoản

**Trường hợp thay thế, sửa chữa, lắp ráp thêm phụ tùng**

Nợ TK 211 TSCĐ hữu hình

Nợ TK 133 Thuế GTGT được khấu trừ

Có TK 331 Phải trả người bán

**Trường hợp đánh giá lại tài sản, giá trị còn lại tăng**

Nợ TK 211, 213, 217&#x20;

Có TK 214 Hao mòn TSCĐ

Có TK 412 Chênh lệch đánh giá lại tài sản

## Các bước thực hiện

**Bước 1:** Lập chứng từ điều chỉnh&#x20;

* Phiếu kế toán: _**Tổng hợp/ Nhập liệu/ Hạch toán/ Phiếu kế toán**_. Dùng trong trường hợp: Định giá lại tài sản
* Hóa đơn mua dịch vụ: _**Mua hàng/ Nhập liệu/ Hóa đơn mua vào/ Hóa đơn mua dịch vụ**_. Dùng trong trường hợp: Thay thế, sửa chữa, lắp ráp thêm phụ tùng,...

<figure><img src="../../.gitbook/assets/image (126).png" alt=""><figcaption><p>Hóa đơn mua dịch vụ</p></figcaption></figure>

**Bước 2:** Vào màn hình điều chỉnh giá trị theo đường dẫn: _**Tài sản/ Khai báo tăng/giảm TSCĐ/ Điều chỉnh TSCĐ.**_

**Bước 3:** Nhập điều kiện lọc mã điều chỉnh, có thể không nhập điều kiện lọc thì sẽ hiện tất cả mã điều chỉnh.

<figure><img src="../../.gitbook/assets/điều chỉnh giá trị TSCĐ 02.png" alt=""><figcaption><p>Nhập điều kiện lọc</p></figcaption></figure>

**Bước 4:** Chọn nút **Thêm** trên thanh công cụ để thêm mới phiếu.

**Bước 5:** Nhập các thông tin trên phiếu và nhấn **Lưu**.

<figure><img src="../../.gitbook/assets/điều chỉnh giá trị TSCĐ 03.png" alt=""><figcaption><p>Nhập thông tin điều chỉnh tăng</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Khi chọn mã tài sản, chương trình sẽ hiện số kỳ khấu hao còn lại.
* Chọn mã lý do tăng và nhập kỳ, ngày thay đổi.
* Số chứng từ: Nhập số chứng từ liên quan.
* Nguyên giá: là giá trị điều chỉnh tăng. Sau khi nhập nguyên giá, chương trình sẽ tính giá trị khấu hao điều chỉnh (giá trị khấu hao phần tăng) và giá trị khấu hao sau điều chỉnh (giá trị khấu hao trước khi điều chỉnh + giá trị khấu hao điều chỉnh).

**Ví dụ:**

* Tài sản: Xe tải có nguyên giá 500.000.000đ. Ngày bắt đầu tính khấu hao là ngày 01/02/2022.
  * Số kỳ khấu hao 36 tháng
  * Giá trị khấu hao 1 kỳ là 13.888.889đ.&#x20;
* Tại thời điểm điều chỉnh ngày 22/05/2023.
  * Số kỳ khấu hao còn lại là 21 tháng, giá trị điều chỉnh tăng là 66.000.000đ.
  * Giá trị khấu hao điều chỉnh 1 kỳ = 66.000.000 / 21 = 3.142.857
  * \=> Giá trị khấu hao sau điều chỉnh = 13.888.889 + 3.142.856 = 17.031.746
