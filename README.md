# speed-test (GitHub Pages)

مستودع بسيط لاستضافة ملف ثابت بحجم 5MB عبر GitHub Pages لاستخدامه في قياس سرعة التحميل.

## المحتويات
- `5mb.bin` — ملف حجمه ~5 ميجابايت
- `index.html` — صفحة بسيطة ورابط مباشر للملف
- `.nojekyll` — لضمان عدم تدخل Jekyll في الملفات الثنائية

## تفعيل GitHub Pages
1. أنشئ مستودع جديد على GitHub (مثال: `speed-test`).
2. ارفع هذه الملفات إلى الفرع `main` في الجذر.
3. من Settings → Pages:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
4. بعد دقيقة تقريبًا سيصبح موقعك متاحًا على:
   `https://<USERNAME>.github.io/speed-test/`
5. رابط الملف المباشر:
   `https://<USERNAME>.github.io/speed-test/5mb.bin`

> استبدل `<USERNAME>` باسم مستخدم GitHub الخاص بك.
