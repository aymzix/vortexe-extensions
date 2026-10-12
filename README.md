# VORTEXE Extensions

مستودع إضافات مستقل متوافق مع Mihon، يوزع ملفات APK الأصلية بتوقيعاتها كما استُلِمت، مع بيانات فهرس خاصة بـ VORTEXE. لا يعتمد استضافة الملفات على مستودع إضافات طرف ثالث.

## إضافة المستودع إلى Mihon/VORTEXE

أضف عنوان manifest التالي من إعدادات مستودعات الإضافات:

`https://raw.githubusercontent.com/aymzix/vortexe-extensions/main/repo.json`

يوجه `repo.json` التطبيق إلى فهرس Mihon الحديث `index-v2.json`. ويمكن تسجيل عنوان الفهرس الحديث مباشرةً في التطبيقات التي تدعمه.

## الإضافات العربية

الإصدارات المدرجة هنا هي بيانات APK التي فُحصت؛ كل الحزم أدناه تعلن مكتبة الإضافة `1.6` واللغة العربية.

| الإضافة | اسم الحزمة | الإصدار |
|---|---|---:|
| AriaToon | `eu.kanade.tachiyomi.extension.ar.ariatoon` | 1.6.1 |
| Azora | `eu.kanade.tachiyomi.extension.ar.azora` | 1.6.73 |
| Despair Manga | `eu.kanade.tachiyomi.extension.ar.despairmanga` | 1.6.1 |
| Dilar | `eu.kanade.tachiyomi.extension.ar.dilar` | 1.6.18 |
| EShadow | `eu.kanade.tachiyomi.extension.ar.eshadow` | 1.6.1 |
| Hijala | `eu.kanade.tachiyomi.extension.ar.hijala` | 1.6.3 |
| HizoManga | `eu.kanade.tachiyomi.extension.ar.hizomanga` | 1.6.55 |
| Kawii Manga | `eu.kanade.tachiyomi.extension.ar.kawiimanga` | 1.6.2 |
| Lava Scans | `eu.kanade.tachiyomi.extension.ar.lavascans` | 1.6.1 |
| Mangalek | `eu.kanade.tachiyomi.extension.ar.mangalek` | 1.6.68 |
| MangaSwat | `eu.kanade.tachiyomi.extension.ar.mangaswat` | 1.6.61 |
| MangaTek | `eu.kanade.tachiyomi.extension.ar.mangatek` | 1.6.7 |
| Onma | `eu.kanade.tachiyomi.extension.ar.onma` | 1.6.0 |
| Team X | `eu.kanade.tachiyomi.extension.ar.teamx` | 1.6.33 |

تحققت أداة Android من التوقيع لكل APK؛ جميع الشهادات تطابق مفتاح التوقيع المسجل في الفهرس. وتعلن الملفات `minSdkVersion = 26` و`targetSdkVersion = 37` و`extensionLib = 1.6`، وهي متوافقة من ناحية بيانات الحزمة مع VORTEXE المبني على Mihon 0.21.0 (API 26 على الأقل، ومكتبة الإضافة 1.6). نُقلت ملفات APK كما هي، دون إعادة توقيع أو تعديل، وتطابقت أسماء الحزم والإصدارات مع الملفات.

تحذير المحتوى `SAFE` هو تصنيف البيانات الوصفية المعلنة، وليس تدقيقًا مستقلًا لمحتوى المواقع أو إثباتًا بأن كل صفحة أو رابط آمن أو متاح. يزور التطبيق مواقع المصادر المذكورة في الفهرس عند استخدام الإضافة.

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

## التحديثات

عند توفر APK جديد، انشره في GitHub Release جديد باسم إصدار جديد، ثم حدّث `versionName` و`versionCode` و`apkUrl` في `index-v2.json` مع إبقاء بصمة المفتاح مطابقة للشهادة. يقرأ Mihon/VORTEXE النسخة الجديدة عند تحديث الفهرس؛ لا يلزم إعادة بناء التطبيق الأساسي. هذه خطوة نشر للمستودع مستقلة عن إصدار التطبيق، وليست تنزيلًا تلقائيًا من مصدر خارجي.
