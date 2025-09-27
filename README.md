# Hệ Thống Quản Lý Lịch Thông Minh

M### 3. Ứng Dụng Di Động

#### Lựa Chọn Phát Triển:

1. **React Native**

   - Tái sử dụng code từ web frontend
   - Phát triển đa nền tảng

2. **Flutter**
   - Giao diện đẹp và mượt mà
   - Hiệu suất tối ưu trên cả Android & iOS

#### Tính Năng Di Động:

- Xem lịch học (dạng lịch và danh sách)
- Thông báo đẩy (Firebase Cloud Messaging)
- Đăng ký môn học/lớp học
- AI gợi ý lịch học
- Xem điểm danh và kết quả học tậpn để quản lý lịch học thông qua nền tảng Web và Mobile.

## 👥 Thành Viên Nhóm

1. [Võ Văn Luận](https://github.com/VanLuanIT24) - Team Leader
2. [Nguyễn Anh Tuấn](https://github.com/TuanTKey) - Developer
3. [Nguyễn Phước Đại](https://github.com/phuocdai2004) - Developer
4. [Y Phai Niê](https://github.com/youngestwall) - Developer
5. [Nguyễn Thành Đạt](https://github.com/nguyendat-d) - Developer

## 🏗️ Kiến Trúc Triển Khai

### 1. Backend & Database (Dùng Chung)

- **Backend Framework:**
  - Node.js (NestJS/Express) hoặc Django/FastAPI
  - API: RESTful hoặc GraphQL để web và app đều dùng được
- **Cơ Sở Dữ Liệu:**
  - MySQL (cài đặt trực tiếp, không dùng Docker)
- **Module AI:**
  - Python (FastAPI) hoặc tích hợp Node.js
  - Cung cấp qua API endpoints

### 2. Web Frontend

- **Công Nghệ Sử Dụng:**
  - React/Next.js
  - TailwindCSS
  - shadcn/ui components
- **Tính Năng Chính:**
  - Bảng điều khiển quản trị
  - Quản lý lịch
  - Quản lý môn học/lớp học
  - AI gợi ý lịch học
- **Triển Khai:**
  - Vercel, Netlify, hoặc máy chủ riêng

### 3. Ứng Dụng Di Động

#### Development Options:

1. **React Native**

   - Code reusability with web frontend
   - Cross-platform development

2. **Flutter**
   - Enhanced UI/UX
   - Optimal performance on Android & iOS

#### Mobile Features:

- Schedule viewing (calendar & list view)
- Push notifications (Firebase Cloud Messaging)
- Course/Class registration
- AI schedule suggestions
- Attendance & academic performance tracking

### 4. Triển Khai & Tích Hợp

- API thống nhất cho Web & Mobile
- Thông báo real-time qua WebSocket/Firebase
- Đồng bộ lịch với Google Calendar/Outlook
- Triển khai ứng dụng trên Google Play & App Store

## 📋 Tính Năng Cốt Lõi (Web + Mobile)

### Quản Lý Người Dùng

- Đăng nhập/đăng ký và phân quyền
- Quản lý hồ sơ cá nhân

### Quản Lý Học Tập

- Quản lý môn học và lớp học
- Quản lý lịch học (CRUD + Xuất file)
- AI tối ưu và cảnh báo lịch học

### Giao Tiếp

- Thông báo thay đổi lịch học
  - Thông báo web
  - Thông báo đẩy trên mobile
- Nền tảng trao đổi giảng viên - sinh viên

### Tích Hợp

- Đồng bộ hóa Google Calendar/Outlook
- Theo dõi điểm danh
- Giám sát kết quả học tập

## Công Nghệ Sử Dụng

### Backend

- Node.js/Python
- RESTful/GraphQL API
- Cơ sở dữ liệu MySQL
- WebSocket/Firebase cho tính năng real-time

### Web Frontend

- Next.js/React
- TailwindCSS
- shadcn/ui

### Ứng Dụng Di Động

- React Native hoặc Flutter
- Firebase Cloud Messaging
- Tích hợp lịch native

## Bắt Đầu

[Đang cập nhật...]

## Đóng Góp

[Đang cập nhật...]

## Giấy Phép

[Đang cập nhật...]

Developed by **Team VNY** (Visionary New Youth).

## 🚀 Features

- ✅ User-friendly appointment scheduling
- ✅ Video call between doctor and patient
- ✅ Dashboard for personal health monitoring
- ✅ AI recommendation for diet & workout plans
- ✅ Role-based security for patients, doctors, and admins

## 🛠 Tech Stack

- **Frontend**: React / Next.js + Tailwind CSS
- **Backend**: Node.js (Express) / NestJS
- **Database**: MongoDB / PostgreSQL
- **AI/ML**: TensorFlow.js / OpenAI API (diet & health suggestion)
- **Video Call**: WebRTC / Socket.IO
- **Deployment**: Docker + Vercel/Heroku/AWS
