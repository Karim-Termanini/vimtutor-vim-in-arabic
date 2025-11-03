<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 3.1 -->

<pre style="text-align: center;">
             الدرس 3.1: أمر الوضع (Put)
</pre>

<p><strong>اكتب <code>p</code> لوضع آخر عملية حذف بعد المؤشر.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر الأول في المجموعة أدناه.</li>

<li>اكتب <code>dd</code> لحذف السطر وتخزينه في buffer الـ Vim.</li>

<li>حرك المؤشر إلى السطر <strong>فوق</strong> المكان الذي يجب أن يذهب إليه السطر المحذوف.</li>

<li>في الوضع العادي، اكتب <code>p</code> لوضع السطر.</li>

<li>كرر الخطوات من 2 إلى 4 لوضع جميع الأسطر بالترتيب الصحيح.</li>
</ol>

<pre style="text-align: left; background: #f8f9fa; padding: 15px; direction: ltr;">
     d) Can you learn too?
     b) Violets are blue,
     c) Intelligence is learned,
     a) Roses are red,
</pre>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 3.2 -->

<pre style="text-align: center;">
               الدرس 3.2: أمر الاستبدال (Replace)
</pre>

<p><strong>اكتب <code>r</code> ثم حرفاً لاستبدال الحرف تحت المؤشر.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر الأول أدناه المحدد بـ --->.</li>

<li>حرك المؤشر ليصبح فوق أول خطأ.</li>

<li>اكتب <code>r</code> ثم الحرف الذي يجب أن يحل محل الخطأ.</li>

<li>كرر الخطوتين 2 و 3 حتى يصبح السطر الأول صحيحاً.</li>
</ol>

<strong>---&gt; Whan this lime was tuoed in, someone presswd some wrojg keys!</strong>
<br><strong>---&gt; When this line was typed in, someone pressed some wrong keys!</strong>

<ol start="5">
  <li>الآن انتقل إلى الدرس 3.3.</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> تذكر أنك يجب أن تتعلم بالممارسة، وليس بالحفظ.
</div>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 3.3 -->

<pre style="text-align: center;">
            الدرس 3.3: أمر التغيير (Change)
</pre>

<p><strong>لتغيير جزء أو كل كلمة، اكتب <code>cw</code>.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر الأول أدناه المحدد بـ --->.</li>

<li>ضع المؤشر على الحرف u في كلمة lubw.</li>

<li>اكتب <code>cw</code> والكلمة الصحيحة (في هذه الحالة، اكتب 'ine').</li>

<li>اضغط <code><ESC></code> وانتقل إلى الخطأ التالي (أول حرف يحتاج للتغيير).</li>

<li>كرر الخطوتين 3 و 4 حتى تصبح الجملة الأولى مطابقة للثانية.</li>
</ol>

<strong>---&gt; This lubw has a few wptfd that mrrf changing usf the change command.</strong>
<br><strong>---&gt; This line has a few words that need changing using the change command.</strong>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>لاحظ أن</strong> <code>cw</code> لا يستبدل الكلمة فقط، بل يضعك أيضاً في وضع الإدراج.
</div>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 3.4 -->

<pre style="text-align: center;">
               الدرس 3.4: المزيد من التغييرات باستخدام c
</pre>

<p><strong>أمر التغيير يستخدم مع نفس الكائنات مثل أمر الحذف.</strong></p>

<ol>
  <li>أمر التغيير يعمل بنفس طريقة الحذف. التنسيق هو:</li>
</ol>

<pre style="text-align: center; background: #f8f9fa; padding: 15px;">
   [number]   c   object   OR   c   [number]   object
</pre>

<ol start="2">
  <li>الكائنات هي نفسها أيضاً، مثل <code>w</code> (كلمة)، <code>$</code> (نهاية السطر)، إلخ.</li>

<li>انتقل إلى السطر الأول أدناه المحدد بـ --->.</li>

<li>حرك المؤشر إلى أول خطأ.</li>

<li>اكتب <code>c$</code> لجعل بقية السطر مثل الثاني واضغط <code><ESC></code>.</li>
</ol>

<strong>---&gt; The end of this line needs some help to make it like the second.</strong>
<br><strong>---&gt; The end of this line needs to be corrected using the  c$  command.</strong>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- ملخص الدرس 3 -->

<pre style="text-align: center;">
                   ملخص الدرس 3
</pre>

<ol>
  <li>لاستبدال النص الذي تم حذفه بالفعل، اكتب <code>p</code>. هذا <strong>يضع</strong> النص المحذوف <strong>بعد</strong> المؤشر (إذا تم حذف سطر، فسيذهب إلى السطر أسفل المؤشر).</li>

<li>لاستبدال الحرف تحت المؤشر، اكتب <code>r</code> ثم الحرف الذي سيحل محل الأصلي.</li>

<li>أمر التغيير يسمح لك بتغيير الكائن المحدد من المؤشر إلى نهاية الكائن. مثال: اكتب <code>cw</code> لتغيير من المؤشر إلى نهاية الكلمة، <code>c$</code> لتغيير إلى نهاية السطر.</li>

<li>تنسيق أمر التغيير هو:</li>
</ol>

<pre style="text-align: center; background: #f8f9fa; padding: 15px;">
   [number]   c   object   OR   c   [number]   object
</pre>

<p><strong>الآن انتقل إلى الدرس التالي.</strong></p>

</div>
