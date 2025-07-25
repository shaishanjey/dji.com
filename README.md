
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>DJI Professional Drones</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background-image: url('https://www.dji.com/images/home/banner.jpg');
            background-size: cover;
            color: #fff;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background: #fff;
            margin: 10px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.3);
            border-radius: 10px;
            text-align: center;
        }
        .card img {
            width: 100%;
            border-radius: 10px;
        }
        .card button {
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #000;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .card button:hover {
            background-color: #333;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>DJI Professional Drones</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="products.html">Products</a>
    <a href="about.html">About</a>
</nav>

<div class="hero">
    <h2>Experience the Future of Aerial Photography</h2>
    <p>High-end drones for professionals and enthusiasts</p>
</div>

<div class="content">
    <div class="card">
        <img src="https://www.dji.com/assets/images/drones/mavic3.jpg" alt="DJI Mavic 3">
        <h3>DJI Mavic 3</h3>
        <p>The most advanced compact drone with dual cameras.</p>
        <button onclick="window.location.href='mavic3.html'">Learn More</button>
    </div>
    <div class="card">
        <img src="https://www.dji.com/assets/images/drones/air2s.jpg" alt="DJI Air 2S">
        <h3>DJI Air 2S</h3>
        <p>Capture stunning 5.4K video with intelligent flight modes.</p>
        <button onclick="window.location.href='air2s.html'">Learn More</button>
    </div>
    <div class="card">
        <img src="https://www.dji.com/assets/images/drones/phantom4.jpg" alt="DJI Phantom 4">
        <h3>DJI Phantom 4 Pro</h3>
        <p>Legendary drone for professionals with advanced sensors.</p>
        <button onclick="window.location.href='phantom4.html'">Learn More</button>
    </div>
</div>

<footer>
    <p>&copy; 2025 DJI Drones. All Rights Reserved.</p>
</footer>

</body>
</html>
