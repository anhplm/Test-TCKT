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

# \[DONE] Danh mục điều kiện thanh toán

Việc quản lý công nợ bán hàng và hạn thanh toán giúp doanh nghiệp chủ động trong việc thu hồi công nợ khi đến hạn, tuy nhiên khách hàng có một thời gian chi trả cố định, nên thời gian thanh toán sẽ phụ thuộc vào kỳ chi tiền của khách hàng, người dùng có thể khai báo thêm điều kiện thanh toán bổ sung, chương trình sẽ tính lại thời gian đến hạn dựa trên điều kiện bổ sung này.

Một số loại kỳ thanh toán cố định thường gặp như:

* Thanh toán vào ngày cố định trong tháng.
* Thanh toán vào ngày cố định trong tuần, ví dụ thứ 5 tuần thứ 2 & 4 hàng tháng.

## Các bước thực hiện

Bước 1: Vào đường dẫn _**Bán hàng/Tiện ích/Cập nhật điều kiện thanh toán**_

Bước 2: Trên thanh công cụ người dùng bấm **thêm** để thêm mới một điều kiện thanh toán

<figure><img src="../../.gitbook/assets/Hạn thanh toán 6 (1).png" alt=""><figcaption></figcaption></figure>

* Mã khách hàng: chọn mã khách hàng có thêm điều kiện thanh toán từ danh mục khách hàng
* Mã điều kiện: mã do người dùng tự đặt
* Tên điều kiện/tên khác: tên điều kiện do người dùng tự đặt
* Loại điều kiện
  * 1.Thanh toán vào ngày cố định trong tháng
  * 2.Thanh toán vào ngày cố định trong tuần
* Ngày gom hóa đơn từ đến: nếu áp dụng trong một khoảng thời gian thì nhập từ ngày đến ngày, ví dụ áp dùng từ ngày 1 đến 15 hàng tháng.
* Ngày trong tuần: khi chọn điều kiện loại 2 sẽ hiện trường này, sẽ chọn ngày thứ trong tuần, ví dụ thứ 2, 3, 4,...
* Ngày thanh toán: Khi chọn điều kiện loại 1 thì chọn ngày trong tháng, có thể chọn nhiều ngày, ví dụ thanh toán vào ngày 15 và 25 hàng tháng.
* Tuần thứ: khi chọn điều kiện loại 2 sẽ hiện trường này, sẽ chọn tuần thứ mấy trong tháng, ví dụ tuần thứ 1,2,3,4
* Số ngày thanh toán: là số ngày của hạn thanh toán 45 ngày, 30 ngày tùy vào điều kiện thanh toán của doanh nghiệp

Bài toán ví dụ:

Ngày hóa đơn là 05/06/2023, hạn thanh toán trong vòng 45 ngày => ngày đến hạn 20/07/2023. Tuy nhiên khách hàng chỉ thanh toán vào ngày 15 hàng tháng, đã qua đợt thanh toán của khách, nên dời đến đợt tiếp theo là ngày 15/08/2023.

Ngày đến hạn: 20/07/2023

Ngày thanh toán của khách: 15/08/2023

Số ngày được nợ của khách: 45 + (15/08/2023 – 20/07/2023 + 1) = 71 ngày

