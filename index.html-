<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="index, follow">
    <title>Thokozile Maduna | MYW Web Agency | Web Design & Management</title>
    <meta name="description" content="MYW Web Agency builds simple, professional websites that help your business get more customers. Custom website design, management, and SEO services in Pretoria, South Africa.">
    <meta name="keywords" content="web design, website management, SEO, Pretoria, South Africa, small business websites, custom websites">
    <meta name="author" content="Thokozile Maduna">
    <meta name="copyright" content="© 2026 MYW Web Agency">
    <link rel="canonical" href="https://myw-web-agency.com">

    <!-- Open Graph -->
    <meta property="og:title" content="Thokozile Maduna | MYW Web Agency">
    <meta property="og:description" content="We build simple, professional websites that help your business get more customers. Custom design, management & SEO.">
    <meta property="og:image" content="https://myw-web-agency.com/og-image.jpg">
    <meta property="og:url" content="https://myw-web-agency.com">
    <meta property="og:type" content="website">

    <!-- Twitter Cards -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="MYW Web Agency | Thokozile Maduna">
    <meta name="twitter:description" content="Simple, professional websites that help your business get more customers.">
    <meta name="twitter:image" content="https://myw-web-agency.com/twitter-image.jpg">

    <link rel="icon" href="favicon.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">

    <!-- Schema Markup -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "LocalBusiness",
      "name": "MYW Web Agency",
      "description": "We build simple, professional websites that help your business get more customers.",
      "url": "https://myw-web-agency.com",
      "telephone": "+27-68-228-0722",
      "email": "myw.webagency@gmail.com",
      "address": {
        "@type": "PostalAddress",
        "addressLocality": "Pretoria",
        "addressCountry": "South Africa"
      },
      "founder": {
        "@type": "Person",
        "name": "Thokozile Maduna"
      },
      "serviceType": ["Custom Website Design", "Website Management", "SEO Services"]
    }
    </script>

    <style>
        :root {
            --bg-primary: #0a0a0f;
            --bg-secondary: #12121a;
            --bg-card: #1a1a2e;
            --text-primary: #f0f0f5;
            --text-secondary: #a0a0b0;
            --text-muted: #6b6b7b;
            --accent: #6366f1;
            --accent-light: #818cf8;
            --accent-dark: #4f46e5;
            --gradient-1: #6366f1;
            --gradient-2: #a855f7;
            --gradient-3: #ec4899;
            --success: #22c55e;
            --warning: #f59e0b;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body {
            font-family: 'Inter', sans-serif;
            background: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
            line-height: 1.6;
        }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--bg-primary); }
        ::-webkit-scrollbar-thumb { background: var(--accent); border-radius: 4px; }

        nav {
            position: fixed; top: 0; width: 100%; z-index: 1000;
            padding: 1.5rem 3rem;
            display: flex; justify-content: space-between; align-items: center;
            transition: all 0.3s ease;
            backdrop-filter: blur(0px);
        }
        nav.scrolled {
            background: rgba(10, 10, 15, 0.85);
            backdrop-filter: blur(20px);
            padding: 1rem 3rem;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
        }
        .logo {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 1.5rem; font-weight: 700;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            cursor: pointer;
        }
        .nav-links {
            display: flex; gap: 2.5rem; list-style: none;
        }
        .nav-links a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.9rem; font-weight: 500;
            transition: color 0.3s ease; position: relative;
        }
        .nav-links a::after {
            content: ''; position: absolute; bottom: -4px; left: 0;
            width: 0; height: 2px;
            background: linear-gradient(90deg, var(--gradient-1), var(--gradient-2));
            transition: width 0.3s ease;
        }
        .nav-links a:hover { color: var(--text-primary); }
        .nav-links a:hover::after { width: 100%; }
        .menu-toggle {
            display: none; flex-direction: column; gap: 5px;
            cursor: pointer; z-index: 1001;
        }
        .menu-toggle span {
            width: 25px; height: 2px;
            background: var(--text-primary); transition: all 0.3s ease;
        }

        .hero {
            min-height: 100vh;
            display: flex; align-items: center; justify-content: center;
            position: relative; overflow: hidden; padding: 0 2rem;
        }
        .hero-bg { position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 0; }
        .hero-bg canvas { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }
        .hero-content { position: relative; z-index: 1; text-align: center; max-width: 900px; }
        .hero-badge {
            display: inline-flex; align-items: center; gap: 0.5rem;
            padding: 0.5rem 1rem;
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 50px; font-size: 0.85rem;
            color: var(--accent-light); margin-bottom: 2rem;
            animation: fadeInUp 0.8s ease;
        }
        .hero-badge .dot {
            width: 8px; height: 8px;
            background: var(--success); border-radius: 50%;
            animation: pulse 2s infinite;
        }
        @keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.5; transform: scale(1.2); } }
        .hero h1 {
            font-family: 'Space Grotesk', sans-serif;
            font-size: clamp(2.5rem, 6vw, 5rem);
            font-weight: 700; line-height: 1.1;
            margin-bottom: 1.5rem;
            animation: fadeInUp 0.8s ease 0.2s both;
        }
        .hero h1 .gradient-text {
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2), var(--gradient-3));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .hero-subtitle {
            font-size: clamp(1rem, 2vw, 1.25rem);
            color: var(--text-secondary); max-width: 600px;
            margin: 0 auto 2.5rem;
            animation: fadeInUp 0.8s ease 0.4s both;
        }
        .hero-buttons {
            display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;
            animation: fadeInUp 0.8s ease 0.6s both;
        }
        .btn {
            padding: 0.875rem 2rem; border-radius: 12px;
            font-size: 0.95rem; font-weight: 600;
            cursor: pointer; transition: all 0.3s ease;
            text-decoration: none; display: inline-flex;
            align-items: center; gap: 0.5rem; border: none;
        }
        .btn-primary {
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            color: white; box-shadow: 0 4px 15px rgba(99, 102, 241, 0.4);
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.5);
        }
        .btn-secondary {
            background: transparent; color: var(--text-primary);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.05);
            border-color: rgba(255, 255, 255, 0.4);
            transform: translateY(-2px);
        }
        .scroll-indicator {
            position: absolute; bottom: 2rem; left: 50%;
            transform: translateX(-50%); animation: bounce 2s infinite;
            cursor: pointer;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
            40% { transform: translateX(-50%) translateY(-10px); }
            60% { transform: translateX(-50%) translateY(-5px); }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        section { padding: 6rem 2rem; position: relative; }
        .container { max-width: 1200px; margin: 0 auto; }
        .section-header { text-align: center; margin-bottom: 4rem; }
        .section-header h2 {
            font-family: 'Space Grotesk', sans-serif;
            font-size: clamp(2rem, 4vw, 3rem); font-weight: 700; margin-bottom: 1rem;
        }
        .section-header p { color: var(--text-secondary); max-width: 600px; margin: 0 auto; }
        .section-tag {
            display: inline-block; padding: 0.25rem 0.75rem;
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid rgba(99, 102, 241, 0.2);
            border-radius: 50px; font-size: 0.8rem;
            color: var(--accent-light); margin-bottom: 1rem;
            text-transform: uppercase; letter-spacing: 1px;
        }

        .about { background: var(--bg-secondary); }
        .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: center; }
        .about-image { position: relative; }
        .about-image-wrapper {
            position: relative; border-radius: 20px; overflow: hidden;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            padding: 3px;
        }
        .about-image-inner {
            background: var(--bg-card); border-radius: 18px;
            padding: 3rem; display: flex; flex-direction: column;
            align-items: center; gap: 1.5rem;
        }
        .avatar {
            width: 120px; height: 120px; border-radius: 50%;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            display: flex; align-items: center; justify-content: center;
            font-size: 3rem; font-weight: 700; font-family: 'Space Grotesk', sans-serif;
        }
        .about-stats {
            display: grid; grid-template-columns: repeat(3, 1fr);
            gap: 1.5rem; width: 100%;
        }
        .stat-item {
            text-align: center; padding: 1rem;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 12px; border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .stat-number {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 1.75rem; font-weight: 700;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .stat-label { font-size: 0.8rem; color: var(--text-muted); margin-top: 0.25rem; }
        .about-text h3 {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 1.75rem; margin-bottom: 1rem;
        }
        .about-text p { color: var(--text-secondary); margin-bottom: 1.5rem; }
        .skills-list { display: flex; flex-wrap: wrap; gap: 0.75rem; }
        .skill-tag {
            padding: 0.5rem 1rem;
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid rgba(99, 102, 241, 0.2);
            border-radius: 50px; font-size: 0.85rem;
            color: var(--accent-light); transition: all 0.3s ease;
        }
        .skill-tag:hover { background: rgba(99, 102, 241, 0.2); transform: translateY(-2px); }

        .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 2rem; }
        .project-card {
            background: var(--bg-card); border-radius: 20px; overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.4s ease; position: relative;
        }
        .project-card:hover {
            transform: translateY(-8px);
            border-color: rgba(99, 102, 241, 0.3);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
        }
        .project-image {
            height: 220px;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            position: relative; overflow: hidden;
            display: flex; align-items: center; justify-content: center;
        }
        .project-image::before {
            content: ''; position: absolute; top: 0; left: 0;
            width: 100%; height: 100%;
            background: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.1'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
            opacity: 0.3;
        }
        .project-icon { font-size: 3rem; z-index: 1; }
        .project-content { padding: 1.75rem; }
        .project-tags { display: flex; gap: 0.5rem; margin-bottom: 0.75rem; flex-wrap: wrap; }
        .project-tag {
            padding: 0.25rem 0.75rem;
            background: rgba(99, 102, 241, 0.1);
            border-radius: 50px; font-size: 0.75rem;
            color: var(--accent-light);
        }
        .project-card h3 { font-family: 'Space Grotesk', sans-serif; font-size: 1.25rem; margin-bottom: 0.5rem; }
        .project-card p { color: var(--text-secondary); font-size: 0.9rem; margin-bottom: 1.25rem; }
        .project-links { display: flex; gap: 1rem; }
        .project-links a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.85rem; font-weight: 500;
            display: flex; align-items: center; gap: 0.25rem;
            transition: color 0.3s ease;
        }
        .project-links a:hover { color: var(--accent-light); }

        .services { background: var(--bg-secondary); }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; }
        .service-card {
            background: var(--bg-card); border-radius: 20px; padding: 2.5rem;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.4s ease; position: relative; overflow: hidden;
        }
        .service-card::before {
            content: ''; position: absolute; top: 0; left: 0;
            width: 100%; height: 3px;
            background: linear-gradient(90deg, var(--gradient-1), var(--gradient-2));
            transform: scaleX(0); transform-origin: left;
            transition: transform 0.4s ease;
        }
        .service-card:hover::before { transform: scaleX(1); }
        .service-card:hover {
            transform: translateY(-5px);
            border-color: rgba(99, 102, 241, 0.2);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        .service-icon {
            width: 60px; height: 60px; border-radius: 16px;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            display: flex; align-items: center; justify-content: center;
            font-size: 1.5rem; margin-bottom: 1.5rem;
        }
        .service-card h3 { font-family: 'Space Grotesk', sans-serif; font-size: 1.25rem; margin-bottom: 0.75rem; }
        .service-card p { color: var(--text-secondary); font-size: 0.9rem; }

        .testimonials-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .testimonial-card {
            background: var(--bg-card); border-radius: 20px; padding: 2rem;
            border: 1px solid rgba(255, 255, 255, 0.05); position: relative;
        }
        .testimonial-card::before {
            content: '"'; position: absolute; top: 1rem; right: 1.5rem;
            font-size: 4rem; color: rgba(99, 102, 241, 0.2);
            font-family: 'Space Grotesk', sans-serif; line-height: 1;
        }
        .testimonial-text { color: var(--text-secondary); margin-bottom: 1.5rem; font-style: italic; line-height: 1.7; }
        .testimonial-author { display: flex; align-items: center; gap: 1rem; }
        .author-avatar {
            width: 48px; height: 48px; border-radius: 50%;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            display: flex; align-items: center; justify-content: center;
            font-weight: 700; font-size: 1rem;
        }
        .author-info h4 { font-size: 0.95rem; margin-bottom: 0.25rem; }
        .author-info span { font-size: 0.8rem; color: var(--text-muted); }

        .contact { background: var(--bg-secondary); }
        .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: start; }
        .contact-info h3 { font-family: 'Space Grotesk', sans-serif; font-size: 1.75rem; margin-bottom: 1rem; }
        .contact-info p { color: var(--text-secondary); margin-bottom: 2rem; }
        .contact-methods { display: flex; flex-direction: column; gap: 1.5rem; }
        .contact-method { display: flex; align-items: center; gap: 1rem; }
        .contact-method-icon {
            width: 50px; height: 50px; border-radius: 12px;
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid rgba(99, 102, 241, 0.2);
            display: flex; align-items: center; justify-content: center;
            font-size: 1.25rem; color: var(--accent-light);
        }
        .contact-method-info h4 { font-size: 0.9rem; margin-bottom: 0.25rem; }
        .contact-method-info a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.85rem; transition: color 0.3s ease;
        }
        .contact-method-info a:hover { color: var(--accent-light); }
        .contact-form {
            background: var(--bg-card); border-radius: 20px;
            padding: 2.5rem; border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .form-group { margin-bottom: 1.5rem; }
        .form-group label {
            display: block; font-size: 0.85rem; font-weight: 500;
            margin-bottom: 0.5rem; color: var(--text-secondary);
        }
        .form-group input, .form-group textarea {
            width: 100%; padding: 0.875rem 1rem;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px; color: var(--text-primary);
            font-family: 'Inter', sans-serif; font-size: 0.9rem;
            transition: all 0.3s ease;
        }
        .form-group input:focus, .form-group textarea:focus {
            outline: none; border-color: var(--accent);
            box-shadow: 0 0 0 3px rgba(99, 102, 241, 0.1);
        }
        .form-group textarea { resize: vertical; min-height: 120px; }
        .form-submit {
            width: 100%; padding: 1rem;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            color: white; border: none; border-radius: 12px;
            font-size: 1rem; font-weight: 600; cursor: pointer;
            transition: all 0.3s ease; font-family: 'Inter', sans-serif;
        }
        .form-submit:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.4);
        }

        footer {
            background: var(--bg-primary);
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            padding: 3rem 2rem; text-align: center;
        }
        .footer-content { max-width: 1200px; margin: 0 auto; }
        .footer-logo {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 1.5rem; font-weight: 700;
            background: linear-gradient(135deg, var(--gradient-1), var(--gradient-2));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 1rem; display: inline-block;
        }
        .footer-links {
            display: flex; justify-content: center; gap: 2rem;
            margin-bottom: 1.5rem; flex-wrap: wrap;
        }
        .footer-links a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.9rem; transition: color 0.3s ease;
        }
        .footer-links a:hover { color: var(--accent-light); }
        .footer-social {
            display: flex; justify-content: center; gap: 1rem;
            margin-bottom: 1.5rem;
        }
        .social-link {
            width: 40px; height: 40px; border-radius: 10px;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.1);
            display: flex; align-items: center; justify-content: center;
            color: var(--text-secondary); text-decoration: none;
            font-size: 1.1rem; transition: all 0.3s ease;
        }
        .social-link:hover {
            background: rgba(99, 102, 241, 0.1);
            border-color: rgba(99, 102, 241, 0.3);
            color: var(--accent-light); transform: translateY(-3px);
        }
        .footer-copy { color: var(--text-muted); font-size: 0.85rem; }

        .reveal { opacity: 0; transform: translateY(30px); transition: all 0.8s ease; }
        .reveal.active { opacity: 1; transform: translateY(0); }

        .toast {
            position: fixed; bottom: 2rem; right: 2rem;
            background: var(--bg-card);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 12px; padding: 1rem 1.5rem;
            display: flex; align-items: center; gap: 0.75rem;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            transform: translateX(150%); transition: transform 0.4s ease;
            z-index: 9999;
        }
        .toast.show { transform: translateX(0); }
        .toast-icon {
            width: 32px; height: 32px; border-radius: 8px;
            background: rgba(34, 197, 94, 0.1);
            display: flex; align-items: center; justify-content: center;
            color: var(--success); font-size: 1.1rem;
        }
        .toast-content h4 { font-size: 0.9rem; margin-bottom: 0.25rem; }
        .toast-content p { font-size: 0.8rem; color: var(--text-muted); }

        @media (max-width: 768px) {
            .nav-links { display: none; position: absolute; top: 100%; left: 0; width: 100%; background: rgba(10, 10, 15, 0.95); backdrop-filter: blur(20px); flex-direction: column; padding: 2rem; gap: 1.5rem; }
            .nav-links.active { display: flex; }
            .menu-toggle { display: flex; }
            .about-grid, .contact-grid { grid-template-columns: 1fr; gap: 2rem; }
            .projects-grid, .services-grid, .testimonials-grid { grid-template-columns: 1fr; }
            .hero-buttons { flex-direction: column; align-items: center; }
            .btn { width: 100%; max-width: 280px; justify-content: center; }
            section { padding: 4rem 1.5rem; }
            nav { padding: 1rem 1.5rem; }
        }
    </style>
