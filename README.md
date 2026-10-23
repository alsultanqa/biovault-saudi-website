# BioVault Software Solutions — Official Saudi Website

## Current live domain and deployment
- **Official company domain:** https://biovaultsa.com
- **www hostname:** https://www.biovaultsa.com
- **Hosting:** **GitHub Pages only**. The custom domain is configured via the `CNAME` file on the `gh-pages` branch (`biovaultsa.com`); the GoDaddy DNS configuration was previously set for GitHub Pages.
- **Live published files:** `gh-pages/index.html` and `gh-pages/assets/` (GitHub Pages publishing source: branch `gh-pages`, root).
- **Editable authoritative source:** `main/site-v14/index.html` and `main/site-v14/assets/`.
- Both HTML locations were synchronized on 2026-10-23, verified to have the same Git blob SHA.
- **IMPORTANT:** Updating only `main` does **not** update the company website automatically. Until a verified native GitHub Pages deployment automation is configured, release by copying approved `main/site-v14/` contents into the `gh-pages/` root and committing there. Keep `CNAME` unchanged.
- **DO NOT use Vercel for future release work**. It is historical/legacy and not the user-selected domain publishing path.

## Approved website details
- Official emerald-and-silver BioVault brand, cinematic layout, untouched first project-selection menu, Arabic/English support.
- Project experiences: BalanceChain, Venture Sentinel, EndlessJob, Custom Software, with internal Next/Previous/Replay/Explore All controls.
- Intro brand film and project films committed under `assets/`. Keep sound enabled for user-triggered playback with a mute choice.
- **Public contact addresses:** `info@biovaultsa.com` and `partners@biovaultsa.com`. Never restore obsolete `support@biovault.app`.
- Footer copyright in both languages: © 2026 BioVault Software Solutions. All rights reserved. / © ٢٠٢٦ بيوفولت لحلول البرمجيات. جميع الحقوق محفوظة.
- Do not show "Private Preview" or "Private Concept" on the public website. Still disclose that illustrative product scenarios use synthetic data.
- Preserve DNS records needed for company email (MX, SPF, DKIM, etc.) if DNS work is ever necessary.

## Release rule
Check the `gh-pages` branch and the official domain before claiming live changes. A successful GitHub commit alone is not proof that a user's browser currently receives the latest page. No changes to domain/hosting platform without explicit user approval.

## Documentation
See [governance](docs/SITE_GOVERNANCE.md) and [historical changelog](docs/CHANGELOG.md). Archived V6 instructions follow for record only.

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
