<div dir="rtl" style="text-align: right; font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.8; direction: rtl;">

<h1 style="text-align: center; color: #2c3e50;">ملخص أوامر Vim - الدروس 1-8</h1>

<div style="background: #e8f4fd; padding: 20px; border-right: 4px solid #3498db; margin: 20px 0;">
<h3 style="color: #2c3e50; margin-top: 0;">🎯 ملاحظة مهمة:</h3>
<p>هذا الملخص يغطي جميع الأوامر التي تعلمناها في دروس vimtutor. احفظ هذا الملف كمرجع سريع أثناء تعلمك Vim.</p>
</div>

<!-- الحركة الأساسية -->
<h2>🔄 أوامر الحركة الأساسية</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>h</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">التحريك لليسار</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>j</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">التحريك لأسفل</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>k</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">التحريك لأعلى</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>l</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">التحريك لليمين</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>w</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال لكلمة تالية</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>$</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال لنهاية السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>0</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال لبداية السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>Ctrl-g</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">عرض موقعك في الملف</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>G</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال لآخر سطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>gg</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال لأول سطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>50G</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الانتقال للسطر 50</td>
</tr>
</table>
</div>

<!-- الإدراج والحذف -->
<h2>✏️ أوامر الإدراج والحذف</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>i</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الإدراج قبل المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>a</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الإدراج بعد المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>A</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">الإدراج في نهاية السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>o</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">فتح سطر جديد تحت</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>O</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">فتح سطر جديد فوق</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>x</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حذف حرف تحت المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>dw</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حذف كلمة من موضع المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>d$</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حذف من المؤشر لنهاية السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>dd</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حذف سطر كامل</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>2dd</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حذف سطرين</td>
</tr>
</table>
</div>

<!-- التغيير والاستبدال -->
<h2>🔄 أوامر التغيير والاستبدال</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>r</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال حرف واحد</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>R</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال متعدد (وضع الاستبدال)</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>cw</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تغيير كلمة من موضع المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>c$</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تغيير من المؤشر لنهاية السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>cc</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تغيير سطر كامل</td>
</tr>
</table>
</div>

<!-- التراجع والإعادة -->
<h2>↩️ أوامر التراجع والإعادة</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>u</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تراجع عن آخر أمر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>U</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تراجع عن كل تغييرات السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>Ctrl-R</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">إعادة التغييرات (عكس التراجع)</td>
</tr>
</table>
</div>

<!-- النسخ واللصق -->
<h2>📋 أوامر النسخ واللصق</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>yy</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">نسخ سطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>p</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">لصق بعد المؤشر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>P</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">لصق قبل المؤشر</td>
</tr>
</table>
</div>

<!-- البحث والاستبدال -->
<h2>🔍 أوامر البحث والاستبدال</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>/كلمة</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">بحث للأمام عن كلمة</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>?كلمة</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">بحث للخلف عن كلمة</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>n</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تكرار البحث بنفس الاتجاه</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>N</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تكرار البحث بالاتجاه المعاكس</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>%</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">البحث عن قوس مطابق</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:s/قديم/جديد</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال أول ظهور في السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:s/قديم/جديد/g</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال كل الظهورات في السطر</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:#,#s/قديم/جديد/g</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال بين سطرين محددين</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:%s/قديم/جديد/g</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">استبدال في الملف كله</td>
</tr>
</table>
</div>

<!-- الملفات والخروج -->
<h2>💾 أوامر الملفات والخروج</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:w</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حفظ الملف</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:w اسم_الملف</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حفظ باسم جديد</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:#,#w اسم_الملف</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حفظ أسطر محددة</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:q</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">خروج</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:q!</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">خروج دون حفظ</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:wq</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">حفظ وخروج</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:r اسم_الملف</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">إدراج محتويات ملف</td>
</tr>
</table>
</div>

<!-- الأوامر الخارجية والإعدادات -->
<h2>⚙️ أوامر خارجية وإعدادات</h2>
<div style="background: #f8f9fa; padding: 15px; border-right: 3px solid #e9ecef;">
<table style="width: 100%; border-collapse: collapse;">
<tr style="background: #e9ecef;">
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الأمر</th>
    <th style="padding: 10px; text-align: right; border: 1px solid #ddd;">الوظيفة</th>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:!أمر</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تنفيذ أمر خارجي</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:help</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">فتح المساعدة</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:set ic</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تجاهل حالة الأحرف في البحث</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:set hls</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">تمييز نتائج البحث</td>
</tr>
<tr>
    <td style="padding: 8px; border: 1px solid #ddd;"><code>:set is</code></td>
    <td style="padding: 8px; border: 1px solid #ddd;">بحث أثناء الكتابة</td>
</tr>
</table>
</div>

<div style="background: #fff3cd; padding: 20px; border-right: 4px solid #ffc107; margin: 20px 0;">
<h3 style="color: #856404; margin-top: 0;">💡 نصائح مهمة:</h3>
<ul>
    <li>اضغط <code>ESC</code> للعودة للوضع العادي إذا فقدت الاتجاه</li>
    <li>يمكن دمج الأرقام مع الأوامر (مثال: <code>5dd</code> لحذف 5 أسطر)</li>
    <li>استخدم <code>:help الأمر</code> لمعرفة المزيد عن أي أمر</li>
    <li>الممارسة المستمرة هي مفتاح الإتقان!</li>
</ul>
</div>

</div>


