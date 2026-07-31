---
title: "Worklog Tuần 4"
date: 2026-07-29
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu Tuần 4

* Tuần 4 bắt đầu từ ngày **29/06/2026** đến ngày **05/07/2026**.
* Tìm hiểu chi tiết các dịch vụ mạng của AWS, đặc biệt là dịch vụ **Amazon Virtual Private Cloud (Amazon VPC)**.
* Tìm hiểu, thực hành cách triển khai (deploy) và quản lý máy chủ ảo bằng **Amazon EC2**.
* Hoàn thiện bản thiết kế đầu tiên kiến trúc phần mềm và luồng hệ thống (workflow) dự án của nhóm.

### Các công việc cần triển khai trong tuần này

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| ---- | --------- | ------------ | --------------- | -------------- | 
| 2 | - **Thực hành**: Làm quen dịch vụ mảng ảo **Amazon Virtual Private Cloud (VPC)** <br>&emsp; + Ôn tập subnets, route tables, các loại gateway <br>&emsp; + Thiết lập tường lửa trong **AWS VPC** | 16/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành**: Thiết lập máy chủ ảo bằng **EC2 Intances** <br>&emsp; + Tạo máy chủ và kiểm tra kết nối <br>&emsp; + Kết nối mạng bằng **NAT Gateway** <br>&emsp; + Quản lý kết nối mạng bằng **Reachability Analyzer** | 17/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Thiết kế kiến trúc cơ bản của dự án: <br>&emsp; + Vẽ sơ đồ các **Use Case** và **Sequence** <br>&emsp; + Chọn cấu trúc dữ liệu cho dự án <br>&emsp; + Cách sử dụng AWS CLI | 18/06/2026 | 21/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - **Thực hành**: Làm quen dịch vụ mảng ảo **Amazon Virtual Private Cloud (VPC)** <br>&emsp; + Tạo và quản lý hệ thống mạng AWS VPC giả lập kết nối hai tiệm net | 20/06/2026 | 21/06/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được Tuần 4

* Nắm vững các thành phần mạng cốt lõi trong **Amazon Virtual Private Cloud (Amazon VPC)**, bao gồm **VPC**, **Subnet**, **Route Table**, **Internet Gateway**, **NAT Gateway**, **Security Group** và **Site to Site AWS VPN**.

* Thiết kế và triển khai thành công một hệ thống mạng ảo mô phỏng kết nối giữa hai tiệm Internet, qua đó tích lũy kinh nghiệm thực tế trong việc cấu hình và quản lý các tài nguyên mạng trên AWS.

* Hiểu và thực hành cách khởi tạo, cấu hình và quản lý các máy chủ ảo **Amazon EC2**, bao gồm kết nối đến máy chủ và kiểm tra khả năng kết nối mạng.

* Hiểu được vai trò và cách cấu hình **NAT Gateway**, cho phép các máy chủ trong **Private Subnet** truy cập Internet một cách an toàn mà không chấp nhận các kết nối truy cập từ bên ngoài.

* Sử dụng **Reachability Analyzer** để phân tích, kiểm tra và xác minh khả năng kết nối mạng giữa các tài nguyên trên AWS.

> ⚠️ **AWS VPC** và **Amazon EC2** tự động trừ tín dụng theo giờ, kể cả khi không ai truy cập. Trung bình, **mỗi ngày cần khoảng $4** để duy trì hệ thống mạng

* **Đối với dự án nhóm:**

    ** Phối hợp với các thành viên trong nhóm để thiết kế kiến trúc ban đầu của dự án thông qua việc xây dựng các **Use Case Diagram** và **Sequence Diagram**.

    ** Xây dựng mô hình dữ liệu và cấu trúc cơ sở dữ liệu ban đầu nhằm đáp ứng các yêu cầu chức năng của dự án.

    ** Củng cố kỹ năng sử dụng **AWS CLI** trong quá trình phát triển, triển khai và quản lý các tài nguyên trên nền tảng AWS.
