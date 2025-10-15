<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rika Restaurant & Café</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family:'Poppins',sans-serif;}
    body {background:#fffaf5; color:#3b2e2a;}
    header {background:#4e342e; color:#fff; padding:20px; text-align:center;}
    header img {height:80px;}
    nav {background:#3b2e2a; text-align:center; padding:10px;}
    nav a {color:#fff; margin:0 15px; text-decoration:none; font-weight:bold;}
    nav a:hover {color:#ffcc80;}
    section {padding:50px 20px; text-align:center;}
    .hero {background:url('hero.jpg') center/cover no-repeat; color:#fff; padding:100px 20px;}
    .hero h1 {font-size:3em; margin-bottom:20px; text-shadow:2px 2px 4px #000;}
    .menu, .gallery {background:#fff;}
    .menu-items, .gallery-items {display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; margin-top:30px;}
    .menu-item, .gallery-item {background:#fffaf0; border-radius:10px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:15px;}
    .menu-item img, .gallery-item img {width:100%; border-radius:10px;}
    .btn {background:#ff9800; color:#fff; padding:10px 20px; border:none; border-radius:8px; cursor:pointer; text-decoration:none; font-weight:bold;}
    .btn:hover {background:#e68900;}
    .map iframe {width:100%; height:400px; border:0; border-radius:10px;}
    footer {background:#4e342e; color:#fff; text-align:center; padding:20px;}
    #whatsapp {position:fixed; bottom:20px; right:20px; background:#25d366; border-radius:50%; padding:15px; box-shadow:0 2px 6px rgba(0,0,0,0.3);} 
    #whatsapp img {width:40px; height:40px;}
  </style>
</head>
<body>
  <header>
    <img src="rika-logo.png" alt="Rika Logo">
    <h1>Rika Restaurant & Café</h1>
    <p>Delicious food, cozy vibes, and unforgettable moments.</p>
  </header>

  <nav>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#order">Order</a>
    <a href="#map">Location</a>
  </nav>

  <section class="hero">
    <h1>Welcome to Rika</h1>
    <p>Your favorite spot for pizza, crepes, grilled meals, and all-day drinks.</p>
    <a href="https://wa.me/201116224586" target="_blank" class="btn">Order on WhatsApp</a>
  </section>

  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <img src="dish1.jpg" alt="Pizza">
        <h3>Signature Pizza</h3>
      </div>
      <div class="menu-item">
        <img src="dish2.jpg" alt="Crepe">
        <h3>Sweet & Savory Crepes</h3>
      </div>
      <div class="menu-item">
        <img src="dish3.jpg" alt="Grilled Meal">
        <h3>Grilled Platters</h3>
      </div>
    </div>
  </section>

  <section id="gallery" class="gallery">
    <h2>Gallery</h2>
    <p>Follow us on Instagram for more!</p>
    <a href="https://www.instagram.com/rika_restaurant_cafe/" target="_blank" class="btn">Visit Instagram</a>
    <div class="gallery-items">
      <div class="gallery-item"><img src="gallery1.jpg" alt="Rika Interior"></div>
      <div class="gallery-item"><img src="gallery2.jpg" alt="Food"></div>
      <div class="gallery-item"><img src="gallery3.jpg" alt="Drinks"></div>
    </div>
  </section>

  <section id="order" class="order">
    <h2>Order & Reservations</h2>
    <p>Order directly via WhatsApp or call us to reserve your table.</p>
    <a href="https://wa.me/201116224586" class="btn" target="_blank">Chat on WhatsApp</a>
  </section>

  <section id="map" class="map">
    <h2>Find Us</h2>
    <iframe src="https://www.google.com/maps?q=Rika%20Restaurant%20%26%20Cafe%20New%20Cairo&output=embed"></iframe>
  </section>

  <footer>
    <p>© 2025 Rika Restaurant & Café | All Rights Reserved</p>
  </footer>

  <a id="whatsapp" href="https://wa.me/201116224586" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
</body>
</html>
