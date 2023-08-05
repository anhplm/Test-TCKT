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

# Lệnh sản xuất

## Mô tả nghiệp vụ

Trong hoạt động sản xuất các doanh nghiệp sẽ lập kế hoạch để sản xuất, các sản phẩm được sản xuất theo từng giai đoạn, lệnh sản xuất được xem như một kế hoạch thực hiện. Lệnh sản xuất cũng được áp dụng vào bài toán giá thành, tập hợp chi phí theo lệnh sản xuất.

## Các bước thực hiện

Lệnh sản xuất được thực hiện trên phần mềm như sau:

**Bước 1**: Vào lệnh theo đường dẫn **Giá thành/Nhập liệu/Lệnh sản xuất**

**Bước 2**: Trên thanh công cụ bấm **thêm** để tạo mới một lệnh sản xuất, lệnh sản xuất có thể được kế thừa từ đơn hàng bán, tham khảo thao tác kế thừa [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thao-tac-chuc-nang-tren-he-thong/ke-thua-du-lieu-theo-quy-trinh)

<figure><img src="../.gitbook/assets/Lệnh sản xuất.png" alt=""><figcaption></figcaption></figure>

**Bước 3**: Khai báo thông tin chung

* Mức độ: chọn mức độ bình thường, càng nhanh càng tốt, khẩn cấp dùng để phân loại tình trạng cần sản xuất sản phẩm
* Mã đối tượng: trường hợp là gia công ngoài thì chọn nhà cung cấp gia công, hoặc là mã đối tượng theo dõi chung của công ty
* Kế hoạch từ/đến: sản phẩm dự kiến sản xuất trong một khoản thời gian nào đó
* Thực hiện từ/đến: thực tế sản phẩm được sản ở khoảng thời gian nào.
* Trạng thái: người dùng chủ động chuyển trạng thái
  * Lập chứng từ: lập nháp lệnh sản xuất
  * Kế hoạch: lệnh sản xuất chuẩn bị thực hiện
  * Sản xuất: lệnh sản xuất đến giai đoạn sản xuất
  * Hoàn thành: đã hoàn thành sản xuất và nhập kho thành phẩm sản xuất

**Bước 4**: khai báo tab chi tiết: sản phẩm cần sản xuất, đơn vị tính, mã kho nhập/xuất, số lượng cần sản xuất, khai báo các thông tin theo dõi thêm.

**Bước 5**: bấm **lưu** để lưu lại thông tin lệnh sản xuất, bấm in trên thanh công cụ để in lệnh sản xuất.

**Lưu ý:**

Với nhiều doanh nghiệp, lệnh sản xuất sẽ được sản xuất theo đơn đặt hàng. Do đó, quy trình có thể đi từ đơn đặt hàng sau đó lệnh sản xuất sẽ kế thừa từ đây.
