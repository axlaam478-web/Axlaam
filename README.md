<!DOCTYPE html>
<html lang="en">
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
