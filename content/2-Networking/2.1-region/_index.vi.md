---
title : "Region"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 2.1 </b> "
---
### Region
**Region** là tập hợp các **AZ** (available zone). Hầu hết các dịch vụ do AWS cung cấp đều có phạm; **region**. Điều này có nghĩa là các dữ liệu của dịch vụ trong **region** này không thể sao chép qua **region** khác;
Ví dụ: us-east-1, eu-west-1,...

### AZ
**AZ** (available zone) là tập hợp các **data center** có tính độc lập về mặt địa lý. Mỗi **region** có từ 2 đến 6 AZ. Thường thì có 3 AZ

Mỗi AZ là một hoặc nhiều trung tâm dữ liệu riêng biệt với công suất dự phòng, kết nối kết nối

Tất cả các AZ khỏi một khu vực được tách biệt về mặt địa lý

Ngay cả khi chúng được tách ra, chúng có kết nối băng thông cao giữa chúng

{{% notice tip %}}
**Best practice**: Triển khai ứng dụng tối thiểu trên 2 AZ để đảm bảo tính ổn định, không bị ảnh hưởng bởi thiên tai.
{{% /notice %}}



