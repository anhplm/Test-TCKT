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

# \[Done] Tính và phân bổ công cụ

## **Mô tả nghiệp vụ**

Tài liệu hướng dẫn các bước thao tác để chạy tính phân bổ CCDC hàng kỳ. Đồng thời ghi nhận giá trị phân bổ hạch toán vào sổ cái.

## **Các bước thực hiện**

### **Phân tích các tùy chọn tính phân bổ CCDC**

Để khai báo tính khấu hao CCDC người dùng vào _**Hệ thống/Các tham số tùy chọn và khóa số liệu/Khai báo tham số.**_ Một số tham số tính phân bổ công cụ:

**Bút toán phân bổ chi tiết theo công cụ**

* Chọn **Có:** Khi tính phân bổ và tạo bút toán phân bổ, chương trình sẽ chi tiết giá trị phân bổ từng công cụ, mỗi công cụ sẽ là một bút toán hạch toán.
* Chọn **Không:** Khi tính phân bổ và tạo bút toán phân bổ, chương trình sẽ tính chung tất cả giá trị, bút toán hạch toán được tạo tổng giá trị theo tài khoản chi phí và tài khoản phân bổ công cụ.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 1.png" alt=""><figcaption></figcaption></figure>

**Tính hết giá trị còn lại vào kỳ kết thúc phân bổ**

* Chọn **Có:** Hệ thống sẽ tính giá trị còn lại của công cụ và ghi nhận hết vào kỳ kết thúc phân bổ
* Chọn **Không:** Hệ thống sẽ tính và ghi nhận đúng giá trị phân bổ của kỳ kết thúc phân bổ, phần giá trị còn lại sẽ được ghi nhận ở kỳ sau.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 2.png" alt=""><figcaption></figcaption></figure>

**Tính phân bổ theo ngày**

* Chọn **Có:** Hệ thống sẽ tính giá trị phân bổ của kỳ bắt đầu và kỳ kết thúc theo ngày (từ ngày công cụ đưa vào sử dụng), các kỳ còn lại vẫn khấu hao theo giá trị khấu hao tháng như bình thường. Đối với khai báo giảm công cụ cũng sẽ ghi nhận phần giá trị phân bổ đến ngày khai báo.
* Chọn **Không:** Hệ thống sẽ tính khấu hao theo nguyên tắc tròn kỳ.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 3.png" alt=""><figcaption></figcaption></figure>

### Thao tác tính phân bổ công cụ

**Bước 1:** Vào tính phân bổ công cụ theo đường dẫn: _**Công cụ/ Nhập liệu/ Phân bổ công cụ dụng cụ/ Tính chi phí phân bổ**_

Thao tác này thông thường được thực hiện vào cuối kỳ.&#x20;

<figure><img src="../../.gitbook/assets/phân bổ CCDC 4.png" alt=""><figcaption><p>Màn hình tính chi phí phân bổ</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Mã công cụ: Khi cần tính phân bổ cho một số công cụ, người dùng nhập mã công cụ tại đây, nếu để trắng chương trình sẽ tính phân bổ tất cả công cụ
* Loại công cụ: Khi cần tính cho riêng một loại công cụ, người dùng chọn loại công cụ cần tính.
* Tùy chọn:
  * 1.Phân bổ CCDC: Chương trình sẽ chạy tính phân bổ công cụ của kỳ tính.
  * 0.Xóa phân bổ: Chương trình sẽ xóa kết quả vừa tính, nhưng không xóa điều chỉnh giá trị phân bổ của kỳ tính.
  * 9.Xóa tất cả: Chương trình sẽ xóa kết quả tính phân bổ bao gổm cả các khai báo điều chỉnh giá trị phân bổ tháng.

Kiểm tra kết quả tính phân bổ theo đường dẫn: _**Công cụ/Báo cáo/Phân bổ CCDC/Bảng tính phân bổ CCDC**_

Báo cáo này chi tiết giá trị phân bổ của công cụ, giá trị đã phân bổ và giá trị còn lại của công cụ.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 5.png" alt=""><figcaption></figcaption></figure>

**Bước 2**: Điều chỉnh giá trị phân bổ (Nếu có)

Do một số đặc thù phát sinh của tháng, công cụ hao mòn nhiều hơn hoặc người dùng muốn làm tròn chi phí phân bổ của kỳ, cần điều chỉnh lại giá trị phân bổ chi phí.

**Bước 2.1:** Vào đường dẫn: _**Công cụ/Nhập liệu/Phân bổ CCDC/Điều chỉnh phân bổ tháng,**_ chọn kỳ và năm cần điều chỉnh giá trị phân bổ.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 6.png" alt=""><figcaption></figcaption></figure>

**Bước 2.2:** Trên thanh công cụ nhấn **Sửa** để sửa lại giá trị phân bổ, nhập thông tin thay đổi và nhấn **Lưu**

<figure><img src="../../.gitbook/assets/phân bổ CCDC 7.png" alt=""><figcaption></figcaption></figure>

**Bước 3: Tạo bút toán phân bổ chi phí công cụ**

Bước này dùng kết quả tính và điều chỉnh giá trị phân bổ tháng của CCDC (Thực hiện ở bước 1 và bước 2) để hạch toán chi phí phân bổ vào sổ cái.

**Bước 3.1:** Vào đường dẫn: _**Công cụ /Nhập liệu /Tính phân bổ CCDC /Bút toán phân bổ CCDC.**_

**Bước 3.2:** Nhập điều kiện lọc và nhấn **Đồng ý** để chạy bút toán.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 8.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý:**

* Kỳ từ/đến, Năm: người dùng chọn thời gian để tạo bút toán phân bổ chi phí.
* **Tùy chọn:**
  * 1.Phân bổ: Chương trình sẽ tạo bút toán phân bổ dựa trên kết quả tính phân bổ của kỳ.
  * 0.Xóa phân bổ: Chương trình sẽ xóa bút toán phân bổ.

<figure><img src="../../.gitbook/assets/phân bổ CCDC 9.png" alt=""><figcaption><p>Kết quả tính phân bổ CCDC</p></figcaption></figure>
