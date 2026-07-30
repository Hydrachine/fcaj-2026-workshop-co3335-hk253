---
title: "UI & Testing"
date: 2026-07-29
weight: 5
chapter: false
pre : " <b> 5.5. </b> "
---

### 1. Registration/Login UI & Admin

**Registration/Login**

![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-4.png)
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-5.png)

**Admin Dashboard**

![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-7.png)


### 2. Testing

**Teacher creates an attendance session**
- Log in with the Teacher account.
- Click **Add Course** (Thêm môn học) to create a new course.
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-1.png)
- In the course details, click **Create Session** (Tạo phiên).
- The screen displays a QR code. Notice that this QR code **continuously changes** 
every few seconds to prevent proxy attendance!
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image.png)
- Students who successfully scan the QR code will appear in the **Attendance List**
on the right. This list can be exported to an Excel file.

**Student scans QR (Check-in)**
- Use your phone to access the website and log in with the Student account.
- Click **Start Scanning** (Bắt đầu quét) to use the camera to scan the QR code.
- A success message appears.
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-3.png)

### 3. View Logs and Metrics (Logging & Monitoring)

To ensure smooth operation, we will examine the logs.

**View Lambda Logs:**
1. Open AWS Console -> **CloudWatch** -> **Log Management**.
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-8.png)
2. Find the log group for `/aws/lambda/qr-attendance-backend-dev-CheckinFunction...`
3. You will see log entries recording successful student check-ins.
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-9.png)

**Check Metrics:**
1. Open AWS Console -> **CloudWatch** -> **Metrics** -> **Classic metrics** 
2. Here you can view various infrastructure-related metrics.
![alt text](/fcaj-2026-workshop-co3335-hk253/images/5-Workshop/5.5/image-10.png)
