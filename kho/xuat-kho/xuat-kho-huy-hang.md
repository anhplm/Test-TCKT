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

# Xuất kho hủy hàng

## Mô tả nghiệp vụ

Sản phẩm, hàng hóa, vật tư, nguyên liệu khi xảy ra hư, hỏng không dùng được, cần xuất kho hủy người dùng sử dụng phiếu xuất kho để xử lý. Các phiếu này sẽ giảm số lượng tồn kho, giá trị tồn kho.

## Định khoản

Nợ TK 632, 641, 642,... ghi nhận khoảng xuất hủy là chi phí giá vốn, chi phí bán hàng hoặc chi phí quản lý.

Có TK 152,153,155,156,... giá trị sản phẩm, hàng hóa, vật tư, nguyên liệu xuất kho

## Các bước thực hiện

Phiếu xuất kho hủy hàng được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu xuất kho theo đường dẫn: _**Kho/ Nhập liệu/ Xuất kho nội bộ/ Phiếu xuất kho**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn loại giao dịch là **Xuất nội bộ** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Xuất kho hủy.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng xuất kho hủy hàng theo mã đối tượng chung của doanh nghiệp.
* Thông tin vật tư: Chỉ cần nhập thông tin vật tư, kho và số lượng. Giá sẽ được tự động áp sau khi chạy tính giá vốn hàng xuất kho, hoặc người dùng muốn dùng giá đích danh, thì check vào Đích danh và nhập giá xuất đích danh.
* Lý do xuất: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người xuất kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản nợ. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản nợ. Chương trình cho phép khai báo lý do xuất và tài khoản nợ mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thiet-lap-su-dung-chung-tu-so-lieu-bao-cao/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* File đính kèm: Chương trình cho phép người dùng đính kèm file thuộc nhiều định dạng khác nhau.&#x20;

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.
