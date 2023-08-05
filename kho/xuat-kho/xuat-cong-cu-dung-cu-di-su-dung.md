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

# Xuất công cụ dụng cụ đi sử dụng

## Mô tả nghiệp vụ

Công cụ dụng cụ mua dùng, có theo dõi tồn kho và đã nhập kho trước đó, khi cần xuất kho người dùng sử dụng phiếu xuất kho loại Mua công cụ/tài sản để xuất kho công cụ.

## Định khoản

Nợ 242 chi phí công cụ dụng cụ xuất dùng

Có 153 giá trị công cụ dụng cụ xuất dùng

## Các bước thực hiện

Phiếu xuất kho công cụ dụng cụ được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu nhập kho theo đường dẫn: _**Kho/ Nhập liệu/ Xuất kho nội bộ/ Phiếu xuất kho**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3**: Chọn loại giao dịch là **Xuất tài sản/ công cụ** và nhập các thông tin công cụ

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã đối tượng: Có thể định nghĩa đối tượng theo mã đối tượng chung của doanh nghiệp.
* Thông tin vật tư: Nhập thông tin vật tư, kho và số lượng.&#x20;
* Giá: Check đích danh và nhập nguyên giá của công cụ xuất dùng. Chương trình sẽ lấy giá trị để ghi nhận nguyên giá công cụ, và phân bổ công cụ hàng kỳ.
* Lý do xuất: Đặt các mã lý do gợi nhớ cho nhân viên dưới kho (trường hợp người xuất kho là nhân viên kho, không rành về tài khoản kế toán) lựa chọn và tự load ra tài khoản nợ. Nếu phần mềm chỉ sử dụng cho kế toán nhập thì mã lý do chính là tài khoản nợ (242). Chương trình cho phép khai báo lý do xuất và tài khoản nợ mặc định theo loại giao dịch [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thiet-lap-su-dung-chung-tu-so-lieu-bao-cao/cach-khai-bao-tai-khoan-ngam-dinh-theo-loai-giao-dich-tren-cac-chung-tu-kho).
* File đính kèm: Chương trình cho phép người dùng đính kèm file thuộc nhiều định dạng khác nhau.&#x20;

**Bước 4:** Sang tab tài sản/công cụ để khai báo thông tin công cụ

<figure><img src="../../.gitbook/assets/Xuất công cụ dụng cụ 2.png" alt=""><figcaption></figcaption></figure>

**Bước 5:** Bấm lưu chương trình sẽ tạo một mã công cụ ở danh mục công cụ.

**Các lưu ý**:

* Nếu giá xuất kho của công cụ khác với nguyên giá khai bên tab thông tin công cụ thì phần mềm sẽ cảnh báo và không cho lưu.
* Khi công cụ đã phân bổ thì sẽ không cho sửa lại phiếu xuất kho. Để sửa lại phiếu thì người dùng phải xóa hết các phân bổ đã phát sinh của mã công cụ.
