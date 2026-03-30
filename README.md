```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel 0771 | Changurabhata, Kushalpur Chowk | Deluxe AC Rooms</title>
    <meta name="description" content="Hotel 0771 offers 4 Deluxe AC Rooms (₹1500/night) & Non-AC Rooms (₹1000/night) at Changurabhata, Kushalpur Chowk beside Dhelabai Chatrwas. Book now!">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #1e3a8a;
            --secondary-color: #3b82f6;
            --accent-color: #f59e0b;
            --dark-color: #0f172a;
            --light-color: #f8fafc;
            --white: #ffffff;
            --shadow-sm: 0 1px 3px 0 rgba(0, 0, 0, 0.1);
            --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            --shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.7;
            color: #374151;
            overflow-x: hidden;
        }

        /* Header */
        .header {
            background: rgba(30, 58, 138, 0.95);
            backdrop-filter: blur(20px);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: all 0.3s ease;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 80px;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 1.75rem;
            font-weight: 800;
            color: var(--white);
            text-decoration: none;
        }

        .logo i {
            color: var(--accent-color);
            font-size: 2rem;
        }

        .nav-menu {
            display: flex;
            list-style: none;
            gap: 2.5rem;
            align-items: center;
        }

        .nav-link {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            font-size: 0.95rem;
            transition: color 0.2s ease;
        }

        .nav-link:hover {
            color: var(--accent-color);
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: var(--white);
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            background: linear-gradient(135deg, rgba(30, 58, 138, 0.9) 0%, rgba(59, 130, 246, 0.9) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
        }

        .hero-content {
            max-width: 800px;
            padding: 0 2rem;
        }

        .hero-title {
            font-size: clamp(2.5rem, 5vw, 4.5rem);
            font-weight: 800;
            margin-bottom: 1.5rem;
        }

        .hero-subtitle {
            font-size: 1.25rem;
            margin-bottom: 2.5rem;
            opacity: 0.95;
        }

        .cta-primary {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            background: linear-gradient(135deg, var(--accent-color) 0%, #eab308 100%);
            color: var(--dark-color);
            padding: 1.25rem 3rem;
            text-decoration: none;
            border-radius: 12px;
            font-weight: 600;
            font-size: 1.125rem;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(245, 158, 11, 0.4);
        }

        .cta-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 20px 40px rgba(245, 158, 11, 0.5);
        }

        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        /* Section */
        .section {
            padding: 7rem 0;
        }

        .section-title {
            text-align: center;
            font-size: clamp(2rem, 4vw, 3rem);
            font-weight: 800;
            color: var(--dark-color);
            margin-bottom: 4rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            width: 60px;
            height: 4px;
            background: linear-gradient(135deg, var(--accent-color), #eab308);
            bottom: -20px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        /* About Section */
        .about-section {
            background: linear-gradient(135deg, var(--light-color) 0%, #f1f5f9 100%);
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 5rem;
            align-items: center;
        }

        .about-text p {
            font-size: 1.125rem;
            line-height: 1.8;
            color: #475569;
            margin-bottom: 1.5rem;
        }

        .location-card {
            background: var(--white);
            padding: 3rem;
            border-radius: 20px;
            box-shadow: var(--shadow-xl);
            text-align: center;
            border: 1px solid #e2e8f0;
            transition: all 0.3s ease;
        }

        .location-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }

        .location-icon {
            font-size: 3.5rem;
            color: var(--secondary-color);
            margin-bottom: 1.5rem;
        }

        .location-title {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--dark-color);
            margin-bottom: 1.5rem;
        }

        .location-details {
            color: #64748b;
            line-height: 1.7;
        }

        .phone-number {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--accent-color);
            display: block;
            margin-top: 1rem;
        }

        /* Rooms Section */
        .rooms-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2.5rem;
        }

        .room-card {
            background: var(--white);
            border-radius: 24px;
            overflow: hidden;
            box-shadow: var(--shadow-xl);
            transition: all 0.4s ease;
            border: 1px solid #f1f5f9;
        }

        .room-card:hover {
            transform: translateY(-12px);
            box-shadow: 0 35px 60px -12px rgba(0, 0, 0, 0.25);
        }

        .room-image {
            height: 260px;
            background: linear-gradient(135deg, var(--secondary-color), var(--primary-color));
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: 4rem;
        }

        .room-content {
            padding: 2.5rem;
        }

        .room-title {
            font-size: 1.75rem;
            font-weight: 700;
            color: var(--dark-color);
            margin-bottom: 1rem;
        }

        .room-features {
            list-style: none;
            margin: 1.5rem 0 2rem 0;
        }

        .room-features li {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            color: #64748b;
            margin-bottom: 0.75rem;
            font-size: 0.95rem;
        }

        .room-features i {
            color: var(--accent-color);
            width: 18px;
        }

        .room-price {
            font-size: 2.25rem;
            font-weight: 800;
            color: var(--accent-color);
            margin-bottom: 1.5rem;
        }

        /* Gallery */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 2rem;
        }

        .gallery-item {
            height: 280px;
            background: linear-gradient(135deg, var(--secondary-color), var(--primary-color));
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: 3.5rem;
            cursor: pointer;
            transition: all 0.4s ease;
        }

        .gallery-item:hover {
            transform: scale(1.03) translateY(-5px);
        }

        /* Contact Section */
        .contact-section {
            background: linear-gradient(135deg, var(--dark-color) 0%, #1e293b 100%);
            color: var(--white);
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 5rem;
        }

        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 2.5rem;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            gap: 1.25rem;
        }

        .contact-icon {
            background: linear-gradient(135deg, var(--accent-color), #eab308);
            width: 56px;
            height: 56px;
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.25rem;
            flex-shrink: 0;
            margin-top: 4px;
        }

        .contact-details h4 {
            font-size: 1.125rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }

        .contact-details p {
            color: #cbd5e1;
        }

        .contact-form-container {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(20px);
            padding: 3rem;
            border-radius: 24px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .form-group {
            margin-bottom: 1.75rem;
        }

        .form-control {
            width: 100%;
            padding: 1.25rem 1.5rem;
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 12px;
            background: rgba(255, 255, 255, 0.9);
            font-family: inherit;
            font-size: 1rem;
            color: var(--dark-color);
            transition: all 0.3s ease;
        }

        .form-control:focus {
            outline: none;
            border-color: var(--accent-color);
            box-shadow: 0 0 0 3px rgba(245, 158, 11, 0.1);
            background: var(--white);
        }

        .form-control::placeholder {
            color: #94a3b8;
        }

        .form-textarea {
            height: 140px;
            resize: vertical;
        }

        /* Footer */
        .footer {
            background: var(--dark-color);
            color: #94a3b8;
            text-align: center;
            padding: 3rem 0 2rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .mobile-menu-btn {
                display: block;
            }

            .nav-menu {
                position: fixed;
                top: 80px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 80px);
                background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
                flex-direction: column;
                justify-content: flex-start;
                align-items: center;
                padding: 3rem 0;
                gap: 2rem;
                transition: left 0.4s ease;
            }

            .nav-menu.active {
                left: 0;
            }

            .about-grid,
            .contact-grid {
                grid-template-columns: 1fr;
                gap: 3rem;
            }

            .section {
                padding: 4rem 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header" id="header">
        <div class="nav-container">
            <a href="#home" class="logo">
                <i class="fas fa-hotel"></i>
                Hotel 0771
            </a>
            <nav>
                <ul class="nav-menu" id="navMenu">
                    <li><a href="#home" class="nav-link">Home</a></li>
                    <li><a href="#about" class="nav-link">About</a></li>
                    <li><a href="#rooms" class="nav-link">Rooms</a></li>
                    <li><a href="#gallery" class="nav-link">Gallery</a></li>
                    <li><a href="#contact" class="nav-link">Contact</a></li>
                </ul>
            </nav>
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1 class="hero-title">Welcome to Hotel 0771</h1>
            <p class="hero-subtitle">Comfortable stay at Changurabhata, Kushalpur Chowk<br>4 Deluxe AC Rooms | Beside Dhelabai Chatrwas</p>
            <a href="#rooms" class="cta-primary">
                <i class="fas fa-bed"></i>
                View Rooms
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section about-section">
        <div class="container">
            <h2 class="section-title">About Hotel 0771</h2>
            <div class="about-grid">
                <div class="about-text">
                    <p>Hotel 0771 offers premium accommodation in the heart of Changurabhata. We are strategically located beside Dhelabai Chatrwas at Kushalpur Chowk, providing easy access to all major locations.</p>
                    <p>Our hotel features <strong>4 Deluxe AC Rooms</strong> with modern amenities and comfortable Non-AC rooms. Perfect for business travelers, families, and tourists visiting Raipur.</p>
                    <p>Experience authentic hospitality with 24/7 service, clean rooms, delicious home-cooked meals, and excellent value for money.</p>
                </div>
                <div class="location-card">
                    <i class="fas fa-map-marker-alt location-icon"></i>
                    <h3 class="location-title">Our Location</h3>
                    <div class="location-details">
                        <strong>Changurabhata, Kushalpur Chowk</strong><br>
                        Beside Dhelabai Chatrwas<br>
                        Raipur, Chhattisgarh
                        <a href="tel:+91947902907" class="phone-number">
                            <i class="fas fa-phone"></i> +91 94790 2907
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Rooms Section -->
    <section id="rooms" class="section">
        <div class="container">
            <h2 class="section-title">Our Rooms</h2>
            <div class="rooms-grid">
                <div class="room-card">
                    <div class="room-image">
                        <i class="fas fa-snowflake"></i>
                    </div>
                    <div class="room-content">
                        <h3 class="room-title">Deluxe AC Room</h3>
                        <p>Luxurious air-conditioned rooms with modern amenities. <strong>Limited 4 Deluxe AC Rooms available.</strong></p>
                        <ul class="room-features">
                            <li><i class="fas fa-check"></i> Split Air Conditioning</li>
                            <li><i class="fas fa-tv"></i> LED Smart TV</li>
                            <li><i class="fas fa-bed"></i> King Size Bedding</li>
                            <li><i class="fas fa-wifi"></i> High-Speed WiFi</li>
                            <li><i class="fas fa-hot-tub"></i> Hot Water 24/7</li>
                        </ul>
                        <div class
