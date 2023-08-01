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

# \[DONE] Bù trừ công nợ

## Mô tả nghiệp vụ

Khi một đối tượng vừa là khách hàng, vừa là nhà cung cấp (vừa có công nợ phải thu, vừa có công nợ phải trả), hoặc có thể đối trừ công nợ giữa các khách hàng, đối trừ công nợ giữa nhà cung cấp và khách hàng, kế toán sẽ xác định giá trị công nợ phải thu và giá trị công nợ phải trả của đối tượng, thực hiện đối trừ công nợ.

## **Định khoản**

**Bù trừ cùng đối tượng:**

Nợ TK 331 Phải trả cho người bán (A)

Có TK 131 Phải thu khách hàng (A)

**Bù trừ khác đối tượng:**

Trường hợp: Nhà cung cấp

&#x20;                    Nợ TK 331 Phải trả cho người bán (A)

&#x20;                    Có TK 331 Phải trả cho người bán (B)

Trường hợp: Khách hàng

&#x20;                    Nợ TK 131 Phải thu cho người mua (A)

&#x20;                    Có TK 131 Phải thu cho người mua (B)

## **Các bước thực hiện**

**Bước 1:** Vào phân hệ **Bán hàng/ Nhập liệu/Điều chỉnh, cấn trừ công nợ/Chứng từ phải trả khác, chứng từ bù trừ công nợ**

**Bước 2:** Nhấn **thêm** để thêm mới chứng từ.

<figure><img src="../../.gitbook/assets/Cấn trừ công nợ.png" alt=""><figcaption></figcaption></figure>

* Khai báo các thông tin chung: số chứng từ, ngày hạch toán, diễn giải, trạng thái,…
* Khai báo thẻ Chi tiết: tài khoản, mã khách, phát sinh nợ, phát sinh có,…
* Nhấn **Lưu**.
* Chọn biểu tượng **In** trên thanh công cụ để in chứng từ.

**Lưu ý**: Trên một chứng từ có nhiều tài khoản Nợ và nhiều tài khoản Có, sẽ dùng trường nhóm định khoản để chương trình biết được tài khoản nào đối ứng với nhau. Nếu trên một chứng từ chỉ có một tài khoản Nợ, một tài khoản Có hoặc nhiều tài khoản Nợ, một tài khoản Có hoặc nhiều tài khoản Có, một tài khoản Nợ thì không cần nhập trường nhóm định khoản này.
