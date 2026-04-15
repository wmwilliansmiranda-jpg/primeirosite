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
<meta name="description" content="WILLSU: Restauração e Envelopamento Premium de eletrodomésticos, bancadas, cozinhas e ambientes. Padrão de qualidade com garantia. Parcelamento facilitado.">
<title>WILLSU | Restauração Premium de Eletrodomésticos e Ambientes</title>
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

    .payment-badge {
        background: rgba(255, 255, 255, 0.15);
        border: 2px solid rgba(255, 255, 255, 0.3);
        color: white;
        padding: 12px 25px;
        border-radius: 30px;
        font-weight: 600;
        font-size: 1rem;
        display: inline-block;
        margin-bottom: 1rem;
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
        font-style: italic;
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

    .payment-info strong {
        color: var(--success);
        font-weight: 600;
    }

    .pricing-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
    }

    .price-card {
        background: white;
        border-radius: var(--radius);
        padding: 2.5rem 2rem;
        text-align: center;
        box-shadow: var(--shadow);
        transition: var(--transition);
        border: 2px solid transparent;
        position: relative;
        overflow: hidden;
    }

    .price-card::after {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        height: 5px;
        background: linear-gradient(90deg, var(--secondary), var(--accent));
    }

    .price-card:hover {
        transform: translateY(-10px);
        border-color: var(--secondary);
        box-shadow: var(--shadow-hover);
    }

    .price-card h3 {
        color: var(--primary);
        margin-bottom: 1.5rem;
        font-size: 1.5rem;
        font-weight: 700;
    }

    .price-benefits {
        list-style: none;
        margin: 1.5rem 0;
    }

    .price-benefits li {
        margin-bottom: 0.8rem;
        padding-left: 1.5rem;
        position: relative;
        text-align: left;
    }

    .price-benefits li::before {
        content: '✓';
        position: absolute;
        left: 0;
        color: var(--success);
        font-weight: bold;
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

    .coverage-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
        gap: 1.2rem;
    }

    .city-card {
        background: white;
        border-radius: 10px;
        padding: 1.2rem;
        text-align: center;
        box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        transition: var(--transition);
        border: 1px solid #e2e8f0;
        font-weight: 500;
    }

    .city-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        border-color: var(--secondary);
    }

    .about-content {
        display: grid;
        grid-template-columns: 1fr;
        gap: 3rem;
    }

    .about-text h3 {
        color: var(--primary);
        margin-bottom: 1.5rem;
        font-size: 2rem;
        font-weight: 700;
    }

    .about-text p {
        margin-bottom: 1.5rem;
        font-size: 1.1rem;
        line-height: 1.8;
        color: var(--dark);
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

    .privacy-link {
        text-align: center;
        margin-top: 1rem;
    }

    .privacy-link a {
        color: #a0aec0;
        text-decoration: none;
        font-size: 1rem;
        transition: var(--transition);
    }

    .privacy-link a:hover {
        color: var(--secondary);
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
        .hero h1 {
            font-size: 3.2rem;
        }
        
        .hero-subtitle {
            font-size: 1.4rem;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
        }
    }

    @media (max-width: 768px) {
        .mobile-menu {
            display: block;
        }

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

        .hero {
            padding: 140px 0 80px;
        }

        .hero h1 {
            font-size: 2.8rem;
        }

        .hero-subtitle {
            font-size: 1.3rem;
        }

        section {
            padding: 70px 0;
        }

        .section-title h2 {
            font-size: 2.2rem;
        }

        .services-grid {
            grid-template-columns: 1fr;
        }

        .btn-whatsapp-hero,
        .btn-whatsapp-cta {
            padding: 18px 35px;
            font-size: 1.2rem;
        }

        .cta h2 {
            font-size: 2.5rem;
        }

        .whatsapp-float {
            width: 60px;
            height: 60px;
            font-size: 1.8rem;
            bottom: 20px;
            right: 20px;
        }
    }

    @media (max-width: 480px) {
        .hero h1 {
            font-size: 2.2rem;
        }

        .hero-subtitle {
            font-size: 1.1rem;
        }

        .section-title h2 {
            font-size: 1.8rem;
        }

        .service-card,
        .price-card,
        .testimonial-card {
            padding: 1.5rem;
        }

        .coverage-grid {
            grid-template-columns: repeat(2, 1fr);
        }

        .btn-whatsapp-hero,
        .btn-whatsapp-cta {
            width: 100%;
            max-width: 300px;
        }
    }
</style>
</head>
<body>
    <!-- Header mantido idêntico -->
    <header>
        <div class="container header-content">
            <a href="#" class="logo">WILL<span>SU</span></a>
            <div class="mobile-menu" id="mobileMenu">
                <i class="fas fa-bars"></i>
            </div>
            <nav class="nav-links" id="navLinks">
                <a href="#servicos">Eletrodomésticos</a>
                <a href="#ambientes">Ambientes</a>
                <a href="#parcerias">Para Profissionais</a>
                <a href="#depoimentos">Avaliações</a>
                <a href="#contato">Contato</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section com ajustes textuais -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="payment-badge">
                    <i class="fas fa-award"></i> PADRÃO DE QUALIDADE COM GARANTIA
                </div>
                
                <!-- AJUSTE 1: Texto acima da frase principal -->
                <p class="hero-subtitle" style="margin-bottom: 1rem;">
                    Restauração premium para cada tipo de necessidade
                </p>
                
                <!-- AJUSTE 2: Frase principal -->
                <h1>Renove seus eletrodomésticos e ambientes sem obras.</h1>
                
                <p class="hero-subtitle" style="margin-top: 1.5rem;">
                    A WILLSU é responsável pelo padrão, qualidade, garantia e atendimento em todos os serviços. 
                    Transformamos eletrodomésticos, bancadas, cozinhas e ambientes completos.
                </p>
                
                <a href="https://wa.me/5511983357198?text=Olá%20WILLSU!%20Gostaria%20de%20saber%20mais%20sobre%20os%20serviços%20de%20restauração." 
                   class="btn-whatsapp-hero"
                   target="_blank"
                   aria-label="Falar no WhatsApp">
                    <i class="fab fa-whatsapp"></i> FALAR COM ESPECIALISTA
                </a>
                
                <div class="btn-disclaimer">
                    Parcelamento em até 12x no cartão, com juros conforme taxas da operadora.
                </div>
                
                <p style="margin-top: 2rem; font-size: 0.9rem; opacity: 0.8; color: rgba(255, 255, 255, 0.8);">
                    <i class="fas fa-shield-alt"></i> Garantia 1 ano • 
                    <i class="fas fa-clock"></i> Atendimento 24h • 
                    <i class="fas fa-home"></i> Atendemos em domicílio
                </p>
            </div>
        </div>
    </section>

    <!-- Seção Eletrodomésticos com ajustes -->
    <section id="servicos">
        <div class="container">
            <div class="section-title">
                <h2>Eletrodomésticos Restaurados</h2>
                <p>Padrão WILLSU de qualidade em cada serviço</p>
            </div>
            
            <div class="services-grid">
                <!-- AJUSTE 3: Card Geladeiras e Freezers -->
                <div class="service-card">
                    <!-- AJUSTE 4: Restaurar ícone original -->
                    <div class="service-icon"><i class="fas fa-snowflake"></i></div>
                    <div class="service-content">
                        <h3>Geladeiras e Freezers</h3>
                        <p>Solução para aparência feia, riscos ou cor antiga:</p>
                        <ul>
                            <li>Envelopamento premium durável</li>
                            <li>Cores modernas: preto, inox, branco gelo</li>
                            <li>Proteção contra ferrugem</li>
                            <li>Execução em 3-4 horas</li>
                        </ul>
                        <!-- AJUSTE 3: Texto de parcelamento -->
                        <div class="payment-info">
                            Parcelamos em até 12x • Juros conforme taxas da operadora.
                        </div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-fire"></i></div>
                    <div class="service-content">
                        <h3>Fogões e Cooktops</h3>
                        <p>Renovação com garantia de qualidade:</p>
                        <ul>
                            <li>Tampo renovado com resistência</li>
                            <li>Resistente a calor e limpeza</li>
                            <li>Acabamento profissional</li>
                            <li>Serviço limpo e organizado</li>
                        </ul>
                        <div class="payment-info">
                            Parcelamento em até 12x no cartão, com juros conforme taxas da operadora.
                        </div>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon"><i class="fas fa-microchip"></i></div>
                    <div class="service-content">
                        <h3>Micro-ondas e Máquinas</h3>
                        <p>Transformação com padrão de qualidade:</p>
                        <ul>
                            <li>Esconde amassados e riscos</li>
                            <li>Cores que harmonizam ambientes</li>
                            <li>Solução econômica e durável</li>
                            <li>Proteção contra umidade</li>
                        </ul>
                        <div class="payment-info">
                            Parcelamento em até 12x no cartão, com juros conforme taxas da operadora.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Ambientes (mantida) -->
    <section id="ambientes" class="projects-section">
        <div class="container">
            <div class="section-title">
                <h2>Ambientes e Projetos Completos</h2>
                <p>A WILLSU atua também em bancadas, balcões, armários, cozinhas e ambientes residenciais e comerciais</p>
            </div>
            
            <div class="project-highlight">
                <h3><i class="fas fa-gem"></i> Solução Completa de Renovação</h3>
                <p style="font-size: 1.1rem; line-height: 1.8; margin-bottom: 1rem;">
                    Além de eletrodom
