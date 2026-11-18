# CSE313 - Hệ thống Quản lý Chuyến bay (Flight Management System)

## 🎯 1. Mục tiêu dự án
* Xây dựng ứng dụng web quản lý lịch trình chuyến bay, thông tin máy bay, hãng hàng không và đặt vé cơ bản.
* Số hóa quy trình tra cứu, thêm mới, cập nhật và hủy chuyến bay cho nhân viên điều hành hoặc hành khách.

## 👥 2. Thành viên nhóm & Phân công công việc
| STT | Họ và tên | Mã sinh viên | Vai trò / Nhiệm vụ chính |
| :---: | :--- | :---: | :--- |
| 1 | Mai Quang Vũ | 2451160817 | Trưởng nhóm, Thiết kế Cơ sở dữ liệu & Backend API |
| 2 | [Tên Thành viên 2] | [MSV] | Phát triển Giao diện Dashboard & Quản lý chuyến bay (Frontend) |
| 3 | [Tên Thành viên 3] | [MSV] | Xức năng Tra cứu, Đặt vé & Quản lý người dùng |

## 🛠 3. Công nghệ sử dụng
* **Frontend:** React.js / Next.js, Tailwind CSS, Lucide Icons
* **Backend:** Node.js (Express) hoặc PHP (Laravel)
* **Database:** MySQL / PostgreSQL (Quản lý các bảng: Flights, Airports, Airplanes, Bookings, Users)

## 🚀 4. Các chức năng chính của hệ thống
* **Quản lý Chuyến bay (Admin):** Thêm, sửa, xóa thông tin chuyến bay (Mã chuyến bay, điểm đi, điểm đến, giờ khởi hành, giờ hạ cánh, giá vé, trạng thái).
* **Tra cứu & Tìm kiếm (Khách hàng):** Tìm kiếm chuyến bay theo địa điểm đi/đến và ngày khởi hành.
* **Đặt vé trực tuyến:** Cho phép chọn chuyến bay, nhập thông tin hành khách và lưu lại lịch sử đặt chỗ.
* **Quản lý tài khoản:** Phân quyền rõ ràng giữa Khách hàng (Passenger) và Quản trị viên (Admin).

## ⚙️ 5. Hướng dẫn cài đặt nhanh (Local Setup)
```bash
# 1. Clone repository về máy
git clone [https://github.com/maiquangvu206/flight-management.git](https://github.com/maiquangvu206/flight-management.git)

# 2. Cài đặt thư viện Backend
cd backend && npm install

# 3. Cài đặt thư viện Frontend
cd ../frontend && npm install

# 4. Khởi chạy ứng dụng
npm run dev
