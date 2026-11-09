طريقة الحصول على ملف APK (بدون تنزيل أي برنامج):
1) اعمل حساب مجاني على github.com ثم New repository (اسمه أي حاجة، Private كويس).
2) اضغط "uploading an existing file" وفك الضغط عن الملف ثم اسحب كل محتويات المجلد DebtApp
   (لازم يظهر معاها فولدر .github) وافتح Commit changes.
   لو الفولدر المخفي .github مظهرش، اعمل ملف جديد بالاسم .github/workflows/build.yml وانسخ محتواه.
3) افتح تبويب Actions - هتلاقي Build APK شغال لوحده (لو مش شغال: Run workflow).
4) بعد ما يخلص (حوالي 3-5 دقايق) افتحه ونزل DebtApp-apk من تحت (Artifacts)، فك الضغط، ثم ثبّت app-debug.apk.
   لازم تسمح بالتثبيت من مصادر غير معروفة.

البديل: افتح المجلد في Android Studio ثم Build > Build APK(s).
