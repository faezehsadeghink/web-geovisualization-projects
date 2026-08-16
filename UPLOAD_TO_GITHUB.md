# راهنمای بارگذاری در GitHub

نام پیشنهادی Repository:

```text
web-geovisualization-projects
```

## روش ساده از طریق سایت GitHub

1. در GitHub گزینه **New repository** را انتخاب کنید.
2. نام Repository را `web-geovisualization-projects` بگذارید.
3. وضعیت را روی **Public** قرار دهید.
4. گزینه‌های ساخت README و `.gitignore` را فعال نکنید؛ این فایل‌ها از قبل وجود دارند.
5. پس از ساخت Repository، گزینه **uploading an existing file** را انتخاب کنید.
6. محتوای داخل این پوشه را بارگذاری کنید؛ خود پوشه والد را به‌عنوان یک فایل ZIP آپلود نکنید.
7. پیام Commit را `Add web geovisualization portfolio projects` وارد کنید.

## روش Git

```bash
git init
git add .
git commit -m "Add web geovisualization portfolio projects"
git branch -M main
git remote add origin https://github.com/faezehsadeghink/web-geovisualization-projects.git
git push -u origin main
```

## فعال‌کردن GitHub Pages

1. وارد **Settings → Pages** شوید.
2. در بخش **Build and deployment**، گزینه **Deploy from a branch** را انتخاب کنید.
3. شاخه `main` و مسیر `/ (root)` را انتخاب کنید.
4. پس از انتشار، صفحه در این آدرس در دسترس خواهد بود:

```text
https://faezehsadeghink.github.io/web-geovisualization-projects/
```

## نکات مهم

- پروژه اول برای نمایش لایه‌های WMS به GeoServer محلی وابسته است؛ نقشه‌های پایه آنلاین بدون GeoServer هم نمایش داده می‌شوند.
- پروژه چهارم برای دوربین و GPS باید روی HTTPS یا localhost اجرا شود. GitHub Pages از HTTPS پشتیبانی می‌کند.
- قبل از عمومی‌کردن Repository، مجوز انتشار داده‌ها، مدل‌ها و بافت‌ها را بررسی کنید.
- برای این مجموعه هنوز فایل License انتخاب نشده است؛ تا زمان تعیین مجوز، حقوق کد به‌طور پیش‌فرض محفوظ می‌ماند.
