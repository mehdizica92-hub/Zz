<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فروشگاه من</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .header {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .product-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .product-image {
            width: 100%;
            height: 200px;
            background: #f8f9fa;
            border-radius: 10px;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #666;
        }
        
        .product-title {
            font-size: 1.3em;
            font-weight: bold;
            margin-bottom: 10px;
            color: #333;
        }
        
        .product-description {
            color: #666;
            margin-bottom: 15px;
        }
        
        .product-price {
            font-size: 1.4em;
            font-weight: bold;
            color: #e74c3c;
            margin-bottom: 15px;
        }
        
        .contact-info {
            background: white;
            border-radius: 10px;
            padding: 20px;
            margin-top: 30px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>فروشگاه من</h1>
        <p>به فروشگاه ما خوش آمدید</p>
    </div>

    <div class="container">
        <div class="products-grid">
            <!-- محصول ۱ -->
            <div class="product-card">
                <div class="product-image">[عکس محصول ۱]</div>
                <div class="product-title">نام محصول اول</div>
                <div class="product-description">توضیحات محصول اول</div>
                <div class="product-price">۱۰۰,۰۰۰ تومان</div>
            </div>
            
            <!-- محصول ۲ -->
            <div class="product-card">
                <div class="product-image">[عکس محصول ۲]</div>
                <div class="product-title">نام محصول دوم</div>
                <div class="product-description">توضیحات محصول دوم</div>
                <div class="product-price">۲۰۰,۰۰۰ تومان</div>
            </div>
        </div>

        <div class="contact-info">
            <h2>تماس با ما</h2>
            <p>شماره تماس: ۰۹۱۲XXXXXX</p>
        </div>
    </div>
</body>
</html>
