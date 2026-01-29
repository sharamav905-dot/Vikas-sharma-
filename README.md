<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Royal Furniture</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4b2e2e;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #6b3f3f;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            padding: 30px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .card {
            background: white;
            width: 300px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            text-align: center;
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card h3 {
            padding: 10px;
        }
        footer {
            background-color: #4b2e2e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        .visit-btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #6b3f3f;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Royal Furniture</h1>
    <p>Comfort • Style • Quality</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container" id="products">
    <h2 style="text-align:center;">Our Products</h2>
    <div class="products">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1586023492125-27b2c045efd7" alt="Sofa">
            <h3>Luxury Sofa</h3>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1616594039964-ae9021a400a0" alt="Bed">
            <h3>Modern Bed</h3>
        </div>
    </div>
</div>

<div class="container" id="contact" style="text-align:center;">
    <h2>Visit Our Store</h2>
    <p>High quality furniture for your home & office</p>
    <a class="visit-btn" href="https://yourwebsite-link.com" target="_blank">
        Visit Our Website
    </a>
</div>

<footer>
    <p>© 2026 Royal Furniture. All Rights Reserved.</p>
</footer>

</body>
</html>
