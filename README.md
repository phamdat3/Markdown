## Tim hiểu về Markdown
---
  Thực hiện: **Phạm Văn Đạt**

  Cập nhập lần cuối: *12/2/2017*

## Mục lục 

**- Github**
  <ul>
    <li>Nội dung</li>
    <li>Công dụng</li>
  </ul>
**- Tạo repository đặt tên là `Web_dev`**
**- Markdown** 
  <ul>
    <li>Nội dung</li>
    <li>Công dụng</li>
  </ul>
**- Cú pháp thường gặp**
**-Cài đặt Sublime text** 
**- các công cụ viết Markdown khác** 
  <ul>
    <li>Stackedit</li>
    <li>Jbt</li>
    <li>Tablesgenerator</li>
  </ul>

## Nội dung.

###I. Github. 

 <img src ="http://prntscr.com/e6ed4u">

####1. Nội dung.

 GitHub là kho lưu trữ các mã nguồn mở, tài liệu.

####2. Công dụng.

 GitHub chủ yếu được sử dụng để lưu trữ mã nguồn phần mềm, nhưng cũng thường được sử dụng với nhiều loại tập tin.

###II. Tạo repository đặt tên là `Web_dev`.

 - Đầu tiên bạn hãy tạo một tài khoản github trên https://github.com/.
 - Vào tài khoản của bạn.  

  <img src ="http://prntscr.com/e64meb" tipe ="img.jpg">
 
 - Nhấp vào dấu cộng và chọn **New repository**.
 - Màn hình hiện lên.  
 
  <img src ="http://prntscr.com/e64o3u" tipe ="img.jpg">
 
 - Phần **Repository name** bạn điền tên kho bạn muốn tạo. Mình đặt là `Web_dev`.
 - Có hai tùy chọn là **Punlic** nghĩa là mọi người đều có thể thấy nội dung của repository này, còn **Private** là chỉ mình bạn xem được nội dung này.
 - Còn 1 tùy chọn nữa đó là **Initialize this repository with a README** là repository có mặc định thêm 1 file README.md.
 - Cuối cùng bạn nhấp vào **Create repository**
 - Như vậy là repository `Web_dev` đã được cài đặt thành công.  
 
  <img src ="http://prntscr.com/e64ooh" tipe ="img.jpg">  
  
###III. Markdown.

####1. Nội dung.

  Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác.

####2. Công dụng.

 Markdown dùng để tạo các tập tin readme, viết tin nhắn trên các diễn đàn, và tạo văn bản có định dạng bằng một trình biên tập văn bản thô.

###IV. Cú pháp thường gặp.

####1. Thẻ tiêu đề

 Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6
 Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.

 Ví dụ:

`#1.Tiêu đề cấp 1`
 #1.Tiêu đề cấp 1
 
`##2.Tiêu đề cấp 2`

 2.Tiêu đề cấp 2

`######6.Tiêu đề cấp 6`

 ######6.Tiêu đề cấp 6

####2. Chèn link, chèn ảnh
 
 Để chèn hyperlink bạn chỉ cần paste luôn linh đó vào file .md
 
 `https://github.com`
 
 https://github.com
 
 Hoặc bạn cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link
 
 `[Github](https://github.com)`
 
 Kết quả là:
 
 [Github](https://github.com)
 
 Để chèn ảnh thì bạn hãy sử dụng cú pháp sau:
 
 `<img src="link anh muon dang">`

####3. Ký tự in đậm, in nghiêng

 Để in đậm một đoạn text bạn chỉ cần làm như sau:
 `**in đậm**`
 **in đậm**
 Để in nghiên một đoạn text bạn chỉ cần làm như sau:
 `*in nghiêng*`
 *in nghiêng*

####4. Trích dẫn, bo chữ
 
 Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:
 ` `đoạn cần bo` `
 Kết quả là: 
 `đoạn cần bo`
 Để làm nổi bật một đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp như ví dụ sau:
 
 ```sh
 
 auto eth0
 iface eth0 inet static
 ipaddress 10.10.10.10
 netmask 255.255.255.0
 gateway 10.10.10.1
 dns-nameservers 8.8.8.8

```
Kết quả như sau:

 ```sh
 auto eth0
 iface eth0 inet static
 ipaddress 10.10.10.10
 netmask 255.255.255.0
 gateway 10.10.10.1
 dns-nameservers 8.8.8.8
 ```

####5. Gạch đầu dòng
 
 Để sử dụng gạch đầu dòng bạn chỉ cần sử dụng cú pháp sau:
```
- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
```

Kết quả là:

- Gạch đầu dòng thứ nhất
  <ul>
   <li>Thụt với đầu dòng 1</li>
   <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
   <li>Thụt với đầu dòng 2</li>
   <li>Thụt với đầu dòng 2</li>
  </ul>

####6. Tạo bảng

Bạn có thể sử dụng cú pháp sau để tạo bảng:

```
| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
```

Kết quả là:

| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |