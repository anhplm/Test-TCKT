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

# Khai báo các bút toán

Tài liệu mô tả các thao tác khai báo các bút toán tự động trong hệ thống, gồm:

* Bút toán kết chuyển
* Bút toán phân bổ
* Bút toán chênh lệch tỷ giá

## Bút toán kết chuyển

Đường dẫn: _**Tổng hợp/Nhập liệu/Khai báo bút toán kết chuyển**_

Dùng để khai báo các bút toán kết chuyển được kế toán thực hiện vào mỗi cuối kỳ kế toán (xác định kết quả kinh doanh, lãi lỗ, thuế GTGT, ...). Các bút toàn này chỉ khai báo một lần, trừ khi có sự thay đổi về các tài khoản liên quan.&#x20;

<figure><img src="../../.gitbook/assets/bút toán 1.png" alt=""><figcaption></figcaption></figure>

Các lưu ý khi khai báo bút toán kết chuyển:

* Loại kết chuyển: dùng để xác định tài khoản _**nguồn**_ và tài khoản _**đích**_ của bút toán kết chuyển.&#x20;



<table><thead><tr><th width="241">Loại kết chuyển</th><th width="121">TK nguồn</th><th width="121">TK đích</th><th>Ví dụ</th></tr></thead><tbody><tr><td>Từ TK có sang TK nợ</td><td>TK có</td><td>TK nợ</td><td><ul><li>Kết chuyển chi phí xác định KQKD (N911/C6xx)</li></ul><ul><li>Kết chuyển chi phí sản xuất (N154/C621,622,627)</li></ul><ul><li>Kết chuyển khoản giảm trừ doanh thu (N911/C521), ...</li></ul></td></tr><tr><td>Từ TK nợ sang TK có</td><td>TK nợ</td><td>TK có</td><td><ul><li>Kết chuyển doanh thu xác định KQKD (Nợ 511/C911) </li></ul><ul><li>Kết chuyển doanh thu tài chính (N515/C911) </li><li>Kết chuyển thu nhập khác (Nợ 711/C911),...</li></ul></td></tr><tr><td>Kết chuyển thuế</td><td>TK thuế có số dư nhỏ hơn</td><td>TK thuế có số dư lớn hơn</td><td><p>Kết chuyển thuế GTGT</p><p>Phải nộp (N333/C133)</p></td></tr><tr><td>Kết chuyển lãi lỗ</td><td>911</td><td>421</td><td></td></tr></tbody></table>

* Tài khoản đích phải được khai báo là tài khoản chi tiết nhất.
* Tài khoản nguồn có thể là tài khoản chi tiết hoặc tài khoản mẹ.
* Chỉ kết chuyển các ps chi tiết: Nếu tick chọn thì chương trình chỉ kết chuyển các phát sinh có chỉ rõ mã bộ phận, vụ việc, ... Các phát sinh không nhập bộ phận, vụ việc, ... sẽ không được kết chuyển.

## Bút toán phân bổ

Cuối kỳ kế toán, tuỳ theo đặc điểm sản xuất kinh doanh của doanh nghiệp, kế toán thường thực hiện các bút toán phân bổ như:

* Phân bổ chi phí sản xuất chung cho các bộ phận;
* Phân bổ chi phí bán hàng, chi phí quản lý doanh nghiệp vào tài khoản kết quả kinh doanh và tài khoản chi phí chờ kết chuyển, ...

Đường dẫn: _**Tổng hợp/Nhập liệu/Khai báo các bút toán phân bổ**_

<figure><img src="../../.gitbook/assets/bút toán 2.png" alt=""><figcaption><p>Khai báo bút toán phân bổ</p></figcaption></figure>

Các lưu ý khi khai báo bút toán phân bổ

* Nếu loại phân bổ là _1- Từ tài khoản có sang tài khoản nợ_ thì kết quả của bút toán sẽ là Ghi Nợ tài khoản nhận (tài khoản đích) và ghi Có tài khoản phân bổ (tài khoản nguồn).
* Nếu loại phân bổ là _2- Từ tài khoản nợ sang tài khoản có_ thì kết quả của bút toán sẽ là ghi nợ tài khoản phân bổ (tài khoản nguồn)/ ghi có tài khoản nhận (tài khoản đích).
* DS tài khoản nợ; DS tài khoản có là các tài khoản dùng làm tiêu thức tính hệ số phân bổ. Chương trình cho phép khai báo 1 cặp tài khoản đối ứng cho 1 tiêu thức tính hệ số phân bổ. Có thể khai báo đối ứng hoặc chỉ khai báo chỉ một bên nợ hoặc bên có.
* Bộ phận, vụ việc, ... là các đối tượng phân bổ chi tiết. Khi phân bổ chương trình sẽ phân bổ chi tiết cho từng đối tượng dựa theo hệ số phân bổ đã được thiết lập.

\--> Hình minh hoạ trên cho thấy khai báo của bút toán 627 xuống tài khoản 911 theo hệ số là phát sinh của tài khoản 511 của từng mã bộ phận.

## Bút toán đánh giá chênh lệch tỷ giá

Dùng để khai báo các bút toán đánh giá chênh lệch tỷ giá cuối kỳ đối với các tài khoản có phát sinh ngoại tệ.

Đường dẫn: _**Tổng hợp/Nhập liệu/Khai báo các bút toán chênh lệch tỷ giá**_

<figure><img src="../../.gitbook/assets/bút toán 3.png" alt=""><figcaption></figcaption></figure>

Người dùng khai báo tài khoản có gốc ngoại tệ, phát sinh chênh lệch tỷ giá, bút toán này chỉ khai báo lần đầu sử dụng, nếu có thêm tài khoản chênh lệch tỷ giá thì người dùng khai báo thêm tại đây.
