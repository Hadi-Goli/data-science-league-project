# 🎓 لیگ علم داده (Data Science League)

<div dir="rtl">

به ریپازیتوری رسمی لیگ علم داده خوش آمدید.
این مخزن شامل **منابع آموزشی** (اسلایدها، تمرین‌ها) و **کدهای پایه پروژه نهایی** است.

---

## 🏗 منظـور از کدهای پایه (Base Codes) چیست؟

در پوشه `src` و فایل `main.py`، ما یک ساختار استاندارد و ماژولار (Modular Pipeline) برای پروژه‌های علم داده آماده کرده‌ایم.
به جای اینکه تمام کدها را در یک فایل نوت‌بوک طولانی بنویسید، از این ساختار استفاده می‌کنید تا پروژه شما قابلیت توسعه، نگهداری و دیباگ راحت‌تری داشته باشد.

**اجزای این ساختار:**
* `src/data_loader.py`: تابعی برای خواندن استاندارد داده‌ها.
* `src/preprocessing.py`: کدهای مربوط به تمیزکردن داده و مدیریت مقادیر گمشده.
* `src/features.py`: محل ساخت ویژگی‌های جدید (Feature Engineering).
* `src/models.py`: **(زمین بازی اصلی شما)** محلی که مدل‌های هوشمند خود را در آن تعریف می‌کنید.
* `main.py`: فایل اصلی که تمام این قطعات را به هم وصل و اجرا می‌کند.

---

## 🚀 نحوه ارسال تمرینات و داوری (Submission & Scoring)

برای ارسال تمرینات هفتگی و پروژه نهایی، مراحل زیر را طی کنید:

### ۱. ارسال فایل در گیت‌هاب
1.  این ریپازیتوری را **Fork** کنید.
2.  فایل نوت‌بوک خود را (با فرمت `Name_WeekX.ipynb`) در مسیر زیر آپلود کنید:
    * `course_materials/submissions/week_X/`
3.  یک **Pull Request** به سمت شاخه اصلی بفرستید.

### ۲. داوری آنلاین (مخصوص هفته سوم) 🤖
برای پروژه نهایی (هفته سوم)، علاوه بر آپلود کد در گیت‌هاب، باید فایل پیش‌بینی‌های مدل خود (`submission.csv`) را به ربات تلگرامی زیر ارسال کنید تا **RMSE** دقیق و رتبه شما مشخص شود:
* 🆔 **آیدی ربات:** [@datascienceleaguebot](https://t.me/datascienceleaguebot)

---

## 📚 ساختار فایل‌ها

تمامی محتوای دوره در پوشه **`course_materials`** تجمیع شده است:

* 📂 **`week_1` تا `week_3`**: شامل دو پوشه داخلی:
    * `questions`: صورت سوالات و فایل‌های خام.
    * `solutions`: پاسخنامه‌های تشریحی.
* 📂 **`submissions`**: محل آپلود تمرینات شما (به تفکیک هفته).

---

## 🙏 تشکر و قدردانی (Acknowledgments)

این دوره با تلاش شبانه‌روزی تیم منتورینگ برگزار شد. تشکر ویژه از:
* هادی گلی بیدگلی
* مرضیه معتمدنیا
* پارمیدا هدایتی
* سهیل نوحی

---

**کارگروه کاوش علمی - انجمن هوش مصنوعی دانشگاه خوارزمی**

</div>

---

<details>
<summary><strong>Click here for English Version 🇬🇧</strong></summary>

# 🎓 Data Science League

Welcome to the official repository of the Data Science League.
This repo contains **educational resources** and the **Base Code Pipeline** for the final project.

## 🏗 What is the Base Code?
Located in `src/` and `main.py`, this is a modular template designed to help you write clean, production-ready code instead of messy notebooks.
- **`src/models.py`**: Where you will implement your machine learning models.
- **`main.py`**: The script that runs the entire pipeline.

## 🚀 How to Submit

1.  **GitHub:** Fork the repo and upload your solution to `course_materials/submissions/week_X/`.
2.  **Pull Request:** Send a PR to the main branch.
3.  **Telegram Bot:** For the Week 3 final project, send your `submission.csv` to **[@datascienceleaguebot](https://t.me/datascienceleaguebot)** to get your RMSE score and ranking.

## 🙏 Special Thanks
- Hadi Goli Bidgoli
- Marzieh Motamednia
- Parmida Hedayati
- Soheil Noohi

**Scientific Exploration Working Group - AI Association of Kharazmi University**

</details>
