<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Brooklyn Shoes Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;900&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      color: #1F2937;
    }

    header {
      background-color: #1F2937;
      color: #F9FAF8;
      display: flex;
      justify-content: space-between;
      padding: 20px;
      align-items: center;
    }

    header .logo {
      font-size: 24px;
      font-weight: bold;
    }

    header .nav-links {
      display: flex;
      align-items: center;
    }

    header .nav-links p {
      font-size: 14px;
      margin: 0 10px;
    }

    header .nav-links .blue {
      color: blue;
    }

    header .nav-links .red {
      color: red;
    }

    header .nav-links a {
      color: #E5E7EB;
      margin-left: 20px;
      text-decoration: none;
      font-size: 14px;
    }

    header .login-btn {
      margin-left: 20px;
      padding: 5px 15px;
      background-color: #3882F6;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 14px;
    }

    /* Other styles remain unchanged */
    
  </style>
</head>
<body>
  <header>
    <div class="logo">Brooklyn Shoes Store</div>
    <div class="nav-links">
      <p class="red">ISHIMWE</p>
      <p class="red">EGIDE</p>
      <p class="blue">26661</p>
    </div>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Step into Style</h1>
      <p>Discover our latest collection of stylish and comfortable shoes. Perfect for every occasion.</p>
      <button>Shop Now</button>
    </div>
    <div class="hero-image">
      <img src="image/logo.JPG" alt="Logo">
    </div>
  </section>

  <section class="info-section">
    <h2>Our Best Sellers</h2>
    <div class="info-cards">
      <div class="card">
        <img src="image/shoes 1.jpg" alt="Shoe Image 1">
        <p>Price: $200</p>
      </div>
      <div class="card">
        <img src="image/jordan.jpg" alt="Shoe Image 2">
        <p>Price: $100</p>
      </div>
      <div class="card">
        <img src="image/antony edwards.jpg" alt="Shoe Image 3">
        <p>Price: $100</p>
      </div>
      <div class="card">
        <img src="image/timber.jpg" alt="Shoe Image 4">
        <p>Price: $400</p>
      </div>
    </div>
  </section>

  <section class="quote-section">
    <p>"Brooklyn Shoes Store, or a testimonial from a customer. Maybe it's just filling up space, or maybe people will actually read it. Who knows? All I know is that it looks nice.</p>
    <p class="author">-Thor, God of Thunder</p>
  </section>

  <section class="call-to-action">
    <p>Call to action! It's time!</p>
    <p>Sign up for our product by clicking that button right over there!</p>
    <button>Sign up</button>
  </section>

  <footer>
    <p>© Brooklyn Shoes Store 2021. All rights reserved.</p>
  </footer>
</body>
</html>
