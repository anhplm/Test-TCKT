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

# Tính giá xuất kho theo phương pháp trung bình di động

Phương pháp tính giá trung bình di động tương tự như cách tính giá trung bình, với trung bình di động giá xuất kho được tính theo ngày, biến động giá sẽ ít chênh lệch với thực tế hơn so với tính giá trung bình theo tháng.

Công thức tính giá trung bình di động ngày

| Giá xuất hàng tồn kho = (Giá trị tồn kho đầu ngày + Giá trị nhập kho trong ngày - Giá trị xuất đích danh trong ngày) / (Số lượng tồn kho đầu ngày + Số lượng nhập kho trong ngày - Số lượng xuất đích danh trong ngày) |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

## Các bước thực hiện

### Khai báo phương pháp tính giá&#x20;

Chương trình cho phép khai báo phương pháp tính giá theo đơn vị cơ sở hoặc vật tư. Xem cách khai báo[ tại đây.](khai-bao-phuong-phap-tinh-gia.md)

### Phân tích các tùy chọn tính giá

Đây là bước mà người dùng phân tích các tùy chọn mà phần mềm hỗ trợ khi thực hiện tính giá trung bình di động ngày.

Đường dẫn: _**Hệ thống/ Khai báo tham số/ Tồn kho**_

**Cách tính giá hàng tồn kho**

* Giá chung tất cả các kho: 1 vật tư nằm ở nhiều kho khác nhau sẽ có cùng giá xuất.
* Giá riêng từng kho: 1 vật tư nằm ở nhiều kho khác nhau có thể có giá xuất khác nhau. VD mặt hàng A ở kho hàng bán sẽ có giá xuất kho khác với ở kho hàng chờ thanh lý.
* Giá riêng từng nhóm kho: Chia danh mục kho thành các nhóm khác nhau, 1 vật tư ở các nhóm kho khác nhau sẽ có giá xuất khác nhau. Nhóm kho này thường áp dụng đối với các doanh nghiệp có nhiều chi nhánh (đơn vị cơ sở), mỗi đơn vị là 1 nhóm kho và có chung mức giá xuất. Khi chọn tham số này, trong danh mục kho sẽ hiển thị trường Nhóm kho để người dùng khai báo và phân loại kho vào các nhóm tương ứng cần áp giá.

Lưu ý: Hệ thống đang thiết lập sẵn tham số mặc định là Giá chung cho tất cả các kho, dựa vào đặc thù của doanh nghiệp để lựa chọn phù hợp.

**Tính giá trung bình ngoại tệ**

* Chọn **Có**: giá xuất hàng tồn kho sẽ được tính theo tiền hạch toán và cả tiền ngoại tệ. Chỉ chọn giá trị này nếu đảm bảo các phát sinh nhập, xuất hàng tồn kho đều theo đồng tiền ngoại tệ.

**Áp giá chênh lệch vào phiếu xuất cuối cùng**

* **Có**: Tiền chênh lệch khi tính giá xuất (nếu có) sẽ được cấn trừ vào giá trị của chứng từ xuất kho cuối cùng trong kỳ tính giá. Tuy nhiên, nếu phiếu xuất cuối cùng là phiếu xuất điều chuyển thì hệ thống không áp phần chênh lệch vào phiếu này được (do phiếu xuất điều chuyển tự động sinh ra phiếu nhập điều chuyển, ảnh hưởng đến giá trung bình).
* **Không**: Hệ thống sẽ tạo một chứng từ chênh lệnh giá xuất riêng (PX6 - Phiếu xuất chênh lệch (tự động)).&#x20;

Chênh lệch khi tính giá xuất hàng tồn kho phát sinh trong các trường hợp sau:

1\. Trường hợp số lượng tồn kho = 0 nhưng giá trị tồn kho khác 0. Phần này có thể phát sinh do làm tròn khi thực hiện các phép tính, hoặc tình huống nhập tăng giá trị của vật tư không còn tồn kho trong kỳ (như mua hàng đã bán hết tháng trước nhưng tháng này mới về hóa đơn chi phí).

