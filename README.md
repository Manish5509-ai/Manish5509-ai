<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BharmouriTrails.com</title>
  <style>
    body { margin: 0; font-family: 'Segoe UI', sans-serif; background-color: #f5f5f5; color: #333; overflow-x: hidden; }
    header {
      background-image: url('https://source.unsplash.com/1600x600/?himalaya,trek');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 100px 20px;
      text-align: center;
      animation: fadeIn 2s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    nav {
      background: #222;
      color: white;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 1.5s ease;
    }
    h2 { color: #2c3e50; }
    .gallery { display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; }
    .gallery img { width: 100%; max-width: 300px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
    .contact p { line-height: 1.8; }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>BharmouriTrails.com</h1>
    <p>Explore the Unseen Bharmour | Travel | Videography | Photography</p>
  </header>

  <nav>
    <a href="#explore">Explore</a>
    <a href="#videos">Videos</a>
    <a href="#photos">Photos</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="explore">
    <h2>Destinations to Discover</h2>
    <p>From the mystical trails of Manimahesh to the peaceful serenity of Kugti Valley and Chaurasi Temple, Bharmour offers unforgettable Himalayan experiences. Join our journey to explore culture, nature, and adventure.</p>
  </section>

  <section id="videos">
    <h2>Travel Videos & Reels</h2>
    <p>Check out reels and cinematic edits that bring Bharmour to life. Follow on Instagram <a href="https://www.instagram.com/manish__5509" target="_blank">@manish__5509</a>.</p>
    <iframe width="320" height="180" src="https://www.youtube.com/embed/tgbNymZ7vqY" title="Sample Travel Video"></iframe>
  </section>

  <section id="photos">
    <h2>Photography</h2>
    <div class="gallery">
      <img src="https://source.unsplash.com/featured/?himalayas" alt="Himalayan Landscape">
      <img src="https://source.unsplash.com/featured/?trekking" alt="Trekking">
      <img src="https://source.unsplash.com/featured/?mountain,village" alt="Mountain Village">
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Name:</strong> Manish Bharmouri</p>
    <p><strong>Mobile & WhatsApp:</strong> <a href="tel:+917876679603">7876679603</a></p>
    <p><strong>Instagram:</strong> <a href="https://www.instagram.com/manish__5509" target="_blank">@manish__5509</a></p>
  </section>

  <footer>
    <p>&copy; 2025 BharmouriTrails.com | Created by Manish Bharmouri</p>
  </footer>
</body>
</html>

