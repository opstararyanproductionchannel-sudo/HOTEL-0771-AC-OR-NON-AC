<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel 0771 | Changurabhata, Kushalpur Chowk | Deluxe AC Rooms</title>
    <meta name="description" content="Hotel 0771 offers 4 Deluxe AC Rooms (₹1500/night) & Non-AC Rooms (₹1000/night) at Changurabhata, Kushalpur Chowk beside Dhelabai Chatrwas. Book now for comfortable stay!">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
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
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
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
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
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
            letter-spacing: -0.025em;
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
            letter-spacing: 0.025em;
            position: relative;
            transition: all 0.2s ease;
        }

        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -8px;
            left: 0;
            background: var(--accent-color);
            transition: width 0.3s ease;
        }

        .nav-link:hover::after,
        .nav-link.active::after {
            width: 100%;
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
            background: linear-gradient(135deg, rgba(30, 58, 138, 0.9) 0%, rgba(59, 130, 246, 0.9) 100%),
                        url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="%23f8fafc" fill-opacity="0.1" d="M0,96L48,112C96,128,192,160,288,160C384,160,480,128,576,112C672,96,768,96,864,112C960,128,1056,160,1152,160C1248,160,1344,128,1392,112L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
            position: relative;
        }

        .hero-content {
            max-width: 800px;
            padding: 0 2rem;
            animation: fadeInUp 1s ease-out;
        }

        .hero-title {
            font-size: clamp(2.5rem, 5vw, 4.5rem);
            font-weight: 800;
            margin-bottom: 1.5rem;
            letter-spacing: -0.02em;
            line-height: 1.1;
        }

        .hero-subtitle {
            font-size: 1.25rem;
            margin-bottom: 2.5rem;
            opacity: 0.95;
            font-weight: 400;
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
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
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

        .about-text {
            font-size: 1.125rem;
            line-height: 1.8;
            color: #475569;
        }

        .about-text p {
            margin-bottom: 1.5rem;
        }

        .location-card {
            background: var(--white);
            padding: 3rem;
            border-radius: 20px;
            box-shadow: var(--shadow-xl);
            text-align: center;
            border: 1px solid #e2e8f0;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .location-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }

        .location-icon {
            font-size: 3.5rem;
            color: var(--secondary-color);
            margin-bottom: 1.5rem;
            display: block;
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
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
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
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
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
            color: var(--white);
        }

        .contact-details p {
            color: #cbd5e1;
            line-height: 1.6;
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

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animate-on-scroll {
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .animate-on-scroll.animated {
            opacity: 1;
            transform: translateY(0);
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

            .nav-container {
                padding: 0 1.5rem;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="nav-container">
            <a href="#home" class="logo
