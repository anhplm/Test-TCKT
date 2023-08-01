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

# \[DONE] Theo dõi tiến độ thanh toán theo hợp đồng bán hàng

## Mô tả nghiệp vụ

Bán hàng với số lượng lớn, phát sinh hợp đồng bán hàng với các điều kiện kèm theo khi bán hàng. Người dùng sử dụng danh mục hợp đồng, để khai báo và lưu trữ các thông tin về hợp đồng, đồng thời có thể theo dõi tiến độ thanh toán của hợp đồng.

## Các bước thực hiện

### Khai báo danh mục hợp đồng

Xem cách khai báo hợp đồng và tiến độ thanh toán [tại đây](done-danh-muc-hop-dong-ban.md).

### Thu tiền thanh toán từng đợt theo hợp đồng

**Bước 1:** Vào đường dẫn&#x20;

* Thu tiền mặt: _**Tiền mặt/Nhập liệu/Hạch toán/Phiếu thu**_
* Thu tiền qua ngân hàng: _**Tiền gửi/Nhập liệu/Hạch toán/Giấy báo có**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo mới phiếu

**Bước 3:** Chọn Loại phiếu thu: **2. Thu theo đối tượng**

<figure><img src="../../.gitbook/assets/Tiến độ thanh toán theo hợp đồng 3 (1).png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: địa chỉ, người nhận tiền, diễn giải, tài khoản nợ, số chứng từ, ngày hạch toán, trạng thái, …
* Khai báo thông tin tab Chi tiết: tài khoản có, mã khách công nợ, số tiền, …
* Chọn mã hợp đồng, đợt thanh toán của hợp đồng, lúc này chương trình mới nhặt dữ liệu lên báo cáo tiến độ thanh toán

**Bước 4**: In phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.

### Kiểm tra báo cáo tiến độ thanh toán theo hợp đồng

**Bước 1:** Lọc báo cáo

<figure><img src="../../.gitbook/assets/Tiến độ thanh toán theo hợp đồng 4.png" alt=""><figcaption></figcaption></figure>

**Điều kiện lọc**

* Ngày ct từ/đến: Chương trình sẽ nhặt các phát sinh thu/chi tiền trong khoảng lọc này.
* Ngày hđ từ/đến: Khi cần lọc thêm chỉ lấy các hợp có ngày ký trong một khoảng thời gian, người dùng chọn thêm ngày ký hợp đồng tại đây.
* Mã khách hàng, mã hợp đồng, nhóm hợp đồng: trường hợp cần lọc cụ thể một đối tượng thì người dùng chọn tại đây.
* Tài khoản, Ghi nợ/có: khi chọn tài khoản tại đây chương trình sẽ lấy phát sinh của tài khoản ở điều kiện lọc, không nhập sẽ lọc tất cả phát sinh của tài khoản. Để xem thu tiền hợp đồng bán, người dùng chọn **tài khoản 131, ghi có.**
* Tài khoản đối ứng: khi chọn tài khoản đối ứng, chương trình chỉ lấy cái phát sinh có đối ứng với tài khoản lọc ở trên. Không nhập sẽ lọc tất cả phát sinh.

Kết quả sau khi lọc.

<figure><img src="../../.gitbook/assets/Tiến độ thanh toán theo hợp đồng 5.png" alt=""><figcaption></figcaption></figure>
