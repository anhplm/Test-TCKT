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

# \[DONE] Mua hàng có chiết khấu

## Mô tả nghiệp vụ

Khi mua hàng, tùy theo hợp đồng hoặc chính sách giá của bên bán mà sẽ được hưởng chương trình chiết khấu. Có các tình huống cơ bản xảy ra khi xử lý phần chiết khấu này đối với bên mua hàng như sau:

## Mua hàng được chiết khấu ngay theo từng lần mua hàng

### Xử lý

Khi mua hàng mà được chiết khấu ngay trên hóa đơn thì phần chiết khấu này sẽ được trừ ngay vào giá vốn NVL, hàng hóa nhập kho.

Giá trị nhập kho = Thành tiền trước chiết khấu - Chiết khấu.

### Các bước thực hiện

**Bước 1:** Vào phân hệ **Mua hàng/ Nhập liệu/Hóa đơn mua vào/Hóa đơn mua hàng trong nước**&#x20;

**Bước 2:** Nhấn T**hêm** để thêm mới chứng từ, Tick vào nút **Chiết khấu** ở thông tin chung

<figure><img src="../../.gitbook/assets/Hóa đơn mua hàng có chiết khấu.png" alt=""><figcaption></figcaption></figure>

Khi tick vào Chiết khấu sẽ hiện ra 3 phương pháp tính chiết khấu:

_**Tự nhập**_

Người dùng tự nhập tỷ lệ chiết khấu trên từng dòng vật tư. Lựa chọn này áp dụng trong trường hợp mỗi mặt hàng được áp 1 tỷ lệ chiết khấu khác nhau.

_**Giảm % theo hóa đơn**_

Trên hóa đơn mua hàng được giảm cùng % cho tất cả mặt hàng, nhập tỷ lệ hóa đơn ở thông tin chung, chương trình sẽ gán mặc định tỷ lệ ở tab chi tiết theo từng mặt hàng.

_**Giảm tiền trên tổng hóa đơn**_

Hóa đơn mua hàng được chiết khấu 1 giá trị tổng, trên hóa đơn có nhiều mặt hàng và số tiền chiết khấu sẽ được phân bổ lại cho các mặt hàng, theo tiêu thức số lượng hoặc theo giá trị.

<figure><img src="../../.gitbook/assets/Hóa đơn mua hàng có chiết khấu 2.png" alt=""><figcaption></figcaption></figure>

**Bước 3**: Nhấn **Lưu.**

**Bước 4**: Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

## Mua hàng được chiết khấu sau

Mua hàng được chiết khấu sau là trong các trường hợp chiết khấu theo số lượng, doanh số, tính theo tổng doanh số mua hàng trong khoảng thời gian áp dụng chương trình chiết khấu mà tính ra được tỷ lệ hoặc tiền chiết khấu.&#x20;

Đối với bên mua khi nhận hóa đơn chiết khấu này, sẽ rơi vào 2 tình huống:

### Trường hợp hàng còn tồn kho

Lúc này ghi giảm giá trị hàng tồn kho

#### Định khoản

Nợ 331 Phải trả người bán

Có 152,153,156,.. nguyên liệu, công cụ, hàng hóa (Giá trị được chiết khấu)

Có 133 thuế GTGT đầu vào

#### Các bước thực hiện

**Bước 1:** Vào phân hệ **Mua hàng/Nhập liệu/Hóa đơn mua điều chỉnh, trả lại/Phiếu nhập điều chỉnh giá hàng mua**

**Bước 2:** Nhấn T**hêm** để thêm mới chứng từ, chọn giao dịch giảm giá

**Bước 3:** Nhập mặt hàng và số tiền chiết khấu phân bổ cho mặt hàng được giảm. Trường hợp chiết khấu 1 giá trị tiền mà không biết chi tiết của mặt hàng nào thì người dùng làm thao tác phân bổ giá trị ngoài file excel rồi nhập vào.

<figure><img src="../../.gitbook/assets/Hóa đơn mua hàng có chiết khấu 3.png" alt=""><figcaption></figcaption></figure>

**Bước 4**: Nhấn **Lưu**.

### Trường hợp hàng không còn tồn kho

Lúc này tùy mục đích sử dụng của NVL, hàng hóa mà hạch toán tài kphù hợp

#### Định khoản

Nợ 331 phải trả người bán

Có 632,711,.. giá vốn, doanh thu khác

Có 133 thuế GTGT đầu vào

#### Các bước thực hiện

**Bước 1:** Vào phân hệ _**Tổng hợp/ Nhập liệu/Hạch toán/Phiếu kế toán**_

**Bước 2:** Nhấn **thêm** để thêm mới chứng từ.

<figure><img src="../../.gitbook/assets/Hóa đơn mua hàng có chiết khấu 4.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: số chứng từ, ngày hạch toán, diễn giải, trạng thái,…
* Khai báo tab Chi tiết: tài khoản, mã khách, phát sinh nợ, phát sinh có,…
* Khai báo tab thuế: số hóa đơn, ngày hóa đơn, tài khoản, giá trị thuế đầu vào được giảm

**Bước 3**: Nhấn **Lưu**.

**Bước 4**: Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.
