<div align="center">

# 🤖 BOT-CORE | Manga Management & Downloader Platform

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100%2B-009688?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Discord.py](https://img.shields.io/badge/Discord.py-v2.3%2B-5865F2?style=for-the-badge&logo=discord)](https://github.com/Rapptz/discord.py)

**مركز الإدارة، البوت، لوحة الويب، ومحركات تنزيل المانجا والمستندات**

---

</div>

## 📂 هيكل المكونات التفصيلي

| الملف / المجلد | الوظيفة التقنية |
| :--- | :--- |
| **`main.py`** | النقطة الرئيسية لتشغيل بوت الديسكورد وربط الأوامر والـ Cogs. |
| **`web_panel.py`** | خادم لوحة تحكم الويب الإدارية المبنية بـ FastAPI + HTML5 UI. |
| **`manga_downloader.py`** | المحرك التنزيل الرئيسي والتنسيق مع السكيربرز. |
| **`smart_stitch.py`** | الخوارزمية الذكية لقص وتجميع صور صفحات المانهوا المترابطة. |
| **`drive_stitch.py`** | محرك الرفع والتزامن التلقائي مع حسابات ومجلدات Google Drive. |
| **`cogs/`** | وحدات أوامر البوت (التحميل، الإدارة، تبييض المانجا، رادار التتبع التلقائي). |
| **`providers/`** | محركات جلب واستخراج الفصول لأكثر من 30+ موقع مانجا عربي وعالمي. |
| **`services/`** | خدمات التتبع الدوري والأعمال السحابية الخلفية. |
| **`hf_worker/`** | خادم العامل البعيد المدمج للنشر المباشر على HuggingFace Spaces. |

---

## ⚡ التشغيل السريع

```bash
# 1. تثبيت المكتبات المطلوبة
pip install -r requirements.txt

# 2. ضبط المتغيرات البيئية
cp .env.example .env

# 3. تشغيل الخادم والبوت
python main.py
```

للمزيد من الشرح حول النشر والهندسة البرمجية:
- 📖 **[ARCHITECTURE.md](../ARCHITECTURE.md)**
- 🚀 **[DEPLOYMENT.md](../DEPLOYMENT.md)**
- 🌐 **[PROVIDERS.md](../PROVIDERS.md)**
