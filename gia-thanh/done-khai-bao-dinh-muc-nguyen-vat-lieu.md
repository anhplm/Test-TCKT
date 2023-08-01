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

# \[DONE] Khai báo định mức nguyên vật liệu

## Mô tả nghiệp vụ

Định mức nguyên vật liệu được dùng để khai báo công thức vật tư cho một sản phẩm, được sử dụng để tính lượng nguyên liệu xuất kho sản xuất, làm tiêu thức phân bổ dựa vào cấu trúc sản phẩm, chương trình sẽ tính hệ số phân bổ chi phí khác trong bài toán giá thành.

## Các bước thực hiện

Khai báo định mức nguyên vật liệu được thực hiện trên phần mềm như sau:

**Bước 1:** Vào định mức theo đường dẫn: _**Giá thành/Nhập liệu/Định mức nguyên vật liệu**_

**Bước 2:** Trên thanh công cụ bấm **thêm** để thêm mới định mức của sản phẩm

<figure><img src="../.gitbook/assets/Định mức nguyên vật liệu.png" alt=""><figcaption></figcaption></figure>

**Các trường thông tin**

* Khai báo thông tin chung
  * Mã sản phẩm: sản phẩm cần khai báo định mức.
  * ĐVT: đơn vị tính của sản phẩm, có thể sử dụng đơn vị tính quy đổi để khai báo định mức.
  * Mã bộ phận: là công đoạn sản xuất nếu sản phẩm trãi qua công đoạn sản xuất.
* Khai báo thông tin chi tiết
  * Mã NVL: nguyên liệu cấu thành sản phẩm.
  * Đvt: đơn vị tính của nguyên liệu.
  * Số lượng: số lượng nguyên liệu cần đủ để sản xuất sản phẩm.
  * TL hao hụt (%): tỷ lệ hao hụt dự kiến sản xuất, dựa trên tỷ lệ này để xuất nguyên vật liệu thêm phần hao hụt đủ sản xuất.
  * Hiệu lực từ/đến: thời gian áp dụng định mức này, nếu nằm ngoài thời gian này chương trình sẽ không tính.

**Công thức tính lượng nguyên vật liệu xuất kho**

Lượng nguyên liệu xuất kho = (1+ tỷ lệ hao hụt) \* số lượng sản xuất \* số lượng định mức
