# vimtutor-arabic

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vimtutor بالعربية - دليل تعلم Vim للمتحدثين بالعربية</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.8;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .header {
            background: white;
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .header h1 {
            color: #2c3e50;
            font-size: 2.5em;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #2c3e50, #3498db);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .header p {
            font-size: 1.2em;
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        
        .badge {
            background: #f8f9fa;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9em;
            border: 2px solid #e9ecef;
        }
        
        .content-section {
            background: white;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
        }
        
        h3 {
            color: #34495e;
            margin: 20px 0 15px 0;
        }
        
        .lesson-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .lesson-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            border-right: 4px solid #3498db;
            transition: transform 0.3s ease;
        }
        
        .lesson-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3);
        }
        
        .lesson-card h4 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .file-structure {
            background: #2c3e50;
            color: white;
            padding: 20px;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            margin: 20px 0;
        }
        
        .file-structure .folder {
            color: #3498db;
        }
        
        .file-structure .file {
            color: #2ecc71;
        }
        
        .tips {
            background: linear-gradient(135deg, #fff3cd, #ffeaa7);
            border-right: 4px solid #f39c12;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .contribution-steps {
            background: #e8f4fd;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .step {
            display: flex;
            align-items: flex-start;
            margin-bottom: 15px;
        }
        
        .step-number {
            background: #3498db;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-left: 15px;
            flex-shrink: 0;
        }
        
        code {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 4px 8px;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            font-size: 0.9em;
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: white;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }
            
            .container {
                padding: 10px;
            }
            
            .content-section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <h1>🎯 Vimtutor بالعربية</h1>
            <p>دليل تعلم Vim التفاعلي للمتحدثين بالعربية</p>
            
            <div class="badges">
                <div class="badge">🔄 مفتوح المصدر</div>
                <div class="badge">📚 تعليمي تفاعلي</div>
                <div class="badge">🌍 باللغة العربية</div>
                <div class="badge">🚀 للمبتدئين</div>
            </div>
        </div>

        <!-- About Section -->
        <div class="content-section">
            <h2>📖 عن المشروع</h2>
            <p>مشروع <strong>Vimtutor بالعربية</strong> يهدف إلى تقديم دروس Vim التفاعلية بلغتنا الأم، مما يجعل تعلم محرر Vim القوي سهلًا ومتاحًا للمبرمجين والمطورين العرب. المشروع مبني على الدروس الرسمية لـ Vim مع ترجمة دقيقة وشرح واضح.</p>
        </div>

        <!-- Why This Project Section -->
        <div class="content-section">
            <h2>🎯 لماذا هذا المشروع؟</h2>
            <div class="lesson-grid">
                <div class="lesson-card">
                    <h4>🌍 مصادر عربية</h4>
                    <p>توفير مصادر تعلم عربية شاملة لمحرر Vim</p>
                </div>
                <div class="lesson-card">
                    <h4>🚀 تبسيط التعلم</h4>
                    <p>جعل تعلم Vim سهلًا للمبرمجين العرب</p>
                </div>
                <div class="lesson-card">
                    <h4>📚 تجربة تفاعلية</h4>
                    <p>تجربة تعلم مشابهة لـ vimtutor الأصلي</p>
                </div>
                <div class="lesson-card">
                    <h4>💡 مرجع سريع</h4>
                    <p>ملخص شامل لأهم أوامر Vim</p>
                </div>
            </div>
        </div>

        <!-- File Structure -->
        <div class="content-section">
            <h2>📁 هيكل المشروع</h2>
            <div class="file-structure">
                <div class="folder">📘 vimtutor-arabic/</div>
                <div class="folder">&nbsp; ├── lessons/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# الدروس الرئيسية</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 01-introduction-المقدمة.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 1.1:Basics-مبادئ.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 2: Commands-الأوامر.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 3: Commands-2-الجزأ الثاني من الأوامر.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 4: search-and-replace-البحث-و-الاستدلال.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; ├── 5:File Commands and External Commands-أوامر-الملفات-والأوامر-الخارجية.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; └── 6:Advanced commands and options-أوامر-متقدمة-وخيارات.md</div>
                <div class="file">&nbsp; │&nbsp;&nbsp;&nbsp; └── 7help-and-setup-المساعدة-وتهيئة.md</div>
                <div class="file">&nbsp; ├── 📊 Summary-ملخص الاوامر.md</div>
                <div class="file">&nbsp; ├── 📄 README.md</div>
                <div class="file">&nbsp; └── ⚖️ LICENSE</div>
            </div>
        </div>

        <!-- How to Use -->
        <div class="content-section">
            <h2>🚀 كيفية الاستخدام</h2>
            
            <h3>الطريقة الأولى: القراءة المباشرة</h3>
            <div class="step">
                <div class="step-number">1</div>
                <div>انتقل إلى مجلد <code>lessons</code></div>
            </div>
            <div class="step">
                <div class="step-number">2</div>
                <div>ابدأ بالدرس الأول واتبع التسلسل</div>
            </div>
            <div class="step">
                <div class="step-number">3</div>
                <div>طبق الأوامر مباشرة في Vim</div>
            </div>
            
            <h3>الطريقة الثانية: التحميل والممارسة</h3>
            <div class="step">
                <div class="step-number">1</div>
                <div>حمل الملفات المحلية على جهازك</div>
            </div>
            <div class="step">
                <div class="step-number">2</div>
                <div>افتح Vim وابدأ بالتطبيق العملي</div>
            </div>
            <div class="step">
                <div class="step-number">3</div>
                <div>استخدم <code>:help</code> للحصول على مساعدة إضافية</div>
            </div>
        </div>

        <!-- Lessons List -->
        <div class="content-section">
            <h2>📚 قائمة الدروس</h2>
            <div class="lesson-grid">
                <div class="lesson-card">
                    <h4>الدرس 1</h4>
                    <p>المقدمة والحركة الأساسية</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 2</h4>
                    <p>أوامر الحذف والتراجع</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 3</h4>
                    <p>الوضع والاستبدال والتغيير</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 4</h4>
                    <p>البحث والاستبدال</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 5</h4>
                    <p>أوامر الملفات والأوامر الخارجية</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 6</h4>
                    <p>أوامر متقدمة وخيارات</p>
                </div>
                <div class="lesson-card">
                    <h4>الدرس 7-8</h4>
                    <p>المساعدة وتهيئة Vim</p>
                </div>
            </div>
        </div>

        <!-- Tips Section -->
        <div class="content-section">
            <h2>💡 نصائح للتعلم</h2>
            <div class="tips">
                <div class="step">
                    <div class="step-number">✅</div>
                    <div><strong>تعلم بالممارسة:</strong> لا تقرأ فقط، طبق الأوامر مباشرة</div>
                </div>
                <div class="step">
                    <div class="step-number">✅</div>
                    <div><strong>ابدأ من البداية:</strong> اتبع تسلسل الدروس</div>
                </div>
                <div class="step">
                    <div class="step-number">✅</div>
                    <div><strong>كرر التمارين:</strong> التكرار يساعد على تثبيت التعلم</div>
                </div>
                <div class="step">
                    <div class="step-number">✅</div>
                    <div><strong>استخدم الملخص:</strong> احتفظ بملخص الأوامر كمرجع سريع</div>
                </div>
            </div>
        </div>

        <!-- Requirements -->
        <div class="content-section">
            <h2>🛠 المتطلبات</h2>
            <ul style="list-style-position: inside; margin-right: 20px;">
                <li>محرر Vim مثبت على نظامك</li>
                <li>معرفة أساسية باستخدام Terminal/Command Line</li>
                <li>الرغبة في التعلم! 💪</li>
            </ul>
        </div>

        <!-- Contribution -->
        <div class="content-section">
            <h2>🤝 المساهمة في المشروع</h2>
            <p>نرحب بمساهماتكم! يمكنكم المساعدة عن طريق:</p>
            
            <div class="lesson-grid">
                <div class="lesson-card">
                    <h4>🔧 تصحيح الأخطاء</h4>
                    <p>الأخطاء اللغوية أو التقنية</p>
                </div>
                <div class="lesson-card">
                    <h4>📝 إضافة شروحات</h4>
                    <p>شروحات إضافية وأمثلة</p>
                </div>
                <div class="lesson-card">
                    <h4>🎨 تحسين التصميم</h4>
                    <p>التنسيق والعرض</p>
                </div>
                <div class="lesson-card">
                    <h4>🌍 ترجمة موارد</h4>
                    <p>موارد إضافية</p>
                </div>
            </div>

            <h3>كيفية المساهمة:</h3>
            <div class="contribution-steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <div>Fork المشروع</div>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <div>أنشئ فرعًا للميزة الجديدة <code>git checkout -b feature/AmazingFeature</code></div>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <div>commit التغييرات <code>git commit -m 'Add some AmazingFeature'</code></div>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <div>push إلى الفرع <code>git push origin feature/AmazingFeature</code></div>
                </div>
                <div class="step">
                    <div class="step-number">5</div>
                    <div>open a Pull Request</div>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>⭐ <strong>لا تنسى عمل Star للمشروع إذا أعجبك!</strong></p>
            <p style="margin-top: 10px; font-style: italic;">"البرمجة مهارة، وVim أداة تمكنك من إتقانها" 🚀</p>
        </div>
    </div>
</body>
</html>