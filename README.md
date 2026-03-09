<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
 ضيف للتوريدات الكهربائية و المقاولات </title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #003366; /* أزرق مؤسسي */
            --secondary: #25d366; /* أخضر واتساب */
            --light: #f8f9fa;
            --dark: #1a1a1a;
        }

        body {
            font-family: 'Cairo', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: var(--dark);
        }

        header {
            background: linear-gradient(135deg, var(--primary), #0055aa);
            color: white;
            padding: 50px 20px;
            text-align: center;
            border-bottom: 5px solid var(--secondary);
        }

        header h1 { margin: 0; font-size: 2.5rem; }
        header p { font-size: 1.2rem; opacity: 0.9; }

        .services-title {
            text-align: center;
            margin-top: 40px;
            font-size: 1.8rem;
            color: var(--primary);
        }

        .container {
            max-width: 1100px;
            margin: 30px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            transition: 0.3s;
            border: 1px solid #eee;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }

        .card h3 { color: var(--primary); font-size: 1.5rem; }
        
        .card p { color: #666; line-height: 1.6; }

        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: var(--secondary);
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 20px;
            transition: 0.3s;
        }

        .btn-whatsapp:hover {
            background-color: #128c7e;
            transform: scale(1.05);
        }

        .info-section {
            background: white;
            padding: 40px 20px;
            text-align: center;
            margin-top: 50px;
        }

        footer {
            background: var(--dark);
            color: white;
            padding: 30px;
            text-align: center;
        }

        @media (max-width: 600px) {
            header h1 { font-size: 1.8rem; }
            .container { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

<header>
    <h1>مؤسسة ضيف للتوريدات الكهربائية</h1>
    <p>شريككم الموثوق في العاشر من رمضان لجميع مستلزمات الكهرباء</p>
</header>

<h2 class="services-title">منتجاتنا الرئيسية</h2>

<div class="container">
    <div class="card">
        <h3>كابلات السويدي</h3>
        <p>توريد جميع أنواع كابلات النحاس والألومنيوم المعتمدة بأفضل الأسعار للمقاولات والمنازل.</p>
        <a href="https://wa.me/201234567890" class="btn-whatsapp">طلب عرض سعر (واتساب)</a>
    </div>

    <div class="card">
        <h3>منتجات شنايدر</h3>
        <p>قواطع تيار، مفاتيح، ولوحات توزيع أصلية لضمان أقصى درجات الأمان والتحمل.</p>
        <a href="https://wa.me/201033318799" class="btn-whatsapp">استفسر الآن</a>
    </div>

    <div class="card">
        <h3>إضاءة وإيجي لايت</h3>
        <p>كشافات LED موفرة للطاقة، نجف، وتجهيزات إضاءة للمصانع والوحدات السكنية.</p>
        <a href="https://wa.me/201234567890" class="btn-whatsapp">شاهد الكتالوج</a>
    </div>
</div>

<div class="info-section">
    <h2>لماذا تختار مؤسسة ضيف؟</h2>
    <p>نحن نوفر المنتجات الأصلية فقط من المصنع إليك مباشرة بأسعار منافسة داخل مدينة العاشر من رمضان.</p>
</div>

<footer>
    <p>جميع الحقوق محفوظة &copy; 2026</p>
    <p style="font-size: 0.8rem; opacity: 0.7;">تم التصميم والبرمجة بواسطة:  أحمد حسام</p>
</footer>

</body>
</html>
