<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GILL PRODUCT COMPANY</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      color: #333;
      background-color: #f9f9f9;
      line-height: 1.6;
    }

    .header {
      background: #fff;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-weight: bold;
      font-size: 1.5rem;
    }

    .nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }

    .nav a:hover {
      color: #0077ff;
    }

    .hero {
      background: url('https://source.unsplash.com/1600x700/?furniture,modern') center/cover no-repeat;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      position: relative;
    }

    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
    }

    .hero-content {
      position: relative;
      z-index: 1;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    .btn {
      background: #0077ff;
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      margin-top: 1rem;
      cursor: pointer;
      text-decoration: none;
    }

    .btn:hover {
      background: #005ec4;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
    }

    .products {
      display: grid;
      gap: 2rem;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    .product-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
    }

    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product-card h3 {
      margin: 1rem 0 0.5rem;
    }

    .product-card p {
      padding: 0 1rem 1rem;
      color: #666;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header class="header">
    <div class="logo">GILL PRODUCT COMPANY</div>
    <nav class="nav">
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-content">
      <h1>Welcome to GILL PRODUCT COMPANY</h1>
      <p>High-quality furniture products made with craftsmanship.</p>
      <a href="#products" class="btn">View Products</a>
    </div>
  </section>

  <section id="products" class="section">
    <h2 class="section-title">Our Products</h2>
    <div class="products">
      <div class="product-card">
        <img style="width:auto;" src="image31.jpg" alt="Table">
        <h3>Table</h3>
        <p>Durable and stylish table for everyday use.</p>
     </div>
      <div class="product-card">
        <img style="width: auto;" src="image30.png" alt="Chair">
        <h3>Chair</h3>
          <p>Ergonomic and elegant chair design.</p>
      </div>
      <div class="product-card">
        <img style="width:auto;" src="image33.jpg" alt="Table with 6 Drawers">
        <h3>Cabinet</h3>
        <p>Spacious storage and workspace combined.</p>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2 class="section-title">About Us</h2>
    <p style="max-width: 800px; margin: auto; text-align: center;">
      GILL PRODUCT COMPANY is dedicated to producing timeless and durable furniture. From ergonomic chairs to elegant tables, our craftsmanship guarantees quality and comfort in every piece.
    </p>
  </section>

  <section id="contact" class="section">
    <h2 class="section-title">Contact Us</h2>
    <p style="text-align: center;">Email: info@gillproductco.com | Phone: +1 (778) 522-6004</p>
  </section>

  <footer>
    <p>&copy; 2025 GILL PRODUCT COMPANY. All rights reserved.</p>
  </footer>

</body>
</html>
