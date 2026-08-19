# ASAS Site UX v3 - Project Apartment

## 📋 وصف المشروع
موقع عرض المشاريع السكنية مع واجهة مستخدم حديثة وتجربة استخدام متقدمة.

## 🚀 التثبيت والتشغيل المحلي

### المتطلبات
- Node.js 16+ 
- npm أو yarn

### خطوات التثبيت

1. **استخراج ملف المشروع:**
```bash
tar -xzf ASAS-site-UX-v3-project-apartment.tar.gz
cd ASAS-site-UX-v3-project-apartment
```

2. **تثبيت المكتبات:**
```bash
npm install
# أو
yarn install
```

3. **إنشاء ملف المتغيرات:**
```bash
cp .env.example .env.local
```

4. **تشغيل المشروع:**
```bash
npm run dev
# أو
yarn dev
```

المشروع سيكون متاحاً على: `http://localhost:3000`

## 🔧 البناء والنشر

### البناء المحلي:
```bash
npm run build
npm run start
```

### النشر على Vercel:

#### الطريقة 1: عبر واجهة Vercel
1. اذهب إلى [vercel.com](https://vercel.com)
2. سجل دخولك أو أنشئ حساباً
3. انقر على "New Project"
4. اختر هذا المستودع من GitHub
5. اضغط "Deploy"

#### الطريقة 2: عبر Vercel CLI
```bash
npm i -g vercel
vercel
```

## 📦 البنية الأساسية

```
ASAS-site-UX-v3-project-apartment/
├── public/           # الملفات الثابتة
├── src/
│   ├── pages/       # صفحات Next.js
│   ├── components/  # المكونات
│   ├── styles/      # الأنماط
│   └── utils/       # الدوال المساعدة
├── package.json     # المكتبات والسكريبتات
└── vercel.json      # إعدادات النشر
```

## 🌐 متغيرات البيئة (Environment Variables)

أضف المتغيرات التالية في Vercel:

| المتغير | الوصف |
|---------|--------|
| `NODE_ENV` | بيئة التشغيل (production/development) |
| `NEXT_PUBLIC_API_URL` | عنوان API |
| `DATABASE_URL` | رابط قاعدة البيانات |

## 📝 السكريبتات المتاحة

```json
{
  "dev": "تشغيل المشروع في وضع التطوير",
  "build": "بناء المشروع للإنتاج",
  "start": "تشغيل المشروع المبني",
  "lint": "فحص الكود"
}
```

## 🔐 تأمين المشروع

- [ ] أضف `NEXT_PUBLIC_API_URL` إلى Vercel Secrets
- [ ] أضف `DATABASE_URL` إلى Vercel Secrets
- [ ] فعّل "Branch Protection" في GitHub
- [ ] اختبر النشر على فرع `staging` قبل `main`

## 🛠️ استكشاف الأخطاء

### الخطأ: "Module not found"
```bash
rm -rf node_modules package-lock.json
npm install
```

### الخطأ: "Build failed"
تحقق من السجلات في لوحة تحكم Vercel

### الخطأ: "Env variables not found"
تأكد من إضافة جميع المتغيرات في Vercel Project Settings

## 📞 التواصل والدعم

- البريد الإلكتروني: asas.agency.dz@gmail.com
- GitHub: [@asas-erp-saas-1](https://github.com/asas-erp-saas-1)

## 📄 الترخيص

هذا المشروع مرخص تحت MIT License

---

**آخر تحديث:** 19 أغسطس 2026
