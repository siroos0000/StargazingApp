# Gini Stargazing | جینی: رصد ستارگان

<div align="center">

**Calculate night sky quality and find the perfect time for stargazing.**
**محاسبه کیفیت آسمان شب و یافتن بهترین زمان برای رصد ستارگان.**

[![Platform](https://img.shields.io/badge/Platform-Android-green)]()
[![Framework](https://img.shields.io/badge/Framework-.NET%20MAUI-purple)]()
[![Language](https://img.shields.io/badge/Language-C%23-blue)]()
[![License](https://img.shields.io/badge/License-None-lightgrey)]()

**[🌍 English](#-english)** | **[🇮🇷 فارسی](#-فارسی)**

</div>

---

# 🌍 English

## 📖 About
**Gini** is an Android application built with .NET MAUI that helps amateur astronomers, astrophotographers, and nature lovers determine if the night sky is ready for stargazing. By analyzing real-time weather data, cloud cover, and local light pollution, it calculates a comprehensive **Sky Quality Score** (0–100) and the standard **Bortle Class** (1–9).

Whether you're planning a telescope session or a naked-eye meteor shower watch, Gini gives you an instant, science‑based go/no‑go recommendation.

## ✨ Features
- ⭐ **Sky Quality Score:** Real-time calculation from 0 (worst) to 100 (pristine).
- 🌃 **Bortle Scale:** Accurate light pollution classification (Class 1 – Excellent Dark Sky, to Class 9 – Inner-city Sky).
- ☁️ **Live Weather:** Temperature, cloud cover, humidity, and precipitation probability via OpenWeatherMap.
- 🌅 **Day/Night Detection:** Precise sunrise, sunset, and astronomical twilight times using server time and coordinates.
- 🏙️ **City Impact:** Identifies nearby cities (up to 100 km) using OpenStreetMap and calculates their individual light pollution contribution based on population and distance.
- 🌐 **Bilingual UI:** Full support for Persian (Farsi) and English, including RTL layout.
- 🧭 **Location Services:** Uses device GPS or manual coordinate entry.
- 📊 **Live Score Breakdown:** See exactly how each factor (clouds, Moon, light domes) affects the final quality.

## 🛠️ Tech Stack
- **Framework:** .NET MAUI (net10.0-android)
- **Language:** C# 12
- **Architecture:** Code-Behind
- **APIs:** 
  - [OpenWeatherMap](https://openweathermap.org/) – Weather and astronomy data (One Call API 3.0)
  - [OpenStreetMap](https://www.openstreetmap.org/) – Nominatim and Overpass API

## 📸 Screenshots
<p align="center">
<img src="ScreenShots/1.png" width="30%" alt="Main screen"/>
<img src="ScreenShots/2.png" width="30%" alt="Score details"/>
<img src="ScreenShots/3.png" width="30%" alt="Persian interface"/>
</p>

## 📥 Installation
1. Download the latest APK from the [Releases](https://github.com/siroos0000/StargazingApp/releases/tag/v2.0.0) page.
2. Enable “Install from unknown sources” on your Android device if required.
3. Install and grant location permission for automatic coordinates.


## 🚀 Usage
- Launch the app. It will fetch your location and display the current Sky Quality Score.
- Tap on any metric (Clouds, Moon, Light Pollution) to see its detailed contribution.
- Use the time slider to check forecast quality for later tonight.
- Switch language at any time.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.  
If you enjoy the project, give it a ⭐ on GitHub!

## 📄 License
No license is currently assigned to this project. All rights reserved until further notice.  
*This may change in future releases.*

---

# 🇮🇷 فارسی

## 📖 درباره
**جینی** یک اپلیکیشن اندرویدی ساخته‌شده با NET MAUI. است که به منجمان آماتور، عکاسان نجومی و علاقه‌مندان به طبیعت کمک می‌کند تشخیص دهند آسمان شب برای رصد آماده است یا خیر. این برنامه با تحلیل داده‌های زندهٔ آب‌وهوا، میزان پوشش ابر و آلودگی نوری محل، یک **امتیاز کیفیت آسمان** (۰ تا ۱۰۰) و **کلاس بورتل** استاندارد (۱ تا ۹) را محاسبه می‌کند.

چه برای رصد با تلسکوپ برنامه‌ریزی کنید چه برای تماشای یک بارش شهابی با چشم غیرمسلح، جینی در لحظه به شما یک توصیهٔ علمی و قاطع می‌دهد.

## ✨ ویژگی‌ها
- ⭐ **امتیاز کیفیت آسمان:** محاسبهٔ لحظه‌ای از ۰ (بدترین) تا ۱۰۰ (بی‌نظیر).
- 🌃 **مقیاس بورتل:** طبقه‌بندی دقیق آلودگی نوری (کلاس ۱ – آسمان کاملاً تاریک، تا کلاس ۹ – آسمان درون‌شهری).
- ☁️ **آب‌وهوای زنده:** دما، پوشش ابر، رطوبت و احتمال بارش با استفاده از OpenWeatherMap.
- 🌅 **تشخیص شب/روز:** محاسبهٔ دقیق طلوع، غروب و گرگ و میش نجومی با استفاده از زمان سرور و مختصات.
- 🏙️ **تأثیر شهرها:** شناسایی شهرهای نزدیک (تا شعاع ۱۰۰ کیلومتر) با OpenStreetMap و محاسبهٔ تأثیر آلودگی نوری هر شهر بر پایهٔ جمعیت و فاصله.
- 🌐 **رابط کاربری دوزبانه:** پشتیبانی کامل از فارسی و انگلیسی (شامل چینش راست‌به‌چپ).
- 🧭 **خدمات مکان‌یابی:** استفاده از GPS دستگاه یا ورود دستی مختصات.
- 📊 **جزئیات امتیاز:** مشاهدهٔ سهم دقیق هر عامل (ابر، ماه، گنبدهای نوری) در امتیاز نهایی.

## 🛠️ فناوری‌ها
- **فریم‌ورک:** NET MAUI. (net10.0-android)
- **زبان برنامه‌نویسی:** C# 12
- **معماری:** Code-Behind
- **رابط‌های برنامه‌نویسی (API):** 
- [OpenWeatherMap](https://openweathermap.org/) – داده‌های هواشناسی و نجوم (One Call API 3.0)
- [OpenStreetMap](https://www.openstreetmap.org/) – Nominatim و Overpass API

## 📸 تصاویر برنامه
<p align="center">
<img src="ScreenShots/1.png" width="30%" alt="صفحه اصلی"/>
<img src="ScreenShots/2.png" width="30%" alt="جزئیات امتیاز"/>
<img src="ScreenShots/3.png" width="30%" alt="رابط فارسی"/>
</p>

## 📥 نصب
۱. آخرین نسخهٔ APK را از صفحهٔ [Releases](https://github.com/siroos0000/StargazingApp/releases/tag/v2.0.0) دانلود کنید.  
۲. در صورت لزوم، نصب از منابع ناشناس را در دستگاه اندرویدی خود فعال کنید.  
۳. برنامه را نصب کرده و مجوز مکان را برای دریافت مختصات خودکار بدهید.  

## 🚀 روش استفاده
- برنامه را باز کنید. مکان شما دریافت شده و امتیاز کیفیت آسمان نمایش داده می‌شود.
- روی هر معیار (ابر، ماه، آلودگی نوری) ضربه بزنید تا سهم دقیق آن را ببینید.
- با نوار زمان می‌توانید پیش‌بینی کیفیت برای ساعات بعدی امشب را بررسی کنید.
-زبان برنامه را در هر زمان تغییر دهید.

## 🤝 مشارکت
درخواست‌های Pull Request با آغوش باز پذیرفته می‌شوند! برای تغییرات بزرگ، لطفاً ابتدا یک Issue باز کنید تا در مورد آن گفتگو کنیم.  
اگر از پروژه لذت می‌برید، با دادن یک ⭐ در گیت‌هاب از ما حمایت کنید!

## 📄 مجوز
در حال حاضر هیچ مجوزی برای این پروژه تعیین نشده است. کلیه حقوق محفوظ است تا اطلاع ثانوی.  
*ممکن است در نسخه‌های آینده تغییر کند.*
