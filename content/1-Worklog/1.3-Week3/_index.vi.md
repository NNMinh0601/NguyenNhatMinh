---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

## Mục tiêu

* Gắn Elastic IP cho EC2 để địa chỉ truy cập ổn định hơn
* Siết Security Group: chỉ mở các cổng thực sự cần thiết
* Tạo RDS MySQL cơ bản, kết nối từ EC2 và thao tác CRUD bằng SQL
* Tìm hiểu backup tự động / snapshot của RDS; viết nhật ký lỗi kết nối DB

## Bảng công việc (04/05 – 08/05/2026)

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |
|-----|-----------|--------------|-----------------|
| 2 | - Cấp phát và gắn Elastic IP cho EC2<br>- Kiểm tra website vẫn truy cập được qua EIP<br>- So sánh Public IP động và Elastic IP | 04/05/2026 | 04/05/2026 |
| 3 | - Rà soát Security Group hiện tại<br>- Chỉ giữ rule cần thiết (SSH, HTTP…)<br>- Hạn chế nguồn SSH nếu có thể<br>- Gỡ rule thừa / quá rộng | 05/05/2026 | 05/05/2026 |
| 4 | - Tạo RDS MySQL (Free Tier)<br>- Cấu hình DB subnet / Security Group cho RDS<br>- Chỉ cho phép EC2 (hoặc SG của EC2) kết nối cổng 3306<br>- Thử kết nối từ EC2 bằng mysql client | 06/05/2026 | 06/05/2026 |
| 5 | - Tạo database/table mẫu<br>- Thực hành CRUD bằng SQL (INSERT/SELECT/UPDATE/DELETE)<br>- Tìm hiểu Automated backup và Manual snapshot của RDS | 07/05/2026 | 07/05/2026 |
| 6 | - Viết nhật ký lỗi khi kết nối DB:<br>  + SG, endpoint, credential, VPC/subnet…<br>- Tổng kết lab Elastic IP – SG – RDS | 08/05/2026 | 08/05/2026 |

## Kết quả đạt được

* Đã gắn Elastic IP cho EC2 để địa chỉ truy cập ổn định hơn.
* Đã chỉnh lại Security Group, chỉ mở các cổng cần thiết.
* Đã tạo RDS MySQL (Free Tier) và kết nối từ EC2.
* Đã thao tác CRUD đơn giản bằng SQL trên RDS.
* Đã tìm hiểu backup tự động và snapshot của RDS ở mức cơ bản.
* Đã ghi lại một số lỗi khi kết nối DB và cách xử lý.

Sau tuần 3, tôi đã kết nối được EC2 với RDS MySQL và làm CRUD cơ bản.
