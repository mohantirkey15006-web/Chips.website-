<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chips King Franchise - High Profit Chips Business</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            font-weight: bold;
            color: #333;
            line-height: 1.6;
        }
        .bg-yellow { background-color: #FFD700; }
        .bg-orange { background-color: #FF8C00; }
        .bg-red { background-color: #FF0000; }
        .text-white { color: #FFF; }
        .text-center { text-align: center; }
        .text-red { color: #FF0000; }
        .fw-bold { font-weight: bold; }
        .lead { font-size: 1.25rem; }
        .display-4 { font-size: 2.5rem; }
        .display-6 { font-size: 2.5rem; }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            text-decoration: none;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn-yellow { background-color: #FFD700; color: #000; }
        .btn-yellow:hover { background-color: #E6C200; }
        .btn-red { background-color: #FF0000; color: #FFF; }
        .btn-red:hover { background-color: #CC0000; }
        .btn-orange { background-color: #FF8C00; color: #FFF; }
        .btn-orange:hover { background-color: #E67E00; }
        .btn-lg { padding: 15px 30px; font-size: 1.25rem; }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .navbar {
            background-color: #FF8C00;
            color: #FFF;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .navbar .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar-brand {
            font-size: 1.5rem;
            font-weight: bold;
            text-decoration: none;
            color: #FFF;
        }
        .navbar-nav {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        .navbar-nav a {
            color: #FFF;
            text-decoration: none;
            font-weight: bold;
        }
        .navbar-nav a:hover { text-decoration: underline; }
        .hero {
            background-image: url('https://via.placeholder.com/1920x600/FFD700/000?text=Chips+Hero');
            background-size: cover;
            background-position: center;
            color: #000;
            padding: 100px 20px;
            text-align: center;
        }
        .section-padding { padding: 60px 20px; }
        .row {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .col-md-3, .col-md-4, .col-md-6 {
            flex: 1;
            min-width: 250px;
        }
        .col-md-3 { flex-basis: calc(25% - 20px); }
        .col-md-4 { flex-basis: calc(33.333% - 20px); }
        .col-md-6 { flex-basis: calc(50% - 20px); }
        .card {
            background-color: #FFD700;
            border-radius: 5px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card-title { margin-bottom: 10px; }
        .list-unstyled { list-style: none; }
        .list-unstyled li { margin-bottom: 10px; }
        .form-control {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-weight: bold;
        }
        .whatsapp-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background-color: #25d366;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            transition: transform 0.3s;
            z-index: 1000;
            text-decoration: none;
        }
        .whatsapp-btn:hover { transform: scale(1.1); }
        .call-btn { margin-left: 10px; }
        footer {
            background-color: #FF8C00;
            color: #FFF;
            text-align: center;
            padding: 20px;
        }
        @media (max-width: 768px) {
            .navbar .container { flex-direction: column; }
            .navbar-nav { margin-top: 10px; gap: 10px; }
            .row { flex-direction: column; }
            .col-md-3, .col-md-4, .col-md-6 { flex-basis: 100%; }
            .hero { padding: 50px 20px; }
            .display-4 { font-size: 2rem; }
            .btn-lg { padding: 12px 24px; font-size: 1rem; }
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="container">
            <a class="navbar-brand" href="#hero">Chips King</a>
            <ul class="navbar-nav">
                <li><a href="#about">About</a></li>
                <li><a href="#why-us">Why Us</a></li>
                <li><a href="#profit">Profit</a></li>
                <li><a href="#offer">Offer</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <a href="tel:+919876543210" class="btn btn-yellow call-btn">Call Now</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="hero">
        <div class="container">
            <h1 class="display-4 fw-bold text-red">Har Bite Mein Taste, Har Packet Mein Profit!</h1>
            <p class="lead fw-bold">Chips King Franchise se Business Grow Karein – Low Investment, High Returns! Kirana Owners, Small Businessmen, Startups – Sab Ke Liye Mauka!</p>
            <a href="https://wa.me/919876543210?text=Hello%20Chips%20King%2C%20Main%20franchise%20ke%20bare%20mein%20jaan%20na%20chahta%20hoon" class="btn btn-red btn-lg" target="_blank">WhatsApp Pe Contact Karein</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section-padding bg-light">
        <div class="container">
            <h2 class="text-center fw-bold text-red">Chips King Ke Baare Mein</h2>
            <p class="text-center lead">Chips King ek trusted brand hai jo aapko high-profit chips business ka mauka deta hai. Hamare products fast-selling hain, affordable pricing ke saath, aur market-tested flavors se bharpoor.</p>
            <ul class="list-unstyled text-center">
                <li class="fw-bold">30%–60% Profit Margins – Har Sale Pe Paise Kamayein!</li>
                <li class="fw-bold">Fast-Selling Chips – Kirana Stores Mein Demand High!</li>
                <li class="fw-bold">Low Investment – ₹50,000 Se Shuruat!</li>
                <li class="fw-bold">Market-Tested Flavors – Masala, Cheese, Salted – Sabko Pasand!</li>
            </ul>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section id="why-us" class="section-padding bg-orange">
        <div class="container">
            <h2 class="text-center fw-bold text-white">Kyun Chips King Choose Karein?</h2>
            <div class="row text-center">
                <div class="col-md-3">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Attractive Packaging</h5>
                        <p class="card-text">Eye-catching design se sales badhein!</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Local Market Demand</h5>
                        <p class="card-text">Har Area Mein Chips Ki Need – Wholesalers Ke Liye Ideal!</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Business Support</h5>
                        <p class="card-text">Training, Marketing, aur Supply Chain Help!</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Repeat Customers</h5>
                        <p class="card-text">Quality se loyal customers banayein!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Profit Calculation Section -->
    <section id="profit" class="section-padding bg-light">
        <div class="container">
            <h2 class="text-center fw-bold text-red">Profit Calculation – Dekhiye Kitna Kamayein!</h2>
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Per Packet Profit</h5>
                        <p class="card-text display-6">₹5–₹10</p>
                        <p>Har Packet Pe Itna Profit!</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">100 Packets/Day</h5>
                        <p class="card-text display-6">₹500–₹1,000</p>
                        <p>Daily Earning – Easy Hai!</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <h5 class="card-title fw-bold text-red">Monthly Income</h5>
                        <p class="card-text display-6">₹15,000–₹30,000+</p>
                        <p>30 Din Mein Itna Kamayein – Business Grow Karein!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Limited Offer Section -->
    <section id="offer" class="section-padding bg-red text-white text-center">
        <div class="container">
            <h2 class="fw-bold">Limited Offer – Abhi Join Karein!</h2>
            <p class="lead fw-bold">Sirf 1 Area Mein 1 Partner – Exclusive Territory!</p>
            <p class="fw-bold">Limited Slots Available – Jaldi Karein, Warna Miss Ho Jayega!</p>
            <a href="https://wa.me/919876543210?text=Hello%20Chips%20King%2C%20Main%20limited%20offer%20ke%20bare%20mein%20jaan%20na%20chahta%20hoon" class="btn btn-yellow btn-lg" target="_blank">Abhi Apply Karein</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section-padding bg-light">
        <div class="container">
            <h2 class="text-center fw-bold text-red">Contact Us – Inquiry Karein!</h2>
            <div class="row">
                <div class="col-md-6">
                    <h5 class="fw-bold">Direct Contact</h5>
                    <p>Phone: +91 98765 43210</p>
                    <p>Email: info@chips-king.com</p>
                    <p>Address: Your City, India</p>
                    <a href="tel:+919876543210" class="btn btn-orange btn-lg">Call Now</a>
                </div>
                <div class="col-md-6">
                    <h5 class="fw-bold">Inquiry Form</h5>
                    <form id="contactForm">
                        <input type="text" class="form-control" id="name" placeholder="Aapka Naam" required>
                        <input type="tel" class="form-control" id="phone" placeholder="Phone Number" required>
                        <textarea class="form-control" id="message" rows="3" placeholder="Message (e.g., Franchise Inquiry)" required></textarea>
                        <button type="submit" class="btn btn-red">Submit Karein</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Chips King. All Rights Reserved. | Business Grow Karein!</p>
    </footer>

    <!-- WhatsApp Button -->
    <a href="https://wa.me/919876543210?text=Hello%20Chips%20King%2C%20Main%20inquiry%20kar%20raha%20hoon" class="whatsapp-btn" target="_blank">
        <img src="https://via.placeholder.com/60x60/25d366/ffffff?text=WA" alt="WhatsApp">
    </a>

    <script>
        // Smooth scrolling for navbar links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Form submission (basic alert for demo; integrate with backend for real leads)
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const message = document.getElementById('message').value;
            alert(`Thank you ${name}! We will contact you at ${phone}. Message: ${message}`);
            // In production, send to server or email service like EmailJS
        });
    </script>
</body>
</html>
