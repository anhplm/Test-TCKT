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

# \[DONE] Lập và nộp tờ khai thuế GTGT

## Mô tả

Tờ khai thuế GTGT là báo cáo dùng để kê khai các thông tin về doanh số và thuế, qua đó xác định được số tiền thuế mà doanh nghiệp phải nộp.

Doanh nghiệp nộp thuế GTGT theo phương phấu khấu trừ thì sẽ phải lập và nộp tờ khai thuế GTGT theo tháng, quý hoặc năm. Phần mềm kế toán của ARITO hỗ trợ tính năng tạo lập tờ khai và xuất XML nộp thuế.&#x20;

## Các bước lập tờ khai

**Bước 1**: Truy cập vào đường dẫn **Thuế/ Nhập liệu/ Tờ khai thuế GTGT** để tiến hành tạo lập tờ khai.

**Bước 2**: Chọn các thông tin để tạo lập tờ khai, sau đó nhấn **Đồng ý**.

* Thời gian: Tờ khai tháng/ Tờ khai quý/ Tờ khai năm và năm kê khai.
* Loại tờ khai: Tờ khai lần đầu/ Tờ khai bổ sung.

<figure><img src="../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

**Bước 3**: Kiểm tra dữ liệu tờ khai theo dữ liệu đã cập nhật trên hệ thống. Lưu ý kiểm tra các khoản thuế đầu vào, đầu ra tương ứng với tài khoản 133, 333 bên sổ cái.

<figure><img src="../.gitbook/assets/TK GTGT_1.jpg" alt=""><figcaption></figcaption></figure>

**Bước 4**: Nhập các chỉ tiêu điều chỉnh (nếu có), sau đó nhấn nút **Tính lạ**i để lưu dữ liệu đã được điều chỉnh này. Các chỉ tiêu công thức phần mềm sẽ tự động tính toán.

<figure><img src="../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

**Bước 5**: Kiểm tra lại 1 lần nữa số liệu trên tờ khai, sau khi đã xác nhận độ chính xác của số liệu, nhấn vào nút chức năng Lập tờ khai để chương trình tạo lập tờ khai dựa trên dữ liệu này.

<figure><img src="../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

**Bước 6**: Kiểm tra tờ khai đã được tạo lập trên hệ thống tại đường dẫn _**Thuế/ Nhập liệu/ Tờ khai thuế đã lập.**_ Tại đây, người dùng kiểm tra lại các thông tin tạo lập, nếu có sai sót thì điều chỉnh lại để nộp lên thuế.

**Một số lưu ý:**

* Nếu tờ khai đã tạo và **chưa nộp** nhưng có sai sót cần phải lập lại, người dùng có thể xóa tờ khai đã tạo sai đi để tạo lại.

<figure><img src="../.gitbook/assets/TK GTGT_4.jpg" alt=""><figcaption></figcaption></figure>

* Tờ khai thuế GTGT PL 43: Doanh nghiệp được giảm thuế theo Nghị quyết 43/2022/QH15 và Nghị định 44/2023/NĐ-CP, khi nộp tờ khai sẽ đính kèm PL43/ PL44. Người dùng qua tab Tờ khai thuế GTGT PL43, và nhấn vào nút In ấn để in phụ lục đính kèm dạng Excel.

<figure><img src="../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

## Kết xuất XML và nộp thuế

### Kết xuất XML

**Bước 1**: Vào đường dẫn _**Thuế/ Nhập liệu/ Tờ khai thuế đã lập,**_ chọn tờ khai đã [tạo lập ở trên](page-12.md#cac-buoc-lap-to-khai).

**Bước 2**: Nhấn vào số tờ khai để xem, sau đó nhấn nút chức năng **Tải file XML HTKK**, chương trình sẽ tạo file XML và lưu vào máy.

<figure><img src="../.gitbook/assets/TK GTGT_3.jpg" alt=""><figcaption></figcaption></figure>

### Nộp tờ khai

#### Nộp từ file XML đã kết xuất

Sau khi Tải file XML HTKK từ phần mềm, người dùng vào trang [thuedientu.gdt.gov.vn](https://thuedientu.gdt.gov.vn/) tải file XML lên, ký và nộp tờ khai.

#### Nộp trực tiếp từ phần mềm

Nếu người dùng sử dụng ứng dụng CyberTax thì có thể tích hợp với Phần mềm để nộp tờ khai trực tiếp từ phầm mềm kế toán bằng thao tác chọn nút **Nộp tờ khai trực tiếp lên thuế** ở màn hình **Tờ khai thuế đã lập**.

<figure><img src="../.gitbook/assets/TK GTGT_5.jpg" alt=""><figcaption></figcaption></figure>



