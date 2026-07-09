---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Tìm hiểu dịch vụ lưu trữ đối tượng Amazon S3 và các lớp lưu trữ dữ liệu.
* Thực hành xây dựng website tĩnh bằng Amazon S3.
* Nghiên cứu các giải pháp phân phối nội dung và bảo vệ dữ liệu trên AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu Amazon S3, cấu trúc Bucket và Object.<br>- Tìm hiểu các Storage Class và tiêu chí lựa chọn cho từng loại dữ liệu.<br>- Khám phá cơ chế tính phí của Amazon S3. | 29/05/2026 | 29/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 3 | - Thực hành tạo S3 Bucket.<br>- Tải dữ liệu lên Bucket.<br>- Thiết lập quyền truy cập bằng Bucket Policy và Access Control. | 30/05/2026 | 30/05/2026 | https://000057.awsstudygroup.com/ |
| 4 | - Triển khai Static Website Hosting trên Amazon S3.<br>- Cấu hình trang mặc định và trang báo lỗi.<br>- Kiểm tra khả năng truy cập website từ Internet. | 31/05/2026 | 31/05/2026 | https://000057.awsstudygroup.com/ |
| 5 | - Cấu hình Bucket Policy và CORS.<br>- Kiểm tra khả năng truy cập từ ứng dụng Frontend.<br>- Đánh giá các thiết lập bảo mật của Bucket. | 01/06/2026 | 01/06/2026 | https://000057.awsstudygroup.com/ |
| 6 | - Thực hành sử dụng Amazon CloudFront.<br>- Tạo Distribution với Amazon S3 làm Origin.<br>- Kiểm tra tốc độ phân phối nội dung thông qua CDN. | 02/06/2026 | 02/06/2026 | https://000094.awsstudygroup.com/ |
| 7 | - Bật Bucket Versioning để quản lý các phiên bản dữ liệu.<br>- Thiết lập Cross Region Replication nhằm sao lưu dữ liệu sang Region khác.<br>- Hoàn thành các bài thực hành về Amazon S3 và CloudFront. | 03/06/2026 | 04/06/2026 | https://000057.awsstudygroup.com/ |

### Kết quả đạt được tuần 7:

* Hiểu được nguyên lý hoạt động của Amazon S3 và cách tổ chức dữ liệu trong Bucket.

* Nắm được các lớp lưu trữ của Amazon S3 và lựa chọn phù hợp theo nhu cầu sử dụng:
  * S3 Standard.
  * Intelligent-Tiering.
  * Standard-IA.
  * Glacier Flexible Retrieval.
  * Glacier Deep Archive.

* Hoàn thành việc triển khai một Static Website trên Amazon S3:
  * Tạo và cấu hình S3 Bucket.
  * Thiết lập Bucket Policy.
  * Cấu hình CORS.
  * Kiểm tra truy cập website thành công.

* Thực hành sử dụng Amazon CloudFront để:
  * Phân phối nội dung thông qua mạng CDN.
  * Giảm độ trễ khi truy cập dữ liệu.
  * Hiểu cơ chế Cache tại Edge Locations.

* Cấu hình các tính năng bảo vệ dữ liệu:
  * Bucket Versioning.
  * Cross Region Replication (CRR).

* Có khả năng triển khai và quản lý giải pháp lưu trữ tĩnh trên AWS, đồng thời hiểu các phương pháp tối ưu hiệu năng và đảm bảo an toàn dữ liệu.