</head>
<body>
    <nav id="navbar">
        <div class="logo">MYW.</div>
        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div class="menu-toggle" id="menuToggle">
            <span></span><span></span><span></span>
        </div>
    </nav>

    <section class="hero" id="home">
        <div class="hero-bg"><canvas id="heroCanvas"></canvas></div>
        <div class="hero-content">
            <div class="hero-badge">
                <span class="dot"></span>
                Fresh startup, big vision
            </div>
            <h1>
                We Build Websites<br>
                <span class="gradient-text">That Get Customers</span>
            </h1>
            <p class="hero-subtitle">
                Hi, I'm Thokozile Maduna, founder of MYW Web Agency. We build simple, professional websites
                that help your business get found online and attract more customers.
            </p>
            <div class="hero-buttons">
                <a href="#projects" class="btn btn-primary">
                    View Our Work
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                </a>
                <a href="#contact" class="btn btn-secondary">
                    Get In Touch
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
                </a>
            </div>
        </div>
        <div class="scroll-indicator" onclick="document.getElementById('about').scrollIntoView({behavior: 'smooth'})">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="var(--text-muted)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5v14"/><path d="m19 12-7 7-7-7"/></svg>
        </div>
    </section>

    <section class="about" id="about">
        <div class="container">
            <div class="section-header reveal">
                <span class="section-tag">About Me</span>
                <h2>Passionate About Helping<br><span class="gradient-text">Your Business Grow</span></h2>
            </div>
            <div class="about-grid">
                <div class="about-image reveal">
                    <div class="about-image-wrapper">
                        <div class="about-image-inner">
                            <div class="avatar">TM</div>
                            <div class="about-stats">
                                <div class="stat-item">
                                    <div class="stat-number">0+</div>
                                    <div class="stat-label">Years (Startup)</div>
                                </div>
                                <div class="stat-item">
                                    <div class="stat-number">3+</div>
                                    <div class="stat-label">Projects</div>
                                </div>
                                <div class="stat-item">
                                    <div class="stat-number">2+</div>
                                    <div class="stat-label">Happy Clients</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="about-text reveal">
                    <h3>Building Your Business Online</h3>
                    <p>
                        I'm Thokozile Maduna, founder of MYW Web Agency based in Pretoria, South Africa.
                        We help businesses get more customers by building simple, professional websites
                        and managing them for you.
                    </p>
                    <p>
                        Whether you need a brand new website, updates to your existing one, or help getting
                        found on Google — we're here to make it happen. Every site we build is mobile-friendly,
                        fast, and designed to turn visitors into customers.
                    </p>
                    <div class="skills-list">
                        <span class="skill-tag">Custom Web Design</span>
                        <span class="skill-tag">Website Management</span>
                        <span class="skill-tag">SEO</span>
                        <span class="skill-tag">Responsive Design</span>
                        <span class="skill-tag">Google Business</span>
                        <span class="skill-tag">Local SEO</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="projects" id="projects">
        <div class="container">
            <div class="section-header reveal">
                <span class="section-tag">Portfolio</span>
                <h2>Featured <span class="gradient-text">Projects</span></h2>
                <p>A selection of our recent work helping businesses grow online.</p>
            </div>
            <div class="projects-grid">
                <div class="project-card reveal">
                    <div class="project-image"><span class="project-icon">🏪</span></div>
                    <div class="project-content">
                        <div class="project-tags">
                            <span class="project-tag">Custom Design</span>
                            <span class="project-tag">SEO</span>
                            <span class="project-tag">Responsive</span>
                        </div>
                        <h3>Local Bakery Website</h3>
                        <p>A beautiful, mobile-friendly website for a local bakery that helped them attract more customers through Google searches.</p>
                        <div class="project-links">
                            <a href="#"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Live Demo</a>
                        </div>
                    </div>
                </div>
                <div class="project-card reveal">
                    <div class="project-image"><span class="project-icon">💇</span></div>
                    <div class="project-content">
                        <div class="project-tags">
                            <span class="project-tag">Booking System</span>
                            <span class="project-tag">Management</span>
                        </div>
                        <h3>Hair Salon Booking Site</h3>
                        <p>A professional website with online booking for a hair salon, making it easy for clients to schedule appointments 24/7.</p>
                        <div class="project-links">
                            <a href="#"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Live Demo</a>
                        </div>
                    </div>
                </div>
                <div class="project-card reveal">
                    <div class="project-image"><span class="project-icon">🏠</span></div>
                    <div class="project-content">
                        <div class="project-tags">
                            <span class="project-tag">Local SEO</span>
                            <span class="project-tag">Google Business</span>
                        </div>
                        <h3>Real Estate Listings</h3>
                        <p>A clean property listing website optimized for local search, helping a real estate agent get found by buyers in their area.</p>
                        <div class="project-links">
                            <a href="#"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Live Demo</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="services" id="services">
        <div class="container">
            <div class="section-header reveal">
                <span class="section-tag">What We Do</span>
                <h2>Services & <span class="gradient-text">Expertise</span></h2>
                <p>Everything you need to grow your business online.</p>
            </div>
            <div class="services-grid">
                <div class="service-card reveal">
                    <div class="service-icon">🎨</div>
                    <h3>Custom Website Design</h3>
                    <p>We create simple, professional websites tailored to your business so customers can easily find you and contact you.</p>
                </div>
                <div class="service-card reveal">
                    <div class="service-icon">🔧</div>
                    <h3>Website Management</h3>
                    <p>We handle updates, changes, and maintenance so your website stays up-to-date and continues to work perfectly.</p>
                </div>
                <div class="service-card reveal">
                    <div class="service-icon">🔍</div>
                    <h3>Get Found on Google</h3>
                    <p>We help your business show up when people search online, making it easier for customers to find you and contact you.</p>
                </div>
                <div class="service-card reveal">
                    <div class="service-icon">📱</div>
                    <h3>Responsive Design</h3>
                    <p>Your website will look and work perfectly on every device — phones, tablets, and desktops.</p>
                </div>
                <div class="service-card reveal">
                    <div class="service-icon">⚡</div>
                    <h3>Fast Loading Speed</h3>
                    <p>We optimize your site for speed so visitors don't leave before they even see what you offer.</p>
                </div>
                <div class="service-card reveal">
                    <div class="service-icon">🚀</div>
                    <h3>Local SEO Focus</h3>
                    <p>We help your business show up in local searches so customers in your area can easily find and contact you.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-header reveal">
                <span class="section-tag">Testimonials</span>
                <h2>What Clients <span class="gradient-text">Say</span></h2>
                <p>Feedback from businesses we've helped grow online.</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card reveal">
                    <p class="testimonial-text">
                        Thokozile built us a beautiful website that actually brings in customers. Within a month,
                        we started getting calls from people who found us on Google. Best investment we made!
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">LN</div>
                        <div class="author-info">
                            <h4>Lerato Nkosi</h4>
                            <span>Owner, Sweet Delights Bakery</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card reveal">
                    <p class="testimonial-text">
                        MYW Web Agency handles everything for us — updates, changes, making sure our site is always
                        running smoothly. I don't have to worry about my website at all anymore.
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">JM</div>
                        <div class="author-info">
                            <h4>James Molefe</h4>
                            <span>Director, Molefe Consulting</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card reveal">
                    <p class="testimonial-text">
                        Our old website was outdated and slow. Thokozile created a modern, fast site that ranks on
                        Google. Our bookings increased by 40% in just two months!
                    </p>
                    <div class="testimonial-author">
                        <div class="author-avatar">SP</div>
                        <div class="author-info">
                            <h4>Sipho Peters</h4>
                            <span>Manager, Pretoria Auto Repairs</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="container">
            <div class="section-header reveal">
                <span class="section-tag">Get In Touch</span>
                <h2>Let's Grow Your Business <span class="gradient-text">Together</span></h2>
                <p>Ready to get more customers online? Let's chat about your project.</p>
            </div>
            <div class="contact-grid">
                <div class="contact-info reveal">
                    <h3>Start a Conversation</h3>
                    <p>Whether you need a new website, updates to your existing one, or help getting found on Google — we're here to help.</p>
                    <div class="contact-methods">
                        <div class="contact-method">
                            <div class="contact-method-icon">📧</div>
                            <div class="contact-method-info">
                                <h4>Email</h4>
                                <a href="mailto:myw.webagency@gmail.com">myw.webagency@gmail.com</a>
                            </div>
                        </div>
                        <div class="contact-method">
                            <div class="contact-method-icon">📱</div>
                            <div class="contact-method-info">
                                <h4>Phone / WhatsApp</h4>
                                <a href="tel:+27682280722">+27 68 228 0722</a>
                            </div>
                        </div>
                        <div class="contact-method">
                            <div class="contact-method-icon">📍</div>
                            <div class="contact-method-info">
                                <h4>Location</h4>
                                <a href="#">Pretoria, South Africa (Online)</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-form reveal">
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name">Your Name</label>
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" placeholder="you@example.com" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" name="subject" placeholder="Website Inquiry" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" placeholder="Tell us about your business and what you need..." required></textarea>
                        </div>
                        <button type="submit" class="form-submit">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <div class="footer-logo">MYW.</div>
            <div class="footer-links">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#projects">Projects</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>
            <div class="footer-social">
                <a href="#" class="social-link" title="Facebook"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg></a>
                <a href="#" class="social-link" title="Instagram"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg></a>
                <a href="#" class="social-link" title="LinkedIn"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect width="4" height="12" x="2" y="9"/><circle cx="4" cy="4" r="2"/></svg></a>
                <a href="#" class="social-link" title="WhatsApp"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg></a>
            </div>
            <p class="footer-copy">© 2026 MYW Web Agency. All rights reserved. Built with passion by Thokozile Maduna.</p>
        </div>
    </footer>

    <div class="toast" id="toast">
        <div class="toast-icon">✓</div>
        <div class="toast-content">
            <h4>Message Sent!</h4>
            <p>We'll get back to you soon.</p>
        </div>
    </div>

    <script>
        const canvas = document.getElementById('heroCanvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        let mouse = { x: null, y: null };
        let animationId;

        function resizeCanvas() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }

        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 2 + 0.5;
                this.speedX = (Math.random() - 0.5) * 0.5;
                this.speedY = (Math.random() - 0.5) * 0.5;
                this.opacity = Math.random() * 0.5 + 0.1;
            }
            update() {
                this.x += this.speedX; this.y += this.speedY;
                if (mouse.x != null && mouse.y != null) {
                    const dx = mouse.x - this.x; const dy = mouse.y - this.y;
                    const distance = Math.sqrt(dx * dx + dy * dy);
                    if (distance < 150) {
                        const force = (150 - distance) / 150;
                        this.x -= dx * force * 0.02; this.y -= dy * force * 0.02;
                    }
                }
                if (this.x < 0 || this.x > canvas.width) this.speedX *= -1;
                if (this.y < 0 || this.y > canvas.height) this.speedY *= -1;
            }
            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(99, 102, 241, ${this.opacity})`;
                ctx.fill();
            }
        }

        function initParticles() {
            particles = [];
            const particleCount = Math.min(window.innerWidth / 8, 100);
            for (let i = 0; i < particleCount; i++) particles.push(new Particle());
        }

        function connectParticles() {
            for (let i = 0; i < particles.length; i++) {
                for (let j = i + 1; j < particles.length; j++) {
                    const dx = particles[i].x - particles[j].x;
                    const dy = particles[i].y - particles[j].y;
                    const distance = Math.sqrt(dx * dx + dy * dy);
                    if (distance < 120) {
                        const opacity = (1 - distance / 120) * 0.15;
                        ctx.beginPath();
                        ctx.strokeStyle = `rgba(99, 102, 241, ${opacity})`;
                        ctx.lineWidth = 0.5;
                        ctx.moveTo(particles[i].x, particles[i].y);
                        ctx.lineTo(particles[j].x, particles[j].y);
                        ctx.stroke();
                    }
                }
            }
        }

        function animate() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => { p.update(); p.draw(); });
            connectParticles();
            animationId = requestAnimationFrame(animate);
        }

        window.addEventListener('mousemove', (e) => { mouse.x = e.x; mouse.y = e.y; });
        window.addEventListener('mouseleave', () => { mouse.x = null; mouse.y = null; });
        window.addEventListener('resize', () => { resizeCanvas(); initParticles(); });
        resizeCanvas(); initParticles(); animate();

        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) navbar.classList.add('scrolled');
            else navbar.classList.remove('scrolled');
        });

        const menuToggle = document.getElementById('menuToggle');
        const navLinks = document.getElementById('navLinks');
        menuToggle.addEventListener('click', () => navLinks.classList.toggle('active'));
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => navLinks.classList.remove('active'));
        });

        const revealElements = document.querySelectorAll('.reveal');
        const revealObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add('active'); });
        }, { threshold: 0.1, rootMargin: '0px 0px -50px 0px' });
        revealElements.forEach(el => revealObserver.observe(el));

        const contactForm = document.getElementById('contactForm');
        const toast = document.getElementById('toast');
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            toast.classList.add('show');
            contactForm.reset();
            setTimeout(() => toast.classList.remove('show'), 3000);
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            });
        });

        const sections = document.querySelectorAll('section[id]');
        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                if (scrollY >= sectionTop - 200) current = section.getAttribute('id');
            });
            document.querySelectorAll('.nav-links a').forEach(link => {
                if (link.getAttribute('href') === `#${current}`) link.style.color = 'var(--text-primary)';
                else link.style.color = '';
            });
        });
    </script>
</body>
</html>
