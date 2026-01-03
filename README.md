<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Arai Consulting | Арест шешу</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --gold: #D4AF37;
            --black: #0a0a0a;
            --card-bg: #161616;
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background-color: var(--black);
            color: var(--white);
            font-family: 'Inter', sans-serif;
            overflow-x: hidden;
        }

        /* БАННЕРДІ (ФОНДЫ) ТӨМЕН ТҮСІРУ */
        .header-section {
            width: 100%;
            /* Жоғарғы бос орынды (padding-top) көбейттік, баннер төмен түсті */
            padding: 80px 20px 40px 20px; 
            text-align: center;
            background: radial-gradient(circle at center, #1c1c1c 0%, #0a0a0a 100%);
            border-bottom: 1px solid #222;
        }

        /* ЛОГОТИП СТИЛІ */
        .logo-container {
            display: inline-block;
            width: 180px;
            height: 180px;
            margin-bottom: 25px;
            position: relative;
        }

        .main-logo {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Фото созылып кетпеуі үшін */
            border-radius: 50%;
            border: 4px solid var(--gold);
            box-shadow: 0 10px 30px rgba(212, 175, 55, 0.4);
        }

        .glitter-text {
            font-size: 1.8rem;
            background: linear-gradient(to right, #BF953F, #FCF6BA, #B38728);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
            text-transform: uppercase;
        }

        .subtitle {
            color: var(--gold);
            font-size: 0.9rem;
            margin-top: 10px;
            letter-spacing: 2px;
            font-weight: 600;
        }

        /* ПРАЙС БӨЛІМІ */
        .container {
            width: 100%;
            max-width: 480px;
            margin: 0 auto;
            padding: 20px 15px;
        }

        .price-card {
            background: var(--card-bg);
            margin-bottom: 12px;
            padding: 18px;
            border-radius: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid #222;
            transition: 0.3s;
        }

        .price-card:hover {
            border-color: var(--gold);
            transform: translateY(-2px);
        }

        .service-info { display: flex; align-items: center; gap: 12px; }
        .service-info i { color: var(--gold); font-size: 1.2rem; }
        .service-name { font-size: 1rem; color: #ddd; }
        .service-price { color: var(--gold); font-weight: 700; }

        /* БАТЫРМАЛАР */
        .btns-group {
            display: grid;
            gap: 15px;
            margin-top: 30px;
        }

        .btn {
            padding: 18px;
            border-radius: 15px;
            text-decoration: none;
            font-weight: 700;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-wa { background: #25D366; color: white; }
        .btn-insta { background: linear-gradient(45deg, #f09433, #dc2743, #bc1888); color: white; }

        /* WHATSAPP FLOAT */
        .wa-float {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background: #25D366;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            color: white;
            box-shadow: 0 5px 20px rgba(0,0,0,0.5);
        }
    </style>
</head>
<body>

    <header class="header-section">
        <div class="logo-container">
            <img src="logo.png" alt="Arai Consulting" class="main-logo" onerror="this.src='https://i.ibb.co/Xz9kH0h/image.png'">
        </div>
        <h1 class="glitter-text">Arai Consulting</h1>
        <p class="subtitle">МЕН АРЕСТТЕРДІ ШЕШЕМІН</p>
    </header>

    <div class="container">
        <div class="price-list">
            <div class="price-card"><div class="service-info"><i class="fas fa-file-invoice"></i><span class="service-name">Нотариальный</span></div><span class="service-price">5 000 ₸</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-gavel"></i><span class="service-name">Сот</span></div><span class="service-price">15 000 ₸</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-university"></i><span class="service-name">Банкроттыққа</span></div><span class="service-price">20 000 ₸+</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-bolt"></i><span class="service-name">Ускоренный</span></div><span class="service-price">10 000 ₸+</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-laptop"></i><span class="service-name">Егов</span></div><span class="service-price">1 000 ₸+</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-car-crash"></i><span class="service-name">Страховка</span></div><span class="service-price">10%</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-chart-line"></i><span class="service-name">Рейтинг көтеру</span></div><span class="service-price">20 000 ₸</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-baby"></i><span class="service-name">Алимент</span></div><span class="service-price">10 000 ₸</span></div>
            <div class="price-card"><div class="service-info"><i class="fas fa-user-shield"></i><span class="service-name">Жұмыссыздық</span></div><span class="service-price">7 000 ₸</span></div>
        </div>

        <div class="btns-group">
            <a href="https://wa.me/77716574345" class="btn btn-wa"><i class="fab fa-whatsapp"></i> WhatsApp-қа жазу</a>
            <a href="https://www.instagram.com/arai_aueskhanovna?igsh=dzVnenAwZDA1ZHRt" target="_blank" class="btn btn-insta"><i class="fab fa-instagram"></i> Instagram</a>
        </div>
    </div>

    <a href="https://wa.me/77716574345" class="wa-float"><i class="fab fa-whatsapp"></i></a>

</body>
</html>
