<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 2.1 -->

<pre style="text-align: center;">
            الدرس 2.1: أوامر الحذف
</pre>

<p><strong>اكتب <code>dw</code> لحذف حتى نهاية الكلمة.</strong></p>

<ol>
  <li>اضغط <code><ESC></code> للتأكد من أنك في الوضع العادي.</li>

<li>حرك المؤشر إلى السطر أدناه المحدد بـ --->.</li>

<li>حرك المؤشر إلى بداية الكلمة التي تحتاج للحذف.</li>
    <li>اكتب <code>dw</code> لجعل الكلمة تختفي.</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> الحروف dw ستظهر على السطر الأخير من الشاشة أثناء الكتابة. إذا كتبت شيئاً خاطئاً، اضغط <code><ESC></code> وابدأ من جديد.
</div>

<strong>---&gt; There are a some words fun that don't belong paper in this sentence.</strong>

<ol start="5">
  <li>كرر الخطوتين 3 و 4 حتى يصبح الجملة صحيحة وانتقل إلى الدرس 2.2.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 2.2 -->

<pre style="text-align: center;">
              الدرس 2.2: المزيد من أوامر الحذف
</pre>

<p><strong>اكتب <code>d$</code> لحذف حتى نهاية السطر.</strong></p>

<ol>
  <li>اضغط <code><ESC></code> للتأكد من أنك في الوضع العادي.</li>

<li>حرك المؤشر إلى السطر أدناه المحدد بـ --->.</li>

<li>حرك المؤشر إلى نهاية السطر الصحيح (بعد أول .).</li>

<li>اكتب <code>d$</code> لحذف حتى نهاية السطر.</li>
</ol>

<strong>---&gt; Somebody typed the end of this line twice. end of this line twice.</strong>

<ol start="5">
  <li>انتقل إلى الدرس 2.3 لفهم ما يحدث.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 2.3 -->

<pre style="text-align: center;">
             الدرس 2.3: حول الأوامر والكائنات
</pre>

<p>تنسيق أمر الحذف <code>d</code> هو كما يلي:</p>

<pre style="text-align: center; background: #f8f9fa; padding: 15px;">
   [number]   d   object    OR      d   [number]   object
</pre>

<p>حيث:</p>
<ul>
  <li><strong>number</strong> - عدد مرات تنفيذ الأمر (اختياري، افتراضي=1)</li>
  <li><strong>d</strong> - هو الأمر للحذف</li>
  <li><strong>object</strong> - هو ما سيعمل عليه الأمر (مذكور أدناه)</li>
</ul>

<p>قائمة مختصرة للكائنات:</p>
<ul>
  <li><code>w</code> - من المؤشر إلى نهاية الكلمة، بما في ذلك المسافة</li>
  <li><code>e</code> - من المؤشر إلى نهاية الكلمة، دون تضمين المسافة</li>
  <li><code>$</code> - من المؤشر إلى نهاية السطر</li>
</ul>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> للمغامرين، الضغط على الكائن فقط في الوضع العادي دون أمر سينقل المؤشر كما هو محدد في قائمة الكائنات.
</div>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 2.4 -->

<pre style="text-align: center;">
        الدرس 2.4: استثناء لـ 'command-object'
</pre>

<p><strong>اكتب <code>dd</code> لحذف سطر كامل.</strong></p>

<p>نظراً لتكرار حذف الأسطر الكاملة، قرر مصممو Vim أن يكون أسهل ببساطة كتابة حرفي d متتاليين لحذف سطر.</p>

<ol>
  <li>حرك المؤشر إلى السطر الثاني في العبارة أدناه.</li>
  <li>اكتب <code>dd</code> لحذف السطر.</li>
  <li>الآن انتقل إلى السطر الرابع.</li>
  <li>اكتب <code>2dd</code> (تذكر number-command-object) لحذف السطرين.</li>
</ol>

<pre style="text-align: left; background: #f8f9fa; padding: 15px; direction: ltr;">
      1)  Roses are red,
      2)  Mud is fun,
      3)  Violets are blue,
      4)  I have a car,
      5)  Clocks tell time,
      6)  Sugar is sweet
      7)  And so are you.
</pre>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 2.5 -->

<pre style="text-align: center;">
             الدرس 2.5: أمر التراجع
</pre>

<p><strong>اضغط <code>u</code> للتراجع عن آخر الأوامر، <code>U</code> لإصلاح سطر كامل.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر أدناه المحدد بـ ---> وضعه على أول خطأ.</li>
  <li>اكتب <code>x</code> لحذف أول حرف غير مرغوب.</li>
  <li>الآن اكتب <code>u</code> للتراجع عن آخر أمر تم تنفيذه.</li>
  <li>هذه المرة أصلح كل الأخطاء في السطر باستخدام أمر <code>x</code>.</li>
  <li>الآن اكتب <code>U</code> (كبير) لإعادة السطر إلى حالته الأصلية.</li>
  <li>الآن اكتب <code>u</code> عدة مرات للتراجع عن <code>U</code> والأوامر السابقة.</li>
  <li>الآن اكتب <code>CTRL-R</code> (مع الاستمرار على مفتاح CTRL أثناء الضغط على R) عدة مرات لإعادة الأوامر (تراجع عن عمليات التراجع).</li>
</ol>

<strong>---&gt; Fiix the errors oon thhis line and reeplace them witth undo.</strong>

<ol start="8">
  <li>هذه أوامر مفيدة جداً. الآن انتقل إلى ملخص الدرس 2.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- ملخص الدرس 2 -->

<pre style="text-align: center;">
                   ملخص الدرس 2
</pre>

<ol>
  <li>لحذف من المؤشر إلى نهاية الكلمة اكتب: <code>dw</code></li>

<li>لحذف من المؤشر إلى نهاية السطر اكتب: <code>d$</code></li>

<li>لحذف سطر كامل اكتب: <code>dd</code></li>

<li>تنسيق الأمر في الوضع العادي هو:
  <pre style="background: #f8f9fa; padding: 10px; margin: 10px 0;">
     [number] command object   OR   command [number] object
  </pre>
  حيث:
  <ul>
    <li><strong>number</strong> - عدد مرات تكرار الأمر</li>
    <li><strong>command</strong> - ما يجب فعله، مثل <code>d</code> للحذف</li>
    <li><strong>object</strong> - ما يجب أن يعمل عليه الأمر، مثل <code>w</code> (كلمة)، <code>$</code> (إلى نهاية السطر)، إلخ.</li>
  </ul>
  </li>

<li>للتراجع عن الإجراءات السابقة، اكتب: <code>u</code> (u صغيرة)
  <br>للتراجع عن كل التغييرات على سطر اكتب: <code>U</code> (U كبيرة)
  <br>للتراجع عن عمليات التراجع اكتب: <code>CTRL-R</code></li>
</ol>

</div>
