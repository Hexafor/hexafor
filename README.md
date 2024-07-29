<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hexafor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #0066cc;
            color: white;
            padding: 10px 20px;
            text-align: left;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        header h1 {
            margin: 0;
            font-size: 24px;
        }
        nav {
            background-color: #005bb5;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #004080;
        }
        .container {
            padding: 20px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: calc(33% - 40px);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .service h3 {
            margin-top: 0;
        }
        footer {
            background-color: #0066cc;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            .service {
                width: calc(50% - 40px);
            }
        }
        @media (max-width: 480px) {
            nav a {
                flex: 1 1 100%;
                text-align: center;
            }
            .service {
                width: calc(100% - 40px);
            }
            header {
                flex-direction: column;
                align-items: flex-start;
            }
            header h1 {
                font-size: 20px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Hexafor IT Consultancy</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="home">
        <h2>Welcome to Hexafor</h2>
        <p>Your trusted partner in IT Consultancy. We offer a range of services to help your business thrive in the digital age.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>IT Strategy Consulting</h3>
                <p>Align your IT strategy with your business goals to drive growth and innovation.</p>
            </div>
            <div class="service">
                <h3>Software Development</h3>
                <p>Custom software solutions tailored to meet your specific business needs.</p>
            </div>
            <div class="service">
                <h3>Cloud Solutions</h3>
                <p>Leverage the power of the cloud to enhance efficiency and scalability.</p>
            </div>
            <div class="service">
                <h3>Cybersecurity</h3>
                <p>Protect your business from cyber threats with our comprehensive security solutions.</p>
            </div>
            <div class="service">
                <h3>Data Analytics</h3>
                <p>Unlock insights from your data to drive better decision-making.</p>
            </div>
            <div class="service">
                <h3>SAP S/4 Hana</h3>
                <p>Transform your business processes with SAP S/4 Hana implementations.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>At Hexafor, we are committed to delivering top-notch IT consultancy services. Our team of experts has extensive experience in various IT domains, ensuring that we can provide the best solutions for your business.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have questions or need more information? Reach out to us:</p>
        <address>
            Flat 5, 301 High Road Leyton, London, UK<br>
            Phone: <a href="tel:+447957581746">07957 581746</a><br>
            Email: <a href="mailto:info@hexafor.com">info@hexafor.com</a>
        </address>
    </section>
</div>

<footer>
    <p>&copy; 2024 Hexafor IT Consultancy. All rights reserved.</p>
</footer>

</body>
</html>
