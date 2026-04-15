<!DOCTYPE html>
<html lang="pt-BR">
<head>
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-17709030845"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'AW-17709030845');
</script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="WILLSU - Envelopamento e restauração de geladeira, fogão, bancada, pia, granito e tampo de vidro. Usamos adesivos automotivos profissionais de alta durabilidade. Recuperamos amassados, ferrugem e buracos antes do envelopamento. Deixamos tudo novo sem obra. Parcelamos em até 12x.">
<title>WILLSU | Envelopamento e Restauração - Adesivos profissionais automotivos</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
    /* CSS ORIGINAL - TOTALMENTE PRESERVADO */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    :root {
        --primary: #1a365d;
        --secondary: #2d74da;
        --accent: #e53e3e;
        --whatsapp: #25D366;
        --light: #f7fafc;
        --dark: #2d3748;
        --success: #38a169;
        --gray: #718096;
        --shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
        --shadow-hover: 0 20px 40px rgba(0, 0, 0, 0.15);
        --radius: 16px;
        --transition: all 0.3s ease;
    }

    body {
        font-family: 'Segoe UI', 'Inter', system-ui, -apple-system, sans-serif;
        line-height: 1.6;
        color: var(--dark);
        background-color: var(--light);
        overflow-x: hidden;
        scroll-behavior: smooth;
    }

    .container {
        width: 100%;
        max-width: 1280px;
        margin: 0 auto;
        padding: 0 20px;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }

    @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.05); }
        100% { transform: scale(1); }
    }

    @keyframes slideIn {
        from { transform: translateX(-100%); }
        to { transform: translateX(0); }
    }

    header {
        background: rgba(26, 54, 93, 0.95);
        color: white;
        padding: 1rem 0;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        z-index: 1000;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(10px);
        animation: slideIn 0.5s ease-out;
    }

    .header-content {
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: relative;
    }

    .logo {
        font-size: 2rem;
        font-weight: 800;
        color: white;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .logo span {
        color: var(--secondary);
        position: relative;
    }

    .logo span::after {
        content: '';
        position: absolute;
        bottom: -2px;
        left: 0;
        width: 100%;
        height: 3px;
        background: linear-gradient(90deg, var(--secondary), var(--accent));
        border-radius: 2px;
    }

    .mobile-menu {
        font-size: 1.8rem;
        cursor: pointer;
        color: white;
        display: none;
        padding: 10px;
        border-radius: 8px;
        transition: var(--transition);
    }

    .mobile-menu:hover {
        background: rgba(255, 255, 255, 0.1);
    }

    .nav-links {
        display: flex;
        gap: 2rem;
        align-items: center;
    }

    .nav-links a {
        color: white;
        text-decoration: none;
        font-weight: 500;
        font-size: 1.1rem;
        padding: 8px 16px;
        border-radius: 8px;
        transition: var(--transition);
        position: relative;
    }

    .nav-links a:hover {
        background: rgba(255, 255, 255, 0.1);
        transform: translateY(-2px);
    }

    .nav-links a::after {
        content: '';
        position: absolute;
        bottom: 0;
        left: 50%;
        width: 0;
        height: 2px;
        background: var(--secondary);
        transition: all 0.3s ease;
        transform: translateX(-50%);
    }

    .nav-links a:hover::after {
        width: 80%;
    }

    .hero {
        background: linear-gradient(135deg, var(--primary) 0%, #2c5282 100%);
        color: white;
        padding: 180px 0 100px;
        text-align: center;
        position: relative;
        overflow: hidden;
    }

    .hero::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg width="60" height="60" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path fill="rgba(255,255,255,0.02)" d="M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z"/></g></svg>');
        animation: moveBackground 20s linear infinite;
    }

    @keyframes moveBackground {
        0% { transform: translate(0, 0); }
        100% { transform: translate(60px, 60px); }
    }

    .hero-content {
        max-width: 900px;
        margin: 0 auto;
        position: relative;
        z-index: 1;
        animation: fadeIn 1s ease-out;
    }

    .hero h1 {
        font-size: 3.5rem;
        margin-bottom: 1.5rem;
        line-height: 1.2;
        font-weight: 800;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        color: white;
    }

    .hero-subtitle {
        font-size: 1.5rem;
        margin-bottom: 2.5rem;
        opacity: 0.9;
        font-weight: 300;
        max-width: 700px;
        margin-left: auto;
        margin-right: auto;
        color: white;
    }

    /* BOTÃO DE AVALIAÇÕES */
    .btn-reviews {
        display: inline-flex;
        align-items: center;
        justify-content: center;
        gap: 12px;
        background: rgba(255, 255, 255, 0.2);
        backdrop-filter: blur(10px);
        color: white;
        padding: 12px 28px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 600;
        font-size: 1rem;
        transition: var(--transition);
        border: 1px solid rgba(255, 255, 255, 0.3);
        cursor: pointer;
    }

    .btn-reviews:hover {
        background: rgba(255, 255, 255, 0.35);
        transform: translateY(-3px);
        border-color: rgba(255, 255, 255, 0.6);
    }

    .btn-reviews i {
        font-size: 1.1rem;
    }

    .reviews-highlight {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 8px;
        margin: 2rem 0 1.5rem 0;
    }

    .reviews-highlight span:first-child {
        font-size: 0.9rem;
        opacity: 0.9;
        letter-spacing: 1px;
    }

    .reviews-highlight span:last-child {
        font-size: 0.85rem;
        opacity: 0.8;
    }

    .btn-whatsapp-hero {
        display: inline-flex;
        align-items: center;
        justify-content: center;
        gap: 12px;
        background: linear-gradient(135deg, var(--whatsapp) 0%, #1da851 100%);
        color: white;
        padding: 20px 45px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 700;
        font-size: 1.3rem;
        transition: var(--transition);
        box-shadow: 0 10px 30px rgba(37, 211, 102, 0.3);
        border: none;
        cursor: pointer;
        animation: pulse 2s infinite;
    }

    .btn-whatsapp-hero:hover {
        transform: translateY(-5px) scale(1.05);
        box-shadow: 0 15px 40px rgba(37, 211, 102, 0.4);
    }

    .btn-disclaimer {
        margin-top: 1rem;
        font-size: 0.9rem;
        opacity: 0.8;
        color: rgba(255, 255, 255, 0.8);
        max-width: 500px;
        margin-left: auto;
        margin-right: auto;
    }

    section {
        padding: 100px 0;
        animation: fadeIn 0.8s ease-out;
    }

    .section-title {
        text-align: center;
        margin-bottom: 4rem;
        position: relative;
    }

    .section-title h2 {
        font-size: 2.8rem;
        color: var(--primary);
        margin-bottom: 1rem;
        font-weight: 800;
        position: relative;
        display: inline-block;
    }

    .section-title h2::after {
        content: '';
        position: absolute;
        bottom: -10px;
        left: 50%;
        transform: translateX(-50%);
        width: 80px;
        height: 4px;
        background: linear-gradient(90deg, var(--secondary), var(--accent));
        border-radius: 2px;
    }

    .section-title p {
        color: var(--gray);
        font-size: 1.2rem;
        max-width: 600px;
        margin: 1rem auto 0;
    }

    .highlight-text {
        font-weight: 800;
        color: var(--secondary);
        background: rgba(45, 116, 218, 0.1);
        display: inline-block;
        padding: 5px 15px;
        border-radius: 30px;
    }

    .quality-badge {
        background: linear-gradient(135deg, var(--primary), var(--secondary));
        color: white;
        padding: 15px 25px;
        border-radius: 50px;
        display: inline-flex;
        align-items: center;
        gap: 15px;
        flex-wrap: wrap;
        justify-content: center;
        margin-bottom: 2rem;
        box-shadow: var(--shadow);
    }

    .quality-badge span {
        display: inline-flex;
        align-items: center;
        gap: 8px;
        font-size: 0.9rem;
        font-weight: 500;
    }

    .quality-badge i {
        font-size: 1.2rem;
    }

    .services-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
        margin-top: 2rem;
    }

    .service-card {
        background: white;
        border-radius: var(--radius);
        padding: 2.5rem;
        box-shadow: var(--shadow);
        transition: var(--transition);
        border: 1px solid rgba(0, 0, 0, 0.05);
        position: relative;
        overflow: hidden;
    }

    .service-card::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 5px;
        height: 100%;
        background: linear-gradient(to bottom, var(--secondary), var(--accent));
    }

    .service-card:hover {
        transform: translateY(-10px);
        box-shadow: var(--shadow-hover);
    }

    .service-icon {
        background: linear-gradient(135deg, var(--secondary), var(--accent));
        color: white;
        width: 70px;
        height: 70px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 1.8rem;
        margin-bottom: 1.5rem;
        box-shadow: 0 10px 20px rgba(45, 116, 218, 0.2);
    }

    .service-content h3 {
        color: var(--primary);
        margin-bottom: 1.2rem;
        font-size: 1.6rem;
        font-weight: 700;
    }

    .service-content ul {
        list-style: none;
    }

    .service-content li {
        margin-bottom: 0.8rem;
        padding-left: 1.8rem;
        position: relative;
        color: var(--dark);
    }

    .service-content li::before {
        content: '✓';
        position: absolute;
        left: 0;
        color: var(--success);
        font-weight: bold;
        font-size: 1.2rem;
    }

    .payment-info {
        margin-top: 1.5rem;
        padding-top: 1.5rem;
        border-top: 2px solid rgba(0, 0, 0, 0.05);
        text-align: center;
        font-size: 0.9rem;
        color: var(--gray);
    }

    .testimonials-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2rem;
    }

    .testimonial-card {
        background: white;
        border-radius: var(--radius);
        padding: 2rem;
        box-shadow: var(--shadow);
        position: relative;
        transition: var(--transition);
    }

    .testimonial-card:hover {
        transform: translateY(-5px);
        box-shadow: var(--shadow-hover);
    }

    .testimonial-card::before {
        content: '"';
        font-size: 5rem;
        color: var(--secondary);
        position: absolute;
        top: -20px;
        left: 20px;
        opacity: 0.2;
        font-family: serif;
    }

    .testimonial-text {
        font-style: italic;
        margin-bottom: 1.5rem;
        padding-left: 1rem;
        color: var(--dark);
        line-height: 1.8;
        font-size: 1.1rem;
    }

    .testimonial-author {
        font-weight: 700;
        color: var(--primary);
        text-align: right;
        font-size: 1.1rem;
    }

    .testimonial-rating {
        color: #ffc107;
        margin-bottom: 1rem;
    }

    .projects-section {
        background: linear-gradient(135deg, #f0f9ff 0%, #e6f4ff 100%);
    }

    .project-highlight {
        background: white;
        border-radius: var(--radius);
        padding: 2.5rem;
        margin-bottom: 2rem;
        box-shadow: var(--shadow);
        border-left: 5px solid var(--secondary);
    }

    .project-highlight h3 {
        color: var(--primary);
        margin-bottom: 1rem;
        font-size: 1.8rem;
    }

    .partnership-section {
        background: linear-gradient(135deg, #f8fafc 0%, #edf2f7 100%);
    }

    .partnership-card {
        background: white;
        border-radius: var(--radius);
        padding: 2.5rem;
        box-shadow: var(--shadow);
        transition: var(--transition);
        border: 2px solid transparent;
    }

    .partnership-card:hover {
        border-color: var(--secondary);
        transform: translateY(-5px);
    }

    .partnership-list {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 1rem;
        margin: 2rem 0;
    }

    .partner-item {
        background: rgba(26, 54, 93, 0.05);
        padding: 1rem;
        border-radius: 8px;
        text-align: center;
        font-weight: 500;
        transition: var(--transition);
    }

    .partner-item:hover {
        background: rgba(26, 54, 93, 0.1);
        transform: translateY(-2px);
    }

    .btn-partnership {
        display: inline-flex;
        align-items: center;
        gap: 10px;
        background: linear-gradient(135deg, var(--primary) 0%, #2c5282 100%);
        color: white;
        padding: 15px 30px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 600;
        font-size: 1.1rem;
        transition: var(--transition);
        margin-top: 1rem;
    }

    .btn-partnership:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 20px rgba(26, 54, 93, 0.2);
    }

    .cta {
        background: linear-gradient(135deg, var(--primary) 0%, #2c5282 100%);
        color: white;
        text-align: center;
        padding: 100px 20px;
        position: relative;
        overflow: hidden;
    }

    .cta::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg width="60" height="60" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path fill="rgba(255,255,255,0.05)" d="M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z"/></g></svg>');
    }

    .cta-content {
        position: relative;
        z-index: 1;
        max-width: 800px;
        margin: 0 auto;
    }

    .cta h2 {
        font-size: 3rem;
        margin-bottom: 1.5rem;
        font-weight: 800;
    }

    .cta p {
        font-size: 1.3rem;
        margin-bottom: 3rem;
        opacity: 0.9;
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
    }

    .btn-whatsapp-cta {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        background: linear-gradient(135deg, var(--whatsapp) 0%, #1da851 100%);
        color: white;
        padding: 20px 45px;
        border-radius: 50px;
        text-decoration: none;
        font-weight: 700;
        font-size: 1.3rem;
        transition: var(--transition);
        box-shadow: 0 10px 30px rgba(37, 211, 102, 0.3);
        animation: pulse 2s infinite;
    }

    .btn-whatsapp-cta:hover {
        transform: translateY(-5px) scale(1.05);
        box-shadow: 0 15px 40px rgba(37, 211, 102, 0.4);
    }

    footer {
        background: var(--dark);
        color: white;
        padding: 80px 0 30px;
    }

    .footer-content {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 3rem;
        margin-bottom: 3rem;
    }

    .footer-column h3 {
        color: var(--secondary);
        margin-bottom: 1.5rem;
        font-size: 1.5rem;
        font-weight: 700;
        position: relative;
        padding-bottom: 10px;
    }

    .footer-column h3::after {
        content: '';
        position: absolute;
        bottom: 0;
        left: 0;
        width: 50px;
        height: 3px;
        background: var(--secondary);
        border-radius: 2px;
    }

    .footer-column ul {
        list-style: none;
    }

    .footer-column li {
        margin-bottom: 1rem;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .footer-column a {
        color: #cbd5e0;
        text-decoration: none;
        transition: var(--transition);
        font-size: 1.1rem;
    }

    .footer-column a:hover {
        color: var(--secondary);
        transform: translateX(5px);
    }

    .social-icons {
        display: flex;
        gap: 1rem;
        margin-top: 1.5rem;
    }

    .social-icons a {
        display: inline-flex;
        align-items: center;
        justify-content: center;
        width: 45px;
        height: 45px;
        background: rgba(255, 255, 255, 0.1);
        border-radius: 50%;
        color: white;
        font-size: 1.2rem;
        transition: var(--transition);
    }

    .social-icons a:hover {
        background: var(--secondary);
        transform: translateY(-3px);
    }

    .copyright {
        text-align: center;
        padding-top: 2rem;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
        font-size: 1rem;
        color: #a0aec0;
    }

    .whatsapp-float {
        position: fixed;
        bottom: 30px;
        right: 30px;
        width: 70px;
        height: 70px;
        background: linear-gradient(135deg, var(--whatsapp) 0%, #1da851 100%);
        color: white;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 2rem;
        box-shadow: 0 10px 30px rgba(37, 211, 102, 0.4);
        z-index: 1000;
        text-decoration: none;
        animation: pulse 2s infinite;
        transition: var(--transition);
    }

    .whatsapp-float:hover {
        transform: scale(1.1) rotate(10deg);
        box-shadow: 0 15px 40px rgba(37, 211, 102, 0.5);
    }

    .whatsapp-badge {
        position: absolute;
        top: -5px;
        right: -5px;
        background: var(--accent);
        color: white;
        font-size: 0.8rem;
        padding: 5px 10px;
        border-radius: 20px;
        font-weight: bold;
        animation: pulse 1.5s infinite;
    }

    @media (max-width: 1024px) {
        .hero h1 { font-size: 3.2rem; }
        .hero-subtitle { font-size: 1.4rem; }
        .section-title h2 { font-size: 2.5rem; }
        .quality-badge { padding: 12px 20px; }
        .quality-badge span { font-size: 0.8rem; }
    }

    @media (max-width: 768px) {
        .mobile-menu { display: block; }
        .nav-links {
            position: fixed;
            top: 70px;
            left: 0;
            right: 0;
            background: var(--primary);
            flex-direction: column;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transform: translateY(-100%);
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            border-radius: 0 0 20px 20px;
            z-index: 999;
        }
        .nav-links.active {
            transform: translateY(0);
            opacity: 1;
            visibility: visible;
        }
        .hero { padding: 140px 0 80px; }
        .hero h1 { font-size: 2.8rem; }
        .hero-subtitle { font-size: 1.3rem; }
        section { padding: 70px 0; }
        .section-title h2 { font-size: 2.2rem; }
        .services-grid { grid-template-columns: 1fr; }
        .btn-whatsapp-hero, .btn-whatsapp-cta { padding: 18px 35px; font-size: 1.2rem; }
        .cta h2 { font-size: 2.5rem; }
        .whatsapp-float { width: 60px; height: 60px; font-size: 1.8rem; bottom: 20px; right: 20px; }
        .quality-badge { flex-direction: column; gap: 8px; text-align: center; }
    }

    @media (max-width: 480px) {
        .hero h1 { font-size: 2.2rem; }
        .hero-subtitle { font-size: 1.1rem; }
        .section-title h2 { font-size: 1.8rem; }
        .service-card { padding: 1.5rem; }
        .btn-whatsapp-hero, .btn-whatsapp-cta { width: 100%; max-width: 300px; font-size: 0.9rem; padding: 15px 20px; white-space: normal; line-height: 1.3; }
        .whatsapp-float { width: 55px; height: 55px; font-size: 1.6rem; bottom: 15px; right: 15px; }
        .btn-reviews { font-size: 0.85rem; padding: 10px 20px; }
    }
</style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="#" class="logo">WILL<span>SU</span></a>
            <div class="mobile-menu" id="mobileMenu">
                <i class="fas fa-bars"></i>
            </div>
            <nav class="nav-links" id="navLinks">
                <a href="#servicos">Serviços</a>
                <a href="#ambientes">Ambientes</a>
                <a href="#parcerias">Parcerias</a>
                <a href="#depoimentos">Depoimentos</a>
                <a href="#contato">Contato</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div style="font-size: 2rem; margin-bottom: 1rem; font-weight: 800; letter-spacing: 2px; color: white;">
                    ENVELOPAMENTO E RESTAURAÇÃO
                </div>
                
                <h1>Deixamos sua geladeira, fogão, móveis, cozinha e ambientes como novos! Sem obra, sem bagunça.</h1>
                
                <p class="hero-subtitle" style="font-size: 1.3rem;">
                    Chega de gastar rios de dinheiro trocando tudo. A gente renova seus eletrodomésticos, móveis e ambientes com qualidade e garantia. Parcelamos no cartão.
                </p>
                
                <!-- BOTÃO DE AVALIAÇÕES - LOGO ACIMA DO BOTÃO WHATSAPP -->
                <div class="reviews-highlight">
                    <span><i class="fas fa-users"></i> Milhares de clientes satisfeitos</span>
                    <a href="https://www.facebook.com/share/p/14XBiswwUDp/" target="_blank" class="btn-reviews" rel="noopener noreferrer">
                        <i class="fab fa-facebook"></i> VER AVALIAÇÕES REAIS
                    </a>
                    <span><i class="fas fa-comment-dots"></i> Veja o que estão falando dos nossos trabalhos</span>
                </div>
                
                <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Quero%20receber%20o%20catálogo%20de%20imagens%20de%20serviços%20antes%20e%20depois,%20as%20cores%20disponíveis%20e%20um%20orçamento%20grátis." 
                   class="btn-whatsapp-hero"
                   target="_blank">
                    <i class="fab fa-whatsapp"></i> QUERO CATÁLOGO DE IMAGENS DE SERVIÇOS ANTES E DEPOIS, CORES E UM ORÇAMENTO GRÁTIS
                </a>
                
                <div class="btn-disclaimer">
                    ✅ Atendimento rápido ✅ Parcelamos em até 12x ✅ 1 ano de garantia
                </div>
            </div>
        </div>
    </section>

    <!-- Seção de Destaque dos Adesivos Profissionais -->
    <section style="padding: 40px 0 0 0;">
        <div class="container">
            <div class="quality-badge">
                <span><i class="fas fa-trophy"></i> ADESIVOS AUTOMOTIVOS PROFISSIONAIS</span>
                <span><i class="fas fa-fire"></i> ALTA RESISTÊNCIA AO CALOR</span>
                <span><i class="fas fa-calendar-alt"></i> ALTA DURABILIDADE</span>
                <span><i class="fas fa-shield-alt"></i> GARANTIA PERMANENTE DO ADESIVO</span>
                <span><i class="fas fa-wrench"></i> 1 ANO DE GARANTIA DA MÃO DE OBRA</span>
            </div>
            <p style="text-align: center; font-size: 0.9rem; color: var(--gray); margin-top: 10px;">
                <i class="fas fa-star" style="color: var(--secondary);"></i> Utilizamos os mesmos adesivos de alta qualidade usados no envelopamento de veículos de luxo — muito superiores aos adesivos comuns de lojas populares.
            </p>
        </div>
    </section>

    <!-- Seção Eletrodomésticos -->
    <section id="servicos">
        <div class="container">
            <div class="section-title">
                <h2>O que a gente faz?</h2>
                <p><span class="highlight-text">Seu eletrodoméstico velho, riscado, amassado ou com ferrugem? A gente resolve!</span></p>
            </div>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">❄</div>
                    <div class="service-content">
                        <h3>Geladeira e Freezer</h3>
                        <p><span class="highlight-text">Aquela geladeira antiga, cheia de riscos, amassados ou ferrugem? Deixamos zero bala primeiro recuperando a superfície!</span></p>
                        <ul>
                            <li><strong>Técnica exclusiva:</strong> recuperamos amassados, ferrugem e buracos antes de envelopar</li>
                            <li><strong>Adesivo automotivo profissional</strong> de alta durabilidade</li>
                            <li>Escolha a cor: preto, inox, branco gelo</li>
                            <li>Serviço rapidinho: 3 a 4 horas</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x no cartão</div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-fire"></i></div>
                    <div class="service-content">
                        <h3>Fogão e Cooktop</h3>
                        <p>Fogão queimado, amassado ou desbotado? Fica novo de verdade:</p>
                        <ul>
                            <li><strong>Recuperamos a superfície</strong> antes do envelopamento</li>
                            <li><strong>Adesivo com alta resistência ao calor</strong> do fogão</li>
                            <li>Resistente e fácil de limpar</li>
                            <li>Serviço limpo, sem sujeira na cozinha</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x no cartão</div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-microchip"></i></div>
                    <div class="service-content">
                        <h3>Micro-ondas e Máquina de Lavar</h3>
                        <p>Aquele micro-ondas amarelado, riscado ou com amassados? Dá um talento:</p>
                        <ul>
                            <li><strong>Recuperamos amassados e ferrugem</strong> antes de envelopar</li>
                            <li><strong>Adesivo profissional</strong> que não desbota com o tempo</li>
                            <li>Cores que combinam com sua casa</li>
                            <li>Muito mais barato que comprar novo</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x no cartão</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Ambientes -->
    <section id="ambientes" class="projects-section">
        <div class="container">
            <div class="section-title">
                <h2>Também fazemos ambientes completos</h2>
                <p><span class="highlight-text">Bancada, armário, balcão... Tudo sem quebrar nada!</span></p>
            </div>
            
            <div class="project-highlight">
                <h3><i class="fas fa-gem"></i> Sua cozinha ou comércio renovado por menos</h3>
                <p style="font-size: 1.1rem; line-height: 1.8;">
                    Cansou da bancada velha? Armário desbotado? Balcão feio? A gente resolve sem obra, sem sujeira, sem dor de cabeça. 
                    Deixamos tudo com cara de novo e você ainda parcela no cartão. É a solução mais inteligente antes de pensar em trocar tudo.
                </p>
            </div>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-utensils"></i></div>
                    <div class="service-content">
                        <h3>Bancada, Pia e Granito</h3>
                        <p>Bancada manchada? Pia feia? Granito do banheiro velho? A gente resolve:</p>
                        <ul>
                            <li>Envelopamento de pias de cozinha</li>
                            <li>Granitos de banheiro renovados</li>
                            <li>Renovamos granito, mármore, quartzo</li>
                            <li>Muito mais barato que trocar a peça</li>
                            <li>Resistente a calor, mancha e risco</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x</div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-archive"></i></div>
                    <div class="service-content">
                        <h3>Armário e Cozinha Completa</h3>
                        <p>Armário desbotado, riscado ou amassado? Fica novo:</p>
                        <ul>
                            <li>Renovamos portas e painéis</li>
                            <li>Cozinha inteira com outra cara</li>
                            <li>Sem quebrar nada, sem bagunça</li>
                            <li>Harmonização de cores bonita</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x</div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-table"></i></div>
                    <div class="service-content">
                        <h3>Tampo de Vidro e Lacado</h3>
                        <p>Sua mesa antiga ou sem graça? Dá um talento:</p>
                        <ul>
                            <li>Tampo de vidro de mesa em lacado</li>
                            <li>Diversas cores para escolher</li>
                            <li>Acabamento premium e brilhante</li>
                            <li>Resistente e fácil de limpar</li>
                            <li>Renovação sem precisar trocar a mesa</li>
                        </ul>
                        <div class="payment-info">💳 Parcelamos em até 12x</div>
                    </div>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 3rem;">
                <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Quero%20receber%20o%20catálogo%20de%20imagens%20de%20serviços%20antes%20e%20depois,%20as%20cores%20disponíveis%20e%20um%20orçamento%20grátis%20para%20ambientes." 
                   class="btn-whatsapp-cta"
                   style="display: inline-flex;"
                   target="_blank">
                    <i class="fab fa-whatsapp"></i> QUERO CATÁLOGO DE IMAGENS, CORES E ORÇAMENTO
                </a>
            </div>
        </div>
    </section>

    <!-- Seção Parcerias Estratégicas -->
    <section id="parcerias" class="partnership-section">
        <div class="container">
            <div class="section-title">
                <h2>Parcerias Estratégicas</h2>
                <p>A WILLSU conecta qualidade a projetos de excelência</p>
            </div>
            
            <div class="partnership-card">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <h3 style="color: var(--primary); margin-bottom: 1rem;">Você é profissional da área?</h3>
                    <p style="font-size: 1.2rem; line-height: 1.6;">
                        Arquitetos, designers de interiores, decoradores, engenheiros civis, 
                        marceneiros e empresários encontram na WILLSU uma parceira estratégica 
                        para agregar valor aos seus projetos com soluções de restauração premium.
                    </p>
                </div>
                
                <div class="partnership-list">
                    <div class="partner-item">Arquitetos</div>
                    <div class="partner-item">Designers de Interiores</div>
                    <div class="partner-item">Decoradores</div>
                    <div class="partner-item">Engenheiros Civis</div>
                    <div class="partner-item">Marceneiros</div>
                    <div class="partner-item">Empresários</div>
                    <div class="partner-item">Construtoras</div>
                    <div class="partner-item">Administradoras</div>
                </div>
                
                <div style="text-align: center; margin-top: 2rem;">
                    <p style="font-size: 1.1rem; margin-bottom: 1.5rem;">
                        Oferecemos padrão de qualidade, agilidade na execução e acabamento profissional 
                        para complementar seus projetos.
                    </p>
                    
                    <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Sou%20profissional%20e%20gostaria%20de%20conversar%20sobre%20parceria." 
                       class="btn-partnership"
                       target="_blank">
                        <i class="fas fa-handshake"></i> FALAR SOBRE PARCERIA
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Depoimentos -->
    <section id="depoimentos">
        <div class="container">
            <div class="section-title">
                <h2>O Que Nossos Clientes Dizem</h2>
                <p>Confiança e qualidade em cada projeto</p>
            </div>
            <div class="testimonials-container">
                <div class="testimonial-card">
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <div class="testimonial-text">
                        "Renovei minha geladeira e a bancada da cozinha com a WILLSU. Qualidade impecável e consegui parcelar conforme combinado. Recomendo!"
                    </div>
                    <div class="testimonial-author">— Carla Mendes, Moema</div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <div class="testimonial-text">
                        "Como arquiteto, indico a WILLSU para meus clientes. O padrão de qualidade e o parcelamento facilitam muito os projetos."
                    </div>
                    <div class="testimonial-author">— Ricardo Silva, Arquiteto</div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-rating">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <div class="testimonial-text">
                        "Fiz a cozinha completa com a WILLSU. Ficou perfeita! Parcelamento facilitou o investimento. Atendimento excelente."
                    </div>
                    <div class="testimonial-author">— Ana Paula, Vila Madalena</div>
                </div>
            </div>
            <div style="text-align: center; margin-top: 3rem;">
                <a href="https://www.facebook.com/share/p/14XBiswwUDp/" target="_blank" class="btn-reviews" style="background: var(--secondary); border: none; padding: 15px 35px; font-size: 1.1rem;" rel="noopener noreferrer">
                    <i class="fab fa-facebook"></i> VER MAIS AVALIAÇÕES NO FACEBOOK
                </a>
            </div>
        </div>
    </section>

    <!-- CTA Final -->
    <section class="cta">
        <div class="container">
            <div class="cta-content">
                <h2>Pronto Para Renovar Com Qualidade?</h2>
                <p>A WILLSU garante padrão, qualidade e atendimento em todos os serviços. Converse com nosso especialista.</p>
                
                <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Gostaria%20de%20receber%20o%20catálogo%20de%20imagens%20de%20serviços%20antes%20e%20depois,%20as%20cores%20disponíveis%20e%20um%20orçamento%20grátis." 
                   class="btn-whatsapp-cta"
                   target="_blank">
                    <i class="fab fa-whatsapp"></i> QUERO CATÁLOGO DE IMAGENS, CORES E ORÇAMENTO
                </a>
                
                <div style="margin-top: 2rem; font-size: 0.9rem; opacity: 0.9;">
                    <p><i class="fas fa-info-circle"></i> Parcelamento em até 12x no cartão, com juros conforme taxas da operadora.</p>
                </div>
                
                <p style="margin-top: 2rem; font-size: 0.9rem; opacity: 0.8;">
                    <i class="fas fa-shield-alt"></i> Garantia 1 ano • 
                    <i class="fas fa-award"></i> Profissionais certificados • 
                    <i class="fas fa-home"></i> Atendimento em toda Grande SP
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contato">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Contato e Condições</h3>
                    <ul>
                        <li><i class="fab fa-whatsapp"></i> <a href="https://wa.me/5511983357198" target="_blank">WhatsApp: (11) 98335-7198</a></li>
                        <li><i class="fas fa-credit-card"></i> Parcelamento em até 12x no cartão</li>
                        <li><i class="fas fa-envelope"></i> <a href="mailto:willsu.envelopamento@gmail.com">willsu.envelopamento@gmail.com</a></li>
                        <li><i class="fas fa-map-marker-alt"></i> Atendemos toda Grande SP</li>
                        <li><i class="fas fa-clock"></i> WhatsApp: 8h às 20h • Todos os dias</li>
                    </ul>
                    <div class="social-icons">
                        <a href="https://www.instagram.com/willsu.envelopamento/" target="_blank" aria-label="Instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="https://www.facebook.com/willsu.envelopamento" target="_blank" aria-label="Facebook">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="https://wa.me/5511983357198" target="_blank" aria-label="WhatsApp">
                            <i class="fab fa-whatsapp"></i>
                        </a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Nossos Serviços</h3>
                    <ul>
                        <li><i class="fas fa-chevron-right"></i> <a href="#servicos">Eletrodomésticos</a></li>
                        <li><i class="fas fa-chevron-right"></i> <a href="#ambientes">Bancadas e Ambientes</a></li>
                        <li><i class="fas fa-chevron-right"></i> <a href="#ambientes">Cozinhas Completas</a></li>
                        <li><i class="fas fa-chevron-right"></i> <a href="#ambientes">Ambientes Comerciais</a></li>
                        <li><i class="fas fa-chevron-right"></i> <a href="#parcerias">Parcerias Profissionais</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Compromisso WILLSU</h3>
                    <ul>
                        <li><i class="fas fa-check-circle"></i> Padrão de qualidade</li>
                        <li><i class="fas fa-check-circle"></i> Garantia de 1 ano</li>
                        <li><i class="fas fa-check-circle"></i> Profissionais certificados</li>
                        <li><i class="fas fa-check-circle"></i> Atendimento responsivo</li>
                        <li><i class="fas fa-check-circle"></i> Parcelamento facilitado</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2024 <strong>WILLSU - Restauração & Envelopamento Premium</strong>. Todos os direitos reservados.</p>
                <p>A WILLSU é responsável pelo padrão, qualidade, garantia e atendimento em todos os serviços.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Float - Bolha Flutuante -->
    <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Gostaria%20de%20receber%20o%20catálogo%20de%20imagens%20de%20serviços%20antes%20e%20depois,%20as%20cores%20disponíveis%20e%20um%20orçamento%20grátis." 
       class="whatsapp-float" 
       target="_blank"
       aria-label="Falar no WhatsApp">
        <i class="fab fa-whatsapp"></i>
        <div class="whatsapp-badge">Online</div>
    </a>

    <!-- JavaScript -->
    <script>
        // Menu Mobile
        const mobileMenu = document.getElementById('mobileMenu');
        const navLinks = document.getElementById('navLinks');
        
        mobileMenu.addEventListener('click', function() {
            navLinks.classList.toggle('active');
            mobileMenu.innerHTML = navLinks.classList.contains('active') 
                ? '<i class="fas fa-times"></i>' 
                : '<i class="fas fa-bars"></i>';
        });
        
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                navLinks.classList.remove('active');
                mobileMenu.innerHTML = '<i class="fas fa-bars"></i>';
            });
        });
        
        document.addEventListener('click', (e) => {
            if (!navLinks.contains(e.target) && !mobileMenu.contains(e.target)) {
                navLinks.classList.remove('active');
                mobileMenu.innerHTML = '<i class="fas fa-bars"></i>';
            }
        });
        
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const target = document.querySelector(targetId);
                if (target) {
                    if (navLinks.classList.contains('active')) {
                        navLinks.classList.remove('active');
                        mobileMenu.innerHTML = '<i class="fas fa-bars"></i>';
                    }
                    
                    window.scrollTo({
                        top: target.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        window.addEventListener('scroll', () => {
            const sections = document.querySelectorAll('section[id]');
            const scrollPos = window.scrollY + 100;
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                const sectionId = section.getAttribute('id');
                
                if (scrollPos >= sectionTop && scrollPos < sectionTop + sectionHeight) {
                    document.querySelectorAll('.nav-links a').forEach(link => {
                        link.classList.remove('active');
                        if (link.getAttribute('href') === `#${sectionId}`) {
                            link.classList.add('active');
                        }
                    });
                }
            });
        });
        
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.service-card, .testimonial-card, .partnership-card, .quality-badge, .btn-reviews').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(el);
        });
        
        document.querySelectorAll('a[href*="whatsapp"]').forEach(link => {
            link.addEventListener('click', function() {
                gtag('event', 'conversion', {
                    'send_to': 'AW-17709030845/xxxxx',
                    'value': 1.0,
                    'currency': 'BRL'
                });
            });
        });
        
        window.addEventListener('load', () => {
            document.body.style.opacity = '0';
            document.body.style.transition = 'opacity 0.3s';
            setTimeout(() => {
                document.body.style.opacity = '1';
            }, 100);
        });
    </script>
</body>
</html>
