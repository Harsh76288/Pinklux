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
  <nav>
    <a href="#">Home</a>
    <a href="#">Clothes</a>
    <a href="#">Shoes</a>
    <a href="#">Beauty</a>
    <a href="#">Men</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Trendy Fashion & Beauty Collection</h2>
  <p>Clothes • Shoes • Beauty • Men's Outfit</p>
  <button>Shop Now</button>
</section>

<section class="products">

  <h2>🔥 Categories</h2>

  <div class="grid">

    <div class="card">👗 Clothes</div>
    <div class="card">👟 Shoes</div>
    <div class="card">💄 Beauty Products</div>
    <div class="card">🧔 Men's Outfits</div>

  </div>

  <h2>✨ Trending Products</h2>

  <div class="grid">

    <div class="card">Pink Dress</div>
    <div class="card">Sneakers</div>
    <div class="card">Lipstick Set</div>
    <div class="card">Men Streetwear</div>

  </div>

</section>

<footer>
  <p>© 2026 Pinklux Store | All Rights Reserved 💖</p>
</footer>

</body>
</html>
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
    <a href="#">Men</a>
  </nav>
</header>

<section class="hero">
  <h2>Trendy Fashion & Beauty Collection</h2>
  <button>Shop Now</button>
</section>

<section class="products">

  <h2>🔥 Products</h2>

  <div class="grid">

    <div class="card">
      👗 Pink Dress<br>
      <button onclick="addToCart()">Add to Cart</button>
    </div>

    <div class="card">
      👟 Sneakers<br>
      <button onclick="addToCart()">Add to Cart</button>
    </div>

    <div class="card">
      💄 Lipstick<br>
      <button onclick="addToCart()">Add to Cart</button>
    </div>

    <div class="card">
      🧔 Men's Outfit<br>
      <button onclick="addToCart()">Add to Cart</button>
    </div>

  </div>

</section>

<footer>
  <p>© 2026 Pinklux 💖</p>
</footer>

<script src="script.js"></script>

</body>
</html>
let cartCount = 0;

function addToCart() {
  cartCount++;
  updateCart();
}

function removeFromCart() {
  if (cartCount > 0) {
    cartCount--;
    updateCart();
  }
}

function updateCart() {
  document.getElementById("cartCount").innerText = cartCount;
}
