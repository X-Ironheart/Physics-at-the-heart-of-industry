<div align="center">

<img src="favicon.ico.jpg" alt="Physics at the Heart of Industry" width="90" style="border-radius:16px"/>

# ⚡ الفيزياء في قلب الصناعة
### Physics at the Heart of Industry

**منصة تفاعلية لتطبيقات التماثل الأسطواني وقانون جاوس في الهندسة الصناعية**

*An Interactive Platform for Cylindrical Symmetry & Gauss's Law in Industrial Engineering*

---

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-GitHub_Pages-14b8a6?style=for-the-badge&logoColor=white)](https://x-ironheart.github.io/Physics-at-the-heart-of-industry/)
[![Language](https://img.shields.io/badge/Language-Arabic_RTL-f59e0b?style=for-the-badge)](https://x-ironheart.github.io/Physics-at-the-heart-of-industry/)
[![Tech](https://img.shields.io/badge/Tech-HTML_·_Tailwind_·_Chart.js-0d9488?style=for-the-badge)](https://x-ironheart.github.io/Physics-at-the-heart-of-industry/)
[![AI](https://img.shields.io/badge/AI-OpenRouter_LLM-6366f1?style=for-the-badge)](https://openrouter.ai/)
[![Made By](https://img.shields.io/badge/Made_By-م%2Fمحمد_طاهر_(E.E.T)-134e4a?style=for-the-badge)](https://github.com/X-Ironheart)

</div>

---

## 📋 جدول المحتويات | Table of Contents

| # | القسم | Section |
|---|-------|---------|
| 1 | [نظرة عامة](#-نظرة-عامة--overview) | Overview |
| 2 | [المميزات](#-المميزات--features) | Features |
| 3 | [التطبيقات الثلاثة](#-التطبيقات-الثلاثة--three-applications) | Three Applications |
| 4 | [التقنيات المستخدمة](#-التقنيات-المستخدمة--tech-stack) | Tech Stack |
| 5 | [هيكل المشروع](#-هيكل-المشروع--project-structure) | Project Structure |
| 6 | [الأوراق البحثية](#-الأوراق-البحثية--research-papers) | Research Papers |
| 7 | [المساعد الذكي](#-المساعد-الهندسي-الذكي--ai-assistant) | AI Assistant |
| 8 | [التشغيل المحلي](#-التشغيل-المحلي--local-setup) | Local Setup |
| 9 | [الفريق](#-الفريق--team) | Team |

---

## 🌟 نظرة عامة | Overview

> *"تكتسب النظريات الفيزيائية قيمتها الحقيقية عندما تتجاوز حيز المعادلات المجردة لتصبح حلولاً ملموسة."*

**الفيزياء في قلب الصناعة** هي منصة تعليمية تفاعلية متكاملة تُجسّد التطبيقات الهندسية المتقدمة لقانون جاوس والتماثل الأسطواني. تدمج المنصة النظرية الفيزيائية مع المحاكاة البصرية التفاعلية والذكاء الاصطناعي في واجهة واحدة عربية بالكامل.

**Physics at the Heart of Industry** is a comprehensive interactive educational platform that bridges abstract physics with real-world industrial engineering. It combines rigorous mathematical theory, real-time visual simulators, and an AI-powered assistant — all within a fully Arabic RTL interface.

### 🎯 الهدف الأكاديمي | Academic Goal

إثبات أن **قانون جاوس + التماثل الأسطواني** ليسا مجرد نظريات أكاديمية، بل هما القلب النابض لأنظمة صناعية حقيقية تعمل الآن في المصانع والمستشفيات ومحطات الطاقة حول العالم.

---

## ✨ المميزات | Features

### 🖥️ واجهة المستخدم | UI/UX
- 🌙 **تصميم داكن احترافي** — Dark theme مع لوحة ألوان Teal / Amber / Slate
- 📱 **متجاوب بالكامل** — Mobile-first responsive design مع `clamp()` و CSS Grid
- 🌐 **عربي RTL كامل** — Arabic right-to-left with Cairo font family
- ✨ **Glassmorphism** — بطاقات شفافة مع `backdrop-filter: blur`
- 🎞️ **Micro-animations** — Cubic-bezier spring transitions على جميع العناصر

### 🔬 المحتوى التفاعلي | Interactive Content
- 📊 **3 محاكيات هندسية** — Live simulation لكل تطبيق صناعي
- 🎚️ **تحكم ديناميكي** — Sliders تُحدّث المعادلات والرسوم البيانية في الوقت الفعلي
- 🧮 **MathJax** — عرض معادلات LaTeX بدقة أكاديمية
- 📈 **Chart.js** — رسوم بيانية تفاعلية متحركة

### 🤖 الذكاء الاصطناعي | AI Integration
- 💬 **مساعد هندسي ذكي** — مدعوم بـ OpenRouter LLM
- ⚡ **توليد دراسات حالة** — بنقرة واحدة لكل قسم
- 📝 **Markdown rendering** — عبر Marked.js

### 📥 تحميل الأوراق البحثية | Research Downloads
- 🇸🇦 تحميل البحث باللغة العربية (DOCX)
- 🇬🇧 تحميل البحث باللغة الإنجليزية (DOCX)
- 📊 تحميل العرض التقديمي (PPTX)

---

## 🏭 التطبيقات الثلاثة | Three Applications

### 1️⃣ المستشعرات السعوية لقياس مستوى السوائل
**Capacitive Level Sensors**

```
المبدأ الفيزيائي: C = (2πε₀kL) / ln(b/a)
```

- **الإشكالية:** قياس مستوى الوقود في البيئات البتروكيماوية الخطرة دون تلامس
- **الحل:** مكثف أسطواني يستغل تغير الثابت العازل `k` مع ارتفاع السائل
- **المحاكي:** تحكم تفاعلي في مستوى الخزان → قراءة السعة بـ pF → إشارة PLC بـ mA
- **التطبيق الصناعي:** أنظمة SCADA في مصافي النفط والمصانع الدوائية

---

### 2️⃣ المرسبات الكهروستاتيكية (ESP)
**Electrostatic Precipitators**

```
المبدأ الفيزيائي: E = λ / (2πε₀r)
```

- **الإشكالية:** إزالة جسيمات PM2.5 السامة من عوادم المصانع دون إعاقة تدفق الهواء
- **الحل:** مجال كهربائي بـ `1/r` يتجاوز حد الانهيار الكهربائي للهواء → Corona Discharge
- **المحاكي:** جهد سلك التفريغ (10-80 kV) → منحنى E(r) → حالة Corona
- **التطبيق الصناعي:** محطات توليد الطاقة، مصانع الأسمنت

---

### 3️⃣ درع فاراداي والكابلات المحورية
**Faraday Shield & Coaxial Cables**

```
المبدأ الفيزيائي: E_inside = E_ext + E_induced = 0
```

- **الإشكالية:** التداخل الكهرومغناطيسي (EMI) من المحركات الضخمة يشوّه إشارات البيانات
- **الحل:** شبكة معدنية مضفرة تُولّد مجالاً داخلياً يُلغي المجال الخارجي تماماً
- **المحاكي:** Oscilloscope يُظهر الإشارة قبل وبعد تفعيل درع فاراداي
- **التطبيق الصناعي:** كابلات الإيثرنت الصناعية، غرف MRI الطبية

---

## 🛠️ التقنيات المستخدمة | Tech Stack

| التقنية | الاستخدام | الإصدار |
|---------|-----------|---------|
| **HTML5** | هيكل الصفحة الدلالي | — |
| **Tailwind CSS** | نظام التصميم والـ Utility Classes | CDN Latest |
| **Chart.js** | الرسوم البيانية التفاعلية | CDN Latest |
| **MathJax 3** | عرض معادلات LaTeX | v3.x |
| **Marked.js** | تحويل Markdown في مخرجات AI | Latest |
| **Cairo Font** | الخط العربي الاحترافي | Google Fonts |
| **OpenRouter API** | نموذج الذكاء الاصطناعي | LLM Backend |
| **GitHub Pages** | الاستضافة والنشر | — |

### 🏗️ Architecture Decisions

```
No Build Tools Required — Zero Config
├── Single HTML file (index.html)
├── CDN-based dependencies (no npm/node)
├── Vanilla CSS with clamp() for fluid typography
├── Modular JavaScript (tab system + chart instances + AI)
└── RTL-first layout system
```

---

## 📁 هيكل المشروع | Project Structure

```
Physics-at-the-heart-of-industry/
│
├── 📄 index.html                          # الملف الرئيسي الوحيد للتطبيق
│                                          # Main application file (HTML + CSS + JS)
│
├── 📝 التدفق الذكي ... (AR).docx          # الورقة البحثية بالعربية
│                                          # Arabic Research Paper
│
├── 📝 Physical Analysis ... (EN).docx     # الورقة البحثية بالإنجليزية
│                                          # English Research Paper
│
├── 📊 Physics Analysis ... .pptx          # العرض التقديمي
│                                          # PowerPoint Presentation
│
├── 🖼️ favicon.ico.jpg                     # أيقونة الموقع | Site favicon
│
└── 📋 README.md                           # توثيق المشروع | Project documentation
```

---

## 📚 الأوراق البحثية | Research Papers

يمكن تحميل الأوراق البحثية مباشرةً من زر **📥 تحميل الأوراق البحثية** في أعلى الموقع.

*All research papers are downloadable directly from the **📥 Download Research Papers** button in the site header.*

| الورقة | اللغة | الحجم |
|--------|-------|-------|
| التدفق الذكي: تسخير قانون جاوس في أنظمة الاستشعار والتحكم | 🇸🇦 العربية | ~3.1 MB |
| Physical Analysis of Cylindrical Gaussian Surfaces and Their Industrial Applications | 🇬🇧 English | ~3.0 MB |
| Physics Analysis of Cylindrical Gaussian Surfaces (Presentation) | 📊 PPTX | ~3.1 MB |

### ملخص الأبحاث | Research Abstract

> تتناول هذه الأوراق البحثية التحليل الرياضي المتعمق للأسطح الغاوسية الأسطوانية وتطبيقاتها الصناعية في ثلاثة مجالات رئيسية: **المستشعرات السعوية**، **المرسبات الكهروستاتيكية**، و**دروع فاراداي** — مع دراسات حالة حقيقية وحسابات مفصّلة.

---

## 🤖 المساعد الهندسي الذكي | AI Assistant

المنصة مدمجة مع نموذج لغوي متقدم عبر **OpenRouter API** يعمل كمساعد هندسي متخصص:

```
المهمة: تبسيط مفاهيم الكهرباء والتماثل الأسطواني
اللغة: العربية بالكامل
القدرات:
  ✅ شرح المعادلات الفيزيائية
  ✅ توليد دراسات حالة صناعية
  ✅ تقييم التأثير البيئي والاقتصادي
  ✅ الإجابة عن الأسئلة الهندسية المخصصة
```

**طريقة التفعيل:**
- زر ✨ العائم في أسفل يمين الشاشة
- أزرار **"توليد دراسة حالة ذكية"** داخل كل قسم

---

## 🚀 التشغيل المحلي | Local Setup

لا يحتاج المشروع لأي إعداد! فقط:

```bash
# 1. استنسخ المستودع
git clone https://github.com/X-Ironheart/Physics-at-the-heart-of-industry.git

# 2. افتح الملف مباشرة في المتصفح
# Open index.html directly in any modern browser
```

أو قم بفتح `index.html` مباشرة بالنقر المزدوج عليه. ✅

> **💡 ملاحظة:** لاستخدام المساعد الذكي، يلزم اتصال بالإنترنت للوصول إلى OpenRouter API.

### المتطلبات | Requirements
```
✅ أي متصفح حديث (Chrome / Firefox / Edge / Safari)
✅ اتصال إنترنت (للـ CDN libraries والـ AI)
❌ لا يلزم Node.js
❌ لا يلزم npm / build tools
❌ لا يلزم server
```

---

## 📱 التوافق | Browser Support

| المتصفح | الدعم |
|---------|-------|
| Chrome 90+ | ✅ كامل |
| Firefox 88+ | ✅ كامل |
| Edge 90+ | ✅ كامل |
| Safari 14+ | ✅ كامل |
| Mobile (iOS/Android) | ✅ متجاوب بالكامل |

---

## 👨‍💻 الفريق | Team

<div align="center">

**صُنع بكل حب بواسطة**

### م/ محمد طاهر
**فريق هندسة الكهرباء والإلكترونيات (E.E.T)**

[![GitHub](https://img.shields.io/badge/GitHub-X--Ironheart-181717?style=for-the-badge&logo=github)](https://github.com/X-Ironheart)

⚡ *"من المعادلات المجردة إلى الواقع الملموس"*

</div>

---

## 📄 الترخيص | License

هذا المشروع محمي بحقوق الملكية الفكرية. جميع الأوراق البحثية والمحتوى التعليمي من إعداد الفريق.

*This project and all research papers are intellectual property of the development team (E.E.T).*

---

<div align="center">

**⭐ إذا أعجبك المشروع، لا تنسَ إعطاءه نجمة على GitHub!**

*If you found this project helpful, please give it a ⭐ on GitHub!*

---

`الفيزياء في قلب الصناعة` · `Physics at the Heart of Industry` · `E.E.T Team` · `2025`

</div>
