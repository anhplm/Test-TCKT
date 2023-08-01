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

# \[DONE] Lập hóa đơn từ đơn hàng mua trong nước

Mua hàng theo đơn hàng thì khi nhà cung cấp giao hàng và nhận hóa đơn, người dùng lập hóa đơn mua hàng kế thừa dữ liệu từ đơn hàng.

## Các bước thực hiện

**Bước 1:** Lập hóa đơn mua trong nước theo đường dẫn: _**Mua hàng/ Hóa đơn mua vào/ Hóa đơn mua hàng trong nước.**_ Chọn nút **Thêm** trên thanh công cụ để thêm mới phiếu.

**Bước 2:** Nhập mã nhà cung cấp và chọn nút kế thừa **Đơn hàng.**

<figure><img src="../../.gitbook/assets/kế thừa mua hàng 01.png" alt=""><figcaption><p>Chọn nút kế thừa trên hóa đơn mua trong nước</p></figcaption></figure>

**Bước 3:** Nhập ngày lọc đơn hàng và nhấn nút tìm kiếm ở trường Số chứng từ.

**Bước 4:** Tick chọn đơn hàng cần lấy dữ liệu và nhấn **Đồng ý**.

<figure><img src="../../.gitbook/assets/kế thừa mua hàng 02.png" alt=""><figcaption><p>Chọn đơn hàng cần kế thừa</p></figcaption></figure>

**Các thông tin cần chú ý:**

* Ngày lọc đơn hàng là ngày chứng từ của đơn hàng.
* Nút tick ở dòng tên cột là nút tick chọn tất cả chứng từ.

**Bước 5:** Chọn các dòng vật tư muốn kế thừa và nhấn **Đồng ý**.

<figure><img src="../../.gitbook/assets/kế thừa mua hàng 03.png" alt=""><figcaption></figcaption></figure>

**Các thông tin cần lưu ý:**

* Có 2 loại Xử lý:
  * Thêm vào chi tiết: Giữ nguyên các dòng đã nhập và thêm các dòng vật tư kế thừa xuống phía dưới.
  * Xóa hết chi tiết và thêm mới: Xóa hết các dòng đã nhập và thêm các dòng vật tư kế thừa.
* Số lượng lấy: là số lượng lấy lên đơn hàng, có thể nhập lại số này.&#x20;
* Số lượng còn lại = Số lượng - Số lượng đã lấy trước đó.&#x20;
* Nếu không kế thừa hết số lượng trên đơn hàng thì đơn hàng này sẽ chuyển trạng thái đang thực hiện và có thể kế thừa tiếp số lượng còn lại bằng hóa đơn khác.

**Bước 6:** Nhập các thông tin khác trên hóa đơn và nhấn **Lưu.**

<figure><img src="../../.gitbook/assets/kế thừa mua hàng 04.png" alt=""><figcaption><p>Hóa đơn kế thừa dữ liệu từ đơn hàng</p></figcaption></figure>
