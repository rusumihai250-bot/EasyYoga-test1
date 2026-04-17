<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EASY YOGA - Echilibru & Energie</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --teal: #1e8e8e;
            --dark: #004d4d;
            --light-bg: #f4fbfb;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            color: #333;
            background-color: #fff;
        }

        /* HEADER */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            background: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
            color: var(--teal);
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            margin-left: 15px;
            font-size: 14px;
        }

        /* HERO - Cu poza ta (Beatris) */
        .hero {
            height: 70vh;
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), 
                        url('poza1.jpg') center/cover no-repeat;
            display: flex;
            align-items: center;
            padding: 0 5%;
            color: #fff;
        }

        .hero-content { max-width: 500px; }
        .hero h1 { font-size: 40px; margin-bottom: 10px; line-height: 1.2; }
        .hero p { font-size: 18px; margin-bottom: 25px; opacity: 0.9; }

        .btn-main {
            padding: 12px 25px;
            background: var(--teal);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            display: inline-block;
        }

        /* BENEFICII */
        .section { padding: 60px 5%; text-align: center; }
        .section-tag { color: var(--teal); font-weight: bold; text-transform: uppercase; font-size: 12px; letter-spacing: 1px; }
        .section-title { font-size: 28px; color: var(--dark); margin: 10px 0 40px; }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .benefit-card i { font-size: 30px; color: var(--teal); margin-bottom: 15px; }
        .benefit-card h3 { font-size: 16px; margin-bottom: 10px; }
        .benefit-card p { font-size: 13px; color: #666; }

        /* GALERIE - Cu poza lui Mihai */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 50px;
        }

        .gallery-item {
            background: #fff;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            text-align: left;
        }

        .gallery-item img { width: 100%; height: 250px; object-fit: cover; }
        .gallery-text { padding: 20px; }
        .gallery-text h3 { margin: 0; font-size: 18px; color: var(--dark); }
        .gallery-text p { font-size: 14px; color: #777; margin-top: 5px; }

        /* CONTACT */
        .contact-section { background: var(--light-bg); padding: 60px 5%; text-align: center; }
        
        .social-links {
            display: flex;
            flex-direction: column;
            gap: 15px;
            max-width: 350px;
            margin: 30px auto 0;
        }

        .social-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 15px;
            border-radius: 12px;
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
        }

        .wa { background: #25D366; }
        .tk { background: #000; }
        .ig { background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888); }

        footer { background: var(--dark); color: white; text-align: center; padding: 20px; font-size: 13px; }

        @media (max-width: 600px) {
            .hero h1 { font-size: 32px; }
            nav { display: none; }
        }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">🌿 EASY YOGA</a>
    <nav>
        <a href="#beneficii">Beneficii</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Yoga & Echilibru</h1>
        <p>Liniște. Natură. Energie interioară pentru tine.</p>
        <a href="https://wa.me/37369404887" class="btn-main">Începe acum</a>
    </div>
</section>

<section id="beneficii" class="section">
    <p class="section-tag">Practica Yoga</p>
    <h2 class="section-title">Beneficii pentru corp și minte</h2>
    
    <div class="benefits-grid">
        <div class="benefit-card"><i class="fas fa-leaf"></i><h3>Stres redus</h3><p>Calmează mintea.</p></div>
        <div class="benefit-card"><i class="fas fa-child-reaching"></i><h3>Flexibilitate</h3><p>Corp mai mobil.</p></div>
        <div class="benefit-card"><i class="fas fa-spa"></i><h3>Energie</h3><p>Vitalitate zilnică.</p></div>
        <div class="benefit-card"><i class="fas fa-heart"></i><h3>Armonie</h3><p>Echilibru interior.</p></div>
    </div>

    <div class="gallery">
        <div class="gallery-item">
            <img src="poza1.jpg" alt="Beatris Yoga">
            <div class="gallery-text">
                <h3>Meditație ghidată</h3>
                <p>Găsește-ți liniștea interioară cu Beatris.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="poza2.jpg" alt="Mihai Yoga">
            <div class="gallery-text">
                <h3>Respirație & Control</h3>
                <p>Tehnici de respirație alături de Mihai.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="contact-section">
    <h2>Hai să ne conectăm</h2>
    <p>Urmărește-ne pentru noutăți sau programează o ședință.</p>
    
    <div class="social-links">
        <a href="https://wa.me/37369404887" class="social-btn wa"><i class="fab fa-whatsapp"></i> WhatsApp</a>
        <a href="https://www.tiktok.com/@easy_yoga33" class="social-btn tk"><i class="fab fa-tiktok"></i> TikTok</a>
        <a href="https://www.instagram.com/easy_yoga33" class="social-btn ig"><i class="fab fa-instagram"></i> Instagram</a>
    </div>
</section>

<footer>
    <p>© 2026 Easy Yoga Moldova. Namaste! 🙏</p>
</footer>

</body>
</html>
# EasyYoga-test1
