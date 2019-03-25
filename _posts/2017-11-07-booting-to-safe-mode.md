---
layout: single
classes: wide
title: Cách khởi động vào chế độ Safe Mode của Windows
description: Các bước để khởi động vào chế độ Safe Mode của Windows 7, 8, 10
categories: [troubleshooting]
tags: [client, diagnostic, windows]
toc: true
---

## Chế độ Safe Mode là gì?

Chế độ **Safe Mode** của Windows là chế độ khởi động của hệ điều hành mà chỉ kèm theo các thành phần hệ thống vốn có của hệ điều hành từ ban đầu.

Điều đó có nghĩa không thêm các *trình điều khiển* (*drivers*) đã được cài đặt, các *tiến trình tự khởi động* đã được thêm vào, vv..

Mục đích để người sử dụng theo dõi và phân loại nguyên nhân lỗi của máy có thể phát sinh từ đâu, bản thân hệ điều hành, các trình điều khiển đã cài đặt hay là phần cứng.

## Các bước thao tác để vào chế độ Safe Mode

Có nhiều cách để thực hiện, tương ứng với nhiều phiên bản khác nhau của hệ điều hành Windows.

### Áp dụng cho mọi phiên bản Windows

1. Bấm tổ hợp phím **Windows + R** để bật hộp thoại **Run**.
2. Gõ lệnh `msconfig`,  sau đó **Enter** hoặc **OK** để bật cửa sổ **System Configuration.**

    ![**Windows + R** để bật hộp thoại **Run**.](/assets/media/171107-safe-mode-booting/2019-03-23_11-28-04.png)

3. Chuyển sang thẻ **Boot**, bấm tick vào **Safe mode**. Nếu bạn cần sử dụng mạng trong Safe Mode, tick vào ô vuông **Network** nếu muốn. Chỉ hỗ trợ mạng dây - Ethernet.

    ![Chuyển sang thẻ **Boot**, bấm tick vào **Safe mode**.](/assets/media/171107-safe-mode-booting/2019-03-23_11-31-08.png)

4. Bấm **OK** để lưu thay đổi, đóng cửa sổ và khởi động lại máy.
    - Nếu được hỏi, chọn **Reboot Now** để khởi động lại ngay; hoặc **Reboot Later** để chủ động thực hiện việc khởi động lại sau.
    - Sau khi khởi động vào **Safe Mode**, giao diện không hình nền, hay nền màu đen.
    - Thực hiện các thao tác mở, duyệt, sao chép file bình thường.

### Trở lại chế độ bình thường

Để trở lại chế độ bình thường, trong **Safe Mode**, thực hiện các bước như trên, và
- Tại thẻ **General**, chọn **Normal startup**

    ![Tại thẻ **General**, chọn **Normal startup**.](/assets/media/171107-safe-mode-booting/2019-03-23_11-57-00.png)

rồi đóng cửa sổ và khởi động lại máy.
