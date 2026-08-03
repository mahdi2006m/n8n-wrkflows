# **🖼️ AI Image Generator (Flux + Gemini)**

**نحوه کار:**
تلگرام → Gemini (پرامپت‌سازی) → Pollinations.ai (Flux) → ارسال تصویر

---

## **⚙️ پیش‌نیازها**
- **Telegram Bot Token**
- **Google Gemini API Key**

---

## **📥 نصب**
1. فایل JSON را در n8n ایمپورت کنید.
2. **Credentials** را تنظیم کنید:
   - `telegramApi` → توکن ربات تلگرام
   - `googlePalmApi` → API Key Gemini
3. **`chatId`** را در گره **Telegram Response** به آیدی چت خود تغییر دهید.

---

## **🔧 تنظیمات**
| پارامتر | پیش‌فرض | توضیح |
|---------|----------|--------|
| `model` | `flux` | مدل Pollinations.ai |
| `width` | `1080` | عرض تصویر (پیکسل) |
| `height` | `1920` | ارتفاع تصویر (پیکسل) |

---
## **🚀 استفاده**
پیام خود را به ربات تلگرام ارسال کنید.
ورک‌فلو به طور خودکار تصویر را تولید و ارسال می‌کند.
