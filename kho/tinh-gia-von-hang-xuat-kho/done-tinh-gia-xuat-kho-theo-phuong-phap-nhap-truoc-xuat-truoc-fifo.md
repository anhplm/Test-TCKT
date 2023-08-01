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

# \[DONE] Tính giá xuất kho theo phương pháp nhập trước xuất trước (FIFO)

Phương pháp nhập trước, xuất trước áp dụng dựa trên giả định là giá trị hàng tồn kho được mua hoặc được sản xuất trước thì được xuất trước, và giá trị hàng tồn kho còn lại cuối kỳ là giá trị hàng tồn.

Lưu ý: Phương pháp này chỉ đưa ra đơn giá xuất cuối cùng chứ không chỉ ra cho người sử dụng biết là phiếu xuất được xuất từ các phiếu nhập nào.

## Các bước thực hiện

### Khai báo phương pháp tính giá&#x20;

Chương trình cho phép khai báo phương pháp tính giá theo đơn vị cơ sở hoặc vật tư. Xem cách khai báo [tại đây](done-khai-bao-phuong-phap-tinh-gia.md).

### Vào tồn kho đầu kỳ nhập trước xuất trước

Đường dẫn: _**Tổng hợp/ Nhập liệu/ Đầu kỳ/ Vào tồn kho đầu kỳ nhập trước xuất trước**_

Tại lần đầu tiên sử dụng chương trình, người dùng cần cập nhật chi tiết số lượng tồn kho theo phiếu nhập và ngày nhập để lúc thực hiện tính phần mềm nhận biết và lấy ra được giá nào để áp trước.

Trong trường hợp lần đầu tiên sử dụng phương pháp nhập trước xuất trước thì có thể coi toàn bộ số tồn kho đầu kỳ của 1 vật tư trong 1 kho là một phiếu nhập còn chưa xuất hết.&#x20;

Sau khi nhập tồn đầu của các phiếu nhập chương trình sẽ tự động cộng dồn và chuyển sang tồn đầu cho các kho và ta không phải nhập số tồn kho (số tổng) nữa.

<figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

Trường hợp dữ liệu tồn đầu nhiều, người dùng sử dụng tính năng import từ excel để hỗ trợ cập nhật nhanh. Xem hướng dẫn import từ excel [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/import-du-lieu-tu-excel-vao-chuong-trinh).

### Tính giá nhập trước xuất trước

Đường dẫn: _**Kho/ Nhập liệu/ Tính giá hàng tồn kho/ Tính giá nhập trước xuất trước**_

Thao tác này thông thường được thực hiện vào cuối tháng hoặc bất kỳ thời điểm nào người dùng cần áp giá vốn cho phiếu xuất.&#x20;

<figure><img src="../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

**Các lưu ý**:

* Mã kho, mã vật tư không bắt buộc chọn khi tính giá. Khi lựa chọn mã kho/ mã vật tư nghĩa là người dùng muốn tính giá cho riêng kho/ vật tư đó.&#x20;
* Khi thực hiện tính giá, nếu lượng tồn không đủ để xuất cho phiếu xuất thì chương trình cũng dừng tính toán và buộc phải kiểm tra lại ngày các phiếu nhập cho dù tồn kho cuối kỳ vẫn đủ để xuất, đồng thời hiện cảnh báo đề người dùng kiểm tra.

<figure><img src="../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

## Các nguyên tắc khi tính giá nhập trước xuất trước

### Nguyên tắc khi áp giá

Giá nhập trước xuất trước sẽ áp theo kho - vị trí - vật tư - lô, tức là phiếu xuất sẽ được áp giá của phiếu nhập có cùng các điều kiện trên. Vị trí và lô không phải là thông tin bắt buộc phải theo dõi mà tùy theo nhu cầu quản lý của từng doanh nghiệp (xem thêm cách khai báo sử dụng [vị trí](http://127.0.0.1:5000/s/8XowuU3e1r2eaKN2nT9D/cach-theo-doi-ton-kho-nhieu-don-vi-tinh) và [lô](http://127.0.0.1:5000/s/8XowuU3e1r2eaKN2nT9D/cach-theo-doi-ton-kho-nhieu-don-vi-tinh)) , do đó đối tượng áp giá thông thường là kho - vật tư.

### Thứ tự ưu tiên khi tính giá

Trong việc tính giá NTXT thì điều quan trọng là phải xác định phiếu nào trước và phiếu nào là sau. Trình tự trước sau được xác định theo thứ tự ưu tiên:

* 1.Ngày của các phiếu xuất
* 2.Tính giá và cập nhật cho tất cả các phiếu xuất điều chuyển
* 3.Tính giá và cập nhật cho các hoá đơn và các phiếu xuất khác

Trong cùng 1 ngày, nếu có cả phiếu nhập và phiếu xuất thì phải xét ưu tiên phiếu nhập trước để có giá gán cho phiếu xuất. Thiết lập ưu tiên cho phiếu nhập [tại đây](http://127.0.0.1:5000/s/rcD7ImF1NXzNzFohN8p5/cach-thiet-lap-thu-tu-uu-tien-cua-chung-tu).

### Xử lý với chi phí mua hàng

Thông thường chi phí mua hàng sẽ được tính vào giá xuất kho. Tuy nhiên trong trường hợp chi phí về không cùng kỳ với phiếu nhập thì trường hợp này phần chi phí sẽ bị treo lại trên sổ sách. Để xử lý trường hợp này, cần phải dùng phiếu xuất kho có loại chứng từ là điều chỉnh để xuất số lượng bằng 0 với vật tư tính giá NTXT. Chức năng “Tính giá nhập trước xuât trước” sẽ không tính toán hoặc áp giá gì cho phiếu xuất kho loại này.

### Xử lý với phiếu nhập hàng bán trả lại

Khác với phương pháp tính giá trung bình tháng có thể xem phiếu nhập hàng bán trả lại như 1 phiếu xuất để áp giá, thì phương pháp tính giá nhập trước xuất trước không xử lý được (vì không thể vừa xem như 1 phiếu xuất để áp giá, lại vừa xem như 1 phiếu nhập để mang đi áp giá cho các phiếu xuất khác). Do đó, khi sử dụng phương pháp này thì khi cập nhật phiếu nhập hàng bán người dùng phải nhật giá luôn.
