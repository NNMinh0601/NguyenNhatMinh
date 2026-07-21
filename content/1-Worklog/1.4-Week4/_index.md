---
title: "Worklog Week 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

## Objectives

* Deploy ứng dụng web 2-tier (tầng web trên EC2 + tầng dữ liệu trên RDS)
* Cấu hình Application Load Balancer và Auto Scaling Group cơ bản
* Theo dõi CPU/memory bằng CloudWatch và tạo alarm khi CPU cao
* Thực hành terminate instance để kiểm chứng Auto Scaling hoạt động

## Task table (11/05 – 15/05/2026)

| Day | Tasks | Start | End |
|-----|-------|-------|-----|
| 2 | - Deploy / hoàn thiện ứng dụng web 2-tier<br>  + Web tier: EC2<br>  + Data tier: RDS<br>- Kiểm thử kết nối ứng dụng ↔ database | 11/05/2026 | 11/05/2026 |
| 3 | - Tạo Application Load Balancer<br>- Tạo Target Group, đăng ký EC2<br>- Cấu hình Listener và Health Check | 12/05/2026 | 12/05/2026 |
| 4 | - Tạo Launch Template cho EC2<br>- Tạo Auto Scaling Group (min/desired/max)<br>- Gắn ASG với ALB / Target Group | 13/05/2026 | 13/05/2026 |
| 5 | - Theo dõi CPU / memory trên CloudWatch<br>- Tạo alarm đơn giản khi CPU vượt ngưỡng<br>- Quan sát trạng thái OK / ALARM | 14/05/2026 | 14/05/2026 |
| 6 | - Terminate một instance trong ASG<br>- Quan sát ASG tạo instance mới<br>- Kiểm tra ALB vẫn phục vụ request | 15/05/2026 | 15/05/2026 |

## Outcomes

* Đã deploy ứng dụng web 2-tier (EC2 + RDS).
* Đã cấu hình Application Load Balancer và Target Group cơ bản.
* Đã tạo Auto Scaling Group với min/desired/max đơn giản.
* Đã theo dõi CPU trên CloudWatch và tạo alarm khi CPU cao.
* Đã thử terminate instance để xem Auto Scaling tạo máy mới.

Sau tuần 4, tôi đã làm được mô hình web có ALB và Auto Scaling ở mức cơ bản.
