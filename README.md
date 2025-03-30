<div align="center">
  
![Preview](preview.png)

# 📌 قالب صفحه کاربری پنل مرزبان - MrClock

<p align="center">
  <a href="#معرفی">معرفی</a> •
  <a href="#ویژگی‌ها">ویژگی‌ها</a> •
  <a href="#نصب">نصب</a> •
  <a href="#به‌روزرسانی">به‌روزرسانی</a> •
  <a href="#شخصی‌سازی">شخصی‌سازی</a>
</p>

</div>

<a name="معرفی"></a>
## 🎨 معرفی

<p dir="rtl">
قالب صفحه کاربری پنل مرزبان با طراحی مینیمال و کاربرپسند. این پروژه با الهام از 
<a href="https://github.com/dermv/marzbanify-template/tree/main">قالب Marzbanify</a>
و با کسب مجوز از توسعه‌دهنده اصلی، توسعه و ساده‌سازی شده است. در این تمپلیت دو اپلیکیشن قرار دارد: hiddify و sing-box. پیشنهاد میکنم برای استفاده هرچه بهتر از اپلیکیشن sing-box از 
<a href="https://github.com/Mrclocks/MrClock-SingBox-Template">این تمپلیت</a>
استفاده کنید.
</p>

<a name="ویژگی‌ها"></a>
## ✨ ویژگی‌های کلیدی

<div dir="rtl" align="center">

| ویژگی | توضیحات |
|:-----:|---------|
| **⚡ سبک و سریع** | حجم کم و بارگذاری سریع بدون المان‌های اضافه |
| **🎨 طراحی مدرن** | رابط کاربری زیبا و مینیمال با تجربه کاربری بهبودیافته |
| **🛠 نصب آسان** | راه‌اندازی سریع با چند دستور ساده |
| **📱 واکنش‌گرا** | سازگاری کامل با تمام دستگاه‌ها (موبایل، تبلت و دسکتاپ) |

</div>

<a name="نصب"></a>
## 📥 نصب و راه‌اندازی

<div>

### 1️⃣ دانلود فایل قالب

</div>

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/Mrclocks/MrClock-Subscription-Template/main/index.html
```

<div>

### 2️⃣ ثبت تنظیمات در محیط مرزبان

</div>

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

<div>

#### 📝 روش جایگزین: اضافه کردن مستقیم به فایل `.env`

مقادیر زیر را مستقیماً در فایل `.env` واقع در `/opt/marzban/` اضافه کنید:

</div>

```bash
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```

<div>

### 3️⃣ راه‌اندازی مجدد مرزبان

</div>

```bash
marzban restart
```

<div>

## 🔄 به‌روزرسانی قالب

<div dir="rtl" align="right">
  <p>برای دریافت آخرین نسخه قالب، کافیست مرحله اول (دانلود فایل قالب) را دوباره اجرا کنید.</p>
</div>

<a name="شخصی‌سازی"></a>
## 🌐 شخصی‌سازی

<div>

### 💬 تغییر لینک پشتیبانی

برای تغییر لینک پشتیبانی در خط 245 فایل، عبارت `YOUR-TELEGRAM-USERNAME` را با نام کاربری تلگرام خود جایگزین کنید.



### 📲 تغییر لینک‌های دانلود برنامه‌ها

جهت تغییر مسیر دانلود برنامه‌ها، لینک‌های موجود بین خط‌های 293 تا 309 را به لینک دلخواه خود ویرایش کنید. به‌صورت پیش‌فرض تمام اپلیکیشن‌ها به‌صورت اتوماتیک آخرین نسخه را دریافت می‌کنند به‌جز نسخه اندروید اپلیکیشن sing-box.

</div>

---

<div align="center">
  <p dir="rtl">🌟 اگر از این پروژه خوشتان آمد، لطفاً به آن ستاره دهید 🌟</p>
  
  <p>
    <a href="https://github.com/Mrclocks/MrClock-Subscription-Template">
      <img src="https://img.shields.io/github/stars/Mrclocks/MrClock-Subscription-Template?style=social" alt="ستاره‌های گیت‌هاب">
  </p>
  
  <p dir="rtl">با ❤️ توسط MrClock</p>
</div>
