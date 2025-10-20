<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nathan Studios | Photography Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Poppins", sans-serif;
      background-color: #f7f7f7;
      color: #222;
    }

    /* --- Navbar --- */
    nav {
      background-color: #000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    nav h1 {
      color: #c19a6b;
      font-size: 1.6em;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #c19a6b;
    }

    /* --- Hero Section --- */
    .hero {
      background: url('https://images.unsplash.com/photo-1516726817505-f5ed825624d8?auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      color: white;
    }

    .hero h2 {
      font-size: 3em;
      letter-spacing: 1px;
    }

    .hero p {
      font-size: 1.3em;
      margin-top: 10px;
    }

    .btn {
      display: inline-block;
      background-color: #c19a6b;
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      margin-top: 25px;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: #a67b4f;
    }

    /* --- Portfolio Section --- */
    section {
      max-width: 1200px;
      margin: 80px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      font-size: 2.5em;
      margin-bottom: 40px;
      color: #111;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      object-fit: cover;
      height: 250px;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    /* --- Contact Section --- */
    .contact {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 60px 20px;
      margin-top: 80px;
    }

    .contact h2 {
      color: #c19a6b;
      margin-bottom: 20px;
    }

    .contact p {
      font-size: 1.1em;
      margin: 10px 0;
    }

    .contact a {
      color: #c19a6b;
      text-decoration: none;
    }

    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }

    footer a {
      color: #c19a6b;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <nav>
    <h1>Nathan Studios</h1>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="packages.html">Packages</a></li>
      <li><a href="prints.html">Prints</a></li>
      <li><a href="equipment.html">Equipment</a></li>
    </ul>
  </nav>

  <section class="hero">
    <h2>Capturing Timeless Stories</h2>
    <p>Professional • Artistic • Luxury Photography</p>
    <a href="packages.html" class="btn">Explore Packages</a>
  </section>

  <section>
    <h2>Featured Works</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?auto=format&fit=crop&w=800&q=80" alt="Portrait">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" alt="Ocean Landscape">
      <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&w=800&q=80" alt="Mountainscape">
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=800&q=80" alt="Wedding Couple">
      <img src="https://images.unsplash.com/photo-1499084732479-de2c02d45fc4?auto=format&fit=crop&w=800&q=80" alt="City Night">
      <img src="https://images.unsplash.com/photo-1542038784456-1ea8e935640e?auto=format&fit=crop&w=800&q=80" alt="Product Shoot">
    </div>
  </section>

  <section class="contact">
    <h2>Let’s Create Something Beautiful</h2>
    <p>📧 <a href="mailto:nathanstudiosphoto@gmail.com">nathanstudiosphoto@gmail.com</a></p>
    <p>📞 +63 *** *** ****</p>
    <p>📍 Philippines</p>
    <a href="about.html" class="btn">Learn More About Us</a>
  </section>

  <footer>
    <p>&copy; 2025 Nathan Studios | <a href="https://nathanstudios.github.io/">Home</a></p>
  </footer>
</body>
</html>
