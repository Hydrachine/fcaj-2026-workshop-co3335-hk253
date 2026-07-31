---
title: "Worklog Tuần 3"
date: 2026-07-29
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---


### Mục tiêu Tuần 3

* Tuần 3 bắt đầu từ ngày **22/06/2026** đến ngày **28/06/2026**.
* Tìm hiểu chi tiết dịch vụ quản lý dữ liệu linh hoạt **Amazon Simple Storage Service (Amazon S3)**.
* Làm quen phần mềm giải lập dòng lệnh và kết nối hệ thống từ xa MobaXterm.
* Thử nghiệm triển khai nguyên mẫu (prototype deployment) dự án nhóm theo 2 hướng: kiến trúc tuỳ chỉnh và theo framework **AWS Serverless Application Model (AWS SAM)**.

### Các công việc cần triển khai trong tuần này

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| ---- | --------- | ------------ | --------------- | -------------- | 
| 2 | - **Thực hành**: Làm quen dịch vụ **Amazon Simple Storage Service (Amazon S3)** <br>&emsp; + Tạo website tĩnh <br>&emsp; + Thiết lập chặn quyền truy cập công khai | 22/06/2026 | 23/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Thử nghiệm deploy nguyên mẫu dự án của nhóm: <br>&emsp; + Hướng 1: Sử dụng **AWS VPC**, **Amazon EC2**, **Amazon S3** hoặc **AWS Amplify Hosting**, và **Amazon RDS** | 23/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Thử nghiệm deploy nguyên mẫu dự án của nhóm: <br>&emsp; + Hướng 2: Sử dụng framework AWS SAM (**AWS Lambda**, **AWS DynamoDB**, **API Gateway**, **AWS Cognito**, ...) | 25/06/2026 | 27/06/2026 | <https://cloudjourney.awsstudygroup.com/> và <https://youtu.be/B_v42hWVwak/> |
| 6 | - **Thực hành**: Vẽ sơ đồ kiến trúc của dự án theo chuẩn yêu cầu của AWS | 27/06/2026 | 28/06/2026 | <https://youtu.be/l8isyDe-GwY/> |
                                           |

## Kết quả đạt được Tuần 3

* Hiểu được cách lưu trữ, quản lý và truy cập dữ liệu bằng **Amazon Simple Storage Service (Amazon S3)**, đồng thời nắm được các khái niệm về **Bucket**, **Object**, **Bucket Policy** và cơ chế phân quyền truy cập.

* Triển khai thành công một website tĩnh trên **Amazon S3**, đồng thời cấu hình chính sách chặn truy cập công khai nhằm nâng cao tính bảo mật cho dữ liệu.

* Làm quen với **MobaXterm** để quản lý kết nối SSH, truyền tệp và thao tác với máy chủ từ xa trong quá trình phát triển và triển khai hệ thống.

* **Đối với dự án nhóm:

    * Đánh giá hai phương án triển khai hệ thống gồm kiến trúc truyền thống (sử dụng **Amazon EC2**, **Amazon RDS**, **Amazon S3**) và kiến trúc **AWS Serverless** sử dụng **AWS SAM**, từ đó hiểu được ưu điểm, hạn chế và phạm vi áp dụng của từng mô hình.

    * Thực hành xây dựng và triển khai ứng dụng serverless đầu tiên bằng **AWS Serverless Application Model (AWS SAM)**, đồng thời làm quen với quy trình **build**, **deploy** và **quản lý hạ tầng dưới dạng mã (Infrastructure as Code)**.
    
    > Hướng 2 sử dụng **framework AWS SAM là tối ưu hơn** vì hệ thống chỉ trừ tín dụng mỗi khi phát sinh giao thức, trong khi hướng 1 sử dụng các dịch vụ tuỳ chỉnh sẽ tốn kém hơn.
    > **Chọn sử dụng AWS SAM**.

    * Hiểu được vai trò của các dịch vụ **AWS Lambda**, **Amazon API Gateway**, **Amazon DynamoDB** và **Amazon Cognito** trong kiến trúc serverless, cũng như cách các dịch vụ này phối hợp để xây dựng một ứng dụng hoàn chỉnh.

    * Thiết kế sơ đồ kiến trúc của dự án theo chuẩn **AWS Architecture Icons**, giúp mô tả trực quan các thành phần của hệ thống và mối quan hệ giữa các dịch vụ AWS được sử dụng.
