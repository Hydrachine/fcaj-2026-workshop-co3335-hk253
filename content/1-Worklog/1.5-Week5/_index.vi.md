---
title: "Worklog Tuần 5"
date: 2026-07-29
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu Tuần 5

* Tuần 5 bắt đầu từ ngày **06/07/2026** đến ngày **12/07/2026**.
* Tìm hiểu dịch vụ bảo mật **Amazon Cognito** để hiểu nhiệm vụ của thành viên khác và cải thiện định nghĩa **API Gateway**.
* Tìm hiểu dịch vụ quản lý cung cấp dữ liệu **Amazon CloudWatch** để cập nhật định dạng kết quả đầu ra (output) của API.
* Lên ý tưởng và tham khảo giao diện người dùng (frontend) cho dự án.

### Các công việc cần triển khai trong tuần này

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| ---- | --------- | ------------ | --------------- | -------------- | 
| 2 | - **Thực hành**: Làm quen dịch vụ bảo mật **Amazon Cognito** <br>&emsp; + Tìm hiểu hai thành phần **User pool** và **Identity pool** <br>&emsp; + Giả lập xác thực tài khoản người dùng <br>&emsp; + Triển khai (deploy) xác thực tài khoản bằng **Cognito Cross Sites** <br>&emsp; + Tham gia kiểm tra luồng dữ liệu **Amazon Cognito** của dự án nhóm | 06/07/2026 | 07/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Thực hành**: Làm quen dịch vụ quản lý cung cấp dữ liệu **Amazon CloudWatch** <br>&emsp; + Tạo sơ đồ phân tích dữ liệu sử dụng bằng **CloudWatch Metric** <br>&emsp; + Tìm hiểu cách quản lý thông tin phản hồi (log) giữa các dịch vụ bằng **CloudWatch Logs** <br>&emsp; + Tự động hoá quản lý luồng dữ liệu bằng **CloudWatch Alarms** <br>&emsp; + Trực quan hoá toàn bộ dữ liệu phân tích bằng **CloudWatch Dashboards** | 08/07/2026 | 09/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Kiểm tra lại độ tương thích của **API Gateway**: <br>&emsp; + **API Gateway** và **Amazon Cognito** <br>&emsp; + **API Gateway** và **Amazon CloudWatch** <br>&emsp; + **API Gateway** và **Amazon DynamoDB** | 09/07/2026 | 12/07/2026 |  |
| 6 | - **Thảo luận nhóm**: Lựa chọn giao diện cho dự án <br>&emsp; + Mã nguồn hỗ trợ hiển thị trên điện thoại và máy tính <br>&emsp; + Tham khảo giao diện từ các mẫu website có sẵn | 09/07/2026 | 18/07/2026 | <https://cloudjourney.awsstudygroup.com/> và <https://www.figma.com/community/website-templates> |


### Kết quả đạt được Tuần 5

* Hiểu được cơ chế xác thực và phân quyền của **Amazon Cognito**, bao gồm vai trò của **User Pool** và **Identity Pool** trong việc quản lý người dùng và cấp quyền truy cập cho ứng dụng.

* Thực hành xây dựng và kiểm thử quy trình xác thực người dùng bằng **Amazon Cognito**, đồng thời hiểu được luồng trao đổi dữ liệu giữa ứng dụng, **Amazon Cognito** và **Amazon API Gateway**.

* Làm quen với các chức năng giám sát của **Amazon CloudWatch**, bao gồm thu thập chỉ số (**Metrics**), quản lý nhật ký (**Logs**), thiết lập cảnh báo (**Alarms**) và trực quan hóa dữ liệu thông qua **Dashboards**.

* Hiểu được cách sử dụng **Amazon CloudWatch** để theo dõi hoạt động của các dịch vụ AWS, hỗ trợ phát hiện lỗi và phân tích nguyên nhân trong quá trình phát triển hệ thống.

* **Đối với dự án nhóm:**

    * Kiểm tra và đánh giá khả năng tích hợp giữa **Amazon API Gateway**, **Amazon Cognito**, **Amazon CloudWatch** và **Amazon DynamoDB**, qua đó hiểu rõ hơn luồng xử lý yêu cầu và cơ chế bảo mật của hệ thống.

    * Tham gia thảo luận, đánh giá và lựa chọn giao diện người dùng phù hợp với yêu cầu của dự án, ưu tiên thiết kế có khả năng hiển thị tốt trên cả máy tính và thiết bị di động.

    * Cập nhật và điều chỉnh thiết kế API dựa trên quá trình tìm hiểu cơ chế xác thực và giám sát hệ thống, góp phần nâng cao tính nhất quán giữa tài liệu thiết kế và quá trình triển khai thực tế.
