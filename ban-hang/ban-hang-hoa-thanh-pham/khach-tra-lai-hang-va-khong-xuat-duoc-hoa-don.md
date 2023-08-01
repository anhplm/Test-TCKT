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

# \[DONE] Khách lẻ trả lại hàng (không xuất được hóa đơn)

Khi hàng bán bị trả lại nhưng khách hàng là khách hàng lẻ, không có pháp nhân để xuất hóa đơn GTGT, hoặc khách hàng là hộ kinh doanh không xuất được hóa đơn GTGT, doanh nghiệp có thể chủ động xuất hóa đơn GTGT hàng trả lại để ghi nhận giảm thuế, doanh thu

## Hướng dẫn thao tác

### Hóa đơn điều chỉnh giá hàng bán

Đường dẫn: _**Bán hàng/Nhập liệu/Hóa đơn điều chỉnh giá hàng bán**_

Sử dụng hóa đơn điều chỉnh giá hàng bán loại giảm số lượng, để xuất giảm số lượng cho khách

**Lập hóa đơn điều chỉnh, kế thừa dữ liệu từ hóa đơn bán hàng.**

Hạch toán:

\+ Giảm công nợ: Nợ 521x/Có 131x

\+ Giảm thuế đầu ra: Nợ 333x/Có 131x

<figure><img src="../../.gitbook/assets/Hóa đơn điều chuyển giá hàng bán.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Hóa đơn điều chỉnh giá hàng bán 1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Hóa đơn điều chỉnh giá hàng bán 3.png" alt=""><figcaption></figcaption></figure>

Tham khảo thao tác phát hành hóa đơn điện tử [tại đây](../../hoa-don-dien-t/xac-thuc-hoa-don-dieu-chinh.md)

### Phiếu nhập kho

Đường dẫn: **Kho/Nhập liệu/Phiếu nhập kho**

Sau khi dùng hóa đơn điều chỉnh giảm số lượng, người dùng sử dụng phiếu nhập kho để ghi nhận tăng số lượng nhập kho, tăng giá vốn.

Hạch toán:

\+ Tăng giá tồn kho: Nợ 15xx/Có 632x

<figure><img src="../../.gitbook/assets/phiếu nhập kho.png" alt=""><figcaption></figcaption></figure>

Trường hợp khi nhập lại kho, người dùng không xác định được giá vốn lúc xuất kho, muốn dùng giá trung bình của tháng nhập lại để làm giá nhập, người dùng check vào checkbox Giá trung bình, khi tính giá trung bình tháng, chương trình sẽ áp giá vốn cho phiếu nhập.
