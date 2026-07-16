---
title: "Worklog Tuần 4"
date: 2026-05-26
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Tìm hiểu sâu về EC2: AMI (Amazon Machine Image) và cách hoạt động (Snapshot + metadata, không lưu cấu hình do không nằm trong ổ đĩa).
* Tìm hiểu Amazon EBS Volume và tự động hóa snapshot với AWS Lifecycle Manager.
* Thực hành Lab4: tạo instance từ AMI tùy chỉnh.
* Thực hành khôi phục quyền truy cập khi mất key: dùng SSM để reset password trên EC2 Windows, dùng User Data trên EC2 Linux.
* Tìm hiểu cách giới hạn tài nguyên sử dụng thông qua IAM Policy: giới hạn theo Region, theo Instance Family, theo Instance Type, giới hạn loại EBS Volume, xóa tài nguyên theo IP và theo thời gian.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu sâu về EC2: <br>&emsp; + AMI (Amazon Machine Image) <br>&emsp; + Cách AMI hoạt động (Snapshot + metadata) <br>                                                                          | 26/05/2026   | 26/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu Amazon EBS Volume <br> - Tìm hiểu AWS Lifecycle Manager để tự động hóa snapshot <br>                                                                                                 | 27/05/2026   | 27/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu cách khôi phục quyền truy cập EC2: <br>&emsp; + Reset password trên EC2 Windows dùng SSM <br>&emsp; + Dùng User Data trên EC2 Linux <br>                                               | 28/05/2026   | 28/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Thực hành Lab4:** <br>&emsp; + Tạo AMI tùy chỉnh <br>&emsp; + Khởi tạo instance từ AMI tùy chỉnh <br>&emsp; + Thực hành khôi phục quyền truy cập <br>                                      | 29/05/2026   | 30/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu IAM policies giới hạn tài nguyên: <br>&emsp; + Giới hạn theo Region <br>&emsp; + Giới hạn theo Instance Family/Type <br>&emsp; + Giới hạn loại EBS Volume <br>&emsp; + Xóa tài nguyên theo IP/thời gian <br>&emsp; + Xem lại tuần 4 <br> | 31/05/2026   | 01/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:
* Nắm vững kiến thức sâu về EC2 và AMI.
* Hiểu cách AMI hoạt động với Snapshot và metadata.
* Hiểu về Amazon EBS Volume và tự động hóa snapshot với AWS Lifecycle Manager.
* Tạo thành công AMI tùy chỉnh và khởi tạo instance từ nó (Lab4).
* Học được cách khôi phục quyền truy cập EC2 khi mất key.
* Nắm vững IAM policies để giới hạn sử dụng tài nguyên.
