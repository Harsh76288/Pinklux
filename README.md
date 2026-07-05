<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pinklux Store</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>💖 Pinklux Store</h1>

  <div class="cart">
    🛒 Cart: <span id="cartCount">0</span>
  </div>

  <nav>
    <a href="#">Home</a>
    <a href="#">Clothes</a>
    <a href="#">Shoes</a>
    <a href="#">Beauty</a>
    <a href="checkout.html">Checkout 🧾</a>
  </nav>
</header>

<section class="hero">
  <h2>Trendy Fashion & Beauty Collection</h2>
  <p>Clothes • Shoes • Beauty • Men's Outfit</p>
  <button>Shop Now</button>
</section>

<section class="products">

  <div class="card">
    👗 Pink Dress
    <button onclick="addToCart()">Add to Cart</button>
    <button onclick="removeFromCart()">Remove</button>
  </div>

  <div class="card">
    👟 Sneakers
    <button onclick="addToCart()">Add to Cart</button>
    <button onclick="removeFromCart()">Remove</button>
  </div>

  <div class="card">
    💄 Lipstick Set
    <button onclick="addToCart()">Add to Cart</button>
    <button onclick="removeFromCart()">Remove</button>
  </div>

  <div class="card">
    🧔 Men's Outfit
    <button onclick="addToCart()">Add to Cart</button>
    <button onclick="removeFromCart()">Remove</button>
  </div>

</section>

<footer>
  <p>© 2026 Pinklux 💖 All Rights Reserved</p>
</footer>

<script src="script.js"></script>

</body>
</html>
