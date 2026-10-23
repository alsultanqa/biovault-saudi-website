# BioVault Saudi — Current Production Website

**Live public URL:** https://biovault-saudi-cinematic-preview.vercel.app/

**Source of truth:** `site-v14/index.html`, with video assets in `site-v14/assets/`.

**Deployment:** The existing Vercel project `biovault-saudi-cinematic-preview` uses GitHub repository `alsultanqa/biovault-saudi-website`, branch `main`, with Root Directory `site-v14`. Changes to the main branch must be reviewed before publication.

**Status:** Publicly accessible company presentation; not a private concept preview. Illustrative project scenarios remain explicitly labeled synthetic and are not claims of live customer integrations.

**Rights:** © 2026 BioVault Software Solutions. All rights reserved. / © ٢٠٢٦ بيوفولت لحلول البرمجيات. جميع الحقوق محفوظة.

**Domain note:** The Vercel URL above is live. A separately purchased company domain still requires its own DNS/Vercel domain connection; pushing code to GitHub does not connect DNS automatically.

**Release documentation:** [Governance](docs/SITE_GOVERNANCE.md) · [Changelog](docs/CHANGELOG.md) · [Historical audit](docs/V14_AUDIT.json).

The remainder below is an archived V6 development record and is **not** the active deployment instructions.

---


# BioVault Saudi — Cinematic Website V6

**الحالة:** نموذج تصميم وتجربة تفاعلية خاص للمراجعة — ليس موقعًا منشورًا ولا نسخة إنتاجية.

## كيف تشغّل المعاينة؟

1. نزّل `preview/BioVault_Cinematic_V6_Offline.html` وافتحه في Chrome أو Edge مباشرة. لا تحتاج إلى استضافة أو خادم أو اتصال إنترنت.
2. اضغط «ادخل التجربة / Enter the experience» ثم اختر أحد الحلول الأربعة.
3. في BalanceChain، انقر «Simulate transfer»، ثم جرّب وضع «Bank only» و«Bank + BalanceChain» ومراحل العرض الأربع.
4. في Venture Sentinel وEndlessJob وCustom Software، استخدم أسهم الفصل التالي/السابق أو مؤشرات الفصول الأربعة.
5. غيّر اللغة من زر أعلى الصفحة. التصميم يدعم العربية والإنجليزية واتجاهي الكتابة.

## ما الذي بُني في V6؟

- واجهة رئيسية مستوحاة من بروفايل BioVault V18 (الزمردي/الفضي/الكحلي ورؤية الرياض والعبارة المعتمدة).
- **BalanceChain:** إدراج وتكييف تجربة V5 البنكية: هاتفان وأرصدة افتراضية، حركة تحويل، معلومات مصدر القيمة، التمثيل بجوار البنك وحدود الرؤية.
- **Venture Sentinel:** شاشة عرض لشركة خيالية + نافذة فحص وثائق وادعاءات، مع أربع مراحل وحالات أدلة.
- **EndlessJob:** هاتف ملف مهارات حواري + بطاقة مهمة افتراضية وسجل مساهمة مصور في أربع مراحل. المشروع مكتمل بحسب إفادة صاحبه؛ العرض ليس إثباتًا مستقلاً لميزات أو أداء المنتج.
- **Custom Software:** مراسلات وجداول ومحادثات متفرقة تتحول إلى تصور لسير عمل موحد ومعايير قبول.
- ملف HTML واحد مستقل يتضمن CSS وJS والصور المستخدمة والسيناريو البنكي المضمن.

## الحدود والصدق التجاري

- كل العملاء والمبالغ والبيانات والأجهزة وسيناريوهات الاستثمار ومهام EndlessJob افتراضية بالكامل.
- لا توجد روابط بنكية حية أو بيانات شخصية لعميل أو تكامل فعلي مع خدمات خارجية.
- مثال نسب التمويل في BalanceChain يستخدم قاعدة تخصيص موضحة ضمن السيناريو، ولا يعني اكتشافًا آليًا لتاريخ أموال غير مرصودة. البنك يحتفظ بدفتر الحسابات المعتمد، وتتوقف الرؤية عند حدود الأنظمة المشاركة.
- Venture Sentinel يصور فحصًا منهجيًا؛ لا ينفذ قرار استثمار مستقلًا، ولا تُستخدم نتيجة العرض كضمان عائد.
- تصميم Custom Software هو مسار عمل مقترح، لا شهادة بأن تنفيذًا معينًا قد حدث عند عميل.
- الهوية المستخدمة مستخرجة من الملف المعتمد، وليست إعادة تصميم للشعار؛ يوصى باستبدال الصورة المستخرجة بالملف الأصلي عالي الجودة قبل نشر موقع رسمي.
- البريد الظاهر وارد في بروفايل الشركة V18. المراسلة تفتح عميل البريد عند الزائر، ولا توجد آلية حجز اجتماعات أو CRM متصلة.

## الاختبارات المنفذة

اختُبر ملف HTML المستقل في Chromium على 1440×900 و390×844. جُرّبت علامات تبويب الحلول والفصول الأربعة وزر إعادة المشهد، وتبديل العربية/الإنجليزية، وتحويل BalanceChain وتغير رصيدي الهاتفين. لم تظهر أخطاء JavaScript في الاختبارات، ولم يزد عرض الصفحة عن عرض الشاشة. هذه اختبارات أولية محدودة وليست تغطية ضمان جودة كاملة.

## قبل الموقع الإنتاجي

- اعتماد النصوص والبنية التجارية ونطاق كل منتج.
- استلام الشعار الأصلي الدقيق والتراخيص/حقوق جميع العناصر المرئية؛ الصور الحالية مستخرجة من مواد الشركة المقدمة.
- مراجعة الصيغ القانونية وحالة التأسيس السعودي وطلبات الموافقة على ذكر العملاء والشركاء.
- بناء تطبيق Next.js + TypeScript إذا اعتمدت تجربة V6، مع فحص الأداء والأمان وإمكانية الوصول ومراجعة الخصوصية وسياسة الاحتفاظ بالبيانات.
- تم حفظ نسخة مراجعة الموقع الحالية على GitHub الخاص بالشركة، بينما يظل ربط الاستضافة والدومين إلى المرحلة الأخيرة حسب قرار المستخدم.
## سجل النسخ المحفوظة في GitHub

- `preview/BioVault_Cinematic_V6_Offline.html`: أحدث نسخة موحدة تعمل دون اتصال.
- `history/V5_BalanceChain_Offline.html`: عرض BalanceChain السينمائي السابق.
- `history/V4_Offline.html`, `history/V3_Offline.html`, `history/V2_Offline.html`: معاينات المراحل السابقة.
- `docs/`: سجل التعديلات ومخططات المحتوى.

هذه محفوظات ملفات HTML للمراجعة وليست بعد مشروع Next.js إنتاجيًا؛ الحزم ZIP والأصول المصدرية الكاملة محفوظة أيضًا في النسخة الاحتياطية المحلية المقدمة للمستخدم، ولم تُرفع كلها إلى هذا المستودع.
