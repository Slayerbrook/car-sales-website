<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Timless Autogroup | Buy & Sell Cars</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f5f5f5;
}

header {
    background: #111;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background: #222;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

.hero {
    background: url("https://images.unsplash.com/photo-1502877338535-766e1452684a") center/cover;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 32px;
    font-weight: bold;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 40px 20px;
}

.car-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.car-card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    padding: 15px;
}

.car-card img {
    width: 100%;
    border-radius: 5px;
}

button {
    padding: 10px;
    background: #00adb5;
    border: none;
    color: white;
    cursor: pointer;
    margin-top: 10px;
    width: 100%;
}

button:hover {
    background: #007b80;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Elite Motors</h1>
    <p>Find Your Dream Car Today</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Inventory</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    Premium Cars. Best Prices.
</div>

<div class="container">
    <h2>Available Cars</h2>

    <div class="car-grid">

        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d" alt="Car">
            <h3>2022 BMW M4</h3>
            <p>$72,000</p>
            <button onclick="alert('Contact us for details!')">View Details</button>
        </div>

        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1619767886558-efdc259cde1a" alt="Car">
            <h3>2023 Tesla Model S</h3>
            <p>$89,000</p>
            <button onclick="alert('Contact us for details!')">View Details</button>
        </div>

        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1583267747677-1f3e3f5f3d36" alt="Car">
            <h3>2021 Mercedes C300</h3>
            <p>$45,000</p>
            <button onclick="alert('Contact us for details!')">View Details</button>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 Elite Motors. All Rights Reserved.</p>
</footer>

</body>
</html>
