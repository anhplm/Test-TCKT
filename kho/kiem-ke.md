# Kiểm kê

## Mô tả nghiệp vụ

Khi có nhu cầu kiểm kê vật tư để biết được tình trạng tồn kho thực tế.

## Các bước thực hiện

Các bước kiểm kê được thực hiện trên phần mềm như sau:

**Bước 1**: Tạo Phiếu yêu cầu kiểm kê theo đường dẫn: _**kho/Nhập liệu/ Kiểm kê/Phiếu yêu cầu kiểm kê**_

&#x20;Tạo phiếu yêu cầu kiểm kê cần kiểm kê&#x20;

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Ngày kiểm kê: Ngày yêu cầu kiểm kê
* Đơn vị: Mã đơn vị cần kiểm kê
* Mã kho: Kiểm trên trên kho nào
* Mã vị trí: Kiểm kê theo mã vị trí
* Mã lô: Kiểm kê theo mã lô hàng
* Diễn giải: Nhập nội dung nhu cầu kiểm kê Trạng thái Kiểm kê hoặc lập chứng từ

**Bước 2**: Cập nhật kiểm kê theo đường dẫn: _**Kho/Nhập liệu/ Kiểm kê/ Cập nhật kiểm kê**_

Lọc phiếu yêu cầu kiểm kê cần kiểm

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

Sau khi chọn phiếu yêu cầu chương trình sẽ hiển thị lên nội dung kiểm kê của kho đó, cho biết tình trạng tồn kho thực tế là bao nhiêu

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Mã kho: Kho được kiểm kê
* Mã vật tư: Danh sách những vật tư được kiểm kê trong kho
* Đvt gốc: Đvt của vật tư được khai báo trong danh mục hàng hóa, vật tư
* Mã vị trí: Mã vị khí kho hàng nếu vị trí có theo dõi tồn kho
* Mã lô: Mã lô hàng nếu lô có theo dõi tồn kho
* Tồn kho thực tế: Số liệu tồn kho thực tế từ dữ liệu nhập xuất trong phần mềm
* Đvt: Đơn vị tính khi kiểm kê, 1 mã vật tư có thể có nhiều đvt
* Sl kiểm kế: Số lượng kiểm kê thực tế, người dùng tự gõ
* Số lượng (Theo dvt gốc): Số lượng sau khi được kiểm kê chương trình sẽ tự động quy đổi về đvt gốc

**Bước 3**: Xử lý chênh lệch số liệu kiểm kê theo đường dẫn: _**Kho/ Kiểm kê/ Xử lý chênh lệch số liệu kiểm kê**_

Khai báo màn hình: Xử lý chênh lệch số liệu kiểm kê

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý**:

* Ngày kiểm kê: Ngày xử lý số liệu kiểm kê
* Tk hàng thừa chờ xử lý: Tài khoản có để hạch toán chứng từ xử lý khi kiểm kê tồn kho thừa so với thực tế&#x20;
* Tk hàng thiếu chờ xử lý: Tài khoản nợ để hạch toán chứng từ xử khi kiểm kê tồn kho thiếu so với thực tế
* Mã khách: Mã khách để hạch toán chứng từ xử lý&#x20;
* Mã kho: Mã kho để hạch toán chứng từ xử lý&#x20;
* Đơn vị: Mã đơn vị được hạch toán chứng từ xử lý&#x20;
* Quyển phiếu nhập kho: Quyển chứng từ để hạch toán phiếu nhập kho khi kiểm kê thừa&#x20;
* &#x20;Quyển phiếu xuất kho: Quyển chứng từ để hạch toán phiếu xuất kho khi kiểm kê thiếu&#x20;
* Số phiếu kiểm kê: Lookup từ phiếu yêu cầu kiểm kê&#x20;
* &#x20;Xử lý Xử lý chênh lệch hoặc xóa kết quả xử lý. Nếu kết quả kiểm kê thừa thì chương trình sẽ tự động tạo 1 phiếu nhập kho hạch toán nợ tk vật tư/ Có tk hàng thừa chờ xử lý. Nếu kết quả kiểm kê thiếu thì chương trình sẽ tự động tạo 1 phiếu xuất kho hạch toán nợ tk hàng thiếu chờ xử lý/ Có tk vật tư.

**Kết quả xử lý chênh lệch**

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

![](https://github.com/anhplm/TC-KT/blob/main/.gitbook/assets/sb\_12.png)
