<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Burek Burgers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            background: #444;
            text-align: center;
            padding: 0.5em 0;
        }
        nav a {
            color: #fff;
            margin: 0 1em;
            text-decoration: none;
        }
        .hero {
            background: #ffcc00;
            height: 50vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #333;
        }
        .hero h2 {
            margin: 0;
            font-size: 2em;
        }
        .menu {
            padding: 2em;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            background: #fff;
            padding: 1em;
            margin: 1em;
            border: 1px solid #ddd;
            width: calc(33% - 2em);
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Burek Burgers</h1>
        <p>We work daily from 10:00 - 20:30</p>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#promo">Promo</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h2>Delicious Burgers Delivered to Your Door</h2>
    </div>
    <section id="menu" class="menu">
        <div class="menu-item">
            <h3>Combo</h3>
            <p>Delicious combo meals</p>
        </div>
        <div class="menu-item">
            <h3>Burgers</h3>
            <p>Our signature burgers</p>
        </div>
        <div class="menu-item">
            <h3>Wraps</h3>
            <p>Fresh and tasty wraps</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Burek Burgers</p>
    </footer>
</body>
</html>
