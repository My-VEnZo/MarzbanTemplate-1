<h1 align="center">🎨 تمپلیت برای پنل <a href="https://github.com/Gozargah/Marzban" target="_blank">مرزبان</a></h1>

---

## 📖 مقدمه  
تمپلیت ساخته شده برای <strong>مرزبان</strong> که به راحتی قابل نصب و استفاده است.

---

## ⚙️ نصب  
برای نصب تمپلیت، دستورات زیر را در ترمینال سرور خود اجرا کنید:

1. **دانلود فایل تمپلیت:**  
```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/My-VEnZo/MarzbanTemplate-1/main/index.html
```
2. دستورات زیر رو تو ترمینال سرورتون بزنید:
```sh
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```
3. و در مرحله آخر مرزبان را ریستارت کنید
```sh
marzban restart
```

🙏 با تشکر از [@yousefbn783](https://github.com/yousefbn783) بابت کمک در توسعه این پروژه.
