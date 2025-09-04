# Kế Hoạch Dịch Subtitle AWS SAA-C03

## Tổng Quan
- **Số lượng file cần dịch**: 229 file .srt
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
1. **01 Introduction - AWS Certified Solutions Architect Associate** (12 files)
2. **03 Getting started with AWS** (6 files)  
3. **06 EC2 - Solutions Architect Associate Level** (9 files)
4. **07 EC2 Instance Storage** (24 files)
5. **08 High Availability and Scalability ELB & ASG** (30 files)
6. **09 AWS Fundamentals RDS + Aurora + ElastiCache** (23 files)
7. **11 Classic Solutions Architecture Discussions** (16 files)
8. **12 Amazon S3 Introduction** (16 files)
9. **13 Advanced Amazon S3** (24 files)
10. **14 Amazon S3 Security** (31 files)
11. **15 CloudFront & AWS Global Accelerator** (20 files)
12. **17 Decoupling applications SQS, SNS, Kinesis, Active MQ** (7 files)
13. **18 Containers on AWS ECS, Fargate, ECR & EKS** (16 files)
14. **20 Serverless Solution Architecture Discussions** (10 files)
15. **21 Databases in AWS** (25 files)
16. **22 Data & Analytics** (30 files)
17. **25 Identity and Access Management (IAM) - Advanced** (17 files)
18. **26 AWS Security & Encryption KMS, SSM Parameter Store, Shield, WAF** (31 files)
19. **28 Disaster Recovery & Migrations** (10 files)
20. **29 More Solution Architectures** (12 files)
21. **30 Other Services** (20 files)

## Quy Trình Thực Hiện
1. **Backup file gốc**: Tạo thư mục `original_subtitles_backup`
2. **Dịch từng module**: Bắt đầu từ module 01
3. **Đặt tên file dịch**: Thêm suffix `_vi` (ví dụ: `001_video_vi.srt`)
4. **Quality check**: Kiểm tra sau mỗi file dịch
5. **Progress tracking**: Cập nhật tiến độ trong file này

## Tiến Độ Thực Hiện
- [ ] Module 01: 7/7 files ✅ 001, 003, 004, 005, 006, 006, 007
- [ ] Module 03: 4/6 files ✅ 001 AWS Cloud Overview, 002 [Important], 003 About, 004 About
- [ ] Module 06: 0/9 files
- [ ] Module 07: 0/24 files
- [ ] Module 08: 0/30 files
- [ ] Module 09: 0/23 files
- [ ] Module 11: 0/16 files
- [ ] Module 12: 3/16 files ✅ 005 S3 Website Overview, 007 S3 Versioning, 010 S3 Replication Notes
- [ ] Module 13: 0/24 files
- [ ] Module 14: 1/31 files ✅ 004 S3 Default Encryption
- [ ] Module 15: 0/20 files
- [ ] Module 17: 0/7 files
- [ ] Module 18: 0/16 files
- [ ] Module 20: 0/10 files
- [ ] Module 21: 2/25 files ✅ 007 DocumentDB, 009 Keyspaces
- [ ] Module 22: 0/30 files
- [ ] Module 25: 0/17 files
- [ ] Module 26: 3/31 files ✅ 001 Section Intro, 007 Encrypted AMI Sharing, 021 Amazon Macie
- [ ] Module 28: 0/10 files
- [ ] Module 29: 0/12 files
- [ ] Module 30: 2/20 files ✅ 001 Section Intro, 010 AWS Cost Anomaly Detection

**Tổng tiến độ: 22/229 files (9.6%)**

## Ghi Chú
- Ưu tiên dịch các module cơ bản trước (01, 03, 06)
- Chú ý đặc biệt với các thuật ngữ mới xuất hiện
- Kiểm tra timestamp không bị thay đổi
- Đảm bảo độ dài text phù hợp với thời gian hiển thị
