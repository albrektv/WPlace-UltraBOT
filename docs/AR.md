<p align="center">
  الترجمات ➜&nbsp;
  <a href="../README.md"><img src="https://flagcdn.com/256x192/us.png" width="48" alt="United States Flag"></a>
   <a href="AR.md"><img src="https://flagcdn.com/256x192/sa.png" width="48" alt="Turkey Flag"></a>
  <a href="DE.md"><img src="https://flagcdn.com/256x192/de.png" width="48" alt="Germany Flag"></a>
  <a href="ES.md"><img src="https://flagcdn.com/256x192/es.png" width="48" alt="Spain Flag"></a>
  <a href="FR.md"><img src="https://flagcdn.com/256x192/fr.png" width="48" alt="France Flag"></a>
  <a href="RU.md"><img src="https://flagcdn.com/256x192/ru.png" width="48" alt="Russia Flag"></a>
  <a href="JA.md"><img src="https://flagcdn.com/256x192/jp.png" width="48" alt="Japan Flag"></a>
  <a href="CN.md"><img src="https://flagcdn.com/256x192/cn.png" width="48" alt="China Flag"></a>
  <a href="TR.md"><img src="https://flagcdn.com/256x192/tr.png" width="48" alt="Turkey Flag"></a>
</p>

---

> [!NOTE]
> **أهلاً وسهلاً، بعد ما جت إجراءات جديدة قررت أطور هالبوت وخلصته في يوم واحد بس. بسبب هالإجراءات، ما يبان إنه ممكن نسوي بوت أوتوماتيكي كامل حالياً. ~~بس نقدر نستغل ثغرة موجودة ونرسم من 12 حساب في ثانية واحدة بتحقق واحد بس. لو نفترض إن الحسابات معبية، نقدر نرسل 12 * 62 = <strong>744</strong> بكسل/ثانية.~~ بعد التحديث سكروا هالثغرة؛ عشان كذا لازم تاخذ توكن جديد لكل إرسال حساب. لو مستعد، شرحت لك خطوات الاستخدام تحت.**

---

<p align="center"><strong>WPlace UltraBOT</strong></p>

<p align="center">
  تقدر تضيف البكسلات اللي تبيها على <a href="https://wplace.live" target="_blank">WPlace</a> بعدة حسابات.
</p>

---

<p align="center"><strong>🚀┃ كيف تنصب البوت:</strong></p>

<p align="center">
  تنصيب البوت سهل، بس إتقانه صعب. "امزح" في البداية قد يبان صعب الاستخدام؛ بس بسبب الإجراءات الجديدة ما فيه بوت ثاني يشتغل بهالطريقة. عشان كذا راح يستاهل التعب اللي راح تتعبه.
</p>

<br>

### 🔧┃التنصيب (العربية)

- المتطلبات:
  - Node.js >= 18.18.0

- الخطوات:
  1. نصب المكتبات المطلوبة:
     
     ```bash
     npm install
     ```
  2. شغل التطبيق:
     
     ```bash
     npm start
     ```
  3. افتح `http://localhost:3000` في المتصفح.

<details open>
  <summary><h2>📖┃الدليل</h2></summary>

---

