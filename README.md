<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Organic Earth</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      line-height: 1.6;
      background-color: #f0f9f0;
      color: #333;
    }

    header {
      background: #2e7d32;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: #c8e6c9;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    .hero button {
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #388e3c;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }

    .products {
      padding: 2rem;
      background: #ffffff;
    }

    .products h2 {
      text-align: center;
      margin-bottom: 2rem;
    }

    .product-list {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .product-card {
      background: #e8f5e9;
      border: 1px solid #ccc;
      padding: 1rem;
      text-align: center;
      border-radius: 10px;
      width: 200px;
    }

    .product-card img {
      width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    .contact {
      padding: 2rem;
      background: #f1f8e9;
    }

    .contact form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .contact input, .contact textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact button {
      padding: 10px;
      background: #43a047;
      color: white;
      border: none;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #2e7d32;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>🌱 Organic Earth</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Pure. Natural. Healthy.</h2>
    <p>Your one-stop shop for organic groceries & wellness</p>
    <button onclick="alert('Thank you for visiting!')">Shop Now</button>
  </section>

  <section id="products" class="products">
    <h2>Our Organic Picks</h2>
    <div class="product-list">
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Organic Honey">
        <h3>Organic Honey</h3>
        <p>₹299 - 250g</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Brown Rice">
        <h3>Brown Rice</h3>
        <p>₹199 - 1kg</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Herbal Tea">
        <h3>Herbal Tea</h3>
        <p>₹149 - 100g</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form id="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Organic Earth. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('contact-form').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Thank you! We will get in touch soon.');
    });
  </script>

</body>
</html>
