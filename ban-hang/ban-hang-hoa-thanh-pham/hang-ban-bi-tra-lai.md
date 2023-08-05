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

# Hàng bán bị trả lại

## Mô tả nghiệp vụ

Hàng bán giao cho khách do có sự sai sót về mẫu mã, hàng kém chất lượng, hoặc do bên bán có vi phạm về hợp đồng kinh tế, bên mua tiến hành trả lại hàng, khi đó kế toán ghi nhận hàng trả lại, giảm doanh thu, khoản phải thu, tăng giá tồn kho.

## Định khoản

**Hạch toán giảm doanh thu, công nợ kê thuế đầu vào:**

Nợ TK 511 ,5213 Doanh thu, hàng bán bị trả lại

Nợ TK 133 Thuế GTGT được giảm (khi lên bảng kê thuế sẽ là số dương)

Có TK 131 Phải thu khách hàng

**Hạch toán giảm doanh thu, công nợ kê thuế đầu ra:**

Nợ TK 511 ,5213 Doanh thu, hàng bán bị trả lại

Nợ TK 333 Thuế GTGT được giảm (khi lên bảng kê thuế sẽ là số âm)

Có TK 131 Phải thu khách hàng

**Hạch toán tăng giá vốn:**

Nợ TK 155, 156 Thành phẩm; Hàng hóa

Có TK 632 Giá vốn hàng bán

## Các bước thực hiện

Phiếu nhập hàng bán trả lại được thực hiện trên phần mềm như sau:

**Bước 1**: Vào phiếu nhập kho theo đường dẫn: _**Bán hàng/nhập liệu/Hóa đơn điều chỉnh,trả lại/ Phiếu nhập hàng bán trả lại**_

**Bước 2**: Trên thanh công cụ nhấn nút **Thêm** để tạo mới 1 phiếu.

**Bước 3:** Nhập thông tin hàng bán trả lại, có 2 tình huống sau:

* Hàng trả lại không biết là trả lại của hóa đơn xuất bán nào: Người dùng nhập thông tin khách hàng, hàng hóa, số lượng, giá bán và giá vốn trả lại. Giá vốn nếu không xác định được thì tick vào nút Trung bình để khi tính giá trung bình, chương trình áp giá vốn của tháng nhập trả vào.
* Hàng hóa trả lại biết là trả lại của của hóa đơn nào, người dùng  kế thừa từ hóa đơn bán hàng trước đó, tham khảo thao tác kế thừa [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/thao-tac-chuc-nang-tren-he-thong/ke-thua-du-lieu-theo-quy-trinh)

<figure><img src="../../.gitbook/assets/Nhập hàng bán bị trả lại.png" alt=""><figcaption></figcaption></figure>

**Bước 4:** Nhập thông tin thuế tại tab Khác

* Kê thuế đầu vào: Khi lên bảng kê thuế số tiền trên bảng kê là số dương.
* Kê thuế đầu ra: Khi lên bảng kê thuế số tiền trên bảng kê là số âm.

<figure><img src="../../.gitbook/assets/Nhập hàng bán bị trả lại 2.png" alt=""><figcaption></figcaption></figure>

**Bước 5**: Nhấn **Lưu** để lưu phiếu, sau đó chọn biểu tượng **In** trên thanh công cụ để in chứng từ.
