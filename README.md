<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paging – Nachhaltige Verpackungslösungen</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    * { margin:0; padding:0; box-sizing:border-box; }

    body {
      font-family: 'Inter', sans-serif;
      background:#ffffff;
      color:#1a1a1a;
      line-height:1.6;
    }

    header {
      border-bottom:1px solid #e5e5e5;
      padding:20px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    header h1 {
      font-size:1.5rem;
      font-weight:600;
    }

    nav a {
      margin-left:25px;
      text-decoration:none;
      color:#333;
      font-size:0.95rem;
    }

    nav a:hover { color:#2f7d32; }

    .hero {
      padding:100px 40px;
      max-width:1100px;
      margin:auto;
    }

    .hero h2 {
      font-size:2.5rem;
      margin-bottom:20px;
      font-weight:600;
    }

    .hero p {
      max-width:600px;
      color:#555;
      margin-bottom:30px;
    }

    .btn {
      background:#2f7d32;
      color:white;
      padding:12px 20px;
      text-decoration:none;
      border-radius:6px;
      font-size:0.9rem;
    }

    section {
      max-width:1100px;
      margin:80px auto;
      padding:0 40px;
    }

    h3 {
      font-size:1.8rem;
      margin-bottom:20px;
      font-weight:600;
    }

    .grid {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
      gap:30px;
    }

    .box {
      border:1px solid #e5e5e5;
      padding:25px;
      border-radius:8px;
    }

    .box h4 {
      margin-bottom:10px;
      font-size:1.1rem;
    }

    .box p {
      color:#555;
      font-size:0.95rem;
    }

    .team {
      display:flex;
      gap:30px;
      flex-wrap:wrap;
    }

    .member {
      flex:1;
      min-width:220px;
      border:1px solid #e5e5e5;
      padding:20px;
      border-radius:8px;
    }

    footer {
      border-top:1px solid #e5e5e5;
      padding:40px;
      text-align:center;
      font-size:0.85rem;
      color:#777;
    }

    @media(max-width:600px){
      header { flex-direction:column; gap:10px; }
      nav a { margin:0 10px; }
    }

  </style>
</head>

<body>

<header>
  <h1>Paging</h1>
  <nav>
    <a href="#leistungen">Leistungen</a>
    <a href="#material">Material</a>
    <a href="#anwendungen">Anwendungen</a>
    <a href="#unternehmen">Unternehmen</a>
    <a href="#kontakt">Kontakt</a>
  </nav>
</header>

<section class="hero">
  <h2>Nachhaltige Verpackungslösungen für vielfältige Anwendungen</h2>
  <p>
    Paging entwickelt und produziert umweltfreundliche Verpackungen auf Basis von PHA.
    Unsere Lösungen sind darauf ausgelegt, konventionelle Kunststoffe zu ersetzen und
    nachhaltige Alternativen für unterschiedliche Einsatzbereiche bereitzustellen.
  </p>
  <a class="btn" href="#kontakt">Kontakt aufnehmen</a>
</section>

<section id="leistungen">
  <h3>Leistungen</h3>
  <div class="grid">
    <div class="box">
      <h4>Entwicklung</h4>
      <p>Konzeption und Gestaltung nachhaltiger Verpackungslösungen.</p>
    </div>
    <div class="box">
      <h4>Produktion</h4>
      <p>Herstellung von Verpackungen auf Basis moderner Biokunststoffe.</p>
    </div>
    <div class="box">
      <h4>Anpassung</h4>
      <p>Individuelle Lösungen für verschiedene Produkte und Branchen.</p>
    </div>
  </div>
</section>

<section id="material">
  <h3>Material: PHA</h3>
  <p>
    Polyhydroxyalkanoate (PHA) sind biobasierte Kunststoffe, die als nachhaltige
    Alternative zu herkömmlichen Materialien eingesetzt werden können.
    Sie bieten Potenzial zur Reduzierung von Umweltbelastungen und unterstützen
    langfristig ressourcenschonende Verpackungssysteme.
  </p>
</section>

<section id="anwendungen">
  <h3>Anwendungen</h3>
  <div class="grid">
    <div class="box">
      <h4>Konsumgüter</h4>
      <p>Verpackungen für alltägliche Produkte.</p>
    </div>
    <div class="box">
      <h4>Technische Anwendungen</h4>
      <p>Schutzverpackungen für spezialisierte Produkte.</p>
    </div>
    <div class="box">
      <h4>Sonderlösungen</h4>
      <p>Individuell entwickelte Verpackungskonzepte.</p>
    </div>
  </div>
</section>

<section id="unternehmen">
  <h3>Unternehmen</h3>
  <p>
    Paging ist ein Projekt mit dem Ziel, nachhaltige Verpackungen praktisch umzusetzen
    und weiterzuentwickeln. Der Fokus liegt auf realen Anwendungen und der kontinuierlichen
    Verbesserung von Material und Design.
  </p>

  <div class="team">
    <div class="member">
      <h4>Jacob Niehus</h4>
      <p>Entwicklung und Umsetzung</p>
    </div>
    <div class="member">
      <h4>Luis Tan</h4>
      <p>Design und Konzeption</p>
    </div>
  </div>
</section>

<section id="kontakt">
  <h3>Kontakt</h3>
  <p>
    Für Anfragen oder weitere Informationen kontaktieren Sie uns bitte per E-Mail.
  </p>
  <p>
    Jacob_Hugo.Niehus@gmx.de<br>
    luis.tan@outlook.com
  </p>
</section>

<footer>
  <p>© 2026 Paging – Nachhaltige Verpackungslösungen</p>
</footer>

</body>
</html>
