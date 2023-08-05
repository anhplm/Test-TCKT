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

# Bán hàng thông qua đại lý

## Mô tả nghiệp vụ

Hoạt động bán hàng được diễn ra với nhiều hình thức khác nhau, doanh nghiệp có thể bán trực tiếp, thông qua các kênh phân phối là đại lý. Với hình thức thông qua đại lý, người bán sẽ gửi hàng hóa tại đây, sau đó đại lý sẽ bán hàng cho người tiêu dùng hoặc phân phối tiếp cho các đại lý nhỏ lẻ khác.

## Các bước thực hiện

### Tạo mã kho ký gửi để theo dõi hàng gửi kho đại lý

**Bước 1**: Để tạo kho đại lý người dùng vào đường dẫn _**Danh mục/Vật tư, sản phẩm và kho/Kho hàng**_

**Bước 2**: Trên thanh công cụ bấm **Thêm** để thêm mới một kho hàng

<figure><img src="../../.gitbook/assets/Bán hàng gửi đại lý.png" alt=""><figcaption></figcaption></figure>

**Một số lưu ý**:

* Doanh nghiệp có nhiều đại lý và muốn theo dõi tồn kho về cả số lượng lẫn giá trị tại mỗi đại lý, thì mỗi đại lý sẽ tạo 1 mã kho. Phương án này ít được lựa chọn vì sự phức tạp trong theo dõi và không khả thi nếu số lượng đại lý nhiều.
* Doanh nghiệp có nhiều đại lý, và chỉ muốn theo dõi tồn kho về mặt số lượng hoặc theo dõi cả giá trị nhưng giá vốn tại các đại lý là như nhau (không quan tâm giá trị tại thời điểm chuyển hàng ký gửi, cứ lấy giá trung bình tại thời điểm tính giá để áp) thì chỉ cần tạo 1 kho đại lý, mỗi đại lý sẽ được theo dõi bằng các mã vị trí.

### Tạo mã vị trí cho kho ký gửi đại lý

Dùng trong trường hợp doanh nghiệp có nhiều đại lý, muốn theo dõi chung một kho ký gửi đại lý, tương ứng mỗi vị trí là một đại lý, những kho có tick theo dõi vị trí mới khai báo được vị trí kho.

**Bước 1**: Để tạo vị trí đại lý người dùng vào đường dẫn _**Danh mục/Vật tư, sản phẩm và kho/Vị trí kho hàng**_

**Bước 2**: Trên thanh công cụ bấm **Thêm** để thêm mới một vị trí kho hàng.

<figure><img src="../../.gitbook/assets/Bán hàng gửi đại lý 2.png" alt=""><figcaption></figcaption></figure>

### Xuất hàng gửi đại lý

Khi phát sinh chuyển hàng cho đại lý người dùng sử dụng phiếu xuất điều chuyển để chuyển hàng từ kho công ty sang kho đại lý.

**Định khoản**

Nợ 157 Hàng gửi đi bán

Có 155, 156 Thành phẩm, Hàng hóa

Tham khảo thao tác xuất hàng gửi đại lý[ tại đây](../../kho/chuyen-kho/chuyen-hang-gui-ban-dai-ly.md)

### Xuất hóa đơn hàng gửi bán

**Định khoản**

**Ghi nhận doanh thu, thuế:**

Nợ 131 Phải thu của khách hàng

Có 333 Thuế GTGT đầu ra

Có 511 Doanh thu bán hàng hóa dịch vụ

**Ghi nhận giảm giá vốn:**

Nợ 632 Giá vốn hàng bán

Có 157 Hàng gửi đi bán

Khi đại lý đã bán hàng, kế toán tiến hành xuất hóa đơn từ kho ký gửi. Hóa đơn bán hàng được thực hiện trên phần mềm như sau:

**Bước 1:** Vào phiếu hóa đơn bán hàng theo đường dẫn: _**Bán hàng/Nhập liệu/Hóa đơn bán ra/Hóa đơn bán hàng.**_

**Bước 2:** Chọn biểu tượng **Thêm** trên thanh công cụ để thêm mới phiếu.

**Bước 3:** Nhập các thông tin trên hóa đơn.

<figure><img src="../../.gitbook/assets/Bán hàng gửi đại lý 4.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý:**

* Tài khoản kho mặc định theo tài khoản khai báo trong danh mục vật tư, khi xuất cho đại lý thì chọn lại tài khoản 157.

**Bước 4:** Bấm **Lưu** để lưu lại hóa đơn**,** chọn biểu tượng **In** trên chứng từ hoặc thanh công cụ để in chứng từ.
