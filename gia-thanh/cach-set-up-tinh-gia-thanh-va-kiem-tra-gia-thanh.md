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

# Cách thiết lập tính giá thành

Tài liệu mô tả sơ lược việc phân tích và các bước thực hiện để tính giá thành trên phần mềm.

## Khai báo danh mục

### Đối tượng giá thành

Đối tượng giá thành là việc xác định giá thành của 1 sản phẩm trong doanh nghiệp được xác định như thế nào:

* Theo sản phẩm: Trong kỳ tính giá thành, mỗi sản phẩm chỉ có 1 mức giá duy nhất.
* Theo sản phẩm, lệnh sản xuất: Trong kỳ tính giá thành, 1 sản phẩm ở các lệnh sản xuất khác nhau có thể có giá khác nhau (do chi phí tập hợp cho mỗi lệnh sản xuất khác nhau).
* Theo sản phẩm, bộ phận: Trong kỳ tính giá thảnh, 1 sản phẩm sản xuất ở các bộ phận (công đoạn/ loại hàng) khác nhau có thể có giá khác nhau.
* Theo sản phẩm, lệnh sản xuất, bộ phận: Trong kỳ tính giá thành, 1 sản phẩm ở 1 lệnh sản xuất nhưng sản xuất ở 2 bộ phận khác nhau (mỗi bộ phận sản xuất 1 số lượng nhất định của LSX này) có thể có giá khác nhau.

Khai báo tại đường dẫn: _**Hệ thống/Phân quyền và giới hạn truy cập/Danh sách đơn vị, chi nhánh**_

Chương trình mặc định đối tượng giá thành là sản phẩm, đối tượng bộ phận và lệnh sản xuất, nếu người dùng có tính giá theo hai đối tượng này thì tick thêm.

<figure><img src="../.gitbook/assets/Giá thành 4.png" alt=""><figcaption></figcaption></figure>

### Danh mục công đoạn

Đường dẫn: _**Giá thành/Danh mục công đoạn**_

Sử dụng đối với doanh nghiệp có tính giá thành theo bộ phận (công đoạn sản xuất, nhà máy sản xuất, loại hàng,...). Công đoạn này được chọn từ danh mục bộ phận của kế toán (chỉ khai các bộ phận tham gia vào sản xuất).

* Bộ phận trực tiếp: Tham gia trực tiếp vào giá thành, là 1 đối tượng tính giá.
* Bộ phận gián tiếp: Bộ phận chung dùng để ghi nhận chi phí tham gia vào quá trình sản xuất.

<figure><img src="../.gitbook/assets/Giá thành 3.png" alt=""><figcaption></figcaption></figure>

### Danh mục yếu tố

Đường dẫn: _**Giá thành/Danh mục yếu tố**_

Yếu tố có thể được hiểu là chi phí cấu thành nên thành phẩm, chi phí nguyên vật liệu, chi phí nhân công, chi phí sản xuất chung, các chi phí này tương ứng với một tài khoản theo dõi kế toán.

Các loại chi phí khi tạo phiếu chỉ được chi tiết tới đâu thì danh mục yếu tố sẽ tick tập hợp theo đó. Ví dụ:

* Chi phí NVL chính luôn chỉ được tới sản phẩm và lệnh sản xuất: Tick vào tập hợp theo sản phẩm, tập hợp theo lệnh sản xuất, tập hợp theo NVL.
* Chi phí NVL phụ không chỉ đích danh được cho sản phẩm LSX nào: Không tick vào tập hợp theo sản phẩm, tập hợp theo lệnh sản xuất, chỉ tick tập hợp theo NVL.

<figure><img src="../.gitbook/assets/Giá thành 2.png" alt=""><figcaption></figcaption></figure>

### Khai báo hệ số phân bổ

Đường dẫn: _**Giá thành/Khai báo hệ số phân bổ**_

Dùng để khai báo hệ số phân bổ cho các yếu tố chi phí, có tiêu thức phân bổ là phân bổ theo hệ số. Khi tính giá thành chương trình sẽ lấy hệ số này \* số lượng sản xuất để làm hệ số phân bổ cho các đối tượng tính giá thành

<figure><img src="../.gitbook/assets/Giá thành 5.png" alt=""><figcaption></figcaption></figure>

### Khai báo đối tượng nhận phân bổ chi phí

Đường dẫn: _**Giá thành/Nhập liệu/Khai báo đối tượng nhận phân bổ chi phí**_

Khai báo khi có yếu tố được tập hợp qua một giai đoạn gián tiếp, người dùng khai báo phân bổ cho đối tượng trực tiếp tạo nên sản phẩm.

<figure><img src="../.gitbook/assets/Giá thành 6.png" alt=""><figcaption></figcaption></figure>

### Khai báo các bước tính giá thành

#### Tính số lượng sản phẩm nhập kho, sản xuất trong kỳ

