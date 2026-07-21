---
title: "Worklog Week 2"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

## Objectives

* Thực hành networking cơ bản với Amazon VPC (subnet public/private, Internet Gateway, route table)
* Tạo Security Group đơn giản phù hợp cho web server
* Launch EC2 Amazon Linux, kết nối SSH và khắc phục lỗi kết nối nếu phát sinh
* Cài Nginx và deploy trang web tĩnh đơn giản trên EC2

## Task table (27/04 – 01/05/2026)

| Day | Tasks | Start | End |
|-----|-------|-------|-----|
| 2 | - Tìm hiểu lab VPC trên Cloud Journey<br>- Thực hành tạo VPC<br>- Tạo subnet public / private<br>- Gắn Internet Gateway và cấu hình route table | 27/04/2026 | 27/04/2026 |
| 3 | - Tạo Security Group cho web server<br>  + Inbound: SSH (22), HTTP (80)<br>- Kiểm tra outbound rules mặc định<br>- Ghi chú sự khác nhau giữa Security Group và Network ACL | 28/04/2026 | 28/04/2026 |
| 4 | - Launch EC2 Instance (Amazon Linux) trong subnet public<br>- Tạo / tải key pair<br>- Thử kết nối SSH<br>- Gặp lỗi kết nối (nếu có) và tự sửa theo hướng dẫn lab | 29/04/2026 | 29/04/2026 |
| 5 | - Cài Nginx trên EC2<br>- Deploy trang web tĩnh HTML đơn giản<br>- Kiểm tra truy cập qua Public IP trên trình duyệt | 30/04/2026 | 30/04/2026 |
| 6 | - Rà soát lại SG, key permission, Public IP<br>- Khắc phục lỗi kết nối còn lại<br>- Tổng kết lab VPC – SG – EC2 – Nginx | 01/05/2026 | 01/05/2026 |

## Outcomes

* Đã thực hành tạo VPC với subnet public/private, Internet Gateway và route table.
* Đã tạo Security Group mở cổng SSH (22) và HTTP (80).
* Đã tạo EC2 Amazon Linux và kết nối SSH thành công.
* Đã tự sửa một số lỗi kết nối theo hướng dẫn lab (SG, key pair, Public IP).
* Đã cài Nginx và deploy trang web tĩnh đơn giản.
* Đã truy cập website qua Public IP trên trình duyệt.

Sau tuần 2, tôi đã dựng được web server đơn giản trên EC2 trong VPC tự tạo.
