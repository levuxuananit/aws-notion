---
title : "Region"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 2.1 </b> "
---
### Region
- **Region** bao gồm cụm data center 
+ Đường cáp riêng của AWS: kết nối region to region, AZ to AZ;
+ Best practice: Triển khai ứng dụng từ 2 AZ trở nên, để đảm bảo tính ổn định không bị ảnh hưởng bởi thiên tai;
AWS Regions are clusters of data centers
Example of regions: us-east-1, eu-west-1, etc.
Most services provided by AWS are regions scoped. This means a data for a service used in one region is not replicated in another region