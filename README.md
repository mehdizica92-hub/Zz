# Zz
My Personal Website
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فروشگاه من - محصولات مستقل</title>
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
        }
        
        .header {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .product-card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
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
            font-size: 14px;
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
            font-size: 0.95em;
        }
        
        .product-price {
            font-size: 1.4em;
            font-weight: bold;
            color: #e74c3c;
            margin-bottom: 15px;
        }
        
        .contact-info {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin-top: 40px;
            text-align: center;
        }
        
        .whatsapp-btn {
            display: inline-block;
            background: #25D366;
            color: white;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>🛍️ فروشگاه مستقل من</h1>
        <p>خرید مستقیم با پشتیبانی شخصی</p>
    </div>

    <div class="container">
        <div class="products-grid">
            
            <!-- محصول ۱ -->
            <div class="product-card">
                <div class="product-image">
                    [عکس محصول ۱]
                </div>
                <div class="product-title">نام محصول اول</div>
                <div class="product-description">
                    توضیحات کامل محصول اول اینجا قرار می‌گیرد.
                    مشخصات فنی و ویژگی‌های خاص محصول.
                </div>
                <div class="product-price">۱,۲۹۰,۰۰۰ تومان</div>
                <div style="text-align: center;">
                    <a href="https://wa.me/98912XXXXXX?text=سلام، درباره محصول اول سوال دارم" class="whatsapp-btn">
                        📞 اطلاعات بیشتر
                    </a>
                </div>
            </div>

            <!-- محصول ۲ -->
            <div class="product-card">
                <div class="product-image">
                    [عکس محصول ۲]
                </div>
                <div class="product-title">نام محصول دوم</div>
                <div class="product-description">
                    توضیحات کامل محصول دوم اینجا قرار می‌گیرد.
                    مشخصات فنی و ویژگی‌های خاص محصول.
                </div>
                <div class="product-price">۹۸۰,۰۰۰ تومان</div>
                <div style="text-align: center;">
                    <a href="https://wa.me/98912XXXXXX?text=سلام، درباره محصول دوم سوال دارم" class="whatsapp-btn">
                        📞 اطلاعات بیشتر
                    </a>
                </div>
            </div>

            <!-- محصول ۳ -->
            <div class="product-card">
                <div class="product-image">
                    [عکس محصول ۳]
                </div>
                <div class="product-title">نام محصول سوم</div>
                <div class="product-description">
                    توضیحات کامل محصول سوم اینجا قرار می‌گیرد.
                    مشخصات فنی و ویژگی‌های خاص محصول.
                </div>
                <div class="product-price">۲,۴۵۰,۰۰۰ تومان</div>
                <div style="text-align: center;">
                    <a href="https://wa.me/98912XXXXXX?text=سلام، درباره محصول سوم سوال دارم" class="whatsapp-btn">
                        📞 اطلاعات بیشتر
                    </a>
                </div>
            </div>

        </div>

        <div class="contact-info">
            <h2>📞 راه‌های ارتباطی</h2>
            <p>برای خرید و اطلاعات بیشتر با ما در تماس باشید:</p>
            <p><strong>واتساپ:</strong> ۰۹۱۲XXXXXX</p>
            <p><strong>تلفن:</strong> ۰۲۱XXXXXXX</p>
            <a href="https://wa.me/98912XXXXXX" class="whatsapp-btn">
                💬 ارتباط از طریق واتساپ
            </a>
        </div>
    </div>
</body>
</html>
