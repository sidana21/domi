# الوصول للوحة الإدارة

## 🔐 كيفية الوصول:

1. **الرابط:** `موقعك.com/admin/login`
2. **البيانات الافتراضية:**
   - البريد الإلكتروني: `admin@bizchat.com`
   - كلمة المرور: `admin123456`

## 📋 الصفحات المتوفرة:

- **لوحة التحكم الرئيسية** - `/admin`
- **إدارة المستخدمين** - `/admin/users`
- **إدارة المتاجر** - `/admin/stores` 
- **إدارة الطلبات** - `/admin/orders`
- **طلبات التوثيق** - `/admin/verification-requests`
- **إدارة الميزات** - `/admin/features`
- **الإعدادات** - `/admin/settings`

## ⚠️ مهم:

لتغيير بيانات المدير، استخدم متغيرات البيئة:
```
ADMIN_EMAIL=your_admin@email.com
ADMIN_PASSWORD=your_secure_password
```

أو استخدم صفحة الإعدادات داخل لوحة الإدارة.