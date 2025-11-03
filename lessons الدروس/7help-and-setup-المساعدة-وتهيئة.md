<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<!-- الدرس 7 -->
<h2 style="text-align: center;">الدرس 7: أوامر المساعدة المضمنة</h2>

<p><strong>استخدم نظام المساعدة المضمنة</strong></p>

<p>يحتوي Vim على نظام مساعدة شامل مدمج. للبدء، جرب أحد هذه الخيارات:</p>
<ul>
  <li>اضغط مفتاح <code>HELP</code> (إن وجد)</li>
  <li>اضغط مفتاح <code>F1</code> (إن وجد)</li>
  <li>اكتب <code>:help</code> ثم اضغط <code>Enter</code></li>
</ul>

<p>لإغلاق نافذة المساعدة، اكتب <code>:q</code> ثم اضغط <code>Enter</code>.</p>

<p>يمكنك العثور على مساعدة حول أي موضوع تقريباً بإضافة وسيط لأمر المساعدة. جرب الأوامر التالية:</p>

<pre style="background: #f8f9fa; padding: 15px; text-align: right;">
:help w
:help c_&lt;T
:help insert-index
:help user-manual
</pre>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الدرس 8 -->
<h2 style="text-align: center;">الدرس 8: إنشاء ملف إعدادات البدء</h2>

<p><strong>تفعيل خصائص Vim المتقدمة</strong></p>

<p>يحتوي Vim على العديد من الميزات الإضافية مقارنة بـ Vi، لكن معظمها معطل افتراضياً. لبدء استخدام المزيد من الميزات، يجب إنشاء ملف "vimrc".</p>

<ol>
  <li>ابدأ تحرير ملف الإعدادات حسب نظام التشغيل:
  <br><code>:edit ~/.vimrc</code> لأنظمة Unix
  <br><code>:edit $VIM/_vimrc</code> لأنظمة Windows</li>
  
  <li>اقرأ ملف الإعدادات النموذجي:
  <br><code>:read $VIMRUNTIME/vimrc_example.vim</code></li>
  
  <li>احفظ الملف:
  <br><code>:write</code></li>
</ol>

<p>في المرة القادمة التي تبدأ فيها Vim، سيستخدم تمييز الصيغة البرمجية. يمكنك إضافة جميع إعداداتك المفضلة إلى هذا الملف.</p>

<hr style="margin: 30px 0; border: 1px dashed #ccc;">

<!-- الخاتمة -->
<div style="background: #e8f5e8; padding: 20px; border-right: 4px solid #4caf50; margin: 20px 0;">
<h3 style="text-align: center;">ختام المدرّب</h3>

<p>هذا يختتم مدرّب Vim. كان الهدف منه تقديم نظرة عامة مبسطة عن المحرر، تكفي لتمكينك من استخدامه بفعالية. هذا لا يغطي جميع إمكانيات Vim التي تتضمن أوامراً متقدمة كثيرة.</p>

<p>للتعلم المتقدم، ننصح بقراءة الدليل الشامل: <code>:help user-manual</code></p>

<h4>كتب مقترحة للتعمق:</h4>
<ul>
  <li><strong>Vim - Vi Improved</strong> - تأليف Steve Oualline (ناشر: New Riders)<br>
  أول كتاب مخصص بالكامل لـ Vim، مفيد جداً للمبتدئين ويحتوي على أمثلة وصور عديدة.</li>
  
  <li><strong>Learning the Vi Editor</strong> - تأليف Linda Lamb (ناشر: O'Reilly)<br>
  يركز على Vi مع معلومات عن Vim في الإصدار السادس.</li>
</ul>

<p class="text-muted" style="text-align: left; direction: ltr;">
تم إعداد هذا المدرّب الأصلي بواسطة: Michael C. Pierce و Robert K. Ware<br>
تم تعديله لـ Vim بواسطة: Bram Moolenaar
</p>
</div>

</div>


