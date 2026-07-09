# Easy Starter PRD

[![English README](https://img.shields.io/badge/README-English-blue?style=for-the-badge)](./README.md)
![قالب PRD](https://img.shields.io/badge/PRD-Template-2ea44f?style=for-the-badge)
![Design Brief](https://img.shields.io/badge/Design-Brief-7c3aed?style=for-the-badge)
![Spec Driven](https://img.shields.io/badge/Spec--Driven-Development-f97316?style=for-the-badge)
![AI Agent Ready](https://img.shields.io/badge/AI%20Agent-Ready-0ea5e9?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Docs-Markdown-111827?style=for-the-badge&logo=markdown)
![License MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

یک ریپوزیتوری قالب دو‌زبانه برای نوشتن PRD، Design Brief و مستندات Spec-Driven Development قبل از شروع پیاده‌سازی.

## هدف

مستندات باید منبع حقیقت تیم باشند؛ نه فقط کد پروژه. این قالب کمک می‌کند محصول از نظر کاربر، نیازمندی، طراحی، معماری، تست، لانچ و یادگیری شفاف شود.

## جریان کاری

ایده → خلاصه یک‌صفحه‌ای → تحقیق → PRD → دیزاین بریف → مشخصات UX/UI → بریف فنی → Feature Spec → Plan → تسک‌های تست‌محور → پیاده‌سازی → ریلیز → یادگیری بعد از لانچ

## ساختار

```text
templates/en/                 قالب‌های انگلیسی
templates/fa/                 قالب‌های فارسی
specs/_feature-template/       قالب فیچر برای توسعه spec-driven
specs/features/                spec فیچرهای واقعی
prompts/en/                    پرامپت‌های انگلیسی
prompts/fa/                    پرامپت‌های فارسی
checklists/                   گیت‌های بازبینی
examples/                     نمونه‌های تکمیل‌شده
.github/                      قالب Issue و Pull Request
```

## شناسه‌گذاری

- `GOAL-001` اهداف محصول/بیزینس
- `USER-001` کاربران/پرسوناها
- `REQ-001` نیازمندی فانکشنال
- `NFR-001` نیازمندی غیرفانکشنال
- `AC-001` معیار پذیرش
- `EVT-001` ایونت آنالیتیکس
- `RISK-001` ریسک
- `DEC-001` تصمیم
