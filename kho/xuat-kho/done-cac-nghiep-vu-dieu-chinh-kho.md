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

# \[DONE] Các nghiệp vụ điều chỉnh kho

## Mô tả nghiệp vụ

Khi có sự chênh lệch về tồn kho, vào thời điểm kiểm kê cuối tháng, hoặc kiểm kê đột xuất phát hiện có sự sai lệch và cần xử lý để khớp với thực tế, kế toán sử dụng phiếu xuất kho để điều chỉnh hàng thừa.

## Định khoản

Nợ TK 138, 338, 6xx

Có TK 152, 153, 155, 156 Giá trị nguyên vật liệu, thành phẩm, hàng hóa

## Các bước thực hiện

Phiếu xuất kho điều chỉnh được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu xuất kho theo đường dẫn: _**Kho/ Nhập liệu/ Xuất kho nội bộ/ Phiếu xuất kho**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn loại giao dịch là **Điều chỉnh** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Phiếu xuất điều chỉnh.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng xuất kho điều chỉnh theo mã đối tượng chung của doanh nghiệp.
* Thông tin vật tư: Chỉ cần nhập thông tin vật tư, kho và số lượng. Giá sẽ được tự động áp sau khi tính giá vốn hàng xuất kho, hoặc người dùng muốn dùng giá đích danh, thì check vào Đích danh và nhập giá xuất đích danh.
* Lý do xuất: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người xuất kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản nợ. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản nợ. Chương trình cho phép khai báo lý do xuất và tài khoản nợ mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* File đính kèm: Chương trình cho phép người dùng đính kèm file thuộc nhiều định dạng khác nhau.&#x20;

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.
