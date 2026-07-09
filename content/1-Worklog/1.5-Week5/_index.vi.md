---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Tìm hiểu các phương thức kết nối giữa nhiều Amazon VPC.
* So sánh mô hình VPC Peering và AWS Transit Gateway trong các hệ thống nhiều mạng.
* Thực hành triển khai và cấu hình kết nối giữa các VPC trên AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu cơ chế hoạt động của Amazon VPC Peering.<br>- Tìm hiểu các mô hình kết nối giữa các VPC trong cùng Region, khác Region và khác tài khoản AWS.<br>- Phân tích các giới hạn của VPC Peering. | 15/05/2026 | 15/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 3 | - Thực hành tạo kết nối VPC Peering giữa hai VPC.<br>- Chấp nhận yêu cầu kết nối và kiểm tra trạng thái hoạt động. | 16/05/2026 | 16/05/2026 | https://000019.awsstudygroup.com/ |
| 4 | - Cập nhật Route Table để các VPC có thể giao tiếp với nhau.<br>- Kiểm tra khả năng truyền dữ liệu giữa các EC2 thuộc các VPC khác nhau. | 17/05/2026 | 17/05/2026 | https://000019.awsstudygroup.com/ |
| 5 | - Tìm hiểu AWS Transit Gateway và mô hình mạng Hub-and-Spoke.<br>- So sánh ưu điểm và hạn chế của Transit Gateway với VPC Peering. | 18/05/2026 | 18/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 6 | - Thực hành tạo AWS Transit Gateway.<br>- Kết nối nhiều VPC thông qua Transit Gateway Attachment.<br>- Thiết lập bảng định tuyến cho Transit Gateway. | 19/05/2026 | 20/05/2026 | https://000020.awsstudygroup.com/ |
| 7 | - Kiểm tra khả năng định tuyến giữa các VPC đã kết nối.<br>- Xác nhận lưu lượng hoạt động đúng.<br>- Xóa các tài nguyên sau khi hoàn thành bài thực hành. | 21/05/2026 | 21/05/2026 | https://000020.awsstudygroup.com/ |

### Kết quả đạt được tuần 5:

* Hiểu được nguyên lý hoạt động và các trường hợp sử dụng của Amazon VPC Peering.

* Phân biệt được các mô hình kết nối:
  * VPC Peering trong cùng Region.
  * VPC Peering khác Region.
  * VPC Peering giữa nhiều tài khoản AWS.

* Hoàn thành bài thực hành VPC Peering:
  * Tạo kết nối giữa các VPC.
  * Cấu hình Route Table.
  * Kiểm tra khả năng giao tiếp giữa các EC2 thuộc các VPC khác nhau.

* Hiểu kiến trúc AWS Transit Gateway và mô hình Hub-and-Spoke trong hệ thống mạng lớn.

* Thực hành triển khai Transit Gateway:
  * Tạo Transit Gateway.
  * Kết nối nhiều VPC bằng Transit Gateway Attachment.
  * Cấu hình Transit Gateway Route Table.
  * Kiểm tra định tuyến giữa các VPC.
  * Thu hồi tài nguyên sau khi hoàn thành bài Lab.

* Có khả năng lựa chọn giải pháp kết nối mạng phù hợp giữa VPC Peering và Transit Gateway tùy theo quy mô của hệ thống.


