# 📄 Docker NGINX Static Website

سرو کردن یک وب‌سایت HTML ساده با استفاده از NGINX درون کانتینر Docker.

این پروژه یکی از رایج‌ترین سناریوهای DevOps برای میزبانی صفحات استاتیک است که در محیط‌های واقعی، مثل Landing Page یا صفحه نگهداری (maintenance)، کاربرد دارد.

---

## 🔧 تکنولوژی‌ها

- 🐳 Docker
- 🌐 NGINX (وب‌سرور سبک و پرقدرت)
- 🧾 HTML (زبان ساخت صفحات وب)

---

## 🚀 اجرا

### ۱. ساخت image:

```bash
docker build -t nginx-static .
