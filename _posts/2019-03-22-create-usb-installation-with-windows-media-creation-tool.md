---
layout: single
classes: wide
title: Sử dụng công cụ Windows Media Creation để tải hoặc tạo bộ cài đặt Windows
description: Hướng dẫn sử dụng Windows Media Creation để tạo bộ cài đặt Windows 10
categories: [installation]
tags: [installation, windows, tools]
toc: true
comments: true
---

Windows Media Creation là một công cụ được cung cấp bởi Microsoft, mục đích hỗ trợ người dụng tải và tạo bộ cài đặt Windows 10 một cách dễ dàng và ít thao tác nhất.

Người dùng có thể sử dụng Windows Media Creation để tải bộ cài đặt thành file ISO riêng biệt, hoặc trực tiếp tạo bộ cài đặt lên USB.

Việc tạo file ISO có thể sử dụng để lưu trữ nhằm tránh việc phải tải lại cho lần sau, cũng như có thể sử dụng với các công cụ khác như Rufus hoặc ghi ra đĩa DVD. Tuy nhiên, bộ cài đặt sẽ không phải là mới nhất, vì không được cập nhật khi đã được đóng gói từ thời điểm chương trình chạy.

## Nội dung

- Windows Media Creation Tool là gì.
- Các yêu cầu để sử dụng.
- Nơi tải công cụ.
- Cách **tạo** bộ cài đặt Windows vào USB với Windows Media Creation Tool.
- Cách **tải** bộ cài đặt Windows thành file ISO với Windows Media Creation Tool.

## Yêu cầu

Các thành phần cần phải có:

- 1 USB có dung lượng tối thiểu 8GB. Khuyến nghị USB đủ mới để có tốc độ tốt và ổn định.
- Máy tính chạy Windows. Chương trình chỉ chạy trên Windows.
- Kết nối Internet đủ tốt. Quá trình thực hiện, chương trình sẽ tải một dung lượng khá lớn dữ liệu.

### Lưu ý:

- Sao lưu dữ liệu khỏi USB, vì trong quá trình thực hiện, USB sẽ được format (xóa sạch dữ liệu, định dạng lại), điều này có nghĩa mọi dữ liệu sẽ bị xóa và (chắc chắn) không thể khôi phục.

## Chuẩn bị

