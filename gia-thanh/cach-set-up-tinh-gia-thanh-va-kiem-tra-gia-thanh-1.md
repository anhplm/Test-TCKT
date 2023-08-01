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

# Cách kiểm tra giá thành

## Mô tả chung

Sau khi thực hiện các bước tính giá thành, người dùng cần kiểm tra lại xem đã đúng hay chưa. Nếu chưa thì làm sao để tìm ra sai sót để chỉnh sửa và chạy lại.

Tài liệu này tổng hợp 1 số bước để giúp người dùng kiểm tra tính hợp lý của giá thành.

## Kiểm tra sổ cái và sổ giá thành

### Kiểm tra sổ cái tài khoản 154 và dở dang cuối kỳ

* Nếu giá thành không có dở dang, mà sau khi chạy tính giá thành tài khoản 154 vẫn còn số dư là còn sai.
* Nếu giá thành có dở dang, thì số dư nợ tài khoản 154 phải bằng với giá trị dở dang cuối kỳ bên bảng giá thành.

Kiểm tra sổ cái 154 tại: _**Tổng hợp/ Báo cáo/ Sổ kế toán/ Sổ cái của 1 tài khoản**_

Kiểm tra giá trị dở dang cuối kỳ tại: _**Giá thành/ Báo cáo/ Báo cáo tổng hợp chi phí sản xuất theo yếu tố**_, cột Dở dang cuối kỳ.

### Kiểm tra sổ cái các tài khoản chi phí sản xuất

Các tài khoản chi phí sản xuất 621, 622, 627 không có số dư cuối kỳ. Do đó sau khi chạy các thao tác kết chuyển qua 154 mà còn dư thì giá thành đang sai.

Kiểm tra tại: _**Tổng hợp/ Báo cáo/ Sổ kế toán/ Sổ cái lên cho nhiều tài khoản**_

### Kiểm tra giá thành sản phẩm theo từng chi phí

Đây là việc người dùng kiểm tra giá thành đơn vị của từng sản phẩm nhập kho trong kỳ theo từng yếu tố chi phí. Có thể so sánh, đối chiếu với kỳ trước để xem có phát sinh nào bất thường hay không.

Kiểm tra tại: _**Giá thành/ Báo cáo/ Báo cáo giá thành sản phẩm theo nhóm yếu tố**_

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

## Kiểm tra chi tiết giá thành

Khi có sai sót từ các bước kiểm tra tổng hợp trên, người dùng thực hiện tiếp các bước kiểm tra chi tiết có thể làm sai giá thành.

### Kiểm tra các phiếu nhập kho sản xuất

Nếu có phiếu nhập kho sản xuất không tính được giá, thì kiểm tra các đầu mục:

* Mã giao dịch trên phiếu phải là Nhập thành phẩm, không phải loại này thì không áp được giá.
* Mã sản phẩm nhập kho trên phiếu nhập phải được khai báo là Thành phẩm/ Bán thành phẩm.

### Kiểm tra phát sinh tài khoản 154

Thông thường, phát sinh của tài khoản 154 chỉ liên quan đến tính giá thành sản xuất. Do đó, nếu có nghiệp vụ phát sinh khác mà không liên quan giá thành hạch toán vào tài khoản này hoặc ngược lại sẽ sai. Chi tiết:

* Phiếu nhập kho thành phẩm tài khoản có không đưa vào 154 --> giá thành có, sổ cái không có phát sinh của 154.
* Hạch toán tài khoản 154 ở các nghiệp vụ không liên quan tới tính giá thành.

### Các báo cáo kiểm tra giá thành khác

#### Báo cáo Các yếu tố có DDĐK hoặc phát sinh nhưng không có DDCK và nhập kho

Đường dẫn: _**Giá thành/Báo cáo/ Các yếu tố có DDĐK hoặc phát sinh nhưng không có DDCK và nhập kho**_

Để kiểm tra các yếu tố chi phí phát sinh, nhưng không được tính vào giá thành, không có nhập kho trong kỳ,người dùng có thể dùng báo cáo này để kiểm tra

<figure><img src="../.gitbook/assets/Giá thành 18.png" alt=""><figcaption></figcaption></figure>

#### Báo cáo Chứng từ chưa nhập theo đối tượng tập hợp chi phí

Đường dẫn: _**Giá thành/Báo cáo/Chứng từ chưa nhập theo đối tượng tập hợp chi phí**_

