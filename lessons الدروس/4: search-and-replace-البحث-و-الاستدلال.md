<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 4.1 -->

<pre style="text-align: center;">
             الدرس 4.1: الموقع وحالة الملف
</pre>

<p><strong>اكتب CTRL-g لمعرفة موقعك في الملف وحالة الملف.
<br>اكتب SHIFT-G للانتقال إلى سطر معين في الملف.</strong></p>

<div style="background: #fff3cd; paddin: 10px; border-right: 4px solid #ffc107; margin: 15px 0;">
<strong>! تنبيه: اقرأ هذا الدرس كاملاً قبل تنفيذ أي من الخطوات</strong>
</div>

<ol>
  <li>اضغط باستمرار على مفتاح Ctrl ثم اضغط <code>g</code>. سيظهر سطر الحالة في أسفل الصفحة مع اسم الملف والسطر الذي أنت فيه. تذكر رقم السطر للخطوة 3.</li>

<li>اضغط <code>shift-G</code> للانتقال إلى نهاية الملف.</li>

<li>اكتب رقم السطر الذي كنت فيه ثم اضغط <code>shift-G</code>. هذا سيعيدك إلى السطر الذي كنت فيه عندما ضغطت أول مرة على Ctrl-g.
  <br><em>(عند كتابة الأرقام، لن تظهر على الشاشة.)</em></li>

<li>إذا كنت تشعر بالثقة للقيام بذلك، نفذ الخطوات من 1 إلى 3.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 4.2 -->

<pre style="text-align: center;">
            الدرس 4.2: أمر البحث
</pre>

<p><strong>اكتب <code>/</code> متبوعاً بعبارة للبحث عن العبارة.</strong></p>

<ol>
  <li>في الوضع العادي اكتب حرف <code>/</code>. لاحظ أنه والمؤشر يظهران في أسفل الشاشة كما في الأمر <code>:</code>.</li>

<li>الآن اكتب 'errroor' <code><ENTER></code>. هذه هي الكلمة التي تريد البحث عنها.</li>

<li>للبحث عن نفس العبارة مرة أخرى، ببساطة اكتب <code>n</code>.
  <br>للبحث عن نفس العبارة في الاتجاه المعاكس، اكتب <code>Shift-N</code>.</li>

<li>إذا كنت تريد البحث عن عبارة في الاتجاه العكسي، استخدم الأمر <code>?</code> بدلاً من /.</li>
</ol>

<strong>---&gt; عندما يصل البحث إلى نهاية الملف، سيكمل من البداية.</strong>

<pre style="text-align: left; background: #f8f9fa; padding: 15px; direction: ltr;">
"errroor" is not the way to spell error;  errroor is an error.
</pre>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 4.3 -->

<pre style="text-align: center;">
           الدرس 4.3: البحث عن الأقواس المتطابقة
</pre>

<p><strong>اكتب <code>%</code> للعثور على القوس المغلق ),], أو } المطابق.</strong></p>

<ol>
  <li>ضع المؤشر على أي (, [, أو { في السطر أدناه المحدد بـ --->.</li>

<li>الآن اكتب حرف <code>%</code>.</li>

<li>يجب أن يكون المؤشر على القوس أو الأقواس المطابقة.</li>

<li>اكتب <code>%</code> لنقل المؤشر مرة أخرى إلى القوس الأول (عن طريق المطابقة).</li>
</ol>

<strong>---&gt; This ( is a test line with ('s, ['s ] and {'s } in it. ))</strong>

<div style="background: #f0f0f0; padding: 10px; border-right: 4px solid #ccc; margin: 15px 0;">
<strong>ملاحظة:</strong> هذا مفيد جداً في تصحيح الأخطاء في البرامج ذات الأقواس غير المطابقة!
</div>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 4.4 -->

<pre style="text-align: center;">
              الدرس 4.4: طريقة لتغيير الأخطاء
</pre>

<p><strong>اكتب <code>:s/old/new/g</code> لاستبدال 'new' بـ 'old'.</strong></p>

<ol>
  <li>حرك المؤشر إلى السطر أدناه المحدد بـ --->.</li>

<li>اكتب <code>:s/thee/the <ENTER></code>. لاحظ أن هذا الأمر يغير فقط
  <br>أول ظهور للكلمة في السطر.</li>

<li>الآن اكتب <code>:s/thee/the/g</code> مما يعني الاستبدال الشامل على السطر.
  <br>هذا يغير كل الظهورات على السطر.</li>
</ol>

<strong>---&gt; thee best time to see thee flowers is in thee spring.</strong>

<ol start="4">
  <li>لتغيير كل ظهور لسلسلة أحرف بين سطرين،
  <br>اكتب <code>:#,#s/old/new/g</code> حيث #,# هما رقما السطرين.
  <br>اكتب <code>:%s/old/new/g</code> لتغيير كل الظهورات في الملف كاملاً.</li>
</ol>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- ملخص الدرس 4 -->

<pre style="text-align: center;">
                   ملخص الدرس 4
</pre>

<ol>
  <li><code>Ctrl-g</code> يعرض موقعك في الملف وحالة الملف.
  <br><code>Shift-G</code> ينتقل إلى نهاية الملف. رقم سطر متبوع
  <br>بـ <code>Shift-G</code> ينتقل إلى ذلك رقم السطر.</li>

<li>كتابة <code>/</code> متبوعاً بعبارة تبحث إلى <strong>الأمام</strong> عن العبارة.
  <br>كتابة <code>?</code> متبوعاً بعبارة تبحث إلى <strong>الخلف</strong> عن العبارة.
  <br>بعد البحث اكتب <code>n</code> للعثور على الظهور التالي في نفس الاتجاه
  <br>أو <code>Shift-N</code> للبحث في الاتجاه المعاكس.</li>

<li>كتابة <code>%</code> أثناء وجود المؤشر على (,),[,],{, أو } تعثر على
  <br>زوجها المطابق.</li>

<li>لاستبدال new بـ first old في السطر اكتب <code>:s/old/new</code>
  <br>لاستبدال new بكل old في السطر اكتب <code>:s/old/new/g</code>
  <br>لاستبدال العبارات بين رقمي سطرين اكتب <code>:#,#s/old/new/g</code>
  <br>لاستبدال كل الظهورات في الملف اكتب <code>:%s/old/new/g</code>
  <br>لطلب التأكيد في كل مرة أضف 'c' <code>:%s/old/new/gc</code></li>
</ol>

</div>


