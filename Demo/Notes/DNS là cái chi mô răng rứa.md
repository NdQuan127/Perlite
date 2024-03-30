---
up:
  - "[[../Maps/Firefox MOC]]"
tags:
  - on/firefox
---


> Bài viết dưới đây giải thích DNS là gì, hoạt động của DNS ra sao và những khái niệm cơ bản khác. Bài viết có tham khảo, sử dụng nguồn từ các bài viết trên internet.

## DNS là gì?
- DNS là viết tắt của cụm từ Domain Name System, mang ý nghĩa đầy đủ là hệ thống phân giải tên miền.
- DNS chào đời vào năm 1984 nhờ 4 sinh viên UC Berkeley, là hệ thống cho phép thiết lập/tra cứu tương ứng giữa địa chỉ IP và tên miền.
- DNS được ví như cuốn danh bạ của Internet. Chúng ta truy cập thông tin trên Internet thông qua các tên miền, còn các trình duyệt web tương tác thông qua địa chỉ IP (Internet Protocol). DNS dịch tên miền thành địa chỉ IP để trình duyệt có thể tải tài nguyên Internt và ngược lại.
![[../Utilities/Images/theinternet-dns.svg]]
## Các loại bản ghi DNS
Bản ghi DNS (DNS records) là các hướng dẫn nằm trong máy chủ DNS có thẩm quyền (Authoritative DNS servers) và cung cấp thông tin về tên miền bao gồm địa chỉ IP nào được liên kết với tên miền đó và cách xử lý các yêu cầu cho tên miền đó. Các bản ghi này bao gồm 1 loạt các tệp văn bản được viết bằng cú pháp DNS. Cú pháp DNS chỉ là một chuỗi ký tự được sử dụng làm lệnh cho máy chủ DNS phải làm gì.
