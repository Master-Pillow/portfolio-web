**Nền tảng Self-hosted quản lý và trưng bày các dự án nghiên cứu.**

## 📖 Giới thiệu (Introduction)

**Portfolio Web** là một hệ thống quản lý dự án tập trung (tương tự như một GitHub thu nhỏ), được xây dựng để lưu trữ, tài liệu hóa và chia sẻ các sản phẩm công nghệ của tôi và các cộng sự (partners).

Dự án không chỉ là một Portfolio tĩnh, mà là một hệ thống **Full-stack** hoàn chỉnh giúp quản lý vòng đời dự án, từ ý tưởng đến khi deploy.

### 🎯 Các lĩnh vực trọng tâm
Hệ thống này chuyên lưu trữ các dự án thuộc các lĩnh vực:
* **Artificial Intelligence (AI) / Machine Learning (ML) / Deep Learning (DL)**
* **Information Security & Reverse Engineering**
* **Quantitative Finance & Economics** (Kinh tế lượng & Tài chính)
* **System Programming**

---

## 🛠 Tech Stack (Công nghệ sử dụng)

Dự án áp dụng kiến trúc **3-Tier Architecture** hiện đại và chuẩn mực:

| Thành phần | Công nghệ | Mô tả |
| :--- | :--- | :--- |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) | **Next.js 14 (App Router)**, Tailwind CSS, Lucide React. |
| **Backend** | ![NestJS](https://img.shields.io/badge/NestJS-red?logo=nestjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-green?logo=node.js&logoColor=white) | **NestJS**, RESTful API, JWT Authentication, Swagger UI. |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-blue?logo=postgresql&logoColor=white) | PostgreSQL, TypeORM/Prisma (ORM). |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-blue?logo=docker&logoColor=white) | Docker Compose, Nginx (Reverse Proxy). |

---

## ✨ Tính năng chính (Key Features)

* **Project Showcase:** Hiển thị danh sách dự án dạng Grid/List với bộ lọc theo Tech Stack (Python, C++, Assembly...).
* **Detailed View:** Xem chi tiết dự án, hỗ trợ render file `README.md` (Markdown) trực tiếp.
* **Partner Management:** Quản lý thông tin các thành viên, phân quyền đóng góp.
* **Secure Authentication:** Đăng nhập bảo mật sử dụng **JWT (JSON Web Token)**.
* **Admin Dashboard:** Trang quản trị để thêm/sửa/xóa dự án và quản lý resources (ảnh, tài liệu).

---

## 🚀 Cài đặt & Chạy dự án (Getting Started)

Để chạy dự án này trên máy local, bạn cần cài đặt **Node.js**, **PostgreSQL** và **Git**.

### 1. Clone dự án
```bash
git clone [https://github.com/username/portfolio-web.git](https://github.com/username/portfolio-web.git)
cd portfolio-web
