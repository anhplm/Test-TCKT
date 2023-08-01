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

# \[DONE] Phân bổ tiền trả cho hóa đơn

## Mô tả nghiệp vụ

Phân bổ trả tiền hàng cho các hóa đơn được dùng trong trường hợp có theo dõi công nợ phải trả theo hóa đơn và khi trả tiền cho nhà cung cấp chưa chỉ trực tiếp trả cho hóa đơn nào. Sau khi hoàn thành thanh toán, thực hiện phân bổ cho hóa đơn để cấn trừ trực tiếp cho hóa đơn.

## Các bước thao tác

**Bước 1:** Vào màn hình phân bổ theo đường dẫn: _**Kế toán/ Mua hàng/ Tiện ích/ Phân bổ tiền hàng trả cho các hóa đơn**_

**Bước 2:** Nhập các thông tin để lọc chứng từ thanh toán và nhấn **Đồng ý.**

<figure><img src="../../.gitbook/assets/Phân bổ tiền trả cho hóa đơn 01.png" alt=""><figcaption><p>Nhập điều kiện lọc Phân bổ</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Nhập ngày từ/đến là ngày phát sinh chứng từ thanh toán.
* Loại chứng từ: gồm 3 lựa chọn:
  * Tất cả: lọc tất cả chứng từ thanh toán bao gồm chứng từ đã phân bổ hết và chưa phân bổ hết.
  * Chưa phân bổ hết: để lọc các chứng từ thanh toán chưa phân bổ hết số tiền cho các hóa đơn (vẫn còn tiền để phân bổ tiếp).
  * Đã phân bổ hết: để lọc các chứng từ thanh toán đã phân được phân bổ hết, loại này thường được dùng khi muốn xóa phân bổ đã xử lý.
* Người dùng có thể chọn 1 trong 3 loại Xử lý sau:
  * Người dùng tự phân bổ: nếu chọn loại này, người dùng sẽ tự chọn các hóa đơn muốn phân bổ .
  * Gợi ý tự động theo ngày hóa đơn, số hóa đơn: nếu chọn loại này, chương trình sẽ tự động tick gợi ý số tiền phân bổ xuống cho các hóa đơn theo thứ tự **ưu tiên theo ngày hóa đơn** (hóa đơn có ngày nhỏ hơn thì được phân bổ trước, nếu trùng ngày thì sẽ ưu tiên theo số hóa đơn).
  * Gợi ý tự động theo hạn thanh toán, số hóa đơn: nếu chọn loại này, chương trình sẽ tự động tick gợi ý số tiền phân bổ xuống cho các hóa đơn theo thứ tự **ưu tiên theo hạn thanh toán** (hóa đơn nào đến hạn thanh toán trước thì được ưu tiên phân bổ trước, nếu cùng hạn thanh toán thì sẽ ưu tiên theo số hóa đơn).

**Bước 3:** Xử lý phân bổ

<figure><img src="../../.gitbook/assets/Phân bổ tiền trả cho hóa đơn 02.png" alt=""><figcaption><p>Thao tác phân bổ</p></figcaption></figure>

Chọn phiếu chi muốn phân bổ:

* Nếu chọn loại xử lý tự phân bổ thì người dùng tự tick vào hóa đơn muốn phân bổ.
* Nếu chọn loại xử lý có gợi ý thì sẽ thấy chương trình có hiện tick sẵn các hóa đơn theo điều kiện xử lý, có thể bỏ tick và thay đổi sang chứng từ khác (nếu cần).

Và nhấn nút **Lưu phân bổ.**
