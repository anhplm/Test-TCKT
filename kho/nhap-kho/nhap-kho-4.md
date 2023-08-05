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

# Nhập kho khác

## Mô tả nghiệp vụ

&#x20;Nhập kho khác là những nghiệp vụ dùng chung, ví dụ như nhập hàng thừa, phế phẩm, nhập hàng gửi đi gia công nhập lại kho...

## Định khoản

Nợ TK 152, 156, 155 Giá trị nguyên liệu, hàng hóa sau gia công

Có TK 154,621, 623, 627...

## Các bước thực hiện

Phiếu nhập kho khác được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu nhập kho theo đường dẫn: _**Kho/ Nhập liệu/ Nhập kho nội bộ/ Phiếu nhập kho**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn loại giao dịch là **Nhập khác** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng nhập kho điều chỉnh theo mã đối tượng chung của doanh nghiệp.
* Thông tin vật tư: Nhập thông tin vật tư, kho và số lượng.&#x20;
* Giá: Xảy ra 2 tình huống sau:
  * Xác định được giá nhập lại: Nhập trực tiếp vào cột giá.
  * Không xác định được giá nhập lại: Tick vào nút "Giá trung bình" nếu muốn áp giá nhập lại bằng giá vốn của NVL tại tháng nhập trả. Khi tính giá vốn xuất kho (theo phương pháp trung bình tháng hoặc trung bình di động) thì phần mềm sẽ tự áp giá nhập.
* Lý do nhập: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người nhập kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản có. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản có. Chương trình cho phép khai báo lý do nhập và tài khoản có mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thiet-lap-su-dung-chung-tu-so-lieu-bao-cao/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* File đính kèm: Chương trình cho phép người dùng đính kèm file thuộc nhiều định dạng khác nhau

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.