1. Cắm USB vào máy tính.
2. Truy cập trang tải Windows của Microsoft để tải công cụ về, tại: [https://www.microsoft.com/en-us/software-download/windows10](https://www.microsoft.com/en-us/software-download/windows10)

    - Link trực tiếp ở đây: [https://go.microsoft.com/fwlink/?LinkId=691209](https://go.microsoft.com/fwlink/?LinkId=691209)

    ![Tải Windows Media Creation Tool](/assets/media/190322/2019-03-22-11-37-30-2.png)

3. Công cụ sau khi tải về.

    ![Công cụ sau khi tải về](/assets/media/190322/2019-03-22-12-42-03.png)

## Các bước thực hiện

1. Nhấn đúp để chạy chương trình. Chọn **Yes** nếu được hỏi ở hộp thoại **User Account Control**.
2. Chương trình sẽ chuẩn bị quá trình thực hiện.

    ![Chương trình chuẩn bị quá trình](/assets/media/190322/2019-03-22-12-04-26-7.png)

3. Chọn mục **Accept** ở màn hình điều khoản sử dụng.

    ![Điều khoản sử dụng](/assets/media/190322/2019-03-22-12-06-28.png)

4. Chương trình phân tích hệ thống để đem ra lựa chọn.

    ![Phân tích hệ thống để đem ra lựa chọn](/assets/media/190322/2019-03-22-12-07-12-b.png)

5. Chọn mục **Create installation media ...**. Chương trình cũng có thể giúp thực hiện việc cập nhật (update) Windows. 

    ![Lựa chọn tạo bộ cài đặt](/assets/media/190322/2019-03-22-12-09-44-c.png)

6. Chỉ định ngôn ngữ, kiến trúc và phiên bản của Windows để tạo bộ cài đặt.

    ![Chỉ định ngôn ngữ, kiến trúc và phiên bản](/assets/media/190322/2019-03-22-12-09-57-d.png)

    - Ở đây, nếu bạn quyết định cài đặt cho chính máy đang sử dụng, bạn bấm **Next**.
    - Nếu bạn muốn thay đổi, bỏ chọn mục **Use the recommended options for this PC**.
    - Sau đó bạn có thể chỉ định ngôn ngữ, loại kiến trúc (64bit, 32bit) cho bộ cài đặt, ví dụ như hình:

        ![Chỉ định ngôn ngữ, kiến trúc và phiên bản](/assets/media/190322/2019-03-22-12-32-14.png)

7. Lựa chọn cách tạo bộ cài đặt. USB hay file ISO. Tại đây, hướng dẫn sẽ được chia thành 2 mục nhỏ tiếp theo, tương ứng:
    - [Tạo bộ cài đặt trên USB.](#tạo-bộ-cài-đặt-trên-usb)
    - [Tạo file ISO.](#tạo-bộ-cài-đặt-thành-file-iso)

    ![Lựa chọn cách tạo bộ cài đặt. USB hay file ISO.](/assets/media/190322/2019-03-22-12-38-07.png)

### Tạo bộ cài đặt trên USB

- **Ghi chú**: Sau khi hoàn thành, USB có thể trực tiếp được sử dụng làm nguồn cài đặt cho máy.

1. Chọn mục **USB flash drive**.

    ![Lựa chọn USB flash drive.](/assets/media/190322/2019-03-22-13-17-28.png)

2. Chỉ định thiết bị lưu trữ USB cần sử dụng.

    ![Chỉ định thiết bị lưu trữ USB cần sử dụng.](/assets/media/190322/2019-03-22-13-16-06.png)

3. Đợi chương trình hoàn thành. Thời gian hoàn thành rất phụ thuộc vào tốc độ mạng, tốc độ của thiết bị USB.

    ![Đợi chương trình hoàn thành.](/assets/media/190322/2019-03-22-13-26-22.png)

4. Bộ cài đặt đã hoàn thành và sẵn sàng sử dụng.

    ![Bộ cài đặt đã hoàn thành và sẵn sàng sử dụng.](/assets/media/190322/2019-03-22-14-07-26.png)

### Tạo bộ cài đặt thành file ISO

- **Lưu ý**: File ISO cần được ghi ra đĩa DVD hoặc tạo bộ cài đặt trên USB với một công cụ khác nào đó để có thể sử dụng để cài đặt máy.

1. Lựa chọn mục **ISO file**.

    ![Lựa chọn mục **ISO file**](/assets/media/190322/2019-03-22-12-46-53.png)

2. Chỉ định nơi lưu file, và tên của file ISO sẽ được tạo. Sau đó chọn **Next** để tiếp tục.

    ![Chỉ định nơi lưu file, và tên của file ISO sẽ được tạo.](/assets/media/190322/2019-03-22-12-49-50.png)

3. Bộ cài đặt Windows sẽ được tải.

    ![Bộ cài đặt Windows sẽ được tải.](/assets/media/190322/2019-03-22-12-52-14.png)

4. Sau khi tải xong sẽ được tạo thành file ISO.

    ![Sau khi tải xong sẽ được tạo thành file ISO.](/assets/media/190322/2019-03-22-12-52-52.png)

5. Sau khi tạo file ISO hoàn thành, bộ cài đặt đã sẵn sàng. Ví dụ, sử dụng để lưu trữ, ghi đĩa hoặc sử dụng với mục đích khác.

    ![Tạo file ISO hoàn thành, bộ cài đặt đã sẵn sàng.](/assets/media/190322/2019-03-22-13-41-50.png)

6. Bấm **Finish** để hoàn thành và đóng chương trình.

## Kết

Như vậy, bạn đã nắm được cách sử dụng công cụ Windows Media Creation.

## Tham khảo thêm

- Cách tạo bộ cài đặt Windows từ file ISO với Rufus.
- Cách cài đặt Windows từ USB.
- UEFI và Legacy, MBR hay GPT.