![الجزء الأول](https://i.imgur.com/yS9093x.png)

لما تروح `localhost:3000` لازم تشوف صفحة زي كذا.<br>

---

![الجزء الثاني](https://i.imgur.com/taF0I2T.png)

افتح تاب جديد وروح `chrome://extensions/`.<br>
فعل وضع المطور.<br>

![](https://i.imgur.com/oe42A42.png)

اضغط على "Load unpacked".<br>

![](https://i.imgur.com/jPyzOr3.png)

اختر مجلد `WPlace-Helper`.<br>

---

![الجزء الثالث](https://i.imgur.com/YVyvw3a.png)

روح موقع `wplace.live`.<br>
اضغط `F12`.<br>
في النافذة اللي طلعت، اختر تاب 'Application' من فوق (لو ما لقيته اضغط على المكان الأصفر اللي مبين واختاره).<br>
اضغط على `cf_clearance` وانسخ القيمة من تحت.<br>

---

![الجزء الرابع](https://i.imgur.com/sJvyiC6.png)

ارجع للبوت.<br>
اضغط على زر "Accounts"، بعدين "Add Account". الصق القيمة اللي نسختها في خانة `cf_clearance`.<br>
ملاحظة!<br>
بسبب التحديث الأخير وإجراءات المقاومة، صار لازم تدخل قيمة `cf_clearance` لكل حساب. عشان تسويها بسرعة، افتح موقع wplace.live في تاب خفي واجلب التوكن. ما تحتاج تسجل دخول.

---

![الجزء الخامس](https://i.imgur.com/vJkPMx8.png)

روح `wplace.live` واضغط على الإضافة من فوق، لازم تطلع لك زي كذا.<br>
تأكد إن جزء "pixel token" مفعل، بعدين جرب تلون بكسل عادي في الخريطة.<br>

![الجزء الخامس - خطأ](https://i.imgur.com/uZmJDad.png)

لو طلع لك هالخطأ في الشاشة، معناها إنك في الطريق الصحيح. اضغط على الإضافة مرة ثانية؛ راح تطلع لك معلومات "World X" و "World Y" للمكان اللي جربت تلونه. انسخهم.<br>

---

![الجزء السادس](https://i.imgur.com/LniE1E8.png)

لما تدخل إحداثيات "World X" و "World Y" وتضغط زر 'fetch' لازم تطلع لك خريطة زي اللي في الصورة.<br>

---

![الجزء السابع](https://i.imgur.com/vJkPMx8.png)

ارجع للصفحة اللي قبل، اضغط على الإضافة وانسخ جزء "Account Token".<br>

---

![الجزء الثامن](https://i.imgur.com/8sjhH1L.png)

![الجزء الثامن](https://i.imgur.com/jf6W8NV.png)

بعدين راح يوديك لقسم الحسابات. اضغط على زر "Add Account". في الصفحة اللي تطلع:
- تقدر تكتب أي اسم تبيه للحساب.
- في خانة "Account Token" الصق القيمة اللي نسختها في الخطوة اللي قبل.
- اضغط زر "Add".<br>

---

![الجزء التاسع](https://i.imgur.com/DJUEywj.png)

بعد ما تضيف الحسابات اللي تبيها، تقدر تشوف في الجهة اليمين فوق إجمالي البكسلات والبكسلات المتاحة لكل حساباتك.<br>
الصورة اللي ترفعها تتحول أوتوماتيكياً لألوان الباليت المجانية الموجودة في الموقع وتتحمل بهالطريقة. هالنظام راح يتطور أكثر في المستقبل.<br>

لما تستخدم زر "Upload Image" عشان ترفع صورة:<br>
- في الجهة اليسار فوق من الصورة، راح يطلع لك عدد البكسلات المطلوبة للصورة.<br>
- في الجهة اليمين فوق من الصورة فيه زر قفل. لما تقفله ما تقدر تحرك الصورة. زر 'X' يمسح الصورة.<br>
- تقدر تشوف كل الصور اللي رفعتها في الشريط الجانبي. لو ما لقيت صورة في الصفحة، اضغط عليها من الشريط وراح يوديك لها مباشرة.<br>

---

![الجزء العاشر](https://i.imgur.com/Dzt1p3o.png)

اضغط زر "Ready". في النافذة اللي تطلع اضغط "Select Account" عشان تختار الحسابات النشطة. لما تخلص اضغط "Select Account" مرة ثانية عشان تقفل النافذة.<br>

---

![الجزء الحادي عشر](https://i.imgur.com/QKJRVL9.png)

لما تقرب على الصورة، كل بكسل شفاف تعبيه راح يتلون باللون المناسب من الصورة اللي رفعتها وتقدر تحط بكسلات بس داخل حدود الصورة. لو اخترت لون معين، تقدر تلون أي مكان تبيه لحد أقصى سعة البكسلات عندك.<br>

---

![الجزء الثاني عشر](https://i.imgur.com/vJkPMx8.png)

ارجع لصفحة WPlace وجرب ترسل بكسل جديد عشان التوكن القديم ما عاد يشتغل؛ انسخ قيمة "pixel token" الجديدة.<br>

---

![الجزء الثالث عشر](https://i.imgur.com/wDp07pH.png)

ارجع لصفحتنا، الصق القيمة في خانة 'token' واضغط زر 'Start'.<br>

---

![الجزء الرابع عشر](https://i.imgur.com/iQTH5TR.png)

لو سويت كل شي صح لازم تجيك رسالة زي كذا وتشوف التغييرات مطبقة في الخريطة. وهذا كل شي؛ تقدر تكرر هالخطوات عشان تسوي أي صورة تبيها.<br>

</details>

<br>

> [!IMPORTANT]
> <p><sub><strong>1.</strong> في قسم الحسابات لو ضغطت زر 'Check Pixel'، تقدر تشيك البكسلات المتبقية لذاك الحساب يدوياً. عادة هالفحص يصير أوتوماتيكياً كل 90 ثانية.</sub></p>
> <p><sub><strong>2.</strong> توكنات الحسابات تشتغل تقريباً 4-5 ساعات. لو انتهت صلاحية توكن أثناء الفحص الأوتوماتيكي للحساب، الحساب يصير غير نشط. تقدر تفعله مرة ثانية بإدخال توكن جديد في قسم التعديل والضغط على 'Check Pixel'.</sub></p>
> <p><sub><strong>3.</strong> لما يطلع توكن الإرسال في اللوحة لازم تكون سريع. لو تأخرت كثير راح تنتهي صلاحية التوكن وتجيك رسالة خطأ 403.</sub></p>

<br>

المشروع كله اتسوى في يوم واحد، فلا تنسى تبلغ عن أي نقص تشوفه أو ميزات تبي تضيفها.

---

<p align="center">
  <img src="https://i.imgur.com/msR5dM9.png" alt="الصفحة الرئيسية"/>
</p>

---

### 📋┃قائمة المهام

- [x] الترجمات [TR/USA/AR]  
- [ ] إصلاح أخطاء السكريبت  
- [x] الأدلة

---
-  الترجمة: عزوزالبريك  


<p align="center">
  <a href="#"><img src="https://komarev.com/ghpvc/?username=xacter&repo=WPlace-UltraBOT&style=for-the-badge&label=Views:&color=gray"/></a>
</p>
