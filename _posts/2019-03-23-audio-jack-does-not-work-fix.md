---
layout: single
classes: wide
title: Sửa lỗi cổng headphone 3.5mm không phát âm thanh Windows 10
description: Sửa lỗi cổng headphone 3.5mm không phát âm thanh Windows 10
categories: [troubleshooting]
tags: [installation, windows, drivers, audio]
toc: true
comments: true
---

Sửa lỗi cổng headphone 3.5mm không phát âm thanh trong Windows 10.

**Lưu ý**: Trước khi tiến hành, đảm bảo rằng bạn đã cài đặt đủ các trình điều khiển cho máy từ trang hỗ trợ của Dell tại: [https://www.dell.com/support/](https://www.dell.com/support/).

## Tình trạng

- Âm thanh không phát ra headphone/loa khi cắm vào cổng headphone/jack 3.5mm.
- Tiếng rè, nhiễu thường xuyên phát ra từ loa hay headphone.

## Các bước xử lý

1. Mở **Device Manager**: Bấm tổ hợp phím **Windows X** (*WinX menu*) rồi chọn **Device Manager**, hoặc
    - Chuột phải vào biểu tượng **This PC** rồi chọn **Manager**.
    - Mở mục **Device Manager** trong danh sách ở bên trái của cửa sổ
mới mở.

    ![Mở **Device Manager**.](/assets/media/190323-audio-jack-issue/2019-03-23_16-42-37.png)

2. Bấm xổ mục **Sound, Video and Game controllers** trong cửa sổ **Device Manager**.
3. Chuột phải vào mục con **Realtek Audio** và chọn **Update driver**.

    ![Chuột phải vào mục con **Realtek Audio** và chọn **Update driver**.](/assets/media/190323-audio-jack-issue/2019-03-23_16-49-02.png)

4. Bấm chọn **Browse my computer for driver software**.

    ![Bấm chọn **Browse my computer for driver software**.](/assets/media/190323-audio-jack-issue/2019-03-23_16-49-59.png)

5. Bấm chọn **Let me pick from a list of available drivers on my
computer**.

    ![**Let me pick from a list of available drivers on my
computer**.](/assets/media/190323-audio-jack-issue/2019-03-23_16-51-11.png)

6. Bấm chọn **High Definition Audio Device** và bấm **Next**.
    - Nếu trước đó chọn High Definition Audio Device nhưng không xử lý được, hãy thử lại với Realtek Audio, có thể cần khởi động lại máy.

    ![Bấm chọn **High Definition Audio Device**](/assets/media/190323-audio-jack-issue/2019-03-23_16-55-00.png)

7. Xác nhận **Yes** để bắt đầu quá trình cài đặt.

    ![Xác nhận để bắt đầu quá trình cài đặt.](/assets/media/190323-audio-jack-issue/2019-03-23_16-56-38.png)

8. Đợi quá trình hoàn thành.

    ![Đợi quá trình hoàn thành.](/assets/media/190323-audio-jack-issue/2019-03-23_16-57-19.png)

9. Hoàn thành cài đặt. Ví dụ tương ứng cho từng loại driver nếu chọn.
    - Bấm **Close** để đóng.

    ![Hoàn thành cài đặt.](/assets/media/190323-audio-jack-issue/2019-03-23_17-01-16.png)

10. Khởi động lại máy một lần - nếu được yêu cầu.
    - Bạn đã hoàn thành, thử lại với headphone để theo dõi sự thay đổi.