* Số lượng sản phẩm nhập kho = Số lượng trên các phiếu nhập kho mã giao dịch Nhập thành phẩm.
* Số lượng dở dang cuối kỳ: Trong trường hợp doanh nghiệp sản xuất có dở dang cuối kỳ, thì cuối kỳ khi tính giá phải cập nhật số lượng thành phẩm dở dang để chương trình tính toán. Khai báo tại _**Giá thành/ Nhập liệu/ Cập nhật dở dang/ Cập nhật số lượng sản phẩm dở dang cuối kỳ.**_
* Số lượng thành phẩm sản xuất trong kỳ = Số lượng sản phẩm nhập kho + Số lượng sản phẩm dở dang.

#### Tập hợp chi phí phát sinh trong kỳ

Dựa theo [danh mục yếu tố](cach-set-up-tinh-gia-thanh-va-kiem-tra-gia-thanh.md#danh-muc-yeu-to) đã khai báo, chương trình sẽ tự động tập hợp chi phí từ sổ kho và sổ cái theo tài khoản để chuẩn bị tính giá thành.

Các lưu ý:

* Chương trình sẽ tính số NET phát sinh, tức là nếu 621 có phát sinh cả bên nợ và bên có theo cùng đối tượng thì số tập hợp sẽ là phát sinh Nợ - phát sinh Có.

#### Kết chuyển chi phí tập hợp trực tiếp

Đây là bút toán kết chuyển trực tiếp chi phí được chỉ đích danh cho đối tượng giá thành. VD như chi phí nguyên vật liệu chính thường chỉ rõ để sản xuất cho sản phẩm nào luôn --> chương trình sẽ tự động kết chuyển phần chi phí này qua cho sản phẩm đó.

#### Phân bổ chi phí phát sinh trong kỳ

Đây là việc phân bổ các chi phí đã được tập hợp mà chưa chỉ rõ là dùng cho sản phẩm nào. Hệ thống hỗ trợ các tiêu thức phân bổ sau:

* Phân bổ theo định mức nguyên vật liệu: Sử dụng cho các yếu tố nguyên vật liệu. Lúc này định mức/ cấu trúc nguyên vật liệu của sản phẩm chính là tiêu thức phân bổ.
* Phân bổ theo số lượng sản phẩm sản xuất trong kỳ: [Tính số lượng sản phẩm sản xuấ](cach-set-up-tinh-gia-thanh-va-kiem-tra-gia-thanh.md#tinh-so-luong-san-pham-nhap-kho-san-xuat-trong-ky)t của từng sản phẩm và dùng số này làm hệ số.
* Phân bổ theo hệ số: [Cập nhật hệ số phân bổ](cach-set-up-tinh-gia-thanh-va-kiem-tra-gia-thanh.md#khai-bao-he-so-phan-bo) và dùng số này làm hệ số. Phương pháp này thường áp dụng cho chi phí nhân công (dùng đơn giá giờ công sản xuất 1 sản phẩm) và chi phí sản xuất chung (số giờ chạy máy,...).
* Phân bổ theo yếu tố chi phí khác: Chi phí này dùng chi phí kia làm hệ số phân bổ. VD như sau khi đã tính được chi phí nguyên vật liệu, người dùng muốn dùng chính kết quả này để phân bổ cho chi phí nhân công, thì lựa chọn phương pháp này.

#### Tính giá thành tổng hợp các bước

Đường dẫn: _**Giá thành/Tính giá thành**_

Các thao tác phân tích ở trên sẽ được tính hợp tất cả trong phần tính giá thành, người dùng chỉ cần truy cập vào chức năng, chọn thời gian tính, chọn tất cả các bước tính đã được thiết lập và chạy tính.

<figure><img src="../.gitbook/assets/Giá thành 14.png" alt=""><figcaption></figcaption></figure>

### Kết chuyển chi phí sản xuất qua 154

Sau khi thực hiện tính giá thành và kết chuyển ở sổ giá thành, người dùng sẽ kết chuyển về mặt sổ cái các chi phí sản xuất qua tài khoản dở dang 154. Phần mềm hỗ trợ 2 cách thức kết chuyển như sau:

* Kết chuyển chi tiết 621, 622, 627 qua 154 theo từng sản phẩm. Cách này giúp theo dõi chi tiết số tiền kết chuyển của từng chi phí theo sản phẩm, nhưng sẽ khiến sổ cái nhiều bản ghi hơn.
* Kết chuyển tổng 621, 622, 627 qua 154, tức là tổng phát sinh của các tài khoản này là bao nhiêu sẽ chuyển qua 154 bằng 1 bút toán định khoản duy nhất.

#### Kết chuyển chi tiết theo sản phẩm

Thực hiện tại đường dẫn _**Giá thành/ Nhập liệu/ Bút toán kết chuyển chi phí sản xuất trong kỳ.**_

<figure><img src="../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

**Lưu ý:**

* Để thực hiện chức năng này thì mỗi tài khoản chi phí chi tiết phải khai 1 yếu tố trong [danh mục yếu tố](cach-set-up-tinh-gia-thanh-va-kiem-tra-gia-thanh.md#danh-muc-yeu-to).
* Danh mục yếu tố phải chọn Kết chuyển sang tài khoản dở dang là Có

<figure><img src="../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

#### Kết chuyển tổng hợp

Thực hiện chức năng này tại bút toán cuối kỳ, tham khảo [tại đây](../tong-hop/cac-cong-viec-cuoi-thang-quy/ket-chuyen-lai-lo.md).
