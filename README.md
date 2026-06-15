All impacts are summed and converted to an equivalent Bortle increment.
3. **Final Bortle** = Base Bortle + increment (clamped to 1–9).

### Example
If you are 30 km from a city of 500,000 population and 80 km from a city of 200,000:
- Impact₁ = (500000⁰·⁸) / 30² ≈ 237.5
- Impact₂ = (200000⁰·⁸) / 80² ≈ 18.3
- Total impact ≈ 255.8 → adds ~1.2 Bortle classes on top of a rural base (Class 3) → Final Bortle = 4 (Rural/suburban transition).

## 📸 Screenshots
<p align="center">
<img src="ScreenShots/1.png" width="30%" alt="Main screen - English"/>
<img src="screenshots/2.png" width="30%" alt="Score breakdown - English"/>
<img src="screenshots/3.png" width="30%" alt="Score breakdown - Persian"/>
</p>

## 📥 Installation
1. Download the latest APK from the [Releases]https://github.com/siroos0000/StargazingApp/releases/tag/v2.0.0 page.
2. Enable “Install from unknown sources” on your Android device if required.
3. Install and grant location permission for automatic coordinates.
4. (Optional) Add your OpenWeatherMap API key in **Settings** – a default key is embedded for low‑volume usage.

## 🚀 Usage
- Launch the app. It will fetch your location and display the current Sky Quality Score.
- Tap on any metric (Clouds, Moon, Light Pollution) to see its detailed contribution.
- Use the time slider to check forecast quality for later tonight.
- Switch language at any time from the settings menu.
## 🛠️ Tech Stack
- **Framework:** .NET MAUI (net10.0-android)
- **Language:** C# 12
- **Architecture:** Code-Behind
- **APIs:** 
  - [OpenWeatherMap](https://openweathermap.org/) – Weather and astronomy data (One Call API 3.0)
  - [OpenStreetMap](https://www.openstreetmap.org/) – Nominatim and Overpass API

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

## 🛠️ فناوری‌هاعماری:*
- **فریم‌ورک:** NET MAUI. (net10.0-android)
- **زبان برنامه‌نویسی:** C# 12
  **معماری** Code-Behind
- **رابط‌های برنامه‌نویسی (API):** 
- [OpenWeatherMap](https://openweathermap.org/) – داده‌های هواشناسی و نجوم (One Call API 3.0)
- [OpenStreetMap](https://www.openstreetmap.org/) – Nominatim  و Overpass API
- ## 📄 مجوز
در حال حاضر هیچ مجوزی برای این پروژه تعیین نشده است. کلیه حقوق محفوظ است تا اطلاع ثانوی.  
*ممکن است در نسخه‌های آینده تغییر کند.*

