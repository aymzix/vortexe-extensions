# VORTEXE Extensions

مستودع إضافات مستقل متوافق مع Mihon، يبدأ بإضافة Azora العربية. تنشر بيانات الفهرس وروابط APK تحت حساب VORTEXE، ولا تعتمد على مستودع طرف ثالث لتوزيعها.

## إضافة المستودع إلى Mihon/VORTEXE

أضف عنوان manifest التالي من إعدادات مستودعات الإضافات:

`https://raw.githubusercontent.com/aymzix/vortexe-extensions/main/repo.json`

يوجه `repo.json` التطبيق إلى فهرس Mihon الحديث `index-v2.json`. ويمكن تسجيل عنوان الفهرس الحديث مباشرةً في التطبيقات التي تدعمه.

## الإصدار الأول: Azora

- الاسم: Azora
- اللغة: العربية (`ar`)
- الحزمة: `eu.kanade.tachiyomi.extension.ar.azora`
- الإصدار: `1.6.73`، versionCode `106073`، مكتبة الإضافة `1.6`
- ملف APK: `tachiyomi-ar.azora-v1.6.73.apk` في إصدار GitHub `v1.6.73`
- SHA-256: `e3d7439773f5148cf50ec492a69ab65d7f792177411a22701be0fc3819e1fe31`
- بصمة شهادة التوقيع: `9add655a78e96c4ec7a53ef89dccb557cb5d767489fac5e785d671a5a75d4da2`
- الصفحة الرئيسية للمصدر: <https://azorafly.com>

يُوزّع APK الأصلي بتوقيعه كما استُلم، من دون تعديل أو إعادة توقيع. لا يدّعي VORTEXE تأليف الإضافة؛ راجع ملف `NOTICE` والترخيص المرفق.

## تحديث الإضافة

عند توفر APK جديد، انشره في GitHub Release جديد باسم إصدار جديد، ثم حدّث `versionName` و`versionCode` و`apkUrl` في `index-v2.json` مع إبقاء بصمة المفتاح مطابقة للشهادة. يقرأ Mihon/VORTEXE النسخة الجديدة عند تحديث الفهرس؛ لا يلزم إعادة بناء التطبيق الأساسي. هذه خطوة نشر للمستودع مستقلة عن إصدار التطبيق، وليست تنزيلًا تلقائيًا من مصدر خارجي.
