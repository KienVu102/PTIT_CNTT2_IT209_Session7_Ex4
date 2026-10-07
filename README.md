# Bài 4: Cấu hình Reverse Proxy Nginx

## 1. File cấu hình

File cấu hình:

`spring-proxy.conf`

Đường dẫn:

`/etc/nginx/sites-available/spring-proxy.conf`

Cấu hình đã được kích hoạt bằng symlink:

`/etc/nginx/sites-enabled/spring-proxy.conf`

---

## 2. Kiểm tra cấu hình Nginx

Lệnh thực hiện:

```bash
sudo nginx -t

Kết quả:

nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
nginx: configuration file /etc/nginx/nginx.conf test is successful
