---
title: "Worklog Week 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

## Objectives

* Phát triển các hàm Lambda phục vụ API, Worker và WebSocket
* Thiết lập REST API Gateway, WebSocket API, EventBridge Rules và SQS Trigger
* Triển khai WAF, CloudFront, Origin Access Control (OAC) và upload frontend
* Kiểm thử đặt hàng, thanh toán MoMo, gửi email SES và thông báo WebSocket

## Task table (22/06 – 27/06/2026)

| Day | Tasks | Start | End |
|-----|-------|-------|-----|
| 2 | - Viết Lambda cho REST API<br>- Viết Lambda Worker xử lý hàng đợi<br>- Viết Lambda WebSocket: connect / disconnect / notify | 22/06/2026 | 22/06/2026 |
| 3 | - Hoàn thiện khoảng 5 hàm Lambda chính<br>- Kiểm thử từng function độc lập trước khi nối hệ thống | 23/06/2026 | 23/06/2026 |
| 4 | - Thiết lập REST API Gateway<br>- Thiết lập WebSocket API<br>- Cấu hình EventBridge Rules và SQS Trigger | 24/06/2026 | 24/06/2026 |
| 5 | - Triển khai AWS WAF<br>- Cấu hình CloudFront + OAC cho frontend/S3<br>- Build và upload frontend | 25/06/2026 | 25/06/2026 |
| 6 | - Kiểm thử nghiệp vụ:<br>  + Đặt hàng<br>  + Thanh toán MoMo<br>  + Email SES<br>  + Thông báo WebSocket<br>- Ghi nhận bug ưu tiên sửa | 26/06/2026 | 27/06/2026 |

## Outcomes

* Đã viết các hàm Lambda cho API, Worker và WebSocket.
* Đã thiết lập REST API Gateway, WebSocket API, EventBridge và SQS Trigger.
* Đã cấu hình CloudFront, OAC và AWS WAF ở mức cơ bản; upload frontend.
* Đã kiểm thử đặt hàng, thanh toán MoMo, gửi email SES và thông báo WebSocket.

Sau tuần 10, các luồng chính của WebFood đã chạy được trên AWS.
