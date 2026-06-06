# تسعيرة - تطبيق Flutter
## Frontend Mobile Application

### نظرة عامة
تطبيق Flutter للهاتف الذكي - منصة ذكية لمقارنة الأسعار والعروض

### البنية الأساسية
```
tasaeera-flutter/
├── lib/
│   ├── config/
│   │   ├── theme/
│   │   │   ├── app_colors.dart
│   │   │   ├── app_theme.dart
│   │   │   └── app_typography.dart
│   │   ├── constants/
│   │   └── routes/
│   ├── data/
│   │   ├── models/
│   │   ├── repositories/
│   │   └── services/
│   ├── presentation/
│   │   ├── pages/
│   │   ├── widgets/
│   │   └── providers/
│   └── utils/
├── assets/
├── pubspec.yaml
└── test/
```

### المزايا الرئيسية
✅ تصميم احترافي متوافق مع الصور المرفقة
✅ ألوان أخضر + أزرق + تيل
✅ دعم العربية والإنجليزية
✅ مصادقة آمنة بـ JWT
✅ واجهة مستخدم سلسة
✅ إشعارات فورية
✅ تخزين محلي للبيانات
✅ أداء عالي

### الشاشات الرئيسية
1. **Splash Screen** - شاشة البداية
2. **Welcome Screen** - شاشة الترحيب
3. **Auth Screens** - تسجيل الدخول والتسجيل
4. **Home Screen** - الصفحة الرئيسية
5. **Product Details** - تفاصيل المنتج والأسعار
6. **Store Details** - معلومات المتجر
7. **Merchant Dashboard** - لوحة تحكم التاجر
8. **User Profile** - الملف الشخصي
9. **Shopping Lists** - قوائم التسوق
10. **Notifications** - الإشعارات

### التقنيات
- **Framework**: Flutter 3.x
- **State Management**: Riverpod / Provider
- **HTTP Client**: Dio
- **Storage**: Hive
- **Navigation**: GoRouter
- **Localization**: Easy Localization
- **Firebase**: Firebase Messaging

### البدء السريع

```bash
# تثبيت الحزم
flutter pub get

# تشغيل على Android
flutter run -d android

# تشغيل على iOS
flutter run -d ios

# بناء APK
flutter build apk --release

# بناء App Bundle
flutter build appbundle --release
```

### الألوان الأساسية
- 🟢 أخضر: #00A651
- 🔵 أزرق: #093C5D
- 🔷 تيل: #5FD8D8
- 💚 أخضر فاتح: #5DF8D8

---

**آخر تحديث**: يونيو 2026