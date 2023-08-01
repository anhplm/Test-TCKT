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

# Cập nhật dữ liệu đầu kỳ

Mục đích của việc cập nhật dữ liệu đầu kỳ là để chương trình ghi nhận số dư đầu kỳ của kế toán tính tới trước thời điểm bắt đầu nhập liệu trên chương trình. Thao tác này thường được thực hiện một lần - khi lần đầu tiên sử dụng chương trình. Các chức năng cập nhật dữ liệu đầu kỳ bao gồm:

* Cập nhật số dư đầu kỳ của các tài khoản.
* Cập nhật tồn kho đầu kỳ.
* Cập nhật hoá đơn đầu vào, đầu ra đầu kỳ.
* Cập nhật chứng từ thanh toán đầu kỳ.
* Cập nhật số dư đầu kỳ đặc thù khác (hợp đồng, khế ước, vụ việc, ...).

## Cập nhật số dư đầu kỳ tài khoản

**Đối với tài khoản thường, không theo dõi công nợ**

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào số dư đầu kỳ tài khoản**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 01.png" alt=""><figcaption></figcaption></figure>

**Đối với tài khoản công nợ**

Dùng để cập nhật số dư đầu kỳ của tài khoản công nợ chi tiết theo đối tượng.

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào số dư công nợ đầu kỳ**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 02.png" alt=""><figcaption><p>Vào số dư công nợ đầu kỳ</p></figcaption></figure>

## Cập nhật hoá đơn đầu kỳ

Dùng để cập nhật các hoá đơn đầu vào, đầu ra đã phát sinh trước thời điểm nhập liệu trên chương trình. Thao tác này là cần thiết đối với các công ty theo dõi công nợ và quản lý tuổi nợ theo hóa đơn.

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào số dư đầu kỳ hóa đơn đầu vào/đầu ra**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 03.png" alt=""><figcaption><p>Vào số dư đầu kỳ đầu vào/ đầu ra</p></figcaption></figure>

## Cập nhật chứng từ thanh toán đầu kỳ

Dùng để cập nhật các chứng từ thanh toán cho các hoá đơn đã phát sinh trước thời điểm nhập liệu trên chương trình. Các chứng từ này được sử dụng để phân bổ thanh toán cho các hoá đơn đầu kỳ.&#x20;

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Chứng từ thanh toán đầu kỳ cho các hóa đơn đầu vào/đầu ra**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 04.png" alt=""><figcaption><p>Chứng từ thanh toán đầu kỳ cho các hóa đơn</p></figcaption></figure>

## Cập nhật tồn kho đầu kỳ

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào tồn kho đầu kỳ**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 05.png" alt=""><figcaption><p>Vào tồn kho đầu kỳ</p></figcaption></figure>

## Cập nhật tồn kho đầu kỳ nhập trước xuất trước

Trường hợp doanh nghiệp chọn phương pháp tính giá vốn hàng tồn kho là phương pháp nhập trước xuất trước thì cần cập nhật tồn kho đầu kỳ nhập trước xuất trước.

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào tồn kho đầu kỳ nhập trước xuất trước**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 06.png" alt=""><figcaption><p>Vào tồn kho đầu kỳ nhập trước xuất trước</p></figcaption></figure>

## Vào các số dư đầu kỳ khác

Nếu có theo dõi theo Khế ước, vụ việc, dự án, công trình thì khai báo số dư đầu kỳ thêm các mục này (nếu không có thì bỏ qua bước này).

Đường dẫn: _**Kế toán/ Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào tồn kho đầu kỳ theo khế ước/vụ việc/dự án, công trình**_

<figure><img src="../../.gitbook/assets/khai báo số dư đầu kỳ 07.png" alt=""><figcaption><p>Vào số dư đầu kỳ vụ việc, dự án, công trình</p></figcaption></figure>

Người dùng có thể cập nhật các giá trị đầu kỳ bằng thao tác import từ excel vào phần mềm. Xem hướng dẫn thao tác import từ excel [tại đây.](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/import-du-lieu-tu-excel-vao-chuong-trinh)