Các yếu tố tập hợp tính giá thành, khi nhập liệu cần chỉ rõ đối tượng tập hợp chi phí, người dùng quên nhập dẫn đến tập hợp thiếu chi phí, có thể dùng báo cáo này để kiểm tra thao tác nhập liệu trên chứng từ

<figure><img src="../.gitbook/assets/Giá thành 19.png" alt=""><figcaption></figcaption></figure>

#### Vật tư xuất sản xuất nhưng chưa khai báo định mức

Đường dẫn: _**Giá thành/Báo cáo/Vật tư xuất sản xuất nhưng chưa khai báo định mức**_

Trong bài toán giá thành mà vật tư không được chỉ trực tiếp cụ thể cho đối tượng tập hợp giá thành nào mà phải phân bổ qua định mức vật tư, khi chạy chức năng “Vật tư xuất sản xuất nhưng chưa khai báo định mức”, chương trình sẽ báo những phiếu xuất kho vật tư cho sản xuất không nằm trong danh sách các vật tư trong chi tiết tổng tất cả các định mức hiệu lực.

#### Vật tư có khai báo định mức nhưng các TP không sản xuất

Đường dẫn: _**Giá thành/Báo cáo/Vật tư có khai báo định mức nhưng các TP không sản xuất**_

Dùng để kiểm tra trong trường hợp một vật tư có xuất cho sản xuất nhưng không tồn tại ít nhất một sản phẩm nhận chi phí (không nhập bất kỳ sản phẩm nào có dùng vật tư đó)

Sử dụng trong bài toán giá thành mà vật tư không được chỉ trực tiếp cụ thể cho đối tượng tập hợp giá thành nào mà phải phân bổ qua định mức vật tư.

#### Các yếu tố không được phân bổ trong kỳ

Đường dẫn: _**Giá thành/Báo cáo/Các yếu tố không được phân bổ trong kỳ**_

Dùng để kiểm tra trong trường hợp một yếu tố chi phí có phát sinh trong kỳ nhưng không tồn tại ít nhất một sản phẩm nào nhận chi phí.

#### Thành phẩm nhập kho sai với thành phẩm trong lệnh sản xuất

Đường dẫn: _**Giá thành/Báo cáo/Thành phẩm nhập kho sai với thành phẩm trong lệnh sản xuất**_

Trong bài toán có đối tượng tập hợp giá thành là lệnh sản xuất, nếu phiếu nhập kho thành phẩm không nằm trong danh sách các sản phẩm trong chi tiết tổng tất cả các lệnh hiệu lực thì chương trình sẽ báo. Trường hợp sai sót này có thể do bộ phận sản xuất thực hiện nhập kho với mã không chính xác.

#### Lệnh sản xuất có DDĐK - không nhập TP nhưng khai báo kết lệnh

Đường dẫn: _**Giá thành/Báo cáo/Thành phẩm nhập kho sai với thành phẩm trong lệnh sản xuất**_

Chương trình sẽ kiểm tra ngày hiệu lực của lệnh sản xuất (được khai báo trong chức năng “lệnh sản xuất”) để so sánh với kỳ phát sinh của số liệu. Nếu lệnh sản xuất có dở dang đầu kỳ nhưng không nhập thành phẩm trong kỳ mà đã khai báo kết thúc lệnh trong kỳ, chức năng này sẽ cảnh báo đối với những lệnh sản xuất đó.

#### Các lệnh sản xuất đã kết thúc kỳ trước nhưng vẫn có phát sinh

Đường dẫn: _**Giá thành/Báo cáo/Thành phẩm nhập kho sai với thành phẩm trong lệnh sản xuất**_

Chương trình sẽ kiểm tra ngày hiệu lực của lệnh sản xuất (được khai báo trong menu “lệnh sản xuất”) để so sánh với kỳ phát sinh của số liệu. Trong trường hợp thời điểm hiệu lực bé hơn chương trình sẽ thông báo.

#### Kiểm tra đối tượng tính giá thành trong PXK và PNK

Đường dẫn: _**Giá thành/Báo cáo/Thành phẩm nhập kho sai với thành phẩm trong lệnh sản xuất**_

Kiểm tra giữa việc xuất kho NVL tập hợp trực tiếp cho các đối tượng tính giá thành (Bộ phận – LSX - Sản phẩm) có phù hợp với việc nhập kho bán sản phẩm tương ứng hay không. Chương trình sẽ hiện ra các chứng từ xuất kho NVL và nhập kho sản phẩm hoàn thành mà xảy ra tình trạng có xuất kho nhưng không có nhập kho tương ứng và ngược lại.
