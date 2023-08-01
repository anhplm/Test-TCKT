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

# Cập nhật dự toán ngân sách

## Mô tả nghiệp vụ

Các khoản chi phí trong quá trình hoạt động sản xuất kinh doanh diễn ra thường xuyên, các khoản chi phí được dự trù để kiểm soát các khoản chi không hợp lý, hoặc chi vượt dự toán.

## Các bước thực hiện

**Bước 1: Khai báo danh mục chỉ tiêu ngân sách**

_**Đường dẫn**_: Vào phân hệ **Ngân sách/ Danh mục chỉ tiêu ngân sách**, nhấn **Thêm** để tạo danh mục mới.

<figure><img src="../.gitbook/assets/Cập nhật dự toán ngân sách.png" alt=""><figcaption></figcaption></figure>

Giải thích các trường thông tin

* Mã chỉ tiêu: do người dùng tự đặt
* Tên chỉ tiêu, tên khác: do người dùng tự đặt
* Khai báo trường thông tin chung:
  * Loại phát sinh:
    * Nợ: lấy phát sinh bên Nợ của tài khoản.
    * Có: lấy phát sinh bên Có của tài khoản.
    * Nợ - Có: lấy phát sinh bên Nợ - phát sinh bên Có
    * Có – Nợ: lấy phát sinh bên Có - phát sinh bên Nợ
  * Giá trị: có 3 sự lựa chọn
    * Bình thường: khi lấy các chỉ tiêu, giá trị âm hoặc dương khi lên báo cáo sẽ thể hiện như kết quả tính
      * Không âm: chỉ lấy giá trị không âm. Ví dụ nếu chỉ tiêu khai báo lấy số dư bên Nợ tài khoản 111, nếu tài khoản này có số dư bên Có thì sẽ không lấy.
      * Đảo dấu: trường hợp muốn đảo dấu kết quả tính thì chọn đảo dấu, nếu kết quả là dương thì lên báo cáo là âm, nếu kết quả âm thì lên báo cáo là dương.
  * Tài khoản đối ứng, tài khoản giảm trừ, tài khoản: dùng để khai báo các tài khoản cần nhặt dữ liệu.
* Tab điều kiện khác: dùng để khai báo điều kiện để lấy dữ liệu theo đơn vị cơ sở, khách hàng, các đối tượng cần theo dõi thêm như bộ phận, mã phí, lệnh sản xuất,...
* Nhấn **Lưu** để lưu lại chỉ tiêu.

**Bước 2: Cập nhật dự toán ngân sách**

Vào cập nhật dự toán theo đường dẫn **Ngân sách/Nhập liệu/Cập nhật dự toán ngân sách**

<figure><img src="../.gitbook/assets/Cập nhật dự toán ngân sách 2.png" alt=""><figcaption></figcaption></figure>

* Chọn mẫu ngân sách: chọn mẫu báo cáo đã tạo trước đó để khai báo chỉ tiêu
* Năm: chọn năm cần lập ngân sách
* Đơn vị: mã đơn vị cơ sở được lập ngân sách, mặc nhiên theo đơn vị truy nhập. (không bắt buộc nhập)
* Mã bộ phân, mã vụ việc: phòng ban và mã vụ việc tương ứng sẽ được lập ngân sách (không bắt buộc nhập)

**Bước 3:** Sau khi chọn mẫu báo cáo và năm khai báo chỉ tiêu, trên thanh công cụ bấm thêm để thêm mới chỉ tiêu

<figure><img src="../.gitbook/assets/Cập nhật dự toán ngân sách 3.png" alt=""><figcaption></figcaption></figure>

* Khai báo thông tin chung
  * Năm: năm áp dụng chỉ tiêu
  * Đơn vị: nếu có nhiều chi nhánh thì chọn chi nhánh áp dụng
  * Mã bộ phận: nếu áp dụng cụ thể cho một bộ phận
  * Mã vụ việc: nếu áp dụng cụ thể cho một vụ việc
  * Mã chỉ tiêu: chọn chỉ tiêu đã khai báo ở danh mục chỉ tiêu
* Khai báo thông tin kế hoạch: khai báo chi tiết chi phí dự trù cho từng tháng, có thể khai báo giá trị ngoại tệ và VND.
