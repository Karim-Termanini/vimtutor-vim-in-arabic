<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 6.1 -->

<pre style="text-align: center;">
             الدرس 6.1: أمر الفتح (Open)
</pre>

<p><strong>اكتب <code>o</code> لفتح سطر أسفل المؤشر ووضعك في وضع الإدراج.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر أدناه المحدد بـ --->.</li>

<li>اكتب <code>o</code> (صغير) لفتح سطر <strong>أسفل</strong> المؤشر ووضعك في وضع الإدراج.</li>

<li>الآن انسخ السطر المحدد بـ ---> واضغط <code><ESC></code> للخروج من وضع الإدراج.</li>
</ol>

<strong>---&gt; After typing  o  the cursor is placed on the open line in Insert mode.</strong>

<ol start="4">
  <li>لفتح سطر <strong>فوق</strong> المؤشر، ببساطة اكتب <code>O</code> (كبير)، بدلاً من <code>o</code> (صغير). جرب هذا على السطر أدناه.
  <br>افتح سطراً فوق هذا بكتابة <code>Shift-O</code> بينما المؤشر على هذا السطر.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 6.2 -->

<pre style="text-align: center;">
            الدرس 6.2: أمر الإلحاق (Append)
</pre>

<p><strong>اكتب <code>a</code> لإدراج نص <strong>بعد</strong> المؤشر.</strong></p>

<ol>
  <li>حرك المؤشر إلى نهاية السطر الأول أدناه المحدد بـ ---> عن طريق
  <br>كتابة <code>$</code> في الوضع العادي.</li>

<li>اكتب <code>a</code> (صغير) لإلحاق نص <strong>بعد</strong> الحرف تحت المؤشر. (<code>A</code> كبير يلحق بنهاية السطر.)</li>
</ol>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> هذا يتجنب كتابة <code>i</code>، آخر حرف، النص للإدراج، <code><ESC></code>، المؤشر لليمين، وأخيراً <code>x</code>، فقط للإلحاق بنهاية السطر!
</div>

<ol start="3">
  <li>الآن أكمل السطر الأول. لاحظ أيضاً أن الإلحاق هو تماماً مثل وضع الإدراج، باستثناء الموقع حيث يتم إدراج النص.</li>
</ol>

<strong>---&gt; This line will allow you to practice</strong>
<br><strong>---&gt; This line will allow you to practice appending text to the end of a line.</strong>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 6.3 -->

<pre style="text-align: center;">
            الدرس 6.3: نسخة أخرى من الاستبدال
</pre>

<p><strong>اكتب <code>R</code> كبير لاستبدال أكثر من حرف واحد.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر الأول أدناه المحدد بـ --->.</li>

<li>ضع المؤشر في بداية أول كلمة مختلفة عن السطر الثاني المحدد بـ ---> (كلمة 'last').</li>

<li>الآن اكتب <code>R</code> واستبدل بقية النص في السطر الأول عن طريق
  <br>الكتابة فوق النص القديم لجعل السطر الأول مثل الثاني.</li>
</ol>

<strong>---&gt; To make the first line the same as the last on this page use the keys.</strong>
<br><strong>---&gt; To make the first line the same as the second, type R and the new text.</strong>

<ol start="4">
  <li>لاحظ أنه عند الضغط على <code><ESC></code> للخروج، أي نص غير معدل يبقى كما هو.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 6.4 -->

<pre style="text-align: center;">
                الدرس 6.4: ضبط الخيارات
</pre>

<p><strong>ضبط خيار لجعل البحث أو الاستبدال يتجاهل حالة الأحرف</strong></p>

<ol>
  <li>ابحث عن 'ignore' بإدخال:
  <br><code>/ignore</code>
  <br>كرر عدة مرات بالضغط على مفتاح <code>n</code></li>

<li>اضبط خيار 'ic' (تجاهل حالة الأحرف) بالكتابة:
  <br><code>:set ic</code></li>

<li>الآن ابحث عن 'ignore' مرة أخرى بإدخال: <code>n</code>
  <br>كرر البحث عدة مرات بالضغط على مفتاح <code>n</code></li>

<li>اضبط خيارات 'hlsearch' و 'incsearch':
  <br><code>:set hls is</code></li>

<li>الآن أدخل أمر البحث مرة أخرى، وشاهد ما يحدث:
  <br><code>/ignore</code></li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- ملخص الدرس 6 -->

<pre style="text-align: center;">
                   ملخص الدرس 6
</pre>

<ol>
  <li>كتابة <code>o</code> تفتح سطراً <strong>أسفل</strong> المؤشر وتضع المؤشر على السطر المفتوح في وضع الإدراج.
  <br>كتابة <code>O</code> كبير تفتح السطر <strong>فوق</strong> السطر الذي عليه المؤشر.</li>

<li>اكتب <code>a</code> لإدراج نص <strong>بعد</strong> الحرف الذي عليه المؤشر.
  <br>كتابة <code>A</code> كبير تلحق النص تلقائياً بنهاية السطر.</li>

<li>كتابة <code>R</code> كبير تدخل وضع الاستبدال حتى الضغط على <code><ESC></code> للخروج.</li>

<li>كتابة <code>:set xxx</code> تضبط الخيار "xxx"</li>
</ol>

</div>
