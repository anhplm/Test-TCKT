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

# \[DONE] Chi phí mua hàng

Phân bổ chi phí mua tính vào giá trị nhập kho của vật tư, hàng hóa.

Có các cách phân bổ tùy từng tình huống như sau:

* Phân bổ trực tiếp trong hóa đơn mua hàng.
* Phân bổ gián tiếp bằng phiếu nhập chi phí mua hàng.
* Phân bổ gián tiếp bằng hóa đơn mua dịch vụ và phân bổ bằng phiếu nhập chi phí mua hàng.

## Các bước thực hiện

### Danh mục chi phí

Đường dẫn: _**Kế toán/ Danh mục/ Chi phí mua hàng**_

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 01.png" alt=""><figcaption><p>Khai báo danh mục chi phí</p></figcaption></figure>

Nhập các thông tin trên màn hình khai báo. Chọn 1 trong 4 tiêu thức phân bổ gồm:&#x20;

* **Số lượng**: hệ số phân bổ được tính theo số lượng mua của từng mặt hàng.&#x20;
* **Giá trị**: hệ số phân bổ được tính theo giá trị mua của từng mặt hàng.&#x20;
* **Thể tích**: hệ số phân bổ được tính = Thể tích đơn vị x Số lượng mua. Thể tích đơn vị của mặt hàng được khai báo trong Danh mục hàng hóa, vật tư.&#x20;
* **Khối lượng**: hệ số phân bổ được tính = Khối lượng đơn vị x Số lượng mua. Khối lượng đơn vị của mặt hàng được khai báo trong Danh mục hàng hóa, vật tư.

Nếu mã phí này chỉ sử dụng cho một loại chứng từ nhất định, thì có thể chọn mã Chứng từ lấy từ Danh mục chứng từ (các chứng từ khác sẽ không chọn được mã phí này).

## Phân bổ chi phí mua hàng

### Cách 1: Phân bổ trực tiếp trong hóa đơn mua hàng

#### Mô tả nghiệp vụ

Sử dụng trong trường hợp hóa đơn chi phí về cùng lúc với hóa đơn mua hàng.

#### Hạch toán

&#x20;Hạch toán chi phí vào giá vốn hàng nhập mua

Nợ TK 152, 156 Chi phí mua hàng

Nợ TK 133 Thuế GTGT được khấu trừ (nếu có)

Có TK 331 Phải trả cho người bán (NCC chi phí)

#### Các bước thực hiện

**Bước 1**: Truy cập vào đường dẫn: **Kế toán/ Mua hàng/ Nhập liệu/ Hóa đơn mua trong nước (Hóa đơn mua hàng nhập khẩu)**

**Bước 2**: Nhập chi phí trên hóa đơn mua

Sau khi nhập các thông tin trên hóa đơn, vào tab Chi phí để nhập chi phí mua hàng. Trường hợp NCC chi phí khác NCC cung cấp hàng hóa thì nhập mã NCC tại tab chi phí luôn.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 02.png" alt=""><figcaption><p>Nhập chi phí ở tab Chi phí trên hóa đơn mua hàng</p></figcaption></figure>

Vào tab Chi phí chi tiết để xem phân bổ chi tiết chi phí cho từng mã hàng. Có thể sửa số tiền phân bổ chi tiết ở tab này.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 03.png" alt=""><figcaption><p>Xem chi phí phân bổ chi tiết</p></figcaption></figure>

Nếu Số tiền sửa ở tab Chi phí chi tiết lệch với số tiền ở tab Chi phí thì sẽ xuất hiện cảnh báo và không cho lưu phiếu.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 04 (1).png" alt=""><figcaption><p>Hiện cảnh báo và không cho lưu phiếu</p></figcaption></figure>

### Cách 2: Phân bổ bằng phiếu nhập chi phí

#### Mô tả nghiệp vụ

Sử dụng trong các trường hợp sau:

* Hóa đơn chi phí về sau hóa đơn mua hàng.
* Hóa đơn chi phí về cho nhiều hóa đơn mua hàng khác nhau, của các nhà cung cấp khác nhau.

#### Hạch toán

* Hóa đơn chi phí về cùng tháng với hàng hóa
  * Nợ TK 152, 156 Chi phí mua hàng\
    Nợ TK 133 Thuế GTGT được khấu trừ (nếu có)
  * Có TK 331 Phải trả cho người bán (NCC chi phí)
* Hóa đơn chi phí về khác tháng với hàng hóa và hàng hóa còn tồn kho
  * Nợ TK 152, 156 Chi phí mua hàng\
    Nợ TK 133 Thuế GTGT được khấu trừ (nếu có)
  * Có TK 331 Phải trả cho người bán (NCC chi phí)
