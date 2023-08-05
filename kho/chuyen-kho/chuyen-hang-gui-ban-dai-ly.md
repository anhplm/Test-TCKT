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

# Chuyển hàng gửi bán đại lý

## Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ bán hàng qua đại lý, doanh nghiệp lập phiếu xuất đều chuyển để chuyển hàng ký gửi tại đại lý.

## Định khoản

Nợ TK 157 Hàng gửi đi bán

Có TK 155, 156,… Thành phẩm; Hàng hóa

## **Các bước thực hiện**

Phiếu xuất điều chuyển có hai loại điều chuyển:

* Điều chuyển 1 bước: khi dùng loại này khi lưu chương trình sẽ tự động hạch toán tăng số lượng ở kho nhập.
* Điều chuyển 2 bước: Khi dùng loại này chương trình sẽ tạo tự động một phiếu nhập điều chuyển ở kho nhập, phiếu nhập tạo tự động ở trạng thái lập chứng từ (lập nháp), thủ kho nhập xác nhận đủ số lượng sau khi nhận đủ hàng thì chuyển trạng thái thành nhập kho, lúc này sẽ tăng số lượng ở kho nhập.

### Phiếu xuất kho điều chuyển 1 bước được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu xuất kho theo đường dẫn: _**Kho/ Nhập liệu/Xuất kho nội bộ/ Phiếu xuất điều chuyển**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn loại giao dịch là **Khác** và nhập các thông tin sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Phiếu xuất điều chuyển 4.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng xuất kho hủy hàng theo mã đối tượng chung của doanh nghiệp.
* Khai báo các thông tin chung: **mã kho xuất (kho công ty)**, diễn giải, ngày chứng từ, trạng thái,…
* Khai báo tab Chi tiết: mã sản phẩm, **Mã kho nhập (kho đại lý),** số lượng,...
* Lý do nhập xuất: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người xuất kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản nợ. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản nợ. Chương trình cho phép khai báo lý do xuất và tài khoản nợ mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thiet-lap-su-dung-chung-tu-so-lieu-bao-cao/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* Khai báo thêm File đính kèm ( nếu có).

**Bước 4**: Nhấn vào Lưu.

**Bước 5**: Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

**Phiếu xuất kho điều chuyển 2 bước** (tham khảo nghiệp vụ điều chuyển hai bước[ tại đây](chuyen-vat-tu-hang-hoa-giua-cac-kho-noi-bo.md))
