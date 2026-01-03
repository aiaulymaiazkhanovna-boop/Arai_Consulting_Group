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
            font-family: 'Inter', -apple-system, sans-serif;
            overflow-x: hidden; /* Телефонда шетке шығып кетпеу үшін */
        }

        /* Header Section - Логотипті төмен түсіру */
        .header-section {
            width: 100%;
            padding: 60px 20px 30px 20px; /* Жоғарғы жағын 60px-ке дейін арттырдық */
            text-align: center;
            background: radial-gradient(circle at center, #1c1c1c 0%, #0a0a0a 100%);
        }

        .logo-container {
            display: inline-block;
            width: 160px; /* Телефонға ыңғайлы өлшем */
            height: 160px;
            margin-bottom: 25px; /* Мәтінмен арасы */
        }

        .main-logo {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Фотоны қисайтпай толтырады */
            border-radius: 50%;
            border: 3px solid var(--gold);
            box-shadow: 0 10px 30px rgba(212, 175, 55, 0.3);
            background-color: #000;
        }

        .glitter-text {
            font-size: 1.6rem;
            background: linear-gradient(to right, #BF953F, #FCF6BA, #B38728);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .subtitle {
            color: var(--gold);
            font-size: 0.85rem;
            margin-top: 8px;
            letter-spacing: 2px;
            opacity: 0.9;
        }

        /* Прайс Бөлімі */
        .container {
            width: 100%;
            max-width: 480px;
            margin: 0 auto;
            padding: 15px;
        }

        .price-card {
            background: var(--card-bg);
            margin-bottom: 10px;
            padding: 16px 20px;
            border-radius: 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid #222;
            transition: 0.3s;
        }

        /* Телефонда басқанда сәл кішірейетін эффект */
        .price-card:active {
            transform: scale(0.97);
            border-color: var(--gold);
        }

        .service-info { display: flex; align-items: center; gap: 12px; }
        .service-info i { color: var(--gold); font-size: 1.1rem; }
        .service-name { font-size: 0.95rem; color: #eee; }
        .service-price { color: var(--gold); font-weight: 700; font-size: 1rem; }

        /* Батырмалар */
        .btns-group {
            display: grid;
            gap: 12px;
            margin-top: 25px;
            padding-bottom: 40px;
        }

        .btn {
            padding: 16px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: 700;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-size: 1rem;
        }

        .btn-wa { background: #25D366; color: white; }
        .btn-insta { background: linear-gradient(45deg, #f09433, #dc2743, #bc1888); color: white; }

        /* WhatsApp Floating */
        .wa-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            color: white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.4);
            z-index: 1000;
        }

        footer { text-align: center; padding: 20px; color: #333; font-size: 0.7rem; }
    </style>
</head>
<body>

    <header class="header-section">
        <div class="logo-container">
            <img src="11.jpeg" alt="Arai Consulting" class="main-logo" onerror="11.jpeg">
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

    <footer>&copy; 2026 ARAI CONSULTING. Барлық құқықтар қорғалған.</footer>

</body>
</html>
