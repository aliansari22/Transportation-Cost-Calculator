# ماشین‌حساب هزینه حمل‌ونقل

## مرور کلی

این پروژه یک ماشین‌حساب مبتنی بر وب برای تخمین هزینه‌های حمل‌ونقل برای روش‌ها و انواع مختلف کالاها است. برنامه شامل سه ماشین‌حساب برای سناریوهای مختلف است: کالاهای عمومی، جعبه‌ها، و کانتینرها.

## ویژگی‌ها

- **سه زبانه ماشین‌حساب**:
  - ماشین‌حساب کالاهای عمومی
  - ماشین‌حساب جعبه‌ها
  - ماشین‌حساب کانتینر
- **محاسبات بلادرنگ**:
  - محاسبه خودکار هزینه‌ها با ورود داده‌ها.
- **رابط کاربری تعاملی**:
  - ناوبری زبانه‌ها برای دسترسی آسان به ماشین‌حساب‌های مختلف.
  - اعتبارسنجی ورودی‌ها و مدیریت خطا.
  - نمایش پویا نتایج محاسبات.
- **پارامترهای حمل‌ونقل قابل تنظیم**:
  - گزینه‌هایی برای روش‌های حمل‌ونقل مختلف (حمل‌ونقل دریایی و هوایی).
  - انواع مختلف کالاها با نرخ‌های متفاوت (عادی، کپی، مایع، باتری).

## تکنولوژی‌های استفاده‌شده

- **HTML5**
- **CSS3**
- **JavaScript**

## نحوه کار

### 1. ماشین‌حساب کالاهای عمومی
- ابعاد (طول، عرض، ارتفاع) را بر حسب سانتی‌متر و وزن را بر حسب کیلوگرم وارد کنید.
- روش حمل‌ونقل و نوع کالا را انتخاب کنید.
- قیمت کالاها را به ین (¥) وارد کنید.
- هزینه بر اساس CBM (متر مکعب) یا وزن محاسبه می‌شود.

### 2. ماشین‌حساب جعبه‌ها
- ابعاد و وزن جعبه‌های تکی را وارد کنید.
- تعداد جعبه‌ها را وارد کنید.
- روش حمل‌ونقل و نوع کالا را انتخاب کنید.
- هزینه کل بر اساس CBM یا وزن کل جعبه‌ها محاسبه می‌شود.

### 3. ماشین‌حساب کانتینر
- نوع کانتینر (20 فوت یا 40 فوت) را انتخاب کنید.
- تعداد کانتینرها را مشخص کنید.
- نوع کالا را انتخاب کنید.
- هزینه بر اساس ظرفیت کانتینر (CBM) محاسبه می‌شود.

## دستورالعمل نصب

1. مخزن را کلون کنید:
   ```bash
   git clone <repository-url>
   ```
2. فایل `calculator.html` را در مرورگر باز کنید تا برنامه اجرا شود.

## نحوه استفاده

- به زبانه ماشین‌حساب موردنظر بروید.
- تمام فیلدهای لازم را با مقادیر مناسب پر کنید.
- هزینه محاسبه‌شده حمل‌ونقل را که به‌طور پویا نمایش داده می‌شود مشاهده کنید.
- فرم را با استفاده از دکمه "بازنشانی" یا میانبر (Shift+N) بازنشانی کنید.

## میانبرها

- **Shift+N**: بازنشانی فرم فعال فعلی.

## ساختار فایل

- **`calculator.html`**: فایل اصلی برنامه که شامل تمام HTML، CSS، و جاوااسکریپت است.
- **استایل‌ها**:
  - استایل‌های سفارشی در داخل HTML برای واکنش‌گرایی و انیمیشن‌ها قرار دارند.
- **جاوااسکریپت**:
  - مدیریت رویدادهای ورودی فرم، محاسبات پویا و تعاملات کاربر.

## مشکلات شناخته‌شده و بهبودهای آتی

- **بازخورد خطا**: در حال حاضر پیام‌های خطا محدود به اعلان‌های مرتبط با فیلدها هستند.
- **یکپارچه‌سازی پایگاه داده**: افزودن پشتیبانی برای ذخیره نتایج محاسبه‌شده یا داده‌های تاریخی.
- **نرخ‌های سفارشی**: امکان وارد کردن نرخ‌های سفارشی برای انواع کالا و روش‌های حمل‌ونقل.

## لایسنس

این پروژه منبع‌باز بوده و تحت [مجوز MIT](LICENSE) موجود است.

---

اگر نیاز به تغییر یا گسترش بیشتر این قالب دارید، اطلاع دهید!
