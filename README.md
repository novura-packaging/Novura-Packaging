<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Novura Packaging</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #0f172a;
      color: #e2e8f0;
      line-height: 1.6;
    }

    header {
      background: radial-gradient(circle at top, #22c55e, #020617);
      padding: 100px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 15px;
    }

    header p {
      max-width: 600px;
      margin: 0 auto 20px;
      opacity: 0.85;
    }

    .btn {
      display: inline-block;
      background: #22c55e;
      color: #020617;
      padding: 12px 24px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    .btn:hover {
      background: #16a34a;
      transform: translateY(-2px);
    }

    nav {
      position: sticky;
      top: 0;
      background: rgba(2, 6, 23, 0.8);
      backdrop-filter: blur(10px);
      padding: 15px;
      text-align: center;
      border-bottom: 1px solid rgba(255,255,255,0.05);
    }

    nav a {
      color: #cbd5f5;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 500;
      transition: 0.2s;
    }

    nav a:hover {
      color: #22c55e;
    }

    section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #22c55e;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      margin-top: 25px;
    }

    .card {
      background: rgba(255,255,255,0.03);
      padding: 25px;
      border-radius: 16px;
      backdrop-filter: blur(8px);
      border: 1px solid rgba(255,255,255,0.05);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: #22c55e;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .highlight {
      background: rgba(34,197,94,0.1);
      border-left: 4px solid #22c55e;
      padding: 18px;
      border-radius: 10px;
      margin-top: 20px;
    }

    .team {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
    }

    .team-member {
      flex: 1;
      min-width: 220px;
      background: rgba(255,255,255,0.03);
      padding: 25px;
      border-radius: 16px;
      transition: 0.3s;
    }

    .team-member:hover {
      transform: translateY(-5px);
    }

    footer {
      background: #020617;
      text-align: center;
      padding: 30px;
      margin-top: 60px;
      font-size: 0.9rem;
      opacity: 0.7;
    }
  </style>
</head>

<body>

<header>
  <h1>Novura Packaging</h1>
  <p>Innovative nachhaltige Verpackungen aus PHA</p>
  <p>
    Wir sind Jacob Niehus und Luis Tann und entwickeln umweltfreundliche
    Alternativen zu Plastik – mit Fokus auf echte Anwendungen.
  </p>
  <a class="btn" href="#kontakt">Kontakt</a>
</header>

<nav>
  <a href="#idee">Idee</a>
  <a href="#pha">PHA</a>
  <a href="#prototyp">Prototyp</a>
  <a href="#team">Team</a>
  <a href="#kontakt">Kontakt</a>
</nav>

<section id="idee">
  <h2>Unsere Idee</h2>
  <p>
    Wir entwickeln nachhaltige Verpackungslösungen auf Basis von PHA.
    Ziel ist es, funktionale und umweltfreundliche Alternativen zu herkömmlichem Plastik zu schaffen.
  </p>

  <div class="highlight">
    Fokus: reale Anwendungen – z. B. Verpackungen für Angelzubehör als erster Prototyp.
  </div>
</section>

<section id="pha">
  <h2>Warum PHA?</h2>

  <div class="cards">
    <div class="card">
      <h3>Biobasiert</h3>
      <p>PHA ist ein biologisch erzeugter Kunststoff.</p>
    </div>

    <div class="card">
      <h3>Umweltfreundlicher</h3>
      <p>Reduziert langfristig Mikroplastikbelastung.</p>
    </div>

    <div class="card">
      <h3>Zukunftstechnologie</h3>
      <p>Großes Potenzial für nachhaltige Verpackungen.</p>
    </div>
  </div>
</section>

<section id="prototyp">
  <h2>Prototyp</h2>

  <div class="cards">
    <div class="card">
      <h3>1. Analyse</h3>
      <p>Material und Einsatzmöglichkeiten untersuchen.</p>
    </div>

    <div class="card">
      <h3>2. Design</h3>
      <p>Verpackung konzipieren und entwickeln.</p>
    </div>

    <div class="card">
      <h3>3. Umsetzung</h3>
      <p>Prototyp erstellen und präsentieren.</p>
    </div>
  </div>
</section>

<section id="team">
  <h2>Team</h2>

  <div class="team">
    <div class="team-member">
      <h3>Jacob Niehus</h3>
      <p>Konzept, Entwicklung & Umsetzung</p>
    </div>

    <div class="team-member">
      <h3>Luis Tann</h3>
      <p>Design, Ideen & Präsentation</p>
    </div>
  </div>
</section>

<section id="kontakt">
  <h2>Kontakt</h2>

  <div class="highlight">
    E-Mail: deine-mail@beispiel.de<br>
    Schule: Gymnasium Kronshagen<br>
    Projekt: Profilseminar
  </div>
</section>

<footer>
  <p>© 2026 Novura Packaging</p>
</footer>

</body>
</html>
