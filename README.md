<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTC - Maa Tara Construction</title>

    <!-- 🎨 Basic Styling -->
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: #34495e;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
        }
        nav a:hover {
            color: #f39c12;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 400px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
        }
        .hero h1 {
            font-size: 50px;
            margin: 0;
        }
        .hero p {
            font-size: 22px;
        }
        .section {
            padding: 50px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }
        .service-card {
            background: white;
            width: 300px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
        }
        .service-card img {
            width: 100%;
            border-radius: 10px;
        }
        form {
            background: white;
            padding: 30px;
            border-radius: 10px;
            width: 400px;
            margin: auto;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
        }
        input, textarea {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #2c3e50;
            color: white;
            padding: 12px;
            width: 100%;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        button:hover {
            background-color: #f39c12;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <!-- 🏗 HEADER -->
    <header>
    <img src="images/logo.png" alt="MTC Logo" style="height: 60px;">
    <h1>MTC – Maa Tara Construction</h1>
    <p>Building Your Dreams with Strength & Trust</p>
</header>

    <!-- 🔗 NAVIGATION -->
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- 🌇 HERO SECTION -->
    <section class="hero" id="home">
        <h1>Welcome to MTC</h1>
        <p>Your Trusted Construction Partner</p>
    </section>

    <!-- 🏗 SERVICES SECTION -->
    <section class="section" id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1581091012184-5c814c3f1e5c?auto=format&fit=crop&w=800&q=80" alt="Residential">
                <h3>Residential Projects</h3>
                <p>We design and build beautiful, safe, and modern homes.</p>
            </div>
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1?auto=format&fit=crop&w=800&q=80" alt="Commercial">
                <h3>Commercial Buildings</h3>
                <p>We construct reliable and strong office and commercial spaces.</p>
            </div>
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1533106418989-88406c7cc8bb?auto=format&fit=crop&w=800&q=80" alt="Road Construction">
                <h3>Infrastructure</h3>
                <p>From roads to bridges, we build essential infrastructure for tomorrow.</p>
            </div>
        </div>
    </section>

    <!-- 📬 CONTACT FORM -->
    <section class="section" id="contact">
        <h2>Contact Us</h2>
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <p style="margin-top: 10px;">📍 Cuttack , India | 📞 +91-7008688691</p>
    </section>

    <!-- 🔻 FOOTER -->
    <footer>
        <p>© 2025 MTC – Maa Tara Construction. All Rights Reserved.</p>
    </footer>

</body>
</html>




