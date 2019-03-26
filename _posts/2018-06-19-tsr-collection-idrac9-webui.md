---
layout: single
classes: wide
title: Cách lấy TSR log trên iDRAC9 trong WebUI.
description: Các bước để lấy TSR log trên iDRAC9 với Server PowerEdge Gen 14 của Dell
categories: [troubleshooting]
tags: [server, idrac, idrac9, tsr, log, poweredge]
toc: true
---

Hướng dẫn sử dụng giao diện WebUI để thực hiện các bước lấy TSR log trên iDRAC9 với các Server PowerEdge Gen 14 của Dell.

## Yêu cầu

- Bạn đã đăng nhập thành công vào giao diện quản lý của iDRAC9.
- Lifecycle đang không được sử dụng tức đang không thực hiện một tác vụ nào đó. Nếu không, phải chờ tác vụ đó hoàn thành, hoặc hủy.

**Lưu ý:** File TSR log sau khi đã được xuất ra hoàn thành, vui lòng lưu giữ lại tức chọn **Save/Lưu** khi trình duyệt hiện hộp thoại tải file.
{: .notice--danger}

## Các bước thực hiện

1. Tại giao diện chính của iDRAC9, vào menu **Maintenance** và chuyển đến tab **SupportAssist**.

    ![2019-03-26_06-25-51](/assets/media/2018-06-19-tsr-collection-idrac9-webui/2019-03-26_06-25-51.png)

2. Hộp thoại **SupportAssist Registration** có thể hiện ra, bạn chọn **Cancel** rồi **Cancel Registration** để đóng.
    ![2019-03-26_06-31-31](/assets/media/2018-06-19-tsr-collection-idrac9-webui/2019-03-26_06-31-31.png)

3. Bấm vào **Start a Collection**. Chỉ định các mục tương ứng cần lấy thông tin/log ở hộp thoại **SupportAssist Collection**. Tương tự như trên iDRAC8, chúng ta có một số mục như:

    - *System Infomation*: mặc định.
    - *Storage Logs*: cần thiết, đặc biệt với những trường hợp liên quan đến các thành phần lưu trữ.
    - *OS and Application Data*: có thể thêm để kiểm tra các vấn đề liên quan đến hệ điều hành.
    - *Debug log*: các thông tin khác bổ sung.
    - **Chỉ định nơi lưu trữ file log**:
        - *Send Now*: gửi gói log tới hệ thống của Dell để phục vụ việc chuẩn đoán.
        - *Save Locally*: lưu về máy. Khuyến nghị.
        - *Save to Network*: chỉ định thư mục mạng để lưu trữ, *SMB/CIFS* hoặc *NFS*.
    - Bấm **Collect** để bắt đầu.

    ![2019-03-26_06-48-59](/assets/media/2018-06-19-tsr-collection-idrac9-webui/2019-03-26_06-48-59.png)

4. Quá trình thực hiện đang được tiến hành. Phần trăm tiến trình được hiển thị trực quan:

    - Thời gian hoàn thành phụ thuộc vào các thành phần cần lấy và cấu hình hay các thành phần của máy.
    - Có thể 7 đến 10 phút hoặc hơn.
    - Có thể vào **Job Queue** để xem hàng đợi các công việc đang được xử lý.

    ![2019-03-26_07-10-54](/assets/media/2018-06-19-tsr-collection-idrac9-webui/2019-03-26_07-10-54.png)

5. Chương trình thông báo hoàn thành.

    - Bấm **OK** để hoàn thành.
    - Chọn **Save** khi được hỏi để lưu file zip đã được xuất ra.

    ![2019-03-26_22-10-46](/assets/media/2018-06-19-tsr-collection-idrac9-webui/2019-03-26_22-10-46.png)

6. Hoàn thành. Bạn copy/gửi file TSR log đã xuất ra cho bộ phận hỗ trợ.

    - Tên file: **TSR năm tháng ngày giờ _ số service tag**.zip

## Kết

Bài viết đã hướng dẫn các bước thực hiện để lấy log TSR trên iDRAC9. Hi vọng nội dung hữu ích với bạn!

## Tham khảo thêm

- [Cách lấy TSR log trên iDRAC8 trong WebUI](/troubleshooting/idrac8-tsr-collection/)

