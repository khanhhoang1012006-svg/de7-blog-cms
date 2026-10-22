# Đề 7 - Hệ thống Blog/CMS

Môn học: Triển khai và Quản trị Hệ thống Phần mềm

## Giới thiệu
Hệ thống Blog/CMS sử dụng WordPress để quản lý
bài viết, danh mục và người dùng.

## Công nghệ
- WordPress
- MySQL
- phpMyAdmin
- Nginx
- Docker Compose
- Prometheus và Grafana (giai đoạn 2)
- Loki và Promtail (giai đoạn 3)

## Hướng dẫn chạy
1. Cài đặt Docker Desktop.
2. Tạo file .env với các biến:
   MYSQL_ROOT_PASSWORD
   MYSQL_PASSWORD
3. Chạy:
   docker compose up -d
4. Truy cập:
   WordPress: http://localhost:8080
   phpMyAdmin: http://localhost:8081

## Bảo mật
Không đưa file .env chứa mật khẩu lên GitHub.