---
title: "Worklog Tuần 6"
date: 2026-07-29
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Mục tiêu Tuần 6

* Tuần 6 bắt đầu từ ngày **13/07/2026** đến ngày **19/07/2026**.
* Tuần này tập trung vào hoàn thiện dự án của nhóm:
    * Phối hợp với thành viên phụ trách thiết kế giao diện người dùng để tích hợp API (nối tiếp nhiệm vụ của tuần trước).
    * Đánh giá mức sử dụng AWS Credits trong quá trình kiểm thử.

### Các công việc cần triển khai trong tuần này

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| ---- | --------- | ------------ | --------------- | -------------- | 
| 2 | - Cùng tham gia thiết kế giao diện người dùng (frontend) <br>&emsp; + Căn chỉnh vị trí phù hợp <br>&emsp; + Tích hợp **API Gateway** | 14/07/2026 | 16/07/2026 |  |
| 4 | - Kiểm thử dự án: <br>&emsp; + Kiểm tra tính năng đăng nhập (Đăng ký, Đăng nhập, mã OTP) <br>&emsp; + Kiểm tra toàn bộ **6 hàm AWS Lambda** của hệ thống <br>&emsp; + Kiểm tra bảo mật của **Amazon DynamoDB** <br>&emsp; + Kiểm tra hoạt động trên điện thoại (cấp quyền camera quét mã QR, độ trễ tương tác) | 16/07/2026 | 25/07/2026 |  |
| 6 | - Kiểm thử dự án: <br>&emsp; + Phân tích dữ liệu trên **Amazon Cloudwatch** <br>&emsp; + Đánh giá mức sử dụng AWS Credits trong quá trình chạy thử dự án | 17/07/2026 | 19/07/2026 |  |


### Kết quả đạt được Tuần 6

* Hoàn thành việc tích hợp các API vào giao diện người dùng, giúp kết nối giữa frontend và backend hoạt động ổn định trong quá trình kiểm thử.

* Phối hợp với các thành viên trong nhóm để hiệu chỉnh giao diện, cải thiện trải nghiệm người dùng và bảo đảm tính tương thích trên cả máy tính và thiết bị di động.

* Kiểm thử toàn bộ quy trình xác thực người dùng, bao gồm đăng ký tài khoản, đăng nhập, xác thực OTP và phân quyền truy cập thông qua **Amazon Cognito**.

* Thường xuyên kiểm thử các hàm **AWS Lambda**, xác minh các API hoạt động đúng với tài liệu đặc tả và đáp ứng các yêu cầu chức năng của hệ thống.

* Kiểm tra cơ chế lưu trữ và phân quyền của **Amazon DynamoDB**, bảo đảm dữ liệu được truy cập đúng theo các quy tắc bảo mật đã thiết kế.

* Sử dụng **Amazon CloudWatch** để theo dõi nhật ký thực thi, phân tích lỗi phát sinh và đánh giá hiệu năng của các dịch vụ AWS trong quá trình chạy thử.

* Phân tích mức sử dụng **AWS Credits** của hệ thống, xác định các dịch vụ tiêu tốn nhiều tài nguyên và đề xuất các biện pháp tối ưu chi phí trong quá trình phát triển và triển khai.


