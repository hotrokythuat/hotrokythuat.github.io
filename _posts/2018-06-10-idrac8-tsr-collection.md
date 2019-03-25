---
layout: single
classes: wide
title: Cách lấy TSR log trên iDRAC8 trong WebUI.
description: Các bước để lấy TSR log trên iDRAC8 với Server PowerEdge của Dell
categories: [troubleshooting]
tags: [server, idrac, idrac8, tsr, log, poweredge]
toc: true
---

Hướng dẫn sử dụng giao diện WebUI để thực hiện các bước lấy TSR log trên iDRAC8 với các Server PowerEdge của Dell.

## Yêu cầu

- Bạn đã đăng nhập thành công vào giao diện quản lý của iDRAC8.
- Lifecycle đang không được sử dụng tức đang không thực hiện một tác vụ nào đó. Nếu không, phải chờ tác vụ đó hoàn thành, hoặc hủy.

**Lưu ý:** File TSR log sau khi đã được xuất ra hoàn thành, vui lòng lưu giữ lại tức chọn **Save/Lưu** khi trình duyệt hiện hộp thoại tải file.
{: .notice--danger}

## Các bước thực hiện

1. Tại giao diện chính của iDRAC8, vào menu **Overview > Server > Troubleshooting** và chuyển đến tab **SupportAssist**.

    ![2019-03-26_04-55-27](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_04-55-27.png)

2. Chỉ định nơi lưu file TSR log sẽ được xuất ra, **Export Location**. Chọn các mục tương ứng:

    - *Local*: trình duyệt sẽ yêu cầu tải và lưu file.
    - *Network*: chỉ định một thư mục mạng theo giao thức *CIFS/SMB* hoặc *NFS* (*nix*). 

    ![2019-03-26_04-57-28](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_04-57-28.png)

3. Chỉ định các thành phần cần được lấy log tại mục **Edit Collection Data**. Các mục tương ứng:

    - *Hardware*: mặc định. Kiểm tra tình trạng của các thành phần phần cứng.
    - *RAID Controller Log*: cần thiết, đặc biệt với những trường hợp liên quan đến các thành phần lưu trữ.
    - *OS and Application Data*: có thể thêm để kiểm tra các vấn đề liên quan đến hệ điều hành.
    - Bấm **Apply** để tiếp tục.

    ![2019-03-26_04-58-37](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_04-58-37.png)

4. Đồng ý điều khoản sử dụng **Terms and Conditions**.

    - Tick vào ô **I have read...** và chọn **Continue**.

    ![2019-03-26_04-59-34](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_04-59-34.png)

5. Chờ quá trình lấy log hoàn thành.
    - Thời gian hoàn thành phụ thuộc vào các thành phần cần lấy và cấu hình hay các thành phần của máy.
    - Có thể 7 đến 10 phút hoặc hơn.
    - Có thể vào Job Queue để xem hàng đợi các công việc đang được xử lý.

    ![2019-03-26_05-00-30](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_05-00-30.png)

6. Chương trình thông báo hoàn thành.

    - Bấm **OK** để hoàn thành.
    - Chọn **Save** khi được hỏi để lưu file zip đã được xuất ra.

    ![2019-03-26_05-05-34](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_05-05-34.png)

7. Hoàn thành. Copy/Gửi file TSR log đã xuất ra cho bộ phận hỗ trợ.

    ![2019-03-26_05-22-02](/assets/media/2018-06-10-idrac8-tsr-collection/2019-03-26_05-22-02.png)

## Kết

Bài viết đã hướng dẫn các bước thực hiện để lấy log TSR trên iDRAC8. Hi vọng nội dung hữu ích với bạn!

