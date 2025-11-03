<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 5.1 -->

<pre style="text-align: center;">
        الدرس 5.1: كيفية تنفيذ أوامر خارجية
</pre>

<p><strong>اكتب <code>:!</code> متبوعاً بأمر خارجي لتنفيذ ذلك الأمر.</strong></p>

<ol>
  <li>اكتب الأمر المألوف <code>:</code> لوضع المؤشر في أسفل الشاشة. هذا يسمح لك بإدخال أمر.</li>

<li>الآن اكتب حرف <code>!</code> (علامة التعجب). هذا يسمح لك بتنفيذ أي أمر shell خارجي.</li>

<li>كمثال، اكتب <code>ls</code> بعد ! ثم اضغط <code><ENTER></code>. هذا سيعرض لك قائمة بمحتويات مجلدك، كما لو كنت في سطر الأوامر. أو استخدم <code>:!dir</code> إذا لم يعمل ls.</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>---> ملاحظة:</strong> من الممكن تنفيذ أي أمر خارجي بهذه الطريقة.
<br><strong>---> ملاحظة:</strong> جميع أوامر <code>:</code> يجب إنهاؤها بالضغط على <code><ENTER></code>
</div>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 5.2 -->

<pre style="text-align: center;">
              الدرس 5.2: المزيد حول حفظ الملفات
</pre>

<p><strong>لحفظ التغييرات التي أجريت على الملف، اكتب <code>:w اسم_الملف</code>.</strong></p>

<ol>
  <li>اكتب <code>:!dir</code> أو <code>:!ls</code> للحصول على قائمة بمجلدك. أنت تعرف بالفعل أنه يجب الضغط على <code><ENTER></code> بعد هذا.</li>

<li>اختر اسم ملف غير موجود بعد، مثل TEST.</li>

<li>الآن اكتب: <code>:w TEST</code> (حيث TEST هو اسم الملف الذي اخترته).</li>

<li>هذا يحفظ الملف كاملاً (Vim Tutor) تحت اسم TEST. للتحقق من هذا، اكتب <code>:!dir</code> مرة أخرى لرؤية مجلدك.</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>---> لاحظ أنه إذا خرجت من Vim ودخلت مرة أخرى باسم الملف TEST، سيكون الملف نسخة طبق الأصل من المدرّب عندما حفظته.</strong>
</div>

<ol start="5">
  <li>الآن احذف الملف بالكتابة (لـ MS-DOS): <code>:!del TEST</code></li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 5.3 -->

<pre style="text-align: center;">
            الدرس 5.3: أمر حفظ انتقائي
</pre>

<p><strong>لحفظ جزء من الملف، اكتب <code>:#,# w اسم_الملف</code></strong></p>

<ol>
  <li>مرة أخرى، اكتب <code>:!dir</code> أو <code>:!ls</code> للحصول على قائمة بمجلدك واختر اسم ملف مناسب مثل TEST.</li>

<li>حرك المؤشر إلى أعلى هذه الصفحة واكتب <code>Ctrl-g</code> لمعرفة رقم ذلك السطر. <strong>احفظ هذا الرقم!</strong></li>

<li>الآن انتقل إلى أسفل الصفحة واكتب <code>Ctrl-g</code> مرة أخرى. <strong>احفظ رقم هذا السطر أيضاً!</strong></li>

<li>لحفظ جزء فقط في ملف، اكتب <code>:#,# w TEST</code> حيث #,# هما الرقمان اللذان حفظتهما (أعلى، أسفل) و TEST هو اسم ملفك.</li>

<li>مرة أخرى، تحقق من وجود الملف بـ <code>:!dir</code> ولكن <strong>لا تحذفه</strong>.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 5.4 -->

<pre style="text-align: center;">
           الدرس 5.4: استرجاع ودمج الملفات
</pre>

<p><strong>لإدراج محتويات ملف، اكتب <code>:r اسم_الملف</code></strong></p>

<ol>
  <li>اكتب <code>:!dir</code> للتأكد من وجود اسم ملف TEST من قبل.</li>

<li>ضع المؤشر في أعلى هذه الصفحة.</li>
</ol>

<div style="background: #fff3cd; padding: 10px; border-right: 4px solid #ffc107; margin: 15px 0;">
<strong>ملاحظة:</strong> بعد تنفيذ الخطوة 3 سترى الدرس 5.3. ثم انتقل <strong>لأسفل</strong> إلى هذا الدرس مرة أخرى.
</div>

<ol start="3">
  <li>الآن استرجع ملف TEST باستخدام الأمر <code>:r TEST</code> حيث TEST هو اسم الملف.</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> الملف الذي تسترجعه يوضع بدءاً من مكان وجود المؤشر.
</div>

<ol start="4">
  <li>للتحقق من استرجاع الملف، ارجع بالمؤشر ولاحظ أن هناك الآن نسختين من الدرس 5.3، النسخة الأصلية ونسخة الملف.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- ملخص الدرس 5 -->

<pre style="text-align: center;">
                   ملخص الدرس 5
</pre>

<ol>
  <li><code>:!command</code> ينفذ أمراً خارجياً.
  <br>بعض الأمثلة المفيدة (لـ MS-DOS):
  <br><code>:!dir</code> - يعرض قائمة المحتويات
  <br><code>:!del اسم_الملف</code> - يحذف الملف</li>

<li><code>:w اسم_الملف</code> يحفظ ملف Vim الحالي على القرص باسم اسم_الملف.</li>

<li><code>:#,#w اسم_الملف</code> يحفظ الأسطر من # إلى # في ملف اسم_الملف.</li>

<li><code>:r اسم_الملف</code> يسترجع ملف القرص اسم_الملف ويدخله في الملف الحالي بعد موضع المؤشر.</li>
</ol>

</div>
