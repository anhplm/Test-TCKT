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

# \[DONE] Trả lại hàng đã mua về nhập kho

## Mô tả nghiệp vụ

Trong trường hợp doanh nghiệp khi mua hàng về đã nhập kho, sau đó có phát sinh hàng hỏng hóc cần trả lại thì kế toán sẽ hạch toán chứng từ Phiếu xuất trả lại nhà cung cấp để ghi nhận phần xuất trả.

## Định khoản

* Trường hợp người mua trả hàng và xuất hóa đơn trả, kê thuế đầu ra
  * Nợ 331 Phải trả người bán
  * Có 152, 153, 156 Nguyên liệu, công cụ, hàng hóa\
    Có 333 Thuế đầu ra
* Trường hợp người mua trả hàng và xuất hóa đơn trả, kê thuế đầu vào
  * Nợ 331 Phải trả người bán\
    Nợ 133 Thuế đầu vào (khi lên bản kê thuế đầu vào sẽ là giá trị âm)
  * Có 152, 153, 156 Nguyên liệu, công cụ, hàng hóa

## **Các bước thực hiện**

**Bước 1:** Vào chứng từ Phiếu xuất trả lại nhà cung cấp theo đường dẫn **Kế toán/ Mua hàng/ Nhập liệu/ Phiếu xuất trả lại nhà cung cấp**

**Bước 2:** Nhấn **Thêm** để tạo mới chứng từ.

<figure><img src="../../.gitbook/assets/Phiếu xuất trả lại ncc 2.png" alt=""><figcaption></figcaption></figure>

**Bước 3:** Kế thừa dữ liệu từ hoá đơn mua hàng đã nhập

Hướng dẫn thao tác kế thừa dữ liệu [tại đây](http://127.0.0.1:5000/s/uQIjY7kVhyePdTM2Jf1L/tien-ich-khac/tinh-nang-ke-thua-du-lieu)

**Bước 4:** Kiểm tra lại dữ liệu kế thừa, nhập liệu thêm các thông tin theo dõi thêm nếu có, sau đó nhấn **Lưu** để lưu phiếu.

<figure><img src="../../.gitbook/assets/Phiếu xuất trả lại ncc.png" alt=""><figcaption></figcaption></figure>

Lưu ý: Trường hợp doanh nghiệp xuất trả hàng đồng thời xuất hoá đơn cho nhà cung cấp thì sẽ tick vào Kê thuế đầu ra ở tab Thuế, trạng thái HDDT là Chờ phát hành, sau đó thực hiện phát hành hoá đơn tương tự Hoá đơn bán.

<figure><img src="../../.gitbook/assets/Phiếu xuất trả lại ncc 3.png" alt=""><figcaption></figcaption></figure>
