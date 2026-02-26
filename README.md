<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Preetham 78 | Premium Outfits</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background-color: #0f0f0f;
    color: white;
}

header {
    background: black;
    padding: 20px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 24px;
    letter-spacing: 3px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    font-size: 14px;
}

.hero {
    height: 90vh;
    background: linear-gradient(to right, #000000, #1c1c1c);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: center;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    opacity: 0.8;
}

.btn {
    margin-top: 20px;
    padding: 12px 30px;
    background: gold;
    color: black;
    border: none;
    cursor: pointer;
    font-weight: bold;
}

.products {
    padding: 60px 50px;
    text-align: center;
}

.products h2 {
    margin-bottom: 40px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.product {
    background: #1c1c1c;
    padding: 20px;
    border-radius: 10px;
}

.product img {
    width: 100%;
    border-radius: 10px;
}

.product h3 {
    margin: 15px 0 5px;
}

.product p {
    color: gold;
}

.contact {
    padding: 60px 50px;
    background: black;
}

.contact h2 {
    text-align: center;
    margin-bottom: 30px;
}

form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

input, textarea {
    margin-bottom: 15px;
    padding: 12px;
    border: none;
    border-radius: 5px;
}

button {
    padding: 12px;
    background: gold;
    border: none;
    font-weight: bold;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 20px;
    background: #111;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <h1>PREETHAM 78</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#products">Shop</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Elevate Your Style</h2>
    <p>Premium Fashion for Him & Her</p>
    <button class="btn">Shop Now</button>
</section>

<section class="products" id="products">
    <h2>Featured Collection</h2>
    <div class="product-grid">
        <div class="product">
            <img src="https://via.placeholder.com/300x350" alt="Outfit">
            <h3>Luxury Streetwear</h3>
            <p>₹2,499</p>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x350" alt="Outfit">
            <h3>Premium Formal Set</h3>
            <p>₹3,999</p>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x350" alt="Outfit">
            <h3>Casual Essentials</h3>
            <p>₹1,799</p>
        </div>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    © 2026 Preetham 78. All Rights Reserved.
</footer>

</body>
</html>
