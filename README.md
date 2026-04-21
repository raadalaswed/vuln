# 🔐 VulnLab — Interactive Web Security Learning Lab

<div align="center">

![VulnLab Banner](https://img.shields.io/badge/VulnLab-Educational%20Security%20Lab-00ff88?style=for-the-badge&logo=shield&logoColor=black)
![OWASP](https://img.shields.io/badge/Based%20on-OWASP%20Top%2010-ff3366?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-00ff88?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-3388ff?style=for-the-badge)

**مختبر ثغرات ويب تفاعلي — تعلّم الاختراق الأخلاقي بيئة آمنة 100%**

[🚀 Live Demo](https://YOUR-USERNAME.github.io/VulnLab) · [📖 Documentation](#labs) · [🛡 Security Note](#-security-disclaimer)

</div>

---

## ⚠️ Security Disclaimer

> **هذا المشروع للأغراض التعليمية حصراً.**  
> جميع المختبرات تعمل بالكامل في المتصفح (client-side) بدون خادم حقيقي.  
> لا تطبّق هذه التقنيات على مواقع أو أنظمة دون إذن صريح من أصحابها.

---

## 🎯 About

VulnLab هو مختبر تفاعلي يتيح للطلاب والمهتمين بالأمن السيبراني تجربة أشهر ثغرات الويب في بيئة معزولة وآمنة. كل مختبر يحتوي على:

- **⚔️ Attack Mode** — جرّب الهجوم بنفسك
- **📖 Explanation** — افهم لماذا ينجح الهجوم
- **🛡️ Fix It** — تعلّم طريقة الحماية الصحيحة

---

## 🔬 Labs

| # | الثغرة | Severity | OWASP | النقاط |
|---|--------|----------|-------|--------|
| 01 | **XSS** — Cross-Site Scripting | 🔴 Critical | A03:2021 | 100 pts |
| 02 | **SQLi** — SQL Injection | 🔴 Critical | A03:2021 | 150 pts |
| 03 | **CSRF** — Cross-Site Request Forgery | 🟠 High | A01:2021 | 120 pts |
| 04 | **IDOR** — Insecure Direct Object Reference | 🟠 High | A01:2021 | 100 pts |
| 05 | **Broken Authentication** | 🟡 Medium | A07:2021 | 80 pts |

**Total: 550 Points**

---

## ✨ Features

- 🎮 **Gamified** — نقاط وتتبع تقدم لكل مختبر
- 💡 **Hint Payloads** — روابط سريعة لتجربة الـ payloads
- 🌑 **Dark Theme** — واجهة احترافية مناسبة للأمن السيبراني  
- 📱 **Responsive** — يعمل على الجوال والحاسوب
- ⚡ **Zero Dependencies** — HTML + CSS + JS خالص، لا يحتاج تثبيت

---

## 🚀 Quick Start

### Option 1: GitHub Pages (مباشرة)
1. Fork المشروع
2. اذهب لـ Settings → Pages → Source: `main branch`
3. الموقع سيكون متاحاً على: `https://YOUR-USERNAME.github.io/VulnLab`

### Option 2: Local
```bash
git clone https://github.com/YOUR-USERNAME/VulnLab.git
cd VulnLab
# افتح index.html في المتصفح مباشرة
open index.html
```

---

## 🛠️ Tech Stack

```
Frontend:  HTML5, CSS3 (Custom Properties), Vanilla JavaScript
Fonts:     JetBrains Mono, Syne (Google Fonts)
Security:  All sandboxed client-side — no real backend
```

---

## 📚 What You'll Learn

### 1. XSS (Cross-Site Scripting)
- كيف يتم حقن JavaScript عبر مدخلات غير مُعقَّمة
- الفرق بين Stored, Reflected, DOM-based XSS
- الحماية: `textContent` بدل `innerHTML`, CSP Headers

### 2. SQL Injection
- كيف تُكسر استعلامات SQL بـ payloads خبيثة
- Bypass المصادقة واستخراج البيانات
- الحماية: Prepared Statements, ORMs

### 3. CSRF
- كيف تُنفَّذ إجراءات دون علم المستخدم
- استغلال الكوكيز التلقائية
- الحماية: CSRF Tokens, SameSite Cookies

### 4. IDOR
- الوصول لبيانات مستخدمين بتغيير الـ ID
- لماذا Authorization ≠ Authentication
- الحماية: Server-side ownership checks

### 5. Broken Authentication
- هجمات Brute Force على بيانات اعتماد ضعيفة
- الإحصائيات الحقيقية عن كلمات المرور
- الحماية: Rate Limiting, Bcrypt, MFA

---

## 🗂️ Project Structure

```
VulnLab/
├── index.html          # كل شيء في ملف واحد (no build needed)
├── README.md           # هذا الملف
└── assets/             # (اختياري) screenshots
    └── screenshot.png
```

---

## 🔮 Roadmap

- [ ] Lab 06: File Upload Vulnerabilities
- [ ] Lab 07: XXE Injection
- [ ] Lab 08: Server-Side Template Injection (SSTI)
- [ ] Leaderboard & User Accounts
- [ ] Arabic / English Toggle

---

## 👤 Author

**[اسمك]**  
Cybersecurity Engineering Student — Year 3  
📧 your@email.com  
🔗 [LinkedIn](https://linkedin.com) · [GitHub](https://github.com/YOUR-USERNAME)

---

## 📄 License

MIT License — استخدم وعدّل بحرية مع ذكر المصدر.

---

<div align="center">
Made with 🔐 for the cybersecurity community
</div>
