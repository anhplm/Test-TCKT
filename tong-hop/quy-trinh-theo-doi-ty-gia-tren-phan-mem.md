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

# Quy trình theo dõi tỷ giá trên phần mềm

Hướng dẫn theo dõi tỷ giá trên phần mềm.

Hướng dẫn thao tác tính tỷ giá ghi sổ cuối kỳ.

## Khai báo hệ thống

Đường dẫn: _**Hệ thống/ Khai báo tham số**_

Khai báo tham số tùy chọn: kiểm tra khai báo 3 option như hình để phục vụ việc Đánh giá lại tỷ giá cuối năm.

<figure><img src="../.gitbook/assets/tỷ giá 00.png" alt=""><figcaption><p>Khai báo các tham số</p></figcaption></figure>

B1: Khai báo các mục liên quan đến tỷ giá

* Khai báo danh mục ngoại tệ

Đường dẫn: _**Kế toán/ Danh mục/ Kế toán/ Ngoại tệ**_

<figure><img src="../.gitbook/assets/tỷ giá 01.png" alt=""><figcaption><p>Khai báo danh mục tỷ giá</p></figcaption></figure>

* Khai báo, cập nhật danh mục Tỷ giá quy đổi ngoại tệ

Đường dẫn: _**Kế toán/ Danh mục/ Đối tượng/ Tỷ giá quy đổi ngoại tệ**_

<figure><img src="../.gitbook/assets/tỷ giá 02.png" alt=""><figcaption><p>Khai báo, cập nhật tỷ giá quy đổi ngoại tệ</p></figcaption></figure>

* Khai báo mã ngoại tệ và chọn phương pháp tính tggs nợ hoặc có tương ứng với tài khoản khai báo.

Đường dẫn: _**Kế toán/ Danh mục/ Đối tượng/ Hệ thống tài khoản**_

Chọn mã tài khoản cần khai báo và nhấn Sửa

<figure><img src="../.gitbook/assets/tỷ giá 03.png" alt=""><figcaption></figcaption></figure>

* Khai báo bút toán cần đánh giá: Khai báo các tài khoản cần đánh giá

Đường dẫn: _**Tổng hợp/ Nhập liệu/ Khai báo/ Khai báo bút toán chênh lệch tỷ giá**_

<figure><img src="../.gitbook/assets/tỷ giá 04.png" alt=""><figcaption><p>Khai báo bút toán chênh lệch tỷ giá</p></figcaption></figure>

## Các bước thực hiện

**Bước 1:** Các xử lý trên chứng từ

### Giấy báo nợ

Đường dẫn: _**Kế toán/ Tiền gửi/ Giấy báo nợ**_

Sau khi nhập thông tin chi tiết thì vào tab tỷ giá để chọn loại xử lý.

<figure><img src="../.gitbook/assets/tỷ giá 05.png" alt=""><figcaption><p>Giấy báo nợ</p></figcaption></figure>

Trường hợp có check vào nút Sửa tggs thì chương trình sẽ cho phép sửa cả 2 tỷ giá ở trường Ngoại tệ và trường Tỷ giá gs ở tab Chi tiết , và không áp lại khi tính cuối tháng.

Nút check Tạo chênh lệch tỷ giá ngay:

Nếu không check: Lúc này hệ thống sẽ hạch toán theo tiền ở chi tiết. Cuối kỳ chạy tỷ giá ghi sổ, hệ thống sẽ không áp lại tỷ giá nhưng vẫn sẽ hạch toán sổ cái theo tỷ giá mới.

Nếu có check: Lúc này hệ thống sẽ sinh bút toán chênh lệch tỷ giá ngay, cuối kỳ chạy lại sẽ áp lại tỷ giá mới và hạch toán lại bút toán chênh lệch. Trường hợp có check Tạo CL ngay và check thêm sửa tỷ giá, thì sẽ sinh CLTG và cuối kỳ không áp lại khi chạy tỷ giá ghi sổ.

### Giấy báo có

Đường dẫn: _**Kế toán/ Tiền gửi/ Giấy báo có**_

<figure><img src="../.gitbook/assets/tỷ giá 06.png" alt=""><figcaption><p>Giấy báo có</p></figcaption></figure>

Nút check Tạo chênh lệch tỷ giá ngay:

* Nếu không check: Lúc này hệ thống sẽ hạch toán theo tỷ giá tiền ở trường ngoại tệ. Cuối kỳ chạy tỷ giá ghi sổ, hệ thống sẽ không áp lại tỷ giá đối với tỷ giá ghi sổ ở chi tiết nhưng vẫn sẽ hạch toán sổ cái theo tỷ giá mới và sinh cặp hạch toán chênh lệch tỷ giá.
* Nếu có check: Lúc này hệ thống sẽ sinh bút toán chênh lệch tỷ giá ngay, cuối kỳ chạy lại sẽ áp lại tỷ giá mới và hạch toán lại bút toán chênh lệch. Trường hợp có check Tạo chênh lệch tỷ giá ngay và check thêm Sửa tỷ giá ghi sổ, thì sẽ sinh chênh lệch và cuối kỳ không áp lại khi chạy tỷ giá ghi sổ.

### Các chứng từ khác

Ví dụ: Phiếu kế toán: Vẫn có xử lý chênh lệch tỷ giá theo dạng tính cuối tháng, tức là lúc Lưu chứng từ sẽ hạch toán không có chênh lệch, cuối tháng chạy tính tỷ giá thì mới phát sinh chênh lệch nhưng không áp lại tỷ giá trên chứng từ.

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Phiếu kế toán**_

<figure><img src="../.gitbook/assets/tỷ giá 07.png" alt=""><figcaption><p>Lập phiếu kế toán</p></figcaption></figure>

Sau khi chạy tính tỷ giá ghi sổ thì sẽ tạo chênh lệch nhưng không áp lại tỷ giá trên phiếu.

<figure><img src="../.gitbook/assets/tỷ giá 08.png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Tính tỷ giá ghi sổ cuối tháng

Chức năng này dùng để chạy tính và áp lại tỷ giá cuối tháng, chỉ dùng chức năng khi tỷ giá ghi sổ của tài khoản tiền hoặc công nợ tính theo trung bình tháng, trung bình di động.

Đường dẫn: _**Kế toán/ Tiền gửi (tiền mặt)/ Nhập liệu/ Tính tỷ giá ghi sổ**_

<figure><img src="../.gitbook/assets/tỷ giá 09.png" alt=""><figcaption><p>Tính tỷ giá ghi sổ</p></figcaption></figure>
