## Tim hiểu về Markdown
---
  Thực hiện: **Phạm Văn Đạt**

  Cập nhập lần cuối: *12/2/2017*

## Mục lục 

[1.Github](#1)
  <ul>
    <li>[Khái niệm](#1.1)</li>
    <li>[Công dụng](#1.2)</li>
  </ul>
[2.Tạo repository đặt tên là `Web_dev`](#2)  
[3.Markdown](#3)
  <ul>
   <li>[Khái niệm](#3.1)</li>
   <li>[Công dụng](#3.1)</li>
  </ul>
[4.Cú pháp thường gặp](#4)  
[5.Cài đặt Sublime text](#5)      
[6.Các công cụ viết Markdown khác](#6)   
  <ul>
    <li>[Stackedit](#6.1)</li>
    <li>[Jbt](#6.2)</li>
    <li>[Tablesgenerator](#6.3)</li>
  </ul>

## Nội dung.

<a name="1"></a>
###I. Github. 

 <img src ="https://2.bp.blogspot.com/-XK_JfKB1lao/V1krlH5ihyI/AAAAAAAAAy8/nCeUfXPlfKo-MgU7aY6GgimeRcoy5T_IwCLcB/s1600/Github.jpg">

<a name="1.1"></a>
####1. Khái niệm.

 GitHub là kho lưu trữ các mã nguồn mở, tài liệu.

<a name="1.2"></a>
####2. Công dụng.

 GitHub chủ yếu được sử dụng để lưu trữ mã nguồn phần mềm, nhưng cũng thường được sử dụng với nhiều loại tập tin.

<a name="2"></a>
###II. Tạo repository đặt tên là `Web_dev`.

 - Đầu tiên bạn hãy tạo một tài khoản github trên https://github.com/.
 - Vào tài khoản của bạn.  

  <img src ="https://drive.google.com/drive/folders/0B_psBg7ZNak1R0dFd2Z6OUR0VE0">

 - Nhấp vào dấu cộng và chọn **New repository**.
 - Màn hình hiện lên.

  <img src ="https://drive.google.com/drive/folders/0B_psBg7ZNak1R0dFd2Z6OUR0VE0">

 - Phần **Repository name** bạn điền tên kho bạn muốn tạo. Mình đặt là `Web_dev`.
 - Có hai tùy chọn là **Punlic** nghĩa là mọi người đều có thể thấy nội dung của repository này, còn **Private** là chỉ mình bạn xem được nội dung này.
 - Còn 1 tùy chọn nữa đó là **Initialize this repository with a README** là repository có mặc định thêm 1 file README.md.
 - Cuối cùng bạn nhấp vào **Create repository** .
 - Như vậy là repository `Web_dev` đã được cài đặt thành công.

  <img src ="https://drive.google.com/drive/folders/0B_psBg7ZNak1R0dFd2Z6OUR0VE0">

<a name="3"></a>
###III. Markdown.

<a name="3.1"></a>
####1. Khái niệm.

  Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác.

<a name="3.2"></a>
####2. Công dụng.

 Markdown dùng để tạo các tập tin readme, viết tin nhắn trên các diễn đàn, và tạo văn bản có định dạng bằng một trình biên tập văn bản thô.

<a name="4"></a>
###IV. Cú pháp thường gặp.

####1. Thẻ tiêu đề

 Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6
 Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.

 Ví dụ:

`#1.Tiêu đề cấp 1`

#1.Tiêu đề cấp 1
 
`##2.Tiêu đề cấp 2`

##2.Tiêu đề cấp 2

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
 `
 `đoạn cần bo`
 `
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

<a name="5"></a>
###V. Cài đặt Sublime text

- Vào đường linh https://www.sublimetext.com/3 để Download file tương ứng với máy bạn đang dùng.

<img src="http://prntscr.com/e6fr6f.jpg">

- Tải về và cài mặc định.
- Chúng ta phải cài thêm [Package Control](https://packagecontrol.io/)
cho Sublime Text. Hướng dẫn cài đặt **Package Control** tại https://www.youtube.com/watch?v=sy0jf7TJTCM&t=36s.
- Giờ chúng ta bật **Sublime Text** lên và trong phần **Preferences** chúng ta chọn **Package Control**.

<img src="http://prntscr.com/e6fr8.jpg">

- Sau đó ta chọn **Install Package**

<img src="http://prntscr.com/e6fr9i.jpg">

- Giờ ta chỉ cần gõ các công cụ hỗ trợ như **ExportHTML, MarkdownPreview,...** và chọn là song.

<img src="http://prntscr.com/e6fra5.jpg">

<a name="6"></a>

###VI. Tìm hiểu các công cụ viết markdown khác

<a name="6.1"></a>
[Stackedit](https://stackedit.io/editor)

<img src ="http://4.bp.blogspot.com/-hs3_SsTZFgw/UsKTTtNWqiI/AAAAAAAArPE/dB4cAkuicSc/s1600/StackEdit.png">

<a name="6.2"></a>
[Markdown Editor](https://jbt.github.io/markdown-editor/)

<img src="https://camo.githubusercontent.com/34f55bf1b3200576253cfd348ff20a35e1e946c1/687474703a2f2f686f6d65706167652e756e697669652e61632e61742f7765726e65722e726f6269747a612f6d61726b646f776e2f73637265656e73686f742e706e67">

<a name="6.3"></a>
[Tablesgenerator](http://www.tablesgenerator.com/markdown_tables)

<img src="http://pic.accessify.com/thumbnails/777x423/t/tablesgenerator.com.png">

---
## Hoàn thành Task 01
---