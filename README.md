Crazy Balls Advanced - تسجيل متقدم + اقتراح
============================================

هاد المشروع نسخة متقدمة من المسجّل: يحتوي Foreground Service، MediaProjection + MediaRecorder، إشعار مستمر أثناء التسجيل.
يحتوي أيضاً زر اقتراح بسيط (موديل تجريبي).

خطوات سريعة لتشغيل:
1. نزّل هاد ZIP وفكّو على التليفون أو الكمبيوتر.
2. رفع الملفات (مجلد app و settings.gradle و build.gradle) على GitHub في مستودع جديد.
3. ربط المستودع بـ Codemagic أو استخدم Android Studio لبناء المشروع (assembleDebug).
4. ثبّت الـ APK على هاتفك، شغّل التطبيق واضغط "حضّر إذن الشاشة" ثم "بدا التسجيل".
5. لإيقاف التسجيل اضغط "وقف التسجيل"، الفيديو يتخزن فـ: Android/data/<package>/files/crazy_records/

ملاحظات تقنية:
- بعض أجهزة Android لديها سياسات صوت/سجلات خاصة: التسجيل الداخلي للصوت قد لا يعمل في كل الأجهزة.
- لتحسين الجودة أو تقليل الحجم، عدل bitRate وframeRate وvideoSize فـ RecorderForegroundService.setupMediaRecorder().
