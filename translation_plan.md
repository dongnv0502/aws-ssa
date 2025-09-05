# Kế Hoạch Dịch Subtitle AWS SAA-C03

## Tổng Quan
- **Số lượng file cần dịch**: 428 file .srt
- **Ngôn ngữ**: Tiếng Anh → Tiếng Việt
- **Mục tiêu**: Dịch toàn bộ subtitle với chất lượng cao, tuân thủ quy tắc chuyên môn

## Quy Tắc Dịch (Cập Nhật)

### 1. Giữ Nguyên
- **Toàn bộ thuật ngữ kỹ thuật**: VPC, Subnet, EC2, S3, IAM, Lambda, API Gateway, v.v.
- **Tên hàm, biến, câu lệnh, code snippet**: Giữ nguyên hoàn toàn
- **Tên dịch vụ, sản phẩm AWS**: Không dịch

### 2. Phong Cách Dịch
- **Dịch sát nghĩa**: Truyền đạt đúng ý nghĩa, không dịch máy móc
- **Dễ hiểu, ngắn gọn**: Ưu tiên sự rõ ràng
- **Linh hoạt về cấu trúc câu**: Có thể gộp hoặc chia lại câu cho tự nhiên
- **Không dịch cứng nhắc**: Không bắt buộc 1 câu tiếng Anh = 1 câu tiếng Việt
- **Tiếng Việt chuẩn**: Tránh dùng từ địa phương hoặc tiếng lóng

### 3. Quy Tắc Phụ Đề
- **Chiều dài phù hợp**: Mỗi dòng không quá dài
- **Chia theo cụm tự nhiên**: Dễ đọc khi xem video
- **Ngắt câu hợp lý**: Theo nhịp nói và ý nghĩa
- **Giữ nguyên timestamp**: Không thay đổi thời gian hiển thị

## Cấu Trúc File .srt
```
1
00:00:00,180 --> 00:00:03,120
Text content here

2
00:00:03,120 --> 00:00:04,710
Next text content
```

## Danh Sách Module Cần Dịch
1. **01 Introduction - AWS Certified Solutions Architect Associate** (7 files)
2. **03 Getting started with AWS** (6 files)  
3. **04 IAM & AWS CLI** (18 files)
4. **05 EC2 Fundamentals** (18 files)
5. **06 EC2 - Solutions Architect Associate Level** (8 files)
6. **07 EC2 Instance Storage** (14 files)
7. **08 High Availability and Scalability ELB & ASG** (17 files)
8. **09 AWS Fundamentals RDS + Aurora + ElastiCache** (13 files)
9. **10 Route 53** (21 files)
10. **11 Classic Solutions Architecture Discussions** (7 files)
11. **12 Amazon S3 Introduction** (13 files)
12. **13 Advanced Amazon S3** (11 files)
13. **14 Amazon S3 Security** (14 files)
14. **15 CloudFront & AWS Global Accelerator** (9 files)
15. **16 AWS Storage Extras** (10 files)
16. **17 Decoupling applications SQS, SNS, Kinesis, Active MQ** (24 files)
17. **18 Containers on AWS ECS, Fargate, ECR & EKS** (13 files)
18. **19 Serverless Overviews from a Solution Architect Perspective** (28 files)
19. **20 Serverless Solution Architecture Discussions** (4 files)
20. **21 Databases in AWS** (12 files)
21. **22 Data & Analytics** (14 files)
22. **23 Machine Learning** (17 files)
23. **24 AWS Monitoring & Audit CloudWatch, CloudTrail & Config** (17 files)
24. **25 Identity and Access Management (IAM) - Advanced** (9 files)
25. **26 AWS Security & Encryption KMS, SSM Parameter Store, Shield, WAF** (21 files)
26. **27 Networking - VPC** (37 files)
27. **28 Disaster Recovery & Migrations** (10 files)
28. **29 More Solution Architectures** (5 files)
29. **30 Other Services** (18 files)
30. **31 WhitePapers and Architectures** (4 files)
31. **32 Preparing for the Exam + Practice Exam** (7 files)
32. **33 Congratulations** (2 files)

## Quy Trình Thực Hiện
1. **Dịch từng module**: Bắt đầu từ module 01
2. **Đặt tên file dịch**: Thêm suffix `_vi` (ví dụ: `001_video_vi.srt`)
3. **Quality check**: Kiểm tra sau mỗi file dịch
4. **Progress tracking**: Cập nhật tiến độ trong file này
5. **Đánh dấu module hoàn thành**: Tick `[x]` vào module đã dịch xong; không cần liệt kê các file đã hoàn thành

## Tiến Độ Thực Hiện
- [x] Module 01: 7/7 files
- [x] Module 03: 6/6 files
- [x] Module 04: 18/18 files
- [x] Module 05: 18/18 files
- [x] Module 06: 8/8 files
- [x] Module 07: 14/14 files
- [ ] Module 08: 2/17 files
- [ ] Module 09: 2/13 files
- [x] Module 10: 21/21 files
- [x] Module 11: 7/7 files
- [x] Module 12: 13/13 files
- [x] Module 13: 11/11 files
- [x] Module 14: 14/14 files
- [x] Module 15: 9/9 files
- [x] Module 16: 10/10 files
- [x] Module 17: 24/24 files
- [x] Module 18: 13/13 files
- [x] Module 19: 28/28 files
- [x] Module 20: 4/4 files
- [x] Module 21: 12/12 files
- [x] Module 22: 14/14 files
- [ ] Module 23: 0/17 files
- [ ] Module 24: 0/17 files
- [ ] Module 25: 1/9 files
- [ ] Module 26: 10/21 files
- [ ] Module 27: 0/37 files
- [ ] Module 28: 2/10 files
- [ ] Module 29: 0/5 files
- [ ] Module 30: 12/18 files
- [ ] Module 31: 0/4 files
- [ ] Module 32: 0/7 files
- [ ] Module 33: 0/2 files

**Tổng tiến độ: 280/428 files (65.4%)**

## Ghi Chú
### Thứ tự ưu tiên dịch:
1. **Theo thứ tự tăng dần của tên module** (01 → 02 → 03 → ...)
2. **Ưu tiên các module chưa dịch xong** trước khi hoàn thiện các module đã dịch một phần
3. **Module tiếp theo cần dịch**: Module 23 (Machine Learning)

### Quy tắc kỹ thuật:
- Chú ý đặc biệt với các thuật ngữ mới xuất hiện
- Kiểm tra timestamp không bị thay đổi
- Đảm bảo độ dài text phù hợp với thời gian hiển thị
