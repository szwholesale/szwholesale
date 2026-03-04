## Hi there 👋
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>S&Z Wholesale</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: #0b0b0b;
  color: #f5f5f5;
}

/* HEADER */

header {
  background: #000;
  padding: 16px 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 2px solid #e63946;
}

.logo {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo img {
  width: 45px;
  height: 45px;
  border-radius: 50%;
}

.logo-text {
  font-size: 22px;
  font-weight: bold;
  letter-spacing: 1px;
}

/* HERO */

.hero {
  padding: 90px 20px;
  text-align: center;
  background:
    radial-gradient(circle at center, rgba(230,57,70,0.15), transparent 60%),
    #0b0b0b;
}

.hero h1 {
  font-size: 44px;
  margin-bottom: 12px;
}

.hero p {
  color: #bbb;
  margin-bottom: 28px;
}

.btn {
  background: #e63946;
  color: white;
  padding: 14px 28px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.25s;
}

.btn:hover {
  background: #ff4d4d;
  transform: translateY(-2px);
}

/* SECTION */

.section {
  padding: 70px 40px;
  text-align: center;
}

.section h2 {
  margin-bottom: 40px;
  font-size: 32px;
}

/* CATEGORY GRID */

.categories {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 25px;
}

.card {
  background: #111;
  padding: 30px;
  border-radius: 12px;
  border: 1px solid #222;
  transition: 0.25s;
  position: relative;
  overflow: hidden;
}

.card::after {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: 12px;
  border: 1px solid transparent;
  background: linear-gradient(120deg, transparent, #e63946, transparent);
  opacity: 0;
  transition: 0.25s;
}

.card:hover::after {
  opacity: 1;
}

.card:hover {
  transform: translateY(-6px);
}

.card h3 {
  margin-bottom: 10px;
  color: #ff4d4d;
}

.card p {
  color: #aaa;
  font-size: 14px;
}

/* FOOTER */

footer {
  background: #000;
  padding: 25px;
  text-align: center;
  border-top: 1px solid #222;
  color: #777;
}
</style>
</head>

<body>

<header>
  <div class="logo">
    <!-- 🔥 IMPORTANT: replace with your real logo file -->
    <img src="logo.png" alt="S&Z Logo">
    <div class="logo-text">S&Z WHOLESALE</div>
  </div>
</header>

<section class="hero">
  <h1>Powering Your Store Inventory</h1>
  <p>Premium Wholesale • Fast Supply • Trusted Source</p>
  <a href="#categories" class="btn">Browse Products</a>
</section>

<section class="section" id="categories">
  <h2>Product Categories</h2>

  <div class="categories">

    <div class="card">
      <h3>Vapes & E-Juices</h3>
      <p>Nixodine vapes, disposables, and premium e-liquids.</p>
    </div>

    <div class="card">
      <h3>Smoke Shop Essentials</h3>
      <p>Glass smoking pipes and popular smoke accessories.</p>
    </div>

    <div class="card">
      <h3>Adult Wellness</h3>
      <p>Performance supplements and specialty honey products.</p>
    </div>

    <div class="card">
      <h3>Air Fresheners</h3>
      <p>Car and home fragrance best-sellers.</p>
    </div>

    <div class="card">
      <h3>Snacks & Drinks</h3>
      <p>Fast-moving beverages and convenience snacks.</p>
    </div>

    <div class="card">
      <h3>Kids Toys</h3>
      <p>Popular toys for convenience and retail stores.</p>
    </div>

    <div class="card">
      <h3>Liquor Store Items</h3>
      <p>High-demand accessories and retail essentials.</p>
    </div>

    <div class="card">
      <h3>Apparel</h3>
      <p>T-shirts and fast-selling clothing items.</p>
    </div>

    <div class="card">
      <h3>Automotive</h3>
      <p>Car care and automotive convenience products.</p>
    </div>

    <div class="card">
      <h3>Gas Station Essentials</h3>
      <p>Everyday high-turn convenience store inventory.</p>
    </div>

  </div>
</section>

<footer>
  © 2026 S&Z Wholesale. All rights reserved.
</footer>

</body>
</html>
<!--
**szwholesale/szwholesale** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
