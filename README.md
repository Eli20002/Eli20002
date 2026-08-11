<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GameZone | Official Game Website</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b12;
      color: white;
    }

    header {
      background: #11111c;
      padding: 18px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 15px;
    }

    nav a:hover {
      color: #ff3b30;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px 20px;
      background:
        linear-gradient(rgba(5,5,10,.75), rgba(5,5,10,.9)),
        url("https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&w=1600&q=80")
        center/cover;
    }

    .hero h1 {
      font-size: 55px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #ccc;
      font-size: 18px;
      max-width: 650px;
      margin: auto;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 28px;
      background: #ff3b30;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    section {
      padding: 70px 8%;
    }

    .title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 35px;
    }

    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 25px;
    }

    .card {
      background: #151522;
      border-radius: 12px;
      overflow: hidden;
      transition: .3s;
    }

    .card:hover {
      transform: translateY(-7px);
    }

    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }

    .card-content {
      padding: 20px;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card p {
      color: #aaa;
      line-height: 1.5;
    }

    .about {
      text-align: center;
      max-width: 800px;
      margin: auto;
      color: #ccc;
      line-height: 1.8;
    }

    .contact {
      text-align: center;
      background: #11111c;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #08080d;
      color: #777;
    }

    @media (max-width: 600px) {
      header {
        padding: 15px 5%;
      }

      nav a {
        margin-left: 8px;
        font-size: 12px;
      }

      .hero h1 {
        font-size: 38px;
      }

      section {
        padding: 50px 5%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">🎮 GameZone</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#games">Games</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div>
      <h1>Welcome to GameZone</h1>
      <p>
        Discover exciting games, latest updates, new features
        and everything you need to know about our gaming community.
      </p>

      <a href="#games" class="btn">Explore Games</a>
    </div>
  </section>

  <section id="games">
    <h2 class="title">🔥 Featured Games</h2>

    <div class="games">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?auto=format&fit=crop&w=800&q=80">
        <div class="card-content">
          <h3>Action World</h3>
          <p>Enter an exciting world full of missions and challenges.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&w=800&q=80">
        <div class="card-content">
          <h3>Cyber Battle</h3>
          <p>Compete with players and become the ultimate champion.</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1493711662062-fa541adb3fc8?auto=format&fit=crop&w=800&q=80">
        <div class="card-content">
          <h3>Racing City</h3>
          <p>Drive fast cars and dominate the streets.</p>
        </div>
      </div>

    </div>
  </section>

  <section id="about">
    <h2 class="title">🎮 About Us</h2>

    <p class="about">
      GameZone is a gaming platform created for players.
      Here you can find game information, updates, features,
      announcements and community news.
    </p>
  </section>

  <section id="contact" class="contact">
    <h2 class="title">📞 Contact</h2>

    <p>Join our gaming community and stay updated.</p>

    <a href="#" class="btn">Join Community</a>
  </section>

  <footer>
    © 2026 GameZone. All Rights Reserved.
  </footer>

</body>
</html>
