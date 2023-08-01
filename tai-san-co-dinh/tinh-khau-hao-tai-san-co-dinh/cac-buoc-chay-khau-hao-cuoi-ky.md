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

# \[DONE] Tính và phân bổ khấu hao

## Mô tả nghiệp vụ

Tài liệu hướng dẫn các bước thao tác để chạy tính khấu hao TSCĐ hàng kỳ. Đồng thời ghi nhận giá trị khấu hao hạch toán vào sổ cái.

## Các bước thực hiện

### Các tùy chọn tính khấu hao TSCĐ

Để khai báo các tham số liên quan đến tính khấu hao TSCĐ người dùng vào **Hệ thống/Các tham số tùy chọn và khóa số liệu/Khai báo tham số.** Một số tham số tính khấu hao TSCĐ:

**Bút toán phân bổ khấu hao chi tiết theo tài sản**

* Chọn **Có:** Khi tính khấu hao và tạo bút toán phân bổ, chương trình sẽ chi tiết giá trị khấu hao từng tài sản, mỗi tài sản sẽ là một bút toán hạch toán.
* Chọn **Không:** Khi tính khấu hao và tạo bút toán phân bổ, chương trình sẽ tính chung tất cả giá trị, bút toán hạch toán được tạo tổng giá trị theo tài khoản chi phí và tài khoản khấu hao tài sản.

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb.png" alt=""><figcaption></figcaption></figure>

**Tính hết giá trị còn lại vào kỳ kết thúc khấu hao**

* Chọn **Có:** Hệ thống sẽ tính giá trị còn lại của tài sản và ghi nhận hết vào kỳ kết thúc phân bổ
* Chọn **Không:** Hệ thống sẽ tính và ghi nhận đúng giá trị khấu hao của kỳ kết thúc phân bổ, phần giá trị còn lại sẽ được ghi nhận ở kỳ sau.

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 2.png" alt=""><figcaption></figcaption></figure>

**Tính khấu hao theo ngày**

* Chọn **Có:** Hệ thống sẽ tính giá trị khấu hao của kỳ bắt đầu và kỳ kết thúc theo ngày (từ ngày tài sản đưa vào sử dụng), các kỳ còn lại vẫn khấu hao theo giá trị khấu hao tháng như bình thường. Đối với khai báo giảm tài sản cũng sẽ ghi nhận phần giá trị khấu hao đến ngày khai báo.
* Chọn **Không:** hệ thống sẽ tính khấu hao theo nguyên tắc tròn kỳ.

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 3.png" alt=""><figcaption></figcaption></figure>

### Thao tác tính khấu hao tài sản

**Bước 1:** Vào đường dẫn: _**Tài sản/Nhập liệu/Tính khấu hao TSCĐ/Tính khấu hao tài sản cố định**_

Thao tác này thông thường được thực hiện vào cuối kỳ.&#x20;

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 4.png" alt=""><figcaption><p>Màn hình tham số tính khấu hao</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Mã tài sản: Khi cần tính khấu hao riêng cho một số tài sản, người dùng nhập mã tài sản tại đây, nếu để trắng chương trình sẽ tính khấu hao tất cả tài sản
* Loại tài sản: Khi cần tính cho riêng một loại tài sản, người dùng chọn loại tài sản cần tính.
* **Tùy chọn:**
  * 1.Tính khấu hao: Chương trình sẽ chạy tính khấu hao tài sản của kỳ tính
  * 0.Xóa khấu hao: Chương trình sẽ xóa kết quả vừa tính, nhưng không xóa điều chỉnh giá trị khấu hao của kỳ tính.
  * 9.Xóa tất cả: Chương trình sẽ xóa kết quả tính khấu hao bao gổm cả các khai báo điều chỉnh giá trị khấu hao tháng.

Kiểm tra kết quả tính khấu hao theo đường dẫn: _**Tài sản/Báo cáo/Khấu hao TSCĐ/Bảng tính khấu hao tài sản cố định**_

Báo cáo này chi tiết giá trị khấu hao của tài sản, giá trị đã khấu hao và giá trị còn lại của tài sản.

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 5.png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Điều chỉnh giá trị phân bổ khấu hao (Nếu có)

Do một số đặc thù phát sinh của tháng, tài sản hao mòn nhiều hơn giá trị khai báo hoặc người dùng muốn làm tròn chi phí phân bổ của kỳ, cần điều chỉnh lại giá trị phân bổ khấu hao.

**Bước 2.1:** Vào đường dẫn: _**Tài sản/Nhập liệu/Tính khấu hao TSCĐ/Điều chỉnh khấu hao tháng**_

Chọn kỳ và năm cần điều chỉnh giá trị phân bổ khấu hao

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 8.png" alt=""><figcaption></figcaption></figure>

**Bước 2.2:** Trên thanh công cụ bấm **Sửa** để sửa lại giá trị phân bổ khấu hao, nhập thông tin thay đổi và nhấn **Lưu**

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 9.png" alt=""><figcaption></figcaption></figure>

**Bước 3: Tạo bút toán phân bổ khấu hao tài sản**

Bước này dùng kết quả tính và điều chỉnh giá trị khấu hao tháng của TSCĐ (Thực hiện ở bước 1 và bước 2) để hạch toán chi phí khấu hao vào sổ cái.

**Bước 3.1:** Vào đường dẫn: _**Tài sản/Nhập liệu/Tính khấu hao TSCĐ/Bút toán phân bổ khấu hao tài sản**_

**Bước 3.2:** Nhập điều kiện lọc và nhấn **Đồng ý** để chạy bút toán

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 6.png" alt=""><figcaption><p>Màn hình khai báo chạy bút toán phân bổ</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Kỳ từ/đến, Năm: người dùng chọn khoảng thời gian để tạo bút toán phân bổ khấu hao
* **Tùy chọn:**
  * 1.Phân bổ khấu hao: Chương trình sẽ tạo bút toán phân bổ khấu hao dựa trên kết quả tính khấu hao của kỳ.
  * 0.Xóa phân bổ: Chương trình sẽ xóa bút toán phân bổ.

<figure><img src="../../.gitbook/assets/tính khấu hao tscđ kb 7.png" alt=""><figcaption><p>Kết quả của bút toán phân bổ khấu hao</p></figcaption></figure>

