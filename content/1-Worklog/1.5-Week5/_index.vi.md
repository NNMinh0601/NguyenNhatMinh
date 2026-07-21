---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

## Mục tiêu

* Học DynamoDB: tạo table, partition key, thao tác Put/Get/Query
* Viết hàm AWS Lambda đầu tiên (Node.js/Python) xử lý API đơn giản
* Kết nối API Gateway với Lambda
* Host frontend tĩnh trên S3 + CloudFront (mức cơ bản)
* Khắc phục lỗi CORS và IAM permission thiếu khi ghép frontend – API

## Bảng công việc (18/05 – 22/05/2026)

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|-----|-----------|--------------|-----------------|
| 2 | - Tạo bảng DynamoDB<br>- Thiết kế partition key phù hợp<br>- Thực hành PutItem / GetItem / Query | 18/05/2026 | 18/05/2026 |
| 3 | - Viết hàm Lambda đầu tiên (Node.js hoặc Python)<br>- Xử lý API đơn giản (đọc/ghi DynamoDB hoặc trả JSON)<br>- Gán IAM Execution Role cho Lambda | 19/05/2026 | 19/05/2026 |
| 4 | - Tạo API Gateway (HTTP/REST)<br>- Tích hợp Lambda làm backend<br>- Kiểm thử endpoint bằng Postman / curl / browser | 20/05/2026 | 20/05/2026 |
| 5 | - Upload frontend tĩnh lên S3<br>- Tạo CloudFront distribution (mức cơ bản)<br>- Cho frontend gọi API Gateway | 21/05/2026 | 21/05/2026 |
| 6 | - Khắc phục lỗi CORS trên API Gateway / Lambda<br>- Khắc phục lỗi IAM permission thiếu (Lambda ↔ DynamoDB, S3…)<br>- Ghi chú nguyên nhân và cách sửa | 22/05/2026 | 22/05/2026 |

## Kết quả đạt được

* Đã tạo bảng DynamoDB và thực hành Put/Get/Query.
* Đã viết hàm Lambda đầu tiên (Node.js hoặc Python) xử lý API đơn giản.
* Đã kết nối API Gateway với Lambda và gọi thử API được.
* Đã host frontend tĩnh trên S3 và dùng CloudFront ở mức cơ bản.
* Đã sửa được một số lỗi CORS và thiếu quyền IAM khi ghép frontend với API.

Sau tuần 5, tôi đã làm được luồng nhỏ: S3/CloudFront + API Gateway + Lambda + DynamoDB.
