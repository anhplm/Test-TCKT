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

# Xác thực hóa đơn điều chỉnh

Hóa đơn điện tử đã phát hành có thể điều chỉnh trong các tình huống sau:

* Điều chỉnh giảm số lượng
* Điều chỉnh tăng giá
* Điều chỉnh giảm giá
* Điều chỉnh tăng thuế GTGT
* Điều chỉnh giảm thuế GTGT
* Điều chỉnh giảm giá trị dịch vụ
* Điều chỉnh thông tin

Các bước thực hiện để điều chỉnh hóa đơn như sau

### Lập hóa đơn điều chỉnh

Truy cập vào đường dẫn _**Bán hàng/ Nhập liệu/ Hóa đơn điều chỉnh giá hàng bán**_ để làm điều chỉnh cho hóa đơn bán hàng hóa hoặc _**Bán hàng/ Nhập liệu/ Hóa đơn dịch vụ trả lại, giảm giá**_ để làm điều chỉnh cho hóa đơn dịch vụ.

Hóa đơn điều chỉnh chỉ phát hành được, khi kế thừa từ hóa đơn đã được xác thực. Do đó, phiếu hóa đơn điều chỉnh phải được lấy dữ liệu từ hóa đơn bán đã được phát hành trên cùng hệ thống HĐĐT.&#x20;

VD các bước lập điều chỉnh kế thừa từ hóa đơn bán hàng:

<figure><img src="../.gitbook/assets/phát hành hóa đơn 8 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/phát hành hóa đơn 9 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/phát hành hóa đơn 10 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/phát hành hóa đơn 11.png" alt=""><figcaption></figcaption></figure>

**Các lưu ý**:

* Các bước tạo hóa đơn điều chỉnh giảm giá, dịch vụ được thực hiện tương tự.
* Mỗi chứng từ điều chỉnh chỉ được điều chỉnh cho 1 hóa đơn.
* Nếu hóa đơn bị điều chỉnh trước đó không được phát hành từ phầm mềm kế toán hoặc phần mềm hóa đơn điện tử hiện tại, thì người dùng phải làm hóa đơn điều chỉnh trực tiếp trên phần mềm hóa đơn điện tử, ghi rõ diễn giải điều chỉnh cho hóa đơn nào.

### Xác thực hóa đơn điều chỉnh

**Bước 1**: Truy cập chức năng phát hành hóa đơn điện tử tại đường dẫn _**Bán hàng/ Nhập liệu/ Xác thực hóa đơn điện tử,**_ lựa chọn Xử lý "Xác thực hóa đơn điều chỉnh tiền" và các thông tin rồi nhấn Đồng ý.

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

**Bước 2**: Tại màn hình kết quả lọc, tick chọn hóa đơn cần xác thực rồi nhấn biểu tượng xác thực HDDT và đợi đến khi chương trình thông báo hoàn thành.

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

**Bước 3**: Ký các hóa đơn chờ ký. Nếu doanh nghiệp ký bằng HSM và cài đặt khi phát hành là ký luôn thì không thực hiện bước này.

<figure><img src="../.gitbook/assets/phát hành hóa đơn 12 (1).png" alt=""><figcaption></figcaption></figure>

Sau khi phát hành xong, trạng thái HĐĐT của hóa đơn gốc sẽ chuyển sang trạng thái Điều chỉnh. Để xem lịch sử điều chỉnh của hóa đơn thì tại hóa đơn gốc vào tab HĐĐT click vào nút Chứng từ thay thế/điều chỉnh.

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

Hóa đơn gốc trên trang tra cứu HĐĐT của đối tác cũng sẽ chuyển sang trạng thái Điều chỉnh. Diễn giải trên hóa đơn điều chỉnh sẽ tự động ghi rõ điều chỉnh cho hóa đơn nào.
