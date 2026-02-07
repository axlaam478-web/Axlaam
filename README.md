<!DOCTYPE html>
<html lang="so">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Hodan Ali</title>
  <style>
    :root {
      --main: #6c5ce7;
      --soft: #a29bfe;
      --dark: #341f97;
      --glass: rgba(255, 255, 255, 0.18);
    }

    body {
      background: linear-gradient(135deg, #1e1e2f, #3a3a6a);
      min-height: 100vh;
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
    }

    /* ===== HERO PROFILE ===== */
    .hero {
      text-align: center;
      padding: 90px 20px 60px;
    }

    .hero img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 5px solid var(--soft);
      margin-bottom: 20px;
      object-fit: cover;
    }

    .hero h1 {
      font-size: 32px;
      margin-bottom: 8px;
    }

    .hero p {
      opacity: 0.85;
      font-size: 18px;
    }

    /* ===== NAV ===== */
    nav {
      position: sticky;
      top: 20px;
      margin: 0 auto 40px;
      width: fit-content;
      background: var(--glass);
      backdrop-filter: blur(14px);
      padding: 12px 30px;
      border-radius: 30px;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: var(--soft);
    }

    /* ===== MAIN ===== */
    main {
      max-width: 900px;
      margin: auto;
      padding: 0 25px 80px;
    }

    /* ===== CARDS ===== */
    .card {
      background: var(--glass);
      backdrop-filter: blur(14px);
      border-radius: 22px;
      padding: 35px;
      margin-bottom: 25px;
      border: 1px solid rgba(255,255,255,0.1);
    }

    .card h3 {
      color: var(--soft);
      margin-top: 0;
    }

    /* ===== SKILLS ===== */
    .skills span {
      background: rgba(255,255,255,0.25);
      padding: 8px 16px;
      border-radius: 20px;
      margin: 6px;
      display: inline-block;
      font-size: 14px;
    }

    .item h4 {
      margin-bottom: 5px;
    }

    .item small {
      color: var(--soft);
      display: block;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

<header class="hero">
  <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Hodan" alt="Hodan Ali Profile">
  <h1>Hodan Ali</h1>
  <p>Ardayad ka tirsan Tisqaad College</p>
</header>

<nav>
  <a href="#about">Ku saabsan</a>
  <a href="#skills">Xirfadaha</a>
  <a href="#experience">Waxbarashada</a>
  <a href="#contact">Xiriirka</a>
</nav>

<main>

  <section>
    <div class="card" id="about">
      <h3>Ku Saabsan</h3>
      <p>
        Waxaan ahay ardayad hammi sare leh oo wax ka barata <strong>Tisqaad College</strong>. 
        Waxaan xiiseeyaa barashada tignoolajiyada cusub iyo sidii aan aqoontayda ugu adeegi lahaa bulshada Soomaaliyeed.
      </p>
    </div>

    <div class="card" id="skills">
      <h3>Xirfadaha</h3>
      <div class="skills">
        <span>Microsoft Office</span>
        <span>Graphic Design</span>
        <span>Web Basics</span>
        <span>Maamulka Ganacsiga</span>
        <span>Communication</span>
        <span>English Language</span>
      </div>
    </div>

    <div class="card" id="experience">
      <h3>Waxbarashada & Khibrada</h3>
      <div class="item">
        <h4>Tisqaad College</h4>
        <small>2024 – Hadda</small>
        <p>Waxa aan hadda ku jiraa barashada heerka Diploma/Degree ee takhasuska [Geli takhasuskaaga halkan].</p>
      </div>
      <hr style="opacity: 0.1; margin: 20px 0;">
      <div class="item">
        <h4>Tababar Shaqo (Internship)</h4>
        <small>Janaayo 2025</small>
        <p>Ka qayb qaadashada mashaariicda aqoon kororsiga ee kulliyadda dhexdeeda.</p>
      </div>
    </div>

    <div class="card contact" id="contact">
      <h3>Xiriirka</h3>
      <p>📧 hodan.ali@email.com</p>
      <p>📞 +252 61 XXX XXXX</p>
      <p>🌍 Muqdisho, Somalia</p>
    </div>
  </section>

</main>

</body>
</html>