2\. Khi tính giá chung cho tất cả các kho, cần cân đối giá trị tồn giữa các kho nhằm thống nhất một giá tồn cuối kỳ.

Ví dụ: kho A nhập 2 vật tư VT1, đơn giá 20.000. Kho B nhập 2 vật tư VT1, đơn giá 22.000. Trong kỳ, kho A xuất 1 đơn vị, kho B xuất 1 đơn vị.

Giá xuất VT1(Giá chung cho các kho) = (2×20.000 + 2×22.000)/(2+2) = 21.000

Tồn cuối kỳ kho A: số lượng = 1, giá trị = 19.000. Kho B: số lượng = 1, giá trị = 23.000

Để cân đối giá trị tồn giữa 2 kho (thống nhất một đơn giá tồn) thì cần phải xuất chênh lệch cho 2 kho như sau: Kho A xuất chênh lệch âm 2.000, kho B xuất chênh lệch dương 2.000.

Kết quả sau khi tạo tiền xuất chênh lệch: Giá trị tồn kho A = Giá trị tồn kho B = 21.000.

**Tạo phiếu xuất chênh lệch trong trường hợp vật tư không xuất trong kỳ**

* **Có**: tiền chênh lệch khi tính giá xuất (nếu có) sẽ được tạo một chứng từ riêng nếu trong kỳ tính giá không có bất kỳ chứng từ xuất kho nào để cấn trừ. Tham số này có ý nghĩa trong tình huống vật tư hàng hóa đã hết tồn từ kỳ trước, nhưng kỳ này có điều chỉnh về giá trị (hóa đơn tăng, giảm giá mua từ NCC, hóa đơn chi phí về sau,...)
* Không: Không xử lý tạo chênh lệch nếu vật tư không có xuất trong kỳ.

### Thao tác tính giá

**Bước 1:** Vào tính giá trung bình di động theo đường dẫn: _**Kho/ Nhập liệu/ Giá hàng tồn/ Tính giá trung bình**_

Thao tác này thông thường được thực hiện vào cuối tháng hoặc cuối kỳ.&#x20;

<figure><img src="../../.gitbook/assets/Giá trung bình di động.png" alt=""><figcaption></figcaption></figure>

Một số lưu ý:

* Mã kho, mã vật tư không bắt buộc chọn khi tính giá. Khi lựa chọn mã kho/ mã vật tư nghĩa là người dùng muốn tính giá cho riêng kho/ vật tư đó. Khi dùng giá riêng từng kho, người dùng có thể chọn tính từng kho lần lượt.&#x20;
* Tạo chênh lệch:
  * Không tạo: hệ thống sẽ không tạo chênh lệch trong bất kỳ trường hợp chênh lệch nào. Người dùng có thể tự tạo chênh lệch bằng Phiếu xuất kho ở phân hệ **Tồn kho** (nếu cần).
  * Tạo khi không còn tồn kho: hệ thống sẽ tự động tạo chênh lệch trong trường hợp số lượng tồn kho = 0, giá trị tồn khác 0.
  * Tất cả các trường hợp: hệ thống sẽ tự động tạo chênh lệch cho cả 2 trường hợp “Số lượng tồn kho = 0, giá trị tồn khác 0” và “Cân đối giá trị tồn giữa các kho”.
  * Xóa tất cả các phiếu chênh lệch: Khi không muốn tạo chênh lệch, nhưng đã tạo trước đó, người dùng có thể chọn loại xóa để xóa hết các phiếu xuất chênh lệch.

**Bước 2:** Kiểm tra kết quả tính giá trung bình di động&#x20;

* Kiểm tra kết quả ngay sau khi tính giá

<figure><img src="../../.gitbook/assets/Trung bình di động.png" alt=""><figcaption></figcaption></figure>

Các chứng từ xuất kho. Các phiếu xuất có check Đích danh sẽ không áp lại giá khi tính giá.

<figure><img src="../../.gitbook/assets/tính giá tb 02.webp" alt=""><figcaption></figcaption></figure>

* Tồn kho/ Báo cáo hàng tồn/ Thẻ kho (Sổ chi tiết vật tư).
* Các báo cáo liên quan khác.
