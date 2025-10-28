<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WillSu - Especialistas em Restauração e Envelopamento | 12 Anos de Experiência</title>
    <style>
        /* RESET E CONFIGURAÇÕES GERAIS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #1a365d;
            --secondary: #d4af37;
            --accent: #25D366;
            --light: #f8f9fa;
            --dark: #2d3748;
            --text: #2d3748;
            --shadow: 0 5px 20px rgba(0,0,0,0.1);
        }

        body {
            color: var(--text);
            line-height: 1.7;
            overflow-x: hidden;
            background: #ffffff;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        section {
            padding: 100px 0;
        }

        h1, h2, h3 {
            margin-bottom: 25px;
            color: var(--primary);
            font-weight: 700;
        }

        h1 {
            font-size: 3.5rem;
            line-height: 1.2;
        }

        h2 {
            font-size: 2.8rem;
            text-align: center;
            margin-bottom: 60px;
            position: relative;
        }

        h2:after {
            content: '';
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--secondary);
        }

        h3 {
            font-size: 1.6rem;
        }

        p {
            margin-bottom: 20px;
            font-size: 1.1rem;
            color: #4a5568;
        }

        .btn {
            display: inline-block;
            padding: 16px 35px;
            background: var(--secondary);
            color: var(--primary);
            text-decoration: none;
            border-radius: 8px;
            font-weight: 700;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            box-shadow: var(--shadow);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .btn:hover {
            background: #b8941f;
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(212, 175, 55, 0.3);
        }

        .btn-whatsapp {
            background: var(--accent);
            color: white;
        }

        .btn-whatsapp:hover {
            background: #128C7E;
        }

        /* BOTÃO WHATSAPP FLUTUANTE */
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 1000;
        }

        .whatsapp-btn {
            display: flex;
            align-items: center;
            background: var(--accent);
            color: white;
            padding: 18px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 1rem;
            box-shadow: 0 6px 25px rgba(37, 211, 102, 0.4);
            transition: all 0.3s ease;
            animation: pulse 2s infinite;
        }

        .whatsapp-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 30px rgba(37, 211, 102, 0.6);
        }

        .whatsapp-icon {
            font-size: 26px;
            margin-right: 12px;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        /* HEADER */
        header {
            background: rgba(255, 255, 255, 0.95);
            box-shadow: var(--shadow);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            backdrop-filter: blur(10px);
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 25px 0;
        }

        .logo {
            font-size: 2.2rem;
            font-weight: 800;
            color: var(--primary);
            letter-spacing: 1px;
        }

        .logo span {
            color: var(--secondary);
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 10px;
        }

        .nav-links li a {
            color: var(--primary);
            text-decoration: none;
            padding: 12px 20px;
            font-weight: 600;
            font-size: 1rem;
            transition: all 0.3s ease;
            border-radius: 6px;
        }

        .nav-links li a:hover {
            color: var(--secondary);
            background: rgba(212, 175, 55, 0.1);
        }

        .menu-toggle {
            display: none;
            font-size: 1.8rem;
            cursor: pointer;
            color: var(--primary);
        }

        /* HERO SECTION */
        .hero {
            background: linear-gradient(135deg, rgba(26, 54, 93, 0.9) 0%, rgba(45, 55, 72, 0.9) 100%), url('https://i.ibb.co/MDw9S9gC.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            text-align: center;
            padding: 200px 0 120px;
            margin-top: 0;
        }

        .hero h1 {
            color: white;
            font-size: 4rem;
            margin-bottom: 25px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .hero p {
            color: #e2e8f0;
            font-size: 1.3rem;
            max-width: 700px;
            margin: 0 auto 40px;
            line-height: 1.8;
        }

        /* BANNER DE PREÇO */
        .price-banner {
            background: linear-gradient(135deg, var(--primary), #2d3748);
            color: white;
            padding: 40px 0;
            text-align: center;
            margin: 0;
        }

        .price-banner h2 {
            color: white;
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .price-banner h2:after {
            background: var(--secondary);
        }

        .price-banner .price {
            font-size: 4rem;
            font-weight: 800;
            margin: 20px 0;
            color: var(--secondary);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .price-banner .highlight {
            background: var(--secondary);
            color: var(--primary);
            padding: 10px 25px;
            border-radius: 8px;
            font-weight: 700;
            font-size: 1.2rem;
            display: inline-block;
            margin: 15px 0;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* GALERIA DE TRABALHOS */
        .gallery {
            background: var(--light);
            padding: 100px 0;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 25px;
            margin-top: 50px;
        }

        .gallery-item {
            height: 300px;
            background-size: cover;
            background-position: center;
            border-radius: 12px;
            transition: all 0.4s ease;
            box-shadow: var(--shadow);
            position: relative;
            overflow: hidden;
        }

        .gallery-item:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 15px 40px rgba(0,0,0,0.2);
        }

        .gallery-item:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(to bottom, transparent 0%, rgba(0,0,0,0.1) 100%);
            border-radius: 12px;
            transition: all 0.3s ease;
        }

        .gallery-item:hover:before {
            background: linear-gradient(to bottom, transparent 0%, rgba(0,0,0,0.3) 100%);
        }

        /* SERVIÇOS */
        .services {
            background: white;
            padding: 100px 0;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 35px;
        }

        .service-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: all 0.4s ease;
            border: 1px solid #e2e8f0;
        }

        .service-card:hover {
            transform: translateY(-12px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }

        .service-img {
            height: 220px;
            background-size: cover;
            background-position: center;
            transition: transform 0.4s ease;
        }

        .service-card:hover .service-img {
            transform: scale(1.05);
        }

        .service-content {
            padding: 30px;
        }

        .service-content h3 {
            color: var(--primary);
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        .service-content p {
            color: #718096;
            line-height: 1.7;
        }

        /* BENEFÍCIOS */
        .benefits {
            background: linear-gradient(135deg, var(--light) 0%, #ffffff 100%);
            padding: 100px 0;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .benefit-item {
            background: white;
            padding: 40px 30px;
            border-radius: 12px;
            text-align: center;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
        }

        .benefit-item:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
        }

        .benefit-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--secondary);
        }

        .benefit-item h3 {
            color: var(--primary);
            font-size: 1.3rem;
            margin-bottom: 15px;
        }

        .benefit-item p {
            color: #718096;
            font-size: 1rem;
        }

        /* SOBRE */
        .about {
            background: white;
            padding: 100px 0;
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .about-text {
            padding-right: 40px;
        }

        .experience-badge {
            background: var(--secondary);
            color: var(--primary);
            padding: 12px 25px;
            border-radius: 8px;
            display: inline-block;
            margin-bottom: 25px;
            font-weight: 700;
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .about-img {
            height: 500px;
            background: url('https://i.ibb.co/NnWYhJsH.jpg');
            background-size: cover;
            background-position: center;
            border-radius: 15px;
            box-shadow: var(--shadow);
        }

        /* CONTATO */
        .contact {
            background: var(--light);
            padding: 100px 0;
        }

        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
        }

        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 20px;
            padding: 25px;
            background: white;
            border-radius: 12px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
        }

        .contact-item:hover {
            transform: translateX(10px);
        }

        .contact-icon {
            width: 60px;
            height: 60px;
            background: var(--primary);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
            flex-shrink: 0;
        }

        .contact-form {
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: var(--shadow);
        }

        .form-group {
            display: flex;
            flex-direction: column;
            margin-bottom: 25px;
        }

        .form-group label {
            margin-bottom: 8px;
            font-weight: 600;
            color: var(--primary);
        }

        .form-control {
            padding: 15px;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--secondary);
            box-shadow: 0 0 0 3px rgba(212, 175, 55, 0.1);
        }

        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }

        /* FOOTER */
        footer {
            background: var(--primary);
            color: white;
            padding: 70px 0 30px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
            margin-bottom: 50px;
        }

        .footer-logo {
            font-size: 2.2rem;
            font-weight: 800;
            margin-bottom: 20px;
            color: white;
        }

        .footer-logo span {
            color: var(--secondary);
        }

        .footer-about p {
            color: #cbd5e0;
            line-height: 1.8;
        }

        .footer-links h3, .footer-contact h3 {
            margin-bottom: 25px;
            color: white;
            font-size: 1.3rem;
        }

        .footer-links ul {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 12px;
        }

        .footer-links a {
            color: #cbd5e0;
            text-decoration: none;
            transition: color 0.3s;
            font-size: 1rem;
        }

        .footer-links a:hover {
            color: var(--secondary);
        }

        .footer-contact p {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-bottom: 15px;
            color: #cbd5e0;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 25px;
        }

        .social-link {
            width: 45px;
            height: 45px;
            background: rgba(255,255,255,0.1);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            transition: all 0.3s ease;
            font-size: 1.2rem;
        }

        .social-link:hover {
            background: var(--secondary);
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #a0aec0;
        }

        /* RESPONSIVIDADE */
        @media (max-width: 1200px) {
            h1 { font-size: 3rem; }
            h2 { font-size: 2.5rem; }
        }

        @media (max-width: 992px) {
            .about-content, .contact-container {
                grid-template-columns: 1fr;
                gap: 40px;
            }

            .about-text {
                padding-right: 0;
            }

            .hero {
                padding: 180px 0 100px;
            }
        }

        @media (max-width: 768px) {
            .menu-toggle {
                display: block;
            }

            .nav-links {
                position: fixed;
                top: 90px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 90px);
                background: white;
                flex-direction: column;
                align-items: center;
                justify-content: flex-start;
                padding-top: 60px;
                transition: left 0.3s;
                gap: 0;
            }

            .nav-links.active {
                left: 0;
            }

            .nav-links li {
                margin-bottom: 25px;
            }

            .nav-links li a {
                font-size: 1.2rem;
                padding: 15px 30px;
            }

            h1 {
                font-size: 2.5rem;
            }

            h2 {
                font-size: 2.2rem;
            }

            .hero {
                padding: 160px 0 80px;
                background-attachment: scroll;
            }

            .price-banner h2 {
                font-size: 2rem;
            }

            .price-banner .price {
                font-size: 3rem;
            }

            .whatsapp-btn span {
                display: none;
            }

            .whatsapp-btn {
                padding: 18px;
            }

            .whatsapp-icon {
                margin-right: 0;
            }

            .gallery-grid {
                grid-template-columns: 1fr;
            }

            section {
                padding: 80px 0;
            }
        }

        @media (max-width: 480px) {
            .container {
                width: 95%;
                padding: 0 15px;
            }

            h1 {
                font-size: 2rem;
            }

            h2 {
                font-size: 1.8rem;
            }

            .hero p {
                font-size: 1.1rem;
            }

            .btn {
                padding: 14px 25px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- BOTÃO WHATSAPP FLUTUANTE -->
    <div class="whatsapp-float">
        <a href="https://wa.me/5511983357198?text=Olá! Gostaria de solicitar um orçamento para restauração/envelopamento." class="whatsapp-btn" target="_blank">
            <div class="whatsapp-icon">💬</div>
            <span>Fale Conosco</span>
        </a>
    </div>

    <!-- HEADER -->
    <header>
        <div class="container">
            <nav class="navbar">
                <div class="logo">Will<span>Su</span></div>
                <div class="menu-toggle">☰</div>
                <ul class="nav-links">
                    <li><a href="#home">Início</a></li>
                    <li><a href="#trabalhos">Nossos Trabalhos</a></li>
                    <li><a href="#servicos">Serviços</a></li>
                    <li><a href="#precos">Preços</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="hero" id="home">
        <div class="container">
            <h1>WillSu - Excelência em Restauração</h1>
            <p>12 anos transformando eletrodomésticos e móveis com qualidade superior e acabamento impecável</p>
            <a href="https://wa.me/5511983357198?text=Olá! Gostaria de solicitar um orçamento para restauração/envelopamento." class="btn btn-whatsapp" target="_blank">Solicitar Orçamento</a>
        </div>
    </section>

    <!-- BANNER DE PREÇO -->
    <section class="price-banner" id="precos">
        <div class="container">
            <h2>ENVELOPAMENTO COM GARANTIA WILLSU</h2>
            <div class="price">R$ 480,00</div>
            <div class="highlight">PAGAMENTO APÓS APROVAÇÃO</div>
            <p>GELADEIRA DUPLEX A PARTIR DE R$ 480,00 EM ADESIVO PREMIUM</p>
            <p>QUALIDADE PROFISSIONAL - RESULTADO GARANTIDO</p>
        </div>
    </section>

    <!-- GALERIA DE TRABALHOS -->
    <section class="gallery" id="trabalhos">
        <div class="container">
            <h2>Nossos Trabalhos</h2>
            <p style="text-align: center; margin-bottom: 50px; font-size: 1.2rem; color: #718096;">
                Confira alguns dos nossos projetos realizados com excelência e atenção aos detalhes
            </p>
            
            <div class="gallery-grid">
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/MDw9S9gC.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/NnWYhJsH.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/R57DCp0.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/S49VrwJr.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/5x9bYt0T.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/Ngtd3vqG.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/Tx0ptJ6L.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/MkC1Yb1Q.jpg')"></div>
                <div class="gallery-item" style="background-image: url('https://i.ibb.co/fdVQvhtD.jpg')"></div>
            </div>
        </div>
    </section>

    <!-- SERVIÇOS -->
    <section class="services" id="servicos">
        <div class="container">
            <h2>Serviços Especializados</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://i.ibb.co/tTXBgR7L.jpg');"></div>
                    <div class="service-content">
                        <h3>Envelopamento de Geladeiras</h3>
                        <p>Transformação completa com adesivos premium de alta durabilidade e resistência, disponível em diversas cores e texturas.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://i.ibb.co/S2zq3BN.jpg');"></div>
                    <div class="service-content">
                        <h3>Restauração de Móveis</h3>
                        <p>Recuperação profissional de móveis antigos ou danificados, devolvendo a beleza original com técnicas especializadas.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-img" style="background-image: url('https://i.ibb.co/8g1P2xTK.jpg');"></div>
                    <div class="service-content">
                        <h3>Envelopamento de Fogões</h3>
                        <p>Proteção e renovação com adesivos resistentes ao calor, fáceis de limpar e com acabamento profissional.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BENEFÍCIOS -->
    <section class="benefits">
        <div class="container">
            <h2>Vantagens WillSu</h2>
            <div class="benefits-grid">
                <div class="benefit-item">
                    <div class="benefit-icon">🏠</div>
                    <h3>ATENDIMENTO NO LOCAL</h3>
                    <p>Realizamos o serviço na sua residência ou empresa, com toda comodidade</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">🔧</div>
                    <h3>PREPARAÇÃO COMPLETA</h3>
                    <p>Remoção de ferrugens, amassados e preparação minuciosa da superfície</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">🎨</div>
                    <h3>ACABAMENTO PERFEITO</h3>
                    <p>Pintura de componentes, borrachas e acabamentos com atenção aos detalhes</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">📍</div>
                    <h3>ATENDEMOS GRANDE SP</h3>
                    <p>Cobertura em todo município de São Paulo e região metropolitana</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">⏰</div>
                    <h3>AGENDAMENTO FLEXÍVEL</h3>
                    <p>Trabalhamos com horários agendados para melhor atender sua rotina</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">💯</div>
                    <h3>SATISFAÇÃO GARANTIDA</h3>
                    <p>Pagamento somente após sua total aprovação no resultado final</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SOBRE -->
    <section class="about" id="sobre">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <div class="experience-badge">12 ANOS DE EXCELÊNCIA</div>
                    <h2>WillSu - Tradição e Qualidade</h2>
                    <p>Há mais de uma década, a WillSu se consolidou como referência em restauração e envelopamento na grande São Paulo, construindo uma trajetória baseada na excelência e satisfação dos clientes.</p>
                    <p>Utilizamos materiais premium e técnicas avançadas, garantindo durabilidade e um acabamento que supera expectativas. Cada projeto é tratado com a máxima atenção aos detalhes.</p>
                    <p><strong>COMPROMISSO WILLSU: TRANSFORMAMOS SEU EQUIPAMENTO COM QUALIDADE SUPERIOR!</strong></p>
                    <a href="https://wa.me/5511983357198?text=Olá! Gostaria de solicitar um orçamento para restauração/envelopamento." class="btn btn-whatsapp" target="_blank">Falar com Especialista</a>
                </div>
                <div class="about-img"></div>
            </div>
        </div>
    </section>

    <!-- CONTATO -->
    <section class="contact" id="contato">
        <div class="container">
            <h2>Entre em Contato</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-item">
                        <div class="contact-icon">📞</div>
                        <div>
                            <h3>WhatsApp</h3>
                            <p>(11) 98335-7198</p>
                            <small>Atendimento rápido e direto</small>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">📍</div>
                        <div>
                            <h3>Área de Atendimento</h3>
                            <p>São Paulo e Região Metropolitana</p>
                            <small>Cobertura ampla sem custos adicionais</small>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">⏰</div>
                        <div>
                            <h3>Horário de Atendimento</h3>
                            <p>Segunda a Domingo</p>
                            <small>Agendamento prévio conforme sua disponibilidade</small>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">💰</div>
                        <div>
                            <h3>Condições Especiais</h3>
                            <p>Sem taxa de deslocamento</p>
                            <p>Pagamento após aprovação</p>
                            <small>Transparência e confiança em primeiro lugar</small>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>Solicite um Orçamento</h3>
                    <form id="orcamentoForm">
                        <div class="form-group">
                            <label for="nome">Nome Completo</label>
                            <input type="text" id="nome" class="form-control" required placeholder="Seu nome completo">
                        </div>
                        <div class="form-group">
                            <label for="telefone">Telefone/WhatsApp</label>
                            <input type="tel" id="telefone" class="form-control" required placeholder="(11) 99999-9999">
                        </div>
                        <div class="form-group">
                            <label for="servico">Serviço de Interesse</label>
                            <select id="servico" class="form-control" required>
                                <option value="">Selecione o serviço desejado</option>
                                <option value="envelopamento-geladeira">Envelopamento de Geladeira</option>
                                <option value="envelopamento-fogao">Envelopamento de Fogão</option>
                                <option value="restauracao-moveis">Restauração de Móveis</option>
                                <option value="outro">Outro serviço</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="mensagem">Detalhes do Serviço</label>
                            <textarea id="mensagem" class="form-control" placeholder="Descreva o equipamento, modelo e suas necessidades específicas..." required></textarea>
                        </div>
                        <button type="submit" class="btn" style="width: 100%;">Solicitar Orçamento</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-about">
                    <div class="footer-logo">Will<span>Su</span></div>
                    <p>Especialistas em restauração e envelopamento com 12 anos de excelência. Transformamos seus equipamentos com qualidade superior e compromisso com a satisfação total.</p>
                    <a href="https://wa.me/5511983357198?text=Olá! Gostaria de solicitar um orçamento para restauração/envelopamento." class="btn btn-whatsapp" target="_blank" style="margin-top: 20px; display: inline-block;">Chamar no WhatsApp</a>
                </div>
                <div class="footer-links">
                    <h3>Navegação</h3>
                    <ul>
                        <li><a href="#home">Início</a></li>
                        <li><a href="#trabalhos">Nossos Trabalhos</a></li>
                        <li><a href="#servicos">Serviços</a></li>
                        <li><a href="#precos">Preços</a></li>
                        <li><a href="#sobre">
