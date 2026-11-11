# مصادر المحتوى والحقوق

هذه الصفحة توثق مصادر البيانات المستخدمة في `index.html`. لا يدّعي الموقع ملكية النصوص أو التسجيلات.

## 1. النص القرآني

- الإصدار المستخدم: `quran-uthmani` عبر AlQuran Cloud.
- نقطة البيانات: https://api.alquran.cloud/v1/surah/2/quran-uthmani
- توثيق واجهة AlQuran Cloud: https://legacy.alquran.cloud/api
- شروط AlQuran Cloud: https://alquran.cloud/terms-and-conditions
- المصدر الذي يجب نسبته: مشروع تنزيل (Tanzil)، مع الإشارة كذلك إلى AlQuran Cloud بوصفه مزوّد الواجهة.

تنص شروط AlQuran Cloud على أن نصه العربي يأتي من مصادر منها Tanzil وQuran Academy، وتطلب الحفاظ على الرسم والتشكيل وعدم تغيير النص. وتذكر أن إعادة العرض غير التجارية مسموحة مع مراعاة النسبة. يضع مشروع Tanzil نصه تحت CC BY 3.0، ويشترط النسخ الحرفي دون تغيير، وذكر المصدر والرابط وإبقاء إشعار الحقوق.

**إشعار Tanzil كما في صفحة الترخيص:**

```text
Tanzil Quran Text
Copyright (C) 2007-2021 Tanzil Project
License: Creative Commons Attribution 3.0

This copy of the Quran text is carefully produced, highly
verified and continuously monitored by a group of specialists
in Tanzil Project.

TERMS OF USE:
- Permission is granted to copy and distribute verbatim copies
  of this text, but CHANGING IT IS NOT ALLOWED.
- This Quran text can be used in any website or application,
  provided that its source (Tanzil Project) is clearly indicated,
  and a link is made to tanzil.net to enable users to keep
  track of changes.
- This copyright notice shall be included in all verbatim copies
  of the text, and shall be reproduced appropriately in all files
  derived from or containing substantial portion of this text.

Please check updates at: http://tanzil.net/updates/
```

مراجع الترخيص:
- https://tanzil.net/docs/Text_License
- https://alquran.cloud/terms-and-conditions

## 2. التفسير الميسر

- الإصدار المستخدم: `ar.muyassar` عبر AlQuran Cloud.
- نقطة البيانات: https://api.alquran.cloud/v1/surah/2/ar.muyassar
- النسبة المعروضة: **التفسير الميسر — إعداد نخبة من العلماء، مجمع الملك فهد لطباعة المصحف الشريف**.
- توثيق AlQuran Cloud: https://legacy.alquran.cloud/api
- شروط AlQuran Cloud: https://alquran.cloud/terms-and-conditions

شروط AlQuran Cloud تقول إن الترجمات/التفاسير تأتي من أصحاب الحقوق أو من طبعات متاحة للعموم، وتطلب نسبة صاحب النص عند إعادة نشره. تم وضع نسبة إلى مجمع الملك فهد في واجهة الموقع، لكن لم يتم الحصول على تصريح مستقل مكتوب خاص بهذا الإصدار من الجهة صاحبة الحقوق. قبل أي توزيع مستقل لقاعدة بيانات التفسير أو استخدام تجاري، يجب تأكيد شروط هذا الإصدار تحديداً مع صاحب الحق. لا يجوز اعتبار تطابق عدد الآيات وحده إثباتاً لصحة مضمون كل تفسير.

## 3. التلاوات وملفات MP3

- فهرس القراء: https://www.mp3quran.net/api/v3/reciters?language=ar&sura=2
- فهرس القراءات التي لها توقيتات: https://www.mp3quran.net/api/v3/ayat_timing/reads
- توقيتات سورة البقرة: https://www.mp3quran.net/api/v3/ayat_timing?surah=2&read={read_id}
- وثائق API: https://www.mp3quran.net/ar/api
- وثائق Timing API: https://www.mp3quran.net/ar/timing-api
- صفحة التواصل: https://apiquran.mp3quran.net/ar/contact-us

توثيق MP3Quran يوضح حقول القارئ/المصحف، وخادم الملفات، وقائمة السور، كما يوضح أن توقيت الآية يتضمن `ayah` و`start_time` و`end_time` (بالمللي ثانية في المثال المنشور). لذلك يتحقق الكود من وجود توقيتات الآيات 1–286 قبل السماح بالتشغيل المنفرد.

**تنبيه حقوق:** صفحة التواصل لدى MP3Quran تتضمن عبارة عامة بأن حقوق الموقع متاحة حتى للأغراض التجارية، لكنها لا تعرض في النص المتاح ترخيصاً منفصلاً واضحاً لكل تسجيل ولكل قارئ. حقوق الأداء والتسجيلات قد تبقى لأصحابها. لا يُعاد رفع ملفات الصوت إلى هذا المستودع؛ تُفتح من خادم المصدر. قبل أي استخدام تجاري أو نسخ/إعادة استضافة، اطلب تأكيداً مكتوباً يحدد التسجيلات المقصودة وحق البث والتنزيل وإعادة التوزيع.

## 4. حدود التحقق في هذه المراجعة

في 11 نوفمبر 2026 تعذر من بيئة المراجعة إجراء اتصالات مباشرة بخدمات AlQuran Cloud وMP3Quran أو تشغيل ملفات MP3. الوثائق الرسمية تثبت وجود نقاط API وطريقة استخدامها، لكنها لا تثبت أن كل رابط لقارئ بعينه يعمل الآن أو أن كل تسجيل يملك توقيتات سليمة. كما لم تتم مقارنة نصوص الآيات والتفسير آية بآية مع نسخة مطبوعة مرجعية.
