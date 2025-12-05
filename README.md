# DEZARIO-Fashion-
Redefining Style, One Outfit at a Time! ✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DEZARIO Fashion</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; background: #f8f8f8; }
        header { background: black; color: white; padding: 20px; text-align: center; }
        nav { display: flex; justify-content: center; background: #222; }
        nav a { color: white; padding: 14px 20px; text-decoration: none; }
        nav a:hover { background: #444; }

        .hero {
            background: url('https://i.ibb.co/qnf7YXZ/clothes-bg.jpg') center/cover no-repeat;
            height: 300px;
            display: flex; justify-content: center; align-items: center;
            color: white; text-shadow: 2px 2px 10px black;
            font-size: 2rem; font-weight: bold;
        }

        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px; padding: 20px; }
        .product {
            background: white; border-radius: 8px; padding: 10px; text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img { width: 100%; border-radius: 8px; }

        footer {
            background: black; color: white; padding: 20px; text-align: center; margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>DEZARIO Fashion</h1>
    <p>Stylish & Affordable Retail Clothing for Everyone</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">New Arrivals</a>
    <a href="#">Men & Women</a>
    <a href="#">Kids Collection</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    Stylish • Comfortable • Affordable
</div>

<h2 style="text-align:center; margin-top:20px;">Our Latest Products</h2>

<div class="products">
    <div class="product">
        <img src="https://i.ibb.co/8d6D3yG/kids-cloth1.jpg" alt="Kids T-Shirt">
        <h3>Kids T-Shirt</h3>
        <p>৳250</p>
    </div>

    <div class="product">
        <img src="https://i.ibb.co/YjVfWxf/kids-cloth2.jpg" alt="Winter Hoodie">
        <h3>Winter Hoodie</h3>
        <p>৳450</p>
    </div>

    <div class="product">
        <img src="https://i.ibb.co/M2c3Jzb/kids-cloth3.jpg" alt="Girls Frock">
        <h3>Girls Frock</h3>
        <p>৳350</p>
    </div>
</div>

<footer>
    <p>Contact: 018XXXXXXXX | Facebook: DEZARIO Fashion</p>
    <p>© 2025 All Rights Reserved</p>
</footer>

</body>
</html>
