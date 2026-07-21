---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

## Mục tiêu

* Thực hiện Smoke Test toàn hệ thống qua CloudFront và API Gateway
* Xác minh luồng EventBridge → SQS → Lambda Worker → SES → WebSocket Notification
* Thiết lập CloudWatch Alarms, Amazon SNS và AWS X-Ray
* Chuẩn bị Proposal và dàn ý Workshop demo

## Bảng công việc (29/06 – 03/07/2026)

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|-----|-----------|--------------|-----------------|
| 2 | - Lập checklist Smoke Test cho Customer / Merchant / Admin<br>- Chạy thử end-to-end qua CloudFront và API Gateway | 29/06/2026 | 29/06/2026 |
| 3 | - Kiểm tra pipeline bất đồng bộ:<br>  EventBridge → SQS → Lambda Worker → SES → WebSocket<br>- Xử lý message lỗi / retry nếu có | 30/06/2026 | 30/06/2026 |
| 4 | - Tạo CloudWatch Alarms<br>  + Lỗi Lambda, độ trễ API, độ sâu SQS…<br>- Cấu hình SNS nhận cảnh báo | 01/07/2026 | 01/07/2026 |
| 5 | - Bật / kiểm tra AWS X-Ray tracing<br>- Phân tích bottleneck<br>- Điều chỉnh timeout/memory nếu cần | 02/07/2026 | 02/07/2026 |
| 6 | - Soạn Proposal dự án WebFood<br>- Phác thảo nội dung Workshop demo cho mentor/nhóm | 03/07/2026 | 03/07/2026 |

## Kết quả đạt được

* Đã làm Smoke Test các luồng chính qua CloudFront và API Gateway.
* Đã kiểm tra luồng EventBridge → SQS → Lambda → SES → WebSocket.
* Đã tạo CloudWatch Alarms và SNS cảnh báo cơ bản; xem X-Ray đơn giản.
* Đã chuẩn bị Proposal và dàn ý Workshop.

Sau tuần 11, hệ thống đã được kiểm thử sơ bộ và có giám sát cơ bản.
