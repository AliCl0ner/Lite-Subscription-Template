![Preview](preview.png)

<h1 align="center" dir="rtl">📌 قالب صفحه کاربری پنل مرزبان - MrClock</h1>



---

## 🎨 معرفی

<p dir="rtl">
قالب صفحه کاربری پنل مرزبان با طراحی مینیمال و کاربرپسند. این پروژه با الهام از 
<a href="https://github.com/dermv/marzbanify-template/tree/main">قالب Marzbanify</a>
و با کسب مجوز از توسعه‌دهنده اصلی، توسعه و ساده‌سازی شده است.در این تمپلیت دو اپلیکیشن قرار دارد: hiddify و sing-box . پیشنهاد میکنم برای استفاده هرچه بهتر از اپلیکیشن sing-box از 
   <a href="https://github.com/Mrclocks/MrClock-SingBox-Template">این تمپلیت </a>
استفاده کنید.
</p>

---

## ✨ ویژگی‌های کلیدی

<div align="center" dir="rtl">

| ویژگی          | توضیحات                                                                 |
|----------------|-------------------------------------------------------------------------|
| **⚡ سبک و سریع** | حجم کم و بارگذاری سریع بدون المان‌های اضافه                           |
| **🎨 طراحی مدرن** | رابط کاربری زیبا و مینیمال با تجربه کاربری بهبودیافته                |
| **🛠 نصب آسان**  | راه‌اندازی سریع با چند دستور ساده                                     |
| **📱 واکنش‌گرا**  | سازگاری کامل با تمام دستگاه‌ها (موبایل، تبلت و دسکتاپ)              |

</div>

---


## 📥 نصب اولیه

<p dir="rtl">

### 1- دانلود فایل قالب:
</p>

   ```bash
   sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/Mrclocks/MrClock-Subscription-Template/main/index.html
   ```

<p dir="rtl">

### 2- ثبت تنظیمات در محیط مرزبان:
</p>

   ```bash
   echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
   echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
   ```

<p dir="rtl">

یا مقادیر زیر را مستقیماً در فایل `.env` واقع در `/opt/marzban/` اضافه کنید:
 </p>

   ```bash
   CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
   SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
   ```

<p dir="rtl">

### 3- راه‌اندازی مجدد مرزبان:
</p>

   ```bash
   marzban restart
   ```

---

## 🔄 به‌روزرسانی قالب

##### برای دریافت آخرین نسخه قالب، کافیست مرحله اول (دانلود فایل قالب) را دوباره اجرا کنید.

---

## 🌐 تفییر لینک پشتیبانی و برنامه ها

##### - برای تغییر لینک پشتیبانی کافیست در خط 241 عبارت YOUR-TELEGRAM-USERNAME را پاک کرده و یوزرنیم تلگرام خود را قرار دهید.

##### - جهت تغییر مسیر دانلود برنامه ها کافیت لینک های موجود بین خط های 288 تا 305 را به لینک دلخواه خود ویرایش کنید . بصورت پیشفرض تمام اپلیکیشن ها بصورت اتوماتیک آخرین نسخه را دریافت می کنند بجز نسخه اندروید اپلیکیشن sing-box .








