# EatToday - Hôm nay ăn gì

## Giới thiệu
**EatToday** là ứng dụng web và di động hỗ trợ các bà nội trợ Việt Nam lên kế hoạch bữa ăn hằng ngày cho gia đình.  
Ứng dụng sử dụng **hệ thống gợi ý cá nhân hóa** dựa trên sở thích, chế độ ăn kiêng, ngân sách, nguyên liệu sẵn có và thời tiết.

## Mục tiêu dự án
- Giúp người dùng trả lời câu hỏi **“Hôm nay nấu gì, ăn gì?”** nhanh chóng.  
- Gợi ý thực đơn **ngày/tuần** phù hợp với khẩu vị và dinh dưỡng.  
- Cung cấp **công thức chi tiết, hình ảnh, video và thông tin dinh dưỡng**.  
- Quản lý dữ liệu món ăn, nguyên liệu và tài khoản người dùng (dành cho Admin).  

## Vai trò
- **Người dùng (Nội trợ):** đăng ký, lưu hồ sơ, nhận gợi ý, xem công thức.  
- **Quản trị viên (Admin):** quản lý món ăn, dữ liệu, báo cáo, tài khoản.  

## Công nghệ dự kiến
- **Back-end:** NodeJS / .NET Core / Spring Boot / Python  
- **Database:** MySQL / PostgreSQL / MongoDB  
- **Front-end:** ReactJS / Angular (web)  
- **Mobile:** Flutter hoặc React Native  
- **Triển khai:** Docker, Redis (cache)  

## Cấu trúc repo (dự kiến)
```
CNPM_Ăn hôm nay/
│── docs/        # Tài liệu (SRS, Use-case, ERD, báo cáo…)
│── backend/     # API server
│── web/         # Ứng dụng web (Admin)
│── mobile/      # Ứng dụng mobile (Nội trợ)
│── data/        # Dữ liệu mẫu (JSON/CSV món ăn)
│── tests/       # Kiểm thử
│── README.md
```

## Tiến độ
- [ ] Viết tài liệu yêu cầu (SRS)  
- [ ] Thiết kế Use-case + ERD  
- [ ] Xây dựng backend API  
- [ ] Phát triển mobile app  
- [ ] Phát triển web app  
- [ ] Kiểm thử & triển khai  
