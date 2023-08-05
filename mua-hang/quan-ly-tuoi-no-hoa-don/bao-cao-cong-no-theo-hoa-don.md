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

# \[DONE] Báo cáo công nợ theo hóa đơn

Dùng để theo dõi tuổi nợ của hoá đơn mua. Báo cáo thể hiện được tình hình thanh toán chi tiết theo từng hoá đơn: tiền hoá đơn, tiền đã thanh toán, tiền còn nợ, nợ trong hạn, nợ quá hạn, ...

Đường dẫn: _**Mua hàng/ Báo cáo/ Bảng kê công nợ theo hoá đơn**_

<figure><img src="../../.gitbook/assets/bảng kê công nợ hoá đơn.png" alt=""><figcaption><p>Màn hình lọc báo cáo</p></figcaption></figure>

Lưu ý khi lọc báo cáo:

* Ngày báo cáo là ngày dùng để xét hạn thanh toán, ngày này so với hạn thanh toán của hóa đơn để xét trong hoặc quá hạn, và xét số ngày quá hạn thanh toán.
* Ngày tính hạn tt dùng để lọc theo ngày của chứng từ trả tiền, ví dụ Hóa đơn ngày 01/04, Phiếu chi ngày 10/04, trường hợp lọc Được thanh toán đến ngày là 06/04, thì cột Thanh toán sẽ lên bằng 0.
* Chi tiết: có thể xem báo cáo chi tiết theo hoá đơn hoặc theo nhà cung cấp.
* Số ngày hạn thanh toán dùng để chia các mốc quá hạn công nợ theo từng nhóm là bội số của ngày gõ vào, dựa vào ngày xem báo cáo trừ cho ngày đến hạn của hóa đơn, nếu quá hạn thanh toán bao nhiêu ngày sẽ sắp số tiền vào cột tương ứng.
* Số ngày cảnh báo tùy chọn này được dùng (nếu nhập > 0) để xem dữ liệu báo cáo công nợ hóa đơn sắp đến hạn thanh toán, báo cáo sẽ lên các hóa đơn đã quá hạn và các hóa đơn trong hạn có hạn thanh toán nằm trong khoảng Ngày báo cáo + Số ngày cảnh báo gõ vào.

**Màn hình báo cáo**

<figure><img src="../../.gitbook/assets/bảng kê công nợ hđ 2.png" alt=""><figcaption><p>Bảng kê công nợ hoá đơn</p></figcaption></figure>