* Hóa đơn chi phí về khác tháng với hàng hóa và hàng hóa không còn tồn kho
  * Nợ TK 632 Giá vốn hàng bán\
    Nợ TK 133 Thuế GTGT được khấu trừ (nếu có)
  * Có TK 331 Phải trả cho người bán (NCC chi phí)

#### Các bước thực hiện

**Bước 1**: Lập phiếu nhập chi phí mua hàng tại đường dẫn: _**Kế toán/ Mua hàng/ Nhập liệu/ Hóa đơn mua vào/ Phiếu nhập chi phí mua hàng**_ và nhấn **Thêm** để tạo phiếu.

**Bước 2**: Lấy dữ liệu từ các hóa đơn mua hàng cần phân bổ chi phí.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 05.png" alt=""><figcaption><p>Chọn nhà cung cấp dịch vụ vận chuyển</p></figcaption></figure>

Nếu NCC vận chuyển khác với NCC hàng hóa thì nhập lại mã NCC hàng hóa và chọn hóa đơn cần phân bổ chi phí.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 06 (1).png" alt=""><figcaption><p>Các bước chọn hóa đơn cần phân bổ chi phí</p></figcaption></figure>

Sau khi lọc các hóa đơn cần phân bổ, chương trình sẽ hiện chi tiết các dòng vật tư trên hóa đơn. Có thể chọn tất cả hoặc chọn các dòng vật tư muốn phân bổ chi phí.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 06.png" alt=""><figcaption><p>Chọn dòng vật tư cần phân bổ chi phí</p></figcaption></figure>

Sau khi nhấn đồng ý, vào tab Chi phí để nhập các khoản phí.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 08.png" alt=""><figcaption><p>Nhập chi phí</p></figcaption></figure>

Nếu chi phí có phát sinh thuế thì nhập ở tab Thuế.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 09.png" alt=""><figcaption><p>Nhập thuế</p></figcaption></figure>

Vào tab Chi tiết để kiểm tra tất cả các thông tin phân bổ.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 10.png" alt=""><figcaption><p>Thông tin phân bổ chi tiết</p></figcaption></figure>

Nếu hóa đơn chi phí về khác tháng với hàng hóa và hàng hóa không còn tồn kho, khi tính giá vốn hệ thống sẽ tự sinh 1 bút toán tự động hạch toán Nợ 632/ Có 15x.

### Cách 3: Nhập chi phí bằng hóa đơn mua dịch vụ và phân bổ bằng phiếu nhập chi phí mua hàng

#### Mô tả nghiệp vụ

Cách này sử dụng trong trường hợp hóa đơn chi phí về trước và phải ghi nhận công nợ của nhà cung cấp chi phí, hóa đơn mua vật tư hàng hóa về sau và chờ phân bổ sau.

#### Hạch toán

* Khi hóa đơn chi phí về:
  * Nợ TK 335 Chi phí trả trước\
    Nợ TK 133 Thuế GTGT được khấu trừ (nếu có)
  * Có TK 331 Phải trả cho người bán (NCC chi phí)
* Khi lập phiếu phân bổ chi phí mua hàng
  * Nợ TK 152, 156 Chi phí mua hàng
  * Có TK 335 Chi phí trả trước

#### Các bước thực hiện

**Bước 1**: Lập hóa đơn mua dịch vụ khi hóa đơn chi phí về.

Đường dẫn: _**Kế toán/ Mua hàng/ Nhập liệu/ Hóa đơn mua vào/ Hóa đơn mua dịch vụ**_

Nếu có phát sinh thuế thì nhập thêm tab Thuế.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 11.png" alt=""><figcaption><p>Lập hóa đơn mua dịch vụ</p></figcaption></figure>

**Bước 2**: Lập phiếu nhập chi phí khi hàng về tương tư như [cách 2](cach-thiet-lap-tieu-thuc-phan-bo-chi-phi-va-huong-dan-phan-bo-chi-phi-mua-hang.md#cach-2-phan-bo-gian-tiep-bang-phieu-nhap-chi-phi). Thay đổi tài khoản Có thành TK 335 (TK nợ trên hóa đơn mua dịch vụ), không nhập lại thuế.

<figure><img src="../../.gitbook/assets/Thiết lập tiêu thức phân bổ chi phí và phân bổ chi phí 12.png" alt=""><figcaption><p>Lập phiếu nhập chi phí mua hàng để phân bổ chi chí</p></figcaption></figure>
