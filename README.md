<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NT Biocycle - Nachhaltige Verpackungen aus PHA</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f8f4;
      color: #1f2a1f;
    }

    header {
      background: linear-gradient(135deg, #2f7d32, #4caf50);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.4rem;
      margin-bottom: 15px;
    }

    header p {
      max-width: 700px;
      margin: 0 auto 20px auto;
      font-size: 1.1rem;
    }

    .btn {
      display: inline-block;
      background: white;
      color: #2f7d32;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }

    nav {
      background: #1f5d24;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h2 {
      margin-bottom: 15px;
      color: #2f7d32;
      font-size: 1.8rem;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 14px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.08);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #1f5d24;
    }

    .highlight {
      background: #e8f5e9;
      border-left: 6px solid #2f7d32;
      padding: 18px;
      border-radius: 8px;
      margin-top: 15px;
    }

    .team {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .team-member {
      flex: 1;
      min-width: 220px;
      background: white;
      padding: 20px;
      border-radius: 14px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.08);
    }

    footer {
      background: #1f2a1f;
      color: white;
      text-align: center;
      padding: 25px 20px;
      margin-top: 50px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }

      nav a {
        display: inline-block;
        margin: 8px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>NT Biocycle</h1>
    <p>Wir bringen Nachhaltigkeit ins Gespraech.</p>
    <p>
      Wir entwickeln nachhaltige Verpackungsideen aus PHA und untersuchen,
      wie Plastikalternativen im Alltag sinnvoll eingesetzt werden koennen.
    </p>
    <a class="btn" href="#kontakt">Kontakt</a>
  </header>

  <nav>
    <a href="#idee">Unsere Idee</a>
    <a href="#pha">PHA</a>
    <a href="#prototyp">Prototyp</a>
    <a href="#team">Team</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <section id="idee">
    <h2>Unsere Idee</h2>
    <p>
      Wir sind ein Schuelerprojekt und beschaeftigen uns mit nachhaltigen Verpackungen.
      Unser Ziel ist es, umweltfreundliche Alternativen zu herkoemmlichem Plastik zu entwickeln
      und aufzuzeigen, wie PHA als Biokunststoff eingesetzt werden kann.
    </p>

    <div class="highlight">
      Unser Fokus liegt auf nachhaltigen Verpackungen. Ein erster moeglicher Prototyp ist eine
      Verpackung fuer Angelzubehoer bzw. Angelkoeder, aber das ist nur ein Beispiel fuer die Anwendung.
    </div>
  </section>

  <section id="pha">
    <h2>Warum PHA?</h2>
    <div class="cards">
      <div class="card">
        <h3>Biobasierter Kunststoff</h3>
        <p>
          PHA ist ein Biokunststoff, der als nachhaltigere Alternative zu herkoemmlichem Plastik
          diskutiert wird.
        </p>
      </div>
      <div class="card">
        <h3>Weniger Mikroplastik</h3>
        <p>
          Unser Projekt fragt danach, wie Verpackungen verbessert werden koennen, damit Umwelt
          und Gewaesser weniger belastet werden.
        </p>
      </div>
      <div class="card">
        <h3>Zukunftsorientiert</h3>
        <p>
          Wir wollen zeigen, dass nachhaltige Verpackung nicht nur eine Idee ist,
          sondern praktisch gedacht und umgesetzt werden kann.
        </p>
      </div>
    </div>
  </section>

  <section id="prototyp">
    <h2>Erster Prototyp</h2>
    <p>
      Als moeglichen ersten Anwendungsfall untersuchen wir eine nachhaltige Verpackung fuer
      den Bereich Angelzubehoer. Damit koennen wir unser Konzept an einem konkreten Produkt testen
      und spaeter weiterentwickeln.
    </p>

    <div class="cards">
      <div class="card">
        <h3>Schritt 1</h3>
        <p>Material recherchieren und PHA als Verpackungsstoff bewerten.</p>
      </div>
      <div class="card">
        <h3>Schritt 2</h3>
        <p>Ein erstes Verpackungsdesign planen und als Prototyp umsetzen.</p>
      </div>
      <div class="card">
        <h3>Schritt 3</h3>
        <p>Die Idee praesentieren, dokumentieren und weiter verbessern.</p>
      </div>
    </div>
  </section>

  <section id="team">
    <h2>Unser Team</h2>
    <div class="team">
      <div class="team-member">
        <h3>Jakob Niehus</h3>
        <p>Projektarbeit, Recherche, Konzept und Umsetzung.</p>
      </div>
      <div class="team-member">
        <h3>Luis Tann</h3>
        <p>Projektarbeit, Ideenentwicklung, Design und Praesentation.</p>
      </div>
    </div>
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p>
      Du hast Fragen zu unserem Projekt oder moechtest uns unterstuetzen?
      Dann melde dich gern bei uns.
    </p>
    <div class="highlight">
      E-Mail: deine-mail@beispiel.de<br>
      Schule: Gymnasium Kronshagen<br>
      Projekt: Profilseminar
    </div>
  </section>

  <footer>
    <p>NT Biocycle 2026 - Nachhaltige Verpackungen aus PHA</p>
  </footer>

</body>
</html>
