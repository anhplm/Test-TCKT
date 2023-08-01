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

# \[DONE] Bán dịch vụ thu tiền ngay

## Mô tả

Khi bán dịch vụ thu tiền ngay của khách hàng, ghi nhận trực tiếp việc thu tiền trên hóa đơn.

Về mặt xử lý trên phần mềm, vẫn đi qua tài khoản công nợ trung gian và hỗ trợ tính năng tạo phiếu thu ngay từ hóa đơn.&#x20;

## Định khoản

**Hạch toán doanh thu:**

Nợ TK 131 Phải thu khách hàng

Có TK 5113 Doanh thu cung cấp dịch vụ

Có TK 3331 Thuế GTGT phải nộp

**Thu tiền bán hàng:**

Nợ TK 111, 112 Tiền mặt; Tiền gửi ngân hàng

Có TK 131 Phải thu khách hàng

## Các bước thực hiện

**Bước 1:** Vào hóa đơn theo đường dẫn: _**Bán hàng/ Hóa đơn bán ra/ Hóa đơn bán dịch vụ.**_&#x20;

**Bước 2:** Chọn biểu tượng **Thêm** trên thanh công cụ để thêm hóa đơn mới.

**Bước 3:** Sau khi nhập các thông tin, tick chọn nút **Thu tiền.** Trên hóa đơn xuất hiện tab **Thông tin thanh toán.**&#x20;

**Bước 4:** Ở tab **Thông tin thanh toán**, chọn mã hình thức. Chương trình sẽ tự động hiện các thông tin còn lại, đồng thời hiện Số tiền thanh toán bằng Tổng thanh toán trên hóa đơn.

Có thể nhập lại số tiền này nếu khách hàng chỉ thanh toán trước 1 phần, phần còn lại chưa thanh toán sẽ được ghi nhận vào công nợ.

<figure><img src="../../.gitbook/assets/bán dv thu tiền 01.png" alt=""><figcaption><p>Hóa đơn bán dịch vụ</p></figcaption></figure>

**Bước 5:** Chọn biểu tượng **In** trên chứng từ thanh công cụ để in chứng từ.

**Lưu ý:**

Sau khi lưu hóa đơn, ở tab thông tin thanh toán sẽ hiện chứng từ thanh toán. Có thể click vào số chứng từ thanh toán này để xem chứng từ.

<figure><img src="../../.gitbook/assets/bán dv thu tiền 02.png" alt=""><figcaption></figcaption></figure>
