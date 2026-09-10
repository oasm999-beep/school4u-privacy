[index.html](https://github.com/user-attachments/files/32076629/index.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>سياسة الخصوصية — School4U</title>
<style>
  :root { color-scheme: light dark; }
  body {
    margin: 0; padding: 28px 20px 64px;
    font: 16px/1.9 -apple-system, "Segoe UI", Tahoma, system-ui, sans-serif;
    max-width: 760px; margin-inline: auto;
    background: #fdfdfc; color: #1b1b1a;
  }
  @media (prefers-color-scheme: dark) {
    body { background: #191918; color: #e9e8e4; }
    td, th { border-color: #3a3a37 !important; }
    th { background: #232322 !important; }
    .note { background: #232322 !important; border-color: #4a4a45 !important; }
  }
  h1 { font-size: 1.6rem; margin: 0 0 4px; }
  h2 { font-size: 1.15rem; margin: 34px 0 8px; }
  .sub { color: #6b6b66; margin: 0 0 28px; font-size: .92rem; }
  table { border-collapse: collapse; width: 100%; margin: 12px 0; font-size: .93rem; }
  th, td { border: 1px solid #d8d8d3; padding: 8px 10px; text-align: right; vertical-align: top; }
  th { background: #f2f2ef; font-weight: 700; }
  .note { background: #f5f5f2; border: 1px solid #e0e0da; border-radius: 8px; padding: 12px 14px; margin: 16px 0; }
  ul { padding-inline-start: 22px; }
  li { margin: 5px 0; }
  hr { border: 0; border-top: 1px solid #d8d8d3; margin: 44px 0 28px; }
  .en { direction: ltr; text-align: left; }
  .en th, .en td { text-align: left; }
  code { background: #f2f2ef; padding: 1px 5px; border-radius: 4px; font-size: .88em; }
  @media (prefers-color-scheme: dark) { code { background: #232322; } }
</style>
</head>
<body>

<h1>سياسة الخصوصية</h1>
<p class="sub">
  تطبيق <strong>School4U</strong> (<code>sa.mohmd.jadwal</code>) —
  آخر تحديث: ١٠ سبتمبر ٢٠٢٦
</p>

<p>
  تطبيق «School4U» أداةٌ مدرسية لبناء الجدول الأسبوعي وتوزيع حصص
  الاحتياط ورصد غياب الطلاب والمعلمين. وهذه السياسة تصف — بدقّة — ما
  يُخزَّن في جهازك، وما يغادره، ومتى.
</p>

<h2>١) المبدأ: بياناتك في جهازك</h2>
<p>
  كل ما تُدخله في التطبيق يُحفظ في <strong>قواعد بيانات محلّية داخل
  الجهاز</strong>: المعلمون والمواد والفصول والجدول الأسبوعي وحصص
  الاحتياط، وأسماء الطلاب وأرقام هوياتهم وسجلّات غيابهم وتأخّرهم
  وإنذارات غيابهم ودرجاتهم.
</p>
<p>
  هذه البيانات <strong>لا تُرفع تلقائيًّا إلى أيّ خادم</strong>، ولا
  يصل إليها مطوّر التطبيق. وحذف التطبيق من الجهاز يمحوها معه.
</p>

<div class="note">
  <strong>بيانات الطلاب لا تغادر الجهاز إطلاقًا.</strong>
  هي في ملف قاعدة بيانات منفصل، وآليّة إرسال البيانات إلى الخدمة
  الاختيارية لا تقرأ ذلك الملف أصلًا — فالحصر بنيويّ في التطبيق، لا
  مجرّد وعد.
</div>

<h2>٢) ما يغادر الجهاز — وبأمرٍ منك وحدك</h2>

<h3>أ. خدمة تجهيز الجدول (اختيارية)</h3>
<p>
  إن اخترت إرسال بيانات مدرستك ليُجهَّز جدولها، تُرفع عند ضغطك زرّ
  الإرسال — لا قبله — البيانات التالية إلى خادم الخدمة:
</p>
<ul>
  <li>اسم المدرسة والعام الدراسي والفصل الدراسي</li>
  <li>أسماء المعلمين وتخصّصاتهم ونصابهم</li>
  <li>أسماء الفصول والمواد والربط بينها</li>
  <li>الحصص الزمنية وملاحظاتك النصّية للفريق</li>
</ul>
<p>
  ويعود إليك الجدول المُجهَّز. <strong>ولا تُرفع بيانات الطلاب في هذه
  الحزمة ولا في غيرها.</strong>
</p>
<p>
  <strong>ولا تُرفع أرقام جوّالات المعلمين ولا بُرُدهم</strong> — تبقى في
  جهازك للاتصال وإرسال التكاليف، ولا تحملها الحزمة المرسَلة أصلًا.
</p>

<h3>ب. حساب الخدمة</h3>
<p>
  لاستعمال خدمة التجهيز يلزم حساب: <strong>بريدٌ إلكتروني وكلمة
  مرور</strong>. تُدار المصادقة عبر
  <a href="https://supabase.com/privacy">Supabase</a>، ولا يُخزَّن نصّ
  كلمة المرور. ومن لم يستعمل الخدمة لا يحتاج حسابًا، والتطبيق يعمل
  كاملًا بدونه.
</p>

<h3>ج. الرسائل النصّية (اختيارية)</h3>
<p>
  إن أدخلت اعتمادات بوابة الرسائل الخاصة بمدرستك في الإعدادات، فإن
  إرسال إشعارٍ لوليّ أمرٍ أو لمعلم يُرسل <strong>رقم الجوال ونصّ
  الرسالة</strong> إلى مزوّد البوابة الذي تعاقدت معه مدرستك. ولا يمرّ
  ذلك بخوادم المطوّر. والاعتمادات تُحفظ في جهازك وحده، ولا تخرج في أيّ
  نسخة احتياطية تُشارِكها ولا في ملفات التصدير.
</p>

<h3>د. تطبيقات المراسلة</h3>
<p>
  عند اختيار إرسال رسالة عبر واتساب أو الرسائل، يفتح التطبيق ذلك
  البرنامج <strong>بنصٍّ مُهيَّأ</strong> ولا يرسل نيابةً عنك — الإرسال
  بيدك.
</p>

<h2>٣) ما لا يفعله التطبيق</h2>
<ul>
  <li>لا إعلانات، ولا تتبّع، ولا ملفّات تعريف إعلانية</li>
  <li>لا أدوات تحليلات ولا تقارير أعطال من طرفٍ ثالث</li>
  <li>لا يطلب الموقع الجغرافي ولا جهات الاتصال ولا الميكروفون</li>
  <li>لا يبيع بياناتك ولا يشاركها لأغراض تسويقية</li>
</ul>
<p>
  ويطلب على أندرويد إذنين: <code>INTERNET</code> للخدمة الاختيارية
  ولإرسال الرسائل، و<code>CAMERA</code> لما يلي وحده.
</p>

<h3>هـ. الكاميرا — لمسح بطاقات البوابة</h3>
<p>
  تُستعمل الكاميرا <strong>لقراءة رمز بطاقة الطالب عند بوابة المدرسة</strong>
  لرصد التأخّر الصباحي، ولهذا الغرض وحده.
</p>
<p>
  <strong>ولا تُحفظ صورةٌ ولا تُرسل.</strong> يُقرأ الرمز في اللحظة ولا
  يُخزَّن منه شيء. ورمزُ البطاقة نصٌّ عشوائيٌّ لا يحمل اسمًا ولا رقم هوية
  ولا فصلًا — من التقط بطاقةً ساقطة ومسحها لم يعرف صاحبها.
</p>
<p>
  والإذن <strong>اختياري</strong>: من لم يمنحه استعمل التطبيق كاملًا عدا
  شاشة المسح، ورصد التأخّر يبقى متاحًا بإدخال الرمز يدويًّا.
</p>

<h2>٤) مسؤولية المدرسة عن بيانات الطلاب</h2>
<p>
  يُدخل مستخدم التطبيق (المدرسة أو من تُفوّضه) بيانات طلابٍ قد يكونون
  قاصرين. والمدرسة هي المسؤولة عن مشروعية جمع هذه البيانات ومعالجتها
  وفق الأنظمة المعمول بها. ودورُ التطبيق أداةٌ محلّية للحفظ والعرض
  والطباعة، لا أكثر.
</p>

<h2>٥) الاحتفاظ والحذف</h2>
<table>
  <tr><th>البيانات</th><th>أين</th><th>كيف تُحذف</th></tr>
  <tr>
    <td>الجدول والمعلمون والفصول والطلاب والغياب</td>
    <td>جهازك</td>
    <td>من داخل التطبيق، أو بحذف التطبيق</td>
  </tr>
  <tr>
    <td>حزمة بيانات المدرسة المرفوعة</td>
    <td>خادم الخدمة</td>
    <td>بحذف الطلب، أو بحذف الحساب</td>
  </tr>
  <tr>
    <td>الحساب (البريد)</td>
    <td>خادم المصادقة</td>
    <td><strong>من داخل التطبيق</strong>: الإجراءات السريعة ← نسخة الخادم ← حذف الحساب</td>
  </tr>
</table>
<p>
  حذف الحساب يمحوه ويمحو طلباتك المرفوعة معه، ولا يمكن التراجع عنه.
</p>

<h2>٦) الأمان</h2>
<p>
  كل اتّصالٍ بالخوادم يجري عبر <strong>HTTPS مُعمّى</strong>. والبيانات
  المحلّية محفوظة داخل مساحة التطبيق المعزولة التي يوفّرها نظام
  التشغيل. وللمستخدم أن يضع رقمًا سرّيًّا لفتح التطبيق.
</p>

<h2>٧) التغييرات</h2>
<p>
  إن تغيّرت هذه السياسة نُحدّث تاريخ آخر تعديل أعلاه، ويُعلن التغيير
  في صفحة التطبيق على المتجر.
</p>

<h2>٨) التواصل</h2>
<p>
  لأيّ سؤالٍ عن الخصوصية أو لطلب حذف بيانات:
  <a href="mailto:alrazii2030@gmail.com">alrazii2030@gmail.com</a>
</p>

<hr>

<div class="en" lang="en" dir="ltr">
<h1>Privacy Policy</h1>
<p class="sub"><strong>School4U</strong> (<code>sa.mohmd.jadwal</code>) — Last updated: 10 September 2026</p>

<p>
  School4U is a school tool for building weekly timetables,
  assigning substitute lessons, and recording student and teacher
  attendance.
</p>

<h2>1) Everything stays on your device</h2>
<p>
  Teachers, subjects, classes, the timetable, substitutions, and all
  student records (names, ID numbers, absences, lateness, absence
  warnings, grades) are
  stored in local databases on the device. They are never uploaded
  automatically, and the developer has no access to them. Uninstalling
  the app deletes them.
</p>
<p>
  <strong>Student data never leaves the device.</strong> It lives in a
  separate database file that the upload feature does not read at all.
</p>

<h2>2) What leaves the device — only when you ask</h2>
<p>
  <strong>Timetable preparation service (optional).</strong> When you
  press Send, the app uploads: school name, academic year and term;
  teacher names, specialisations and workloads; class and subject names
  and their links; time slots; and your free-text notes. The prepared
  timetable is returned to you. <strong>No student data is
  included.</strong>
</p>
<p>
  <strong>Teacher phone numbers and emails are never uploaded.</strong>
  They stay on the device for calling and sending assignments; the
  outgoing package does not carry them at all.
</p>
<p>
  <strong>Account.</strong> The service requires an email and password,
  handled by Supabase. Passwords are never stored in plain text. The app
  works fully without an account.
</p>
<p>
  <strong>SMS (optional).</strong> If your school enters its own SMS
  gateway credentials, sending a notice transmits the recipient's phone
  number and the message text to that provider. This does not pass
  through the developer's servers. Credentials stay on the device and
  are excluded from shared backups and exports.
</p>
<p>
  <strong>Messaging apps.</strong> The app opens WhatsApp or the SMS app
  with a prefilled message; it never sends on your behalf.
</p>

<p>
  <strong>Camera — for scanning gate cards.</strong> The camera reads a
  student's card code at the school gate to record morning lateness, and
  for nothing else. <strong>No image is stored or transmitted.</strong>
  The code is read in the moment and nothing is kept. The card code is a
  random string carrying no name, ID number or class — whoever finds a
  dropped card and scans it learns nothing. The permission is
  <strong>optional</strong>: without it the app works fully except that
  one screen, and lateness can still be recorded by typing the code.
</p>

<h2>3) What the app does not do</h2>
<p>
  No ads, no tracking, no advertising identifiers, no third-party
  analytics or crash reporting, no location, contacts or microphone
  access. Data is never sold or shared for marketing. Android
  permissions requested: <code>INTERNET</code> and <code>CAMERA</code>
  (for the gate scanner only).
</p>

<h2>4) School responsibility for student data</h2>
<p>
  The school (or its delegate) enters student data, which may concern
  minors. The school remains responsible for the lawfulness of that
  processing. The app is a local tool for storage, display and printing.
</p>

<h2>5) Retention and deletion</h2>
<p>
  Local data: deleted from within the app or by uninstalling. Uploaded
  school packages: deleted with the order or the account. Account:
  deletable from within the app (Quick actions → Server copy → Delete
  account),
  which permanently removes the account and its uploaded orders.
</p>

<h2>6) Security</h2>
<p>
  All server communication uses HTTPS. Local data is kept in the app's
  sandboxed storage. An optional PIN can lock the app.
</p>

<h2>7) Contact</h2>
<p><a href="mailto:alrazii2030@gmail.com">alrazii2030@gmail.com</a></p>
</div>

</body>
</html>
