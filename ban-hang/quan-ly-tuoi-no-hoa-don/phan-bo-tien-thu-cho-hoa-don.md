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

# \[DONE] Phân bổ tiền thu cho hóa đơn

Phân bổ tiền hàng cho các hóa đơn được dùng trong tình huống thu khoản cọc trước, thu một khoản tiền mà không biết thu cho những hóa đơn nào. Sau khi hoàn thành thanh toán, thực hiện phân bổ cho hóa đơn để cấn trừ trực tiếp cho hóa đơn.

## Hướng dẫn thao tác

**Bước 1:** Lọc các chứng từ thu tiền cần phần bổ (loại chứng từ: 2. Chi theo đối tượng)

Đường dẫn: _**Kế toán/ Bán hàng/ Tiện ích/ Phân bổ thu tiền cho các hóa đơn**_

<figure><img src="../../.gitbook/assets/Phân bổ tiền thu cho hóa đơn 01.png" alt=""><figcaption><p>Nhập điều kiện lọc Phân bổ</p></figcaption></figure>

**Các thông tin cần lưu ý:**

* Nhập ngày từ/đến là ngày chứng từ của chứng từ thanh toán.
* Loại chứng từ: gồm 3 lựa chọn:
  * Tất cả: lọc tất cả chứng từ thanh toán bao gồm chứng từ đã phân bổ hết và chưa phân bổ hết.
  * Chưa phân bổ hết: để lọc các chứng từ thanh toán chưa phân bổ hết số tiền cho các hóa đơn (vẫn còn tiền để phân bổ tiếp).
  * Đã phân bổ hết: để lọc các chứng từ thanh toán đã phân được phân bổ hết, loại này thường được dùng khi muốn xóa phân bổ đã xử lý.
* Người dùng có thể chọn 1 trong 3 loại Xử lý sau:
  * Người dùng tự phân bổ: nếu chọn loại này, người dùng sẽ tự chọn các hóa đơn muốn phân bổ .
  * Gợi ý tự động theo ngày hóa đơn, số hóa đơn: nếu chọn loại này, chương trình sẽ tự động tick gợi ý số tiền phân bổ xuống cho các hóa đơn theo thứ tự ưu tiên theo ngày hóa đơn (hóa đơn có ngày nhỏ hơn thì được phân bổ trước, nếu trùng ngày thì sẽ ưu tiên theo số hóa đơn).
  * Gợi ý tự động theo hạn thanh toán, số hóa đơn: nếu chọn loại này, chương trình sẽ tự động tick gợi ý số tiền phân bổ xuống cho các hóa đơn theo thứ tự ưu tiên theo hạn thanh toán (hóa đơn nào đến hạn thanh toán trước thì được ưu tiên phân bổ trước, nếu cùng hạn thanh toán thì sẽ ưu tiên theo số hóa đơn).
* Dấu check chọn “Tự dộng lưu phân bổ theo gợi ý”: nếu check vào nút này thì khi nhấn Đồng ý chương trình sẽ tự động phân bổ hàng loạt theo gợi ý đã chọn ở mục “Xử lý” và lưu luôn. Khi chọn nút này người dùng cần nhập mã trường ngoại tệ.

_Chú ý:_ _Khi sử dụng tính năng này đối với các chứng từ đã phân bổ hoặc dữ liệu kỳ trước. Hệ thống sẽ tự động xóa kết quả đã phân bổ cũ và tự động phân bổ theo gợi ý._

**Bước 2:** Xử lý phân bổ

Sau khi nhấn Đồng ý ở màn hình lọc

<figure><img src="../../.gitbook/assets/Phân bổ tiền thu cho hóa đơn 02.png" alt=""><figcaption><p>Thao tác phân bổ</p></figcaption></figure>

Chọn phiếu thu muốn phân bổ:

* Nếu chọn loại xử lý tự phân bổ thì người dùng tự tick vào hóa đơn muốn phân bổ.
* Nếu chọn loại xử lý có gợi ý thì sẽ thấy chương trình có hiện tick sẵn các hóa đơn theo điều kiện xử lý, có thể bỏ tick và thay đổi sang chứng từ khác (nếu cần).

Và nhấn **Lưu phân bổ.**

Trường hợp muốn xóa phân bổ thì chọn phiếu thu đã phân bổ và tick vào hóa đơn muốn xóa, nhấn Xóa phân bổ. Nếu phiếu thu đã phân bổ hết thì lọc lại theo điều kiện Loại chứng từ Đã phân bổ hết.

