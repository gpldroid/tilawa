<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مشغل القرآن الكريم - Quran Player</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.8;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            margin-top: 20px;
        }
        
        h1 {
            color: #1b5e20;
            text-align: center;
            border-bottom: 3px solid #4caf50;
            padding-bottom: 15px;
            margin-bottom: 30px;
            font-size: 2.5rem;
        }
        
        h2 {
            color: #2e7d32;
            border-right: 4px solid #4caf50;
            padding-right: 15px;
            margin-top: 30px;
        }
        
        .feature-section {
            margin-bottom: 30px;
            padding: 20px;
            background: #f0f7f0;
            border-radius: 10px;
            border-right: 4px solid #2e7d32;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .feature-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: #2e7d32;
            margin-bottom: 15px;
        }
        
        ul {
            padding-right: 20px;
        }
        
        li {
            margin-bottom: 10px;
            padding: 8px 0;
        }
        
        .tech-badge {
            display: inline-block;
            background: #e8f5e9;
            color: #1b5e20;
            padding: 5px 15px;
            border-radius: 20px;
            margin: 5px;
            border: 1px solid #4caf50;
        }
        
        .steps {
            counter-reset: step-counter;
            padding-right: 20px;
        }
        
        .step {
            position: relative;
            padding-right: 40px;
            margin-bottom: 20px;
        }
        
        .step:before {
            counter-increment: step-counter;
            content: counter(step-counter);
            position: absolute;
            right: 0;
            top: 0;
            background: #4caf50;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
        }
        
        .download-btn {
            display: inline-block;
            background: linear-gradient(135deg, #1b5e20, #2e7d32);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 30px;
            margin: 20px 0;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .download-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(27, 94, 32, 0.3);
        }
        
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .feature-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <h1>مشغل القرآن الكريم - Quran Player</h1>
        
        <p style="text-align: center; font-size: 1.2rem; color: #555; margin-bottom: 30px;">
            مشغل ويب متكامل للقرآن الكريم - واجهة عربية أنيقة لتلاوة وقراءة القرآن الكريم
        </p>
        
        <div class="feature-section">
            <h2><i class="fas fa-star"></i> الميزات الرئيسية</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-headphones"></i>
                    </div>
                    <h3>التلاوة الصوتية</h3>
                    <p>الاستماع لتلاوات 16 قارئًا مشهورًا مثل:</p>
                    <ul>
                        <li>محمد صديق المنشاوي</li>
                        <li>ماهر المعيقلي</li>
                        <li>عبد الباسط عبد الصمد</li>
                        <li>عبد الرحمن السديس</li>
                    </ul>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-book-open"></i>
                    </div>
                    <h3>عرض النص الكامل</h3>
                    <p>عرض نص القرآن الكريم كاملاً مع:</p>
                    <ul>
                        <li>ترقيم الآيات في دوائر خضراء</li>
                        <li>خط عربي واضح ومريح للعين</li>
                        <li>تصميم يشبه صفحات المصحف</li>
                        <li>إمكانية التمرير السلس</li>
                    </ul>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>واجهة عربية متجاوبة</h3>
                    <p>تصميم متكامل باللغة العربية:</p>
                    <ul>
                        <li>اتجاه من اليمين لليسار (RTL)</li>
                        <li>يعمل على جميع الأجهزة</li>
                        <li>متوافق مع جميع الشاشات</li>
                        <li>تصميم عصري وأنيق</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="feature-section">
            <h2><i class="fas fa-cogs"></i> الميزات المتقدمة</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-moon"></i>
                    </div>
                    <h3>الوضع الليلي</h3>
                    <p>وضع قراءة مريح للعين:</p>
                    <ul>
                        <li>تبديل بين الوضع النهاري والليلي</li>
                        <li>ألوان مخصصة للقراءة الليلية</li>
                        <li>حفظ التفضيل تلقائيًا</li>
                        <li>مثالي للقراءة في الإضاءة المنخفضة</li>
                    </ul>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-save"></i>
                    </div>
                    <h3>حفظ التقدم</h3>
                    <p>تذكر آخر مكان وصلت إليه:</p>
                    <ul>
                        <li>حفظ السورة الحالية</li>
                        <li>تذكر وقت التشغيل</li>
                        <li>استعادة التقدم عند العودة</li>
                        <li>تخزين محلي في المتصفح</li>
                    </ul>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-play-circle"></i>
                    </div>
                    <h3>تشغيل ذكي</h3>
                    <p>ميزات تشغيل متقدمة:</p>
                    <ul>
                        <li>التشغيل التلقائي بين السور</li>
                        <li>قائمة سور كاملة (114 سورة)</li>
                        <li>معلومات كل سورة (عدد الآيات، النوع)</li>
                        <li>زر العودة للأعلى</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="feature-section">
            <h2><i class="fas fa-user-check"></i> سهولة الاستخدام</h2>
            <div class="steps">
                <div class="step">
                    <h3>اختر القارئ المفضل</h3>
                    <p>اختر من بين 16 قارئًا مشهورًا للقرآن الكريم</p>
                </div>
                
                <div class="step">
                    <h3>اختر السورة</h3>
                    <p>تصفح قائمة السور الكاملة واختر السورة المراد استماعها</p>
                </div>
                
                <div class="step">
                    <h3>استمع ومتابعة النص</h3>
                    <p>استمع للتلاوة مع متابعة النص المعروض على الشاشة</p>
                </div>
                
                <div class="step">
                    <h3>استمتع بالقراءة المريحة</h3>
                    <p>استخدم الوضع الليلي للقراءة المريحة في أي وقت</p>
                </div>
            </div>
        </div>
        
        <div class="feature-section">
            <h2><i class="fas fa-code"></i> التقنيات المستخدمة</h2>
            <div style="text-align: center; margin: 20px 0;">
                <span class="tech-badge">HTML5</span>
                <span class="tech-badge">CSS3</span>
                <span class="tech-badge">JavaScript</span>
                <span class="tech-badge">API القرآن الكريم</span>
                <span class="tech-badge">تصميم متجاوب</span>
                <span class="tech-badge">LocalStorage</span>
                <span class="tech-badge">Font Awesome</span>
            </div>
            <p style="text-align: center; font-size: 1.1rem;">
                يستخدم المشغل API من <strong>AlQuran Cloud</strong> لعرض النص القرآني،<br>
                مع تصميم متجاوب يعمل على جميع الأجهزة والشاشات
            </p>
        </div>
        
        <div style="text-align: center; margin-top: 40px; padding-top: 30px; border-top: 2px solid #eee;">
            <h2 style="border: none; text-align: center;">ابدأ الآن</h2>
            <p style="font-size: 1.2rem; margin-bottom: 20px;">
                مشروع بسيط وأنيق لخدمة القرآن الكريم على الإنترنت
            </p>
            
            <div style="margin: 30px 0;">
                <a href="#" class="download-btn" onclick="copyCode()">
                    <i class="fas fa-download"></i> انسخ الكود للاستخدام
                </a>
            </div>
            
            <p style="color: #666; font-size: 0.9rem;">
                © 2023 مشغل القرآن الكريم - تم التطوير بكل ❤️ لخدمة القرآن الكريم
            </p>
        </div>
    </div>

    <script>
        function copyCode() {
            alert('يمكنك نسخ كود المشروع الكامل من الملفات السابقة في المحادثة');
            return false;
        }
        
        // إضافة تأثيرات بسيطة
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.feature-card');
            cards.forEach((card, index) => {
                card.style.animationDelay = `${index * 0.1}s`;
            });
        });
    </script>
</body>
</html>
