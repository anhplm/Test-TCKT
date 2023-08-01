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

# \[DONE] Nhập tự động thành phẩm từ hóa đơn

## Mô tả nghiệp vụ

Đây là tiện ích nhằm tạo phiếu nhập kho thành phẩm cho hóa đơn bán hàng, sử dụng cho các doanh nghiệp bán lẻ (như nhà hàng, quán cafe, cửa hàng bán lẻ có đóng gói, sản xuất,...) xuất bán mỗi ngày nhiều bill, và có nhu cầu tính giá vốn cho thành phẩm bán ra trong ngày.

Nguyên tắc xử lý khi thực hiện tính năng này:

* Chỉ tạo phiếu nhập cho loại vật tư là Bán thành phẩm/ Thành phẩm. VD trong 1 bill dịch vụ ăn uống có các món ăn chế biến và hàng hóa như chai nước, bia,... thì khi tạo phiếu nhập thành phẩm tự động chỉ tạo cho các món ăn.
* Chỉ tạo cho các phiếu bán hàng có mã giao dịch là **Bán hàng POS.**
* Phiếu nhập kho tự sinh sẽ có mã giao dịch là Nhập thành phẩm, hạch toán N155/C154 tương tự như[ thao tác phiếu nhập kho thành phẩm](../nhap-kho/nhap-kho.md).

## Các bước thực hiện

### Lập hóa đơn bán&#x20;

Xem chi tiết thao tác lập hóa đơn bán hóa đơn bán [tại đây](../../ban-hang/ban-hang-hoa-thanh-pham/ban-hang-ghi-nhan-cong-no.md).

Ở tab Khác chọn loại giao dịch là **Bán hàng POS**.

<figure><img src="../../.gitbook/assets/nhập thành phẩm tự động 02.png" alt=""><figcaption></figcaption></figure>

### Nhập tự động thành phẩm từ hóa đơn

&#x20;Truy cập vào chức năng tại đường dẫn _**Kho/ Tiện ích/ Nhập tự động thành phẩm từ hóa đơn**_

<figure><img src="../../.gitbook/assets/nhập thành phẩm tự động 03.png" alt=""><figcaption><p>Nhập thông tin tạo phiếu</p></figcaption></figure>

Giải thích các thông tin:

* Ngày từ đến: Quét dữ liệu hóa đơn từ ngày nào đến ngày nào.
* Đơn vị: Đơn vị cần tạo phiếu.
* Mã khách hàng: Mã đối tượng trên phiếu nhập kho, do tạo hàng loạt phiếu nên gán bằng mã đối tượng chung của đơn vị.
* Quyển/ Sổ chứng từ: Quyển chứng từ cho phiếu nhập kho.
* Xử lý: Tạo phiếu/ Xóa phiếu tự động đã tạo.

### Một số lưu ý

* Chương trình cho phép người dùng tạo mỗi hóa đơn 1 phiếu nhập hoặc gom mỗi ngày 1 phiếu nhập. Trường hợp gom theo ngày để xử lý cho các công ty dạng chuỗi, mỗi ngày phát sinh hàng ngàn bill. Cài đặt tại: **Hệ thống/ Tham số tùy chọn/ Tồn kho**

<figure><img src="../../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>
