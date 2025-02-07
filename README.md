<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>A.K Events & Tent House - Complete Event Solutions</title>

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8f5f0;
            color: #333;
            transition: background-color 0.3s, color 0.3s;
        }

        .header {
            background-color: #1a3657;
            color: white;
            padding: 1.5rem;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .contact-banner {
            background-color: #f8f5f0;
            padding: 1.2rem;
            text-align: center;
            margin-top: 85px;
            position: fixed;
            width: 100%;
            z-index: 99;
            border-bottom: 1px solid #ddd;
        }

        .contact-banner p {
            margin: 0.3rem 0;
            color: #333;
        }

        .banner {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('event-bg.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
            color: white;
            padding: 2rem;
            padding-top: 180px;
        }

        .services {
            padding: 4rem 2rem;
            background-color: #ffffff;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: #fff;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            border: 1px solid #eee;
        }

        .why-choose {
            padding: 4rem 2rem;
            background-color: #f8f5f0;
            text-align: center;
        }

        .footer {
            background-color: #1a3657;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        .contact-button {
            background-color: #c5a047;
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-weight: 600;
            cursor: pointer;
            margin-top: 1.5rem;
            transition: background-color 0.3s;
        }

        .contact-button:hover {
            background-color: #b08d3c;
        }

        a {
            color: #1a3657;
            text-decoration: none;
        }

        /* Dark Theme Styles */
        body.dark {
            background-color: #1a3657;
            color: #fff;
        }

        body.dark .header {
            background-color: #2d3a4b;
        }

        body.dark .contact-banner {
            background-color: #333;
        }

        body.dark .footer {
            background-color: #2d3a4b;
        }

        /* Toggle Button */
        .theme-toggle {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: #c5a047;
            color: white;
            padding: 0.5rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        @media (max-width: 768px) {
            .contact-banner {
                position: relative;
                margin-top: 0;
            }

            .header {
                position: relative;
            }

            .banner {
                padding-top: 2rem;
                height: auto;
                min-height: 100vh;
            }

            .mobile-numbers {
                display: block;
                margin: 0.5rem 0;
            }
        }

    </style>

</head>

<body>

    <!-- Theme Toggle Button -->
    <button class="theme-toggle" onclick="toggleTheme()">Toggle Dark/Light Theme</button>

    <header class="header">
        <h1>A.K EVENTS & TENT HOUSE</h1>
    </header>

    <div class="contact-banner">
        <p>Asif Khan (Proprietor)</p>
        <p>
            <a href="tel:7676965155">76769 65155</a> |
            <a href="tel:7676455797">7676455797</a> |
            <a href="tel:9880488847">98804 88847</a>
        </p>
        <p>Khajisonnenahalli, Kannamangala Post, Bidarahalli Hobli, Bangalore – 560067</p>
    </div>

    <section class="banner">
        <h2 style="font-size: 2.5rem; margin-bottom: 1rem;">Complete Event Solutions</h2>
        <p style="font-size: 1.2rem; margin-bottom: 1.5rem;">For Weddings, Functions & Celebrations</p>
        <button class="contact-button">GET FREE CONSULTATION</button>
    </section>

    <section class="services">
        <h2 style="color: #1a3657; text-align: center; margin-bottom: 2rem;">Our Services</h2>
        <div class="service-grid">
            <div class="service-card">
                <h3 style="color: #1a3657;">Event Lights & Sound Systems</h3>
                <p style="color: #666; margin-top: 1rem;">Professional audio-visual solutions for perfect ambiance</p>
            </div>
            <div class="service-card">
                <h3 style="color: #1a3657;">Tents & Stage Setup</h3>
                <p style="color: #666; margin-top: 1rem;">Customized structures for any event size</p>
            </div>
            <div class="service-card">
                <h3 style="color: #1a3657;">Seating Arrangements</h3>
                <p style="color: #666; margin-top: 1rem;">Comfortable and elegant seating solutions</p>
            </div>
            <div class="service-card">
                <h3 style="color: #1a3657;">Decorative Services</h3>
                <p style="color: #666; margin-top: 1rem;">Transformative decorations for your special occasion</p>
            </div>
        </div>
    </section>

    <section class="why-choose">
        <h2 style="color: #1a3657; margin-bottom: 2rem;">Why Choose Us?</h2>
        <div style="font-size: 1.1rem; color: #444;">
            <p style="margin: 1rem 0;">✔ Reliable & Trustworthy Services</p>
            <p style="margin: 1rem 0;">✔ Affordable Pricing Packages</p>
            <p style="margin: 1rem 0;">✔ Professional Event Management</p>
            <p style="margin: 1rem 0;">✔ Customized Services</p>
        </div>
    </section>
  
      <section class="pricing">
        <h2 style="color: #1a3657; text-align: center; margin-bottom: 2rem;">Our Pricing Plans</h2>
        <div class="service-grid">
            <!-- Silver Plan -->
            <div class="service-card">
                <h3 style="color: #1a3657;">Silver Plan</h3>
                <p style="color: #666; margin-top: 1rem;">Perfect for small and intimate events</p>
                <h4 style="color: #1a3657; font-size: 1.5rem;">₹ 4999</h4>
            </div>

            <!-- Gold Plan -->
            <div class="service-card">
                <h3 style="color: #1a3657;">Gold Plan</h3>
                <p style="color: #666; margin-top: 1rem;">Ideal for medium-sized events</p>
                <h4 style="color: #1a3657; font-size: 1.5rem;">₹ 6999</h4>
            </div>

            <!-- Platinum Plan -->
            <div class="service-card">
                <h3 style="color: #1a3657;">Platinum Plan</h3>
                <p style="color: #666; margin-top: 1rem;">Best suited for grand events and celebrations</p>
                <h4 style="color: #1a3657; font-size: 1.5rem;">₹ 8999</h4>
            </div>
        </div>
    </section>

    <!-- Contact Form -->
    <section class="contact-form">
        <h2 style="color: #1a3657; text-align: center; margin-bottom: 2rem;">Contact Us</h2>
        <form action="https://formsubmit.co/info@akevents.store" method="POST" style="text-align: center;">
            <input type="text" name="name" placeholder="Your Name" required style="padding: 10px; margin: 10px; width: 80%;"><br>
            <input type="email" name="email" placeholder="Your Email" required style="padding: 10px; margin: 10px; width: 80%;"><br>
            <textarea name="message" placeholder="Your Message" required style="padding: 10px; margin: 10px; width: 80%;"></textarea><br>
            <button type="submit" class="contact-button">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p style="margin: 1rem 0;">© 2025 A.K Events & Tent House</p>
        <p>All rights reserved</p>
    </footer>

    <script>
        function toggleTheme() {
            document.body.classList.toggle('dark');
        }
    </script>

</body>

</html>

