---
title : "Giới thiệu"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
### Giới thiệu
Mục lục:
- Điện toán đám mây
- Dịch vụ web của Amazon
- Tối ưu hóa chi phí
- Bảng điều khiển quản lý AWS

### Cloud computing
Cloud computing (Điện toán đám mây) là việc phân phối các tài nguyên công nghệ thông tin theo nhu cầu qua Internet với chính sách thanh toán theo mức sử dụng.

### Amazon web service
Amazon web service (AWS) là nhà cung cấp dịch vụ điện toán đám mây được sử dụng rộng rãi nhất, cung cấp trên 200 dịch vụ đầy đủ tính năng từ các trung tâm dữ liệu trên toàn thế giới.

Sự khác biệt của AWS với các nhà cung cấp dịch vụ khác:
- Tầm nhìn & Văn hóa;
- Triết lý về giá của AWS: sử dụng càng nhiều, chi phí bỏ ra càng ít;
- Nguyên tắc lãnh đạo: [https://www.amazon.jobs/content/en/our-workplace/leadership-principles](https://www.amazon.jobs/content/en/our-workplace/leadership-principles)
  
### Cost Optimization
Để tối ưu chi phí khi sử dụng dịch vụ điện toán đám mây, cần:
- Lựa chọn cấu hình tài nguyện tính toán và nơi lưu trữ data phù hợp;
- Tận dụng các phương thức thanh toán giảm giá như reserved instance, saving plan, spot;
- Xóa các tài nguyện không sử dụng, bật tắt tự động các tài nguyên không cần chạy 24/7;
- Tận dụng các dịch vụ serverless;
- Thiết kế kiến trúc tối ưu giải quyết yêu cầu để ra;
- Cài đặt và sử dụng AWS Budget;
- Quản lý chi phí theo phòng ban/ ứng dụng với cost allocation tag;
- Liên tục theo dõi và tối ưu chi phí.

Sử dụng công vụ tính toán chi phí sử dụng: https://calculator.aws/
- Cho phép tạo các estimate các dịch vụ thông dụng;
- Có thể chia sẻ các estimate cho người khác;
- Chi phí sẽ khát biệt theo từng Region.

### AWS Management Console
AWS Mangement Console là bảng điều kiển quản lý của AWS. Gồm mốt số thành phần:

| Thành phần                         | Chức năng                                      |
| ---------------------------------- | -----------------------------------------------|
| Root Login                         | - Tài khoản gốc, được tạo ra đầu tiên;<br>- Có toàn quyền truy cập đầy đủ không giới hạn vào tất cả tài nguyên.|
| IAM user login                     | - Tài khoản con quản lý truy suất tài nguyên AWS;<br>- Khi login bằng IAM User cần cung cấp Account ID (chuỗi 12 chữ số) để xác định Account AWS.|
| Service Search                     | - Thanh tìm kiếm dịch vụ.|
| Support Center                     | - Tạo các support case để yêu cầu hỗ trợ từ đội ngủ của AWS;|
| AWS Command Line Interface (CLI)   | - Công cụ mã nguồn mở cho phép tương tác với các service AWS bằng cách sử dụng các lệnh (command).|
| AWS Software Development Kit (SDK) | - Bộ công cụ phần mềm do AWS cung cấp để giúp lập trình viên dễ dàng tương tác với các dịch vụ AWS từ ứng dụng của mình thông qua mã code; <br>- Cung cấp việc quản lý vòng đời của API tới AWS services như:<br>+ Quản lý thông tin xác thực (mangage credentials);<br>+ Thử lại (retry);<br>+ Sắp xếp dữ liệu (data marshalling - chuẩn bị dữ liệu);<br>+ Tuần tự hóa (serialization chuyển object sang bytes stream);<br>+ Giải mã hóa (deserialization chuyển bytes stream về lại object).|





