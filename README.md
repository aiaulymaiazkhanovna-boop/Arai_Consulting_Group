<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arai Aueskhanovna | Lex Financia</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --gold: #D4AF37;
            --black: #0d0d0d;
            --gray: #1a1a1a;
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background-color: var(--black);
            color: var(--white);
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
        }

        /* Hero Section */
        .hero {
            padding: 50px 20px;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1589829545856-d10d557cf95f?q=80&w=1000');
            background-size: cover;
            border-bottom: 2px solid var(--gold);
        }

        .main-logo {
            width: 200px;
            height: auto;
            border-radius: 50%;
            border: 3px solid var(--gold);
            margin-bottom: 20px;
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.4);
        }

        .glitter-text {
            font-size: 2rem;
            background: linear-gradient(45deg, #BF953F, #FCF6BA, #B38728);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: bold;
            text-transform: uppercase;
        }

        /* Прайс-лист */
        .container {
            max-width: 500px;
            margin: 20px auto;
            padding: 10px;
        }

        .price-card {
            background: var(--gray);
            margin-bottom: 12px;
            padding: 18px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid #333;
            transition: 0.3s;
        }

        .price-card:hover {
            border-color: var(--gold);
            transform: scale(1.02);
        }

        .service-info { display: flex; align-items: center; gap: 12px; }
        .service-info i { color: var(--gold); font-size: 1.1rem; }
        .service-name { font-size: 0.95rem; font-weight: 500; }
        .service-price { color: var(--gold); font-weight: bold; }

        /* Батырмалар */
        .btn-box {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 30px;
        }

        .btn {
            width: 100%;
            padding: 18px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            font-size: 1rem;
            transition: 0.3s;
        }

        .btn-wa { background: #25D366; color: white; }
        .btn-insta { background: linear-gradient(45deg, #f09433, #dc2743, #bc1888); color: white; }

        /* Floating Button */
        .wa-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            color: white;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
            z-index: 1000;
        }

        footer { text-align: center; padding: 40px; color: #444; font-size: 0.8rem; }
    </style>
</head>
<body>

    <section class="hero">
        <img src="https://i.ibb.co/Xz9kH0h/image.png" alt="Arai Logo" class="main-logo">
        <h1 class="glitter-text">ARAI AUESKHANOVNA</h1>
        <p style="color: #aaa; margin-top: 5px;">Тәжірибелі заңгер көмегі</p>
    </section>

    <div class="container">
        <div class="price-card">
            <div class="service-info"><i class="fas fa-file-contract"></i> <span class="service-name">Нотариальный</span></div>
            <span class="service-price">5 000 ₸</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-gavel"></i> <span class="service-name">Сот</span></div>
            <span class="service-price">15 000 ₸</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-university"></i> <span class="service-name">Банкроттыққа</span></div>
            <span class="service-price">20 000 ₸+</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-bolt"></i> <span class="service-name">Ускоренный</span></div>
            <span class="service-price">10 000 ₸+</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-globe"></i> <span class="service-name">Егов</span></div>
            <span class="service-price">1 000 ₸+</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-car-crash"></i> <span class="service-name">Страховка</span></div>
            <span class="service-price">10%</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-star"></i> <span class="service-name">Рейтинг көтеру</span></div>
            <span class="service-price">20 000 ₸</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-baby"></i> <span class="service-name">Алимент</span></div>
            <span class="service-price">10 000 ₸</span>
        </div>
        <div class="price-card">
            <div class="service-info"><i class="fas fa-user-slash"></i> <span class="service-name">Жұмыссыздық</span></div>
            <span class="service-price">7 000 ₸</span>
        </div>

        <div class="btn-box">
            <a href="https://wa.me/77716574345" class="btn btn-wa">
                <i class="fab fa-whatsapp"></i> WhatsApp-қа жазу
            </a>
            <a href="https://www.instagram.com/arai_aueskhanovna?igsh=dzVnenAwZDA1ZHRt" class="btn btn-insta" target="_blank">
                <i class="fab fa-instagram"></i> Instagram парақша
            </a>
        </div>
    </div>

    <a href="https://wa.me/77716574345" class="wa-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <footer>
        &copy; 2026 LEX FINANCIA. Барлық құқықтар қорғалған.
    </footer>

</body>
</html>
