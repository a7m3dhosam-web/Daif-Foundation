<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مؤسسة ضيف للتوريدات الكهربائية</title>
    <style>
        /* الأساسيات */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
        }

        /* الهيدر (رأس الصفحة) */
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        /* حاوية المنتجات */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 15px;
            display: grid;
            /* هنا السحر: بيقسم الشاشة أعمدة حسب المساحة */
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        /* كارت المنتج */
        .product-card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-card h3 {
            color: #003366;
            margin-bottom: 10px;
        }

        /* زرار الطلب */
        .order-btn {
            display: inline-block;
            background-color: #25d366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 15px;
        }

        /* فوتر (تذييل الصفحة) */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }

        /* الجزء الخاص بالموبايل (Responsive) */
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.5rem;
            }
            .container {
                grid-template-columns: 1fr; /* يخلي المنتجات تحت بعض بالظبط */
            }
        }
    </style>
</head>
<body>

<header>
    <h1>مؤسسة ضيف للتوريدات الكهربائية</h1>
    <p>أجود أنواع الكابلات والمفاتيح الكهربائية في العاشر من رمضان</p>
</header>

<div class="container">
    <div class="product-card">
        <h3>كابلات السويدي</h3>
        <p>جميع المقاسات والأحمال بأعلى جودة نحاس.</p>
        <a href="#" class="order-btn">اطلب عبر واتساب</a>
    </div>

    <div class="product-card">
        <h3>مفاتيح شنايدر</h3>
        <p>أمان وحماية كاملة لمنزلك أو مصنعك.</p>
        <a href="#" class="order-btn">اطلب عبر واتساب</a>
    </div>

    <div class="product-card">
        <h3>كشافات إيجي لايت</h3>
        <p>توفير طاقة وإضاءة قوية تدوم طويلاً.</p>
        <a href="#" class="order-btn">اطلب عبر واتساب</a>
    </div>
</div>

<footer>
    <p>تم التطوير بواسطة أحمد حسام &copy; 2026</p>
</footer>

</body>
</html>
