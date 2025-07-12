
# 🌐 وب‌سایت استاتیک با NGINX و Docker

در این پروژه یک صفحه HTML ساده با استفاده از NGINX در Docker سرو می‌شود.

## 📦 تکنولوژی‌ها
- HTML
- NGINX
- Docker

## ⚙️ مراحل اجرا
```bash
docker build -t nginx-static .
docker run -p 8080:80 nginx-static

🎯 کاربردها

میزبانی سریع صفحات فرانت‌اند

تمرین تنظیمات اولیه NGINX

