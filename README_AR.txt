نسخة الموبايل PWA بدون Netlify
=================================

هذه النسخة جاهزة للرفع على GitHub Pages أو أي استضافة HTTPS.

الطريقة الأسهل باستخدام GitHub Pages:
1) افتح github.com وسجل الدخول.
2) اضغط New repository.
3) اكتب اسم مثل: irrigation-water-footprint-app
4) اختار Public.
5) اضغط Create repository.
6) ارفع كل الملفات الموجودة داخل هذا الفولدر، وليس الفولدر نفسه:
   - index.html
   - manifest.webmanifest
   - sw.js
   - icons
7) بعد الرفع، افتح Settings من صفحة الريبو.
8) ادخل Pages.
9) Source: اختار Deploy from a branch.
10) Branch: اختار main ثم /root ثم Save.
11) انتظر دقيقة تقريبًا ثم افتح رابط GitHub Pages الذي سيظهر.

التثبيت على الموبايل:
- افتح الرابط من Chrome على Android.
- اضغط القائمة ⋮ ثم Install app أو Add to Home screen.
- لو ظهر زر التثبيت داخل البرنامج اضغط عليه.

ملاحظات مهمة:
- لا تفتح index.html مباشرة من ملفات الموبايل لأن التثبيت يحتاج HTTPS.
- GitHub Pages يوفر HTTPS مجانًا.
- لو لم يظهر خيار التثبيت فورًا، افتح الموقع مرتين أو انتظر قليلًا حتى يتفعل Service Worker.
