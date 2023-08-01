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

# \[DONE] Lập chứng từ nghiệp vụ khác

## Mô tả nghiệp vụ

Các nghiệp vụ không đặc thù phát sinh nhiều, không chi tiết từng nghiệp vụ cụ thể như mua hàng, bán hàng, phiếu thu, phiếu chi,... người dùng có thể hạch toán bằng Phiếu kế toán. Các phát sinh của loại này bao gồm hạch toán lương, hạch toán bảo hiểm, thanh lý tài sản, các khoản giảm trừ theo lương, trích trước chi phí dự phòng...

## Định khoản

**Hạch toán lương**

Nợ 622, 627, 641, 642 Chi phí lương nhân viên trực tiếp, lương nhân viên sản xuất, bán hàng,..

Có 334 Phải trả người lao động

**Hạch toán bảo hiểm giảm trừ vào lương**

Nợ TK 334 Phải trả người lao động

Có TK 3383 – BHXH

Có TK 3384 – BHYT

Có TK 3386 – BHTN

**Thanh lý tài sản**

Nợ TK 214: Trị giá hao mòn TSCĐ hữu hình

Nợ TK 811: Giá trị còn lại của TSCĐ hữu hình thanh lý

Có TK 211: Nguyên giá TSCĐ hữu hình thanh lý.

## Các bước thực hiện

Phiếu kế toán được thực hiện trên phần mềm như sau:

**Bước 1:** Vào đường dẫn _**Tổng hợp/Nhập liệu/Hạch toán/Phiếu kế toán**_ hoặc _**Tổng hợp/Nhập liệu/Hạch toán/Phiếu kế toán theo nghiệp vụ.**_

**Bước 2:** Trên thanh công cụ nhấn nút **Thêm** để tạo mới phiếu.

<figure><img src="../../.gitbook/assets/Chứng từ nvk.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: số chứng từ, ngày chứng từ, diễn giải, ngoại tệ,...
* Khai báo tab chi tiết: tài khoản, phát sinh nợ, phát sinh có,...
* Nhóm định khoản: trên một chứng từ có nhiều tài khoản Nợ và nhiều tài khoản Có, sẽ dùng trường nhóm định khoản để chương trình biết được tài khoản nào đối ứng với nhau. Nếu trên một chứng từ chỉ có một tài khoản Nợ, một tài khoản Có hoặc nhiều tài khoản Nợ, một tài khoản Có hoặc nhiều tài khoản Có, một tài khoản Nợ thì không cần nhập trường nhóm định khoản này
* Tab thuế**:** Ở phiếu kế toán, tab thuế chỉ hạch toán được thuế đầu vào, khi lưu chương trình sẽ kiểm tra tiền phát sinh nợ TK 133 bên tab chi tiết và cột tiền thuế bên tab thuế, nếu khác nhau chương trình sẽ cảnh báo tiền thuế chưa đúng so với khai báo thuế đầu vào ở tab chi tiết.

**Bước 5:** Nhấn **lưu** để lưu chứng từ, in phiếu bằng cách nhấn vào nút biểu tượng **In** trên chứng từ hoặc thanh công cụ.&#x20;

