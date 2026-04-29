<!DOCTYPE html>
<html>
<head>
    <title>Habeeb Yakubu | Web Developer</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f7fb;
            color: #222;
        }

        .hero {
            background: linear-gradient(135deg, #1f4037, #99f2c8);
            text-align: center;
            padding: 70px 20px;
            color: white;
        }

        .hero img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0% {transform: translateY(0);}
            50% {transform: translateY(-10px);}
            100% {transform: translateY(0);}
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 20px;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            margin: 5px;
        }

        .wa { background: #25D366; }
        .tg { background: #229ED9; }

        .section {
            max-width: 1000px;
            margin: auto;
            padding: 50px 20px;
        }

        h2 {
            text-align: center;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .price {
            color: green;
            font-weight: bold;
        }

        .contact {
            text-align: center;
            background: #111827;
            color: white;
            padding: 50px 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #000;
            color: white;
        }
    </style>
</head>

<body>

<!-- HERO -->
<div class="hero">

    <img src="profile.jpg" alt="profile">

    <h1>Habeeb Yakubu</h1>
    <p>Web Developer | Freelancer | Business Website Creator</p>

    <p style="max-width:600px;margin:auto;margin-top:10px;">
        ⚡ I help businesses build modern websites that attract customers and increase sales.
        Message me now to grow your business online.
    </p>

    <a class="btn wa" href="https://wa.me/2348085569668?text=Hello%20I%20need%20a%20website" target="_blank">
        WhatsApp Me
    </a>

    <a class="btn tg" href="https://t.me/omogeneral300" target="_blank">
        Telegram Me
    </a>
</div>

<!-- ABOUT -->
<div class="section">
    <h2>About Me</h2>
    <div class="card">
        I am a freelance web developer helping businesses build modern, responsive websites that build trust and increase customers.
    </div>
</div>

<!-- SERVICES -->
<div class="section">
    <h2>My Services</h2>

    <div class="grid">

        <div class="card">
            <h3>Business Website</h3>
            <p>Professional website for companies</p>
            <p class="price">₦10,000+</p>
        </div>

        <div class="card">
            <h3>Portfolio Website</h3>
            <p>Personal branding website</p>
            <p class="price">₦7,000+</p>
        </div>

        <div class="card">
            <h3>Landing Page</h3>
            <p>Sales page for products/services</p>
            <p class="price">₦5,000+</p>
        </div>

    </div>
</div>

<!-- WHY ME -->
<div class="section">
    <h2>Why Choose Me</h2>

    <div class="grid">
        <div class="card">✔ Fast Delivery</div>
        <div class="card">✔ Mobile Friendly</div>
        <div class="card">✔ Clean Professional Design</div>
    </div>
</div>

<!-- CONTACT -->
<div class="contact">
    <h2>Ready to Work With Me?</h2>
    <p>Message me now and let’s build your website today.</p>

    <a class="btn wa" href="https://wa.me/2348085569668?text=Hello%20I%20need%20a%20website">
        WhatsApp Me
    </a>

    <a class="btn tg" href="https://t.me/omogeneral300">
        Telegram Me
    </a>
</div>

<footer>
    © 2026 Habeeb Yakubu | Web Developer
</footer>

</body>
</html>
