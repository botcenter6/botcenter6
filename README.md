# مركز الروبوتات - BOTCENTER (Flutter Web)

مشروع Flutter Web متعدد الصفحات باللغة العربية (RTL) مع ثيم أزرق/أبيض وخط Cairo.
يشمل الصفحات: الرئيسية، بوت النمر، بوت الذئب، طرق الدفع والتواصل، وتنصيب النظام وتشغيل البوت.

## المتطلبات
- Flutter 3+
- تفعيل الويب: `flutter config --enable-web`

## التشغيل محلياً
```
flutter pub get
flutter run -d chrome
```

## البناء للنشر
```
flutter build web
```
ارفع محتويات `build/web` إلى GitHub Pages أو Netlify أو Vercel.

## تخصيص
- الألوان والخط: `lib/theme.dart`
- النصوص/المحتوى: `lib/pages/*.dart`
- الصور: `assets/images/`
