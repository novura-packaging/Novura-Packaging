<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Novura Packaging | Manufacturing Future</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #22c55e; /* Frisches Grün */
            --bg: #020617;      /* Tiefes Dunkelblau/Schwarz */
            --card-bg: rgba(30, 41, 59, 0.4);
            --border: rgba(255, 255, 255, 0.08);
            --text-main: #f8fafc;
            --text-dim: #94a3b8;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; scroll-behavior: smooth; }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg);
            color: var(--text-main);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* --- Dekoration im Hintergrund --- */
        .glow {
            position: fixed;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at 50% -20%, rgba(34, 197, 94, 0.15), transparent 70%);
            z-index: -1;
        }

        /* --- Hero Bereich --- */
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }

        .tag {
            background: rgba(34, 197, 94, 0.1);
            color: var(--primary);
            padding: 6px 16px;
            border-radius: 100px;
            font-size: 0.8rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: 1px solid rgba(34, 197, 94, 0.2);
            margin-bottom: 20px;
        }

        h1 {
            font-size: clamp(3rem, 10vw, 6rem);
            font-weight: 800;
            line-height: 1;
            margin-bottom: 25px;
            background: linear-gradient(to bottom, #fff 40%, #64748b);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero-desc {
            max-width: 600px;
            font-size: 1.2rem;
            color: var(--text-dim);
            margin-bottom: 40px;
        }

        /* --- Bento Grid --- */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px 100px;
        }

        .bento-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-auto-rows: minmax(180px, auto);
            gap: 20px;
        }

        .bento-card {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 28px;
            padding: 30px;
            backdrop-filter: blur(10px);
            transition: 0.4s cubic-bezier(0.23, 1, 0.32, 1);
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
        }

        .bento-card:hover {
            border-color: var(--primary);
            transform: translateY(-5px);
            background: rgba(30, 41, 59, 0.6);
        }

        /* Verschiedene Kachelgrößen */
        .large { grid-column: span 2; grid-row: span 2; }
        .wide { grid-column: span 2; }
        .tall { grid-row: span 2; }

        .bento-card h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: var(--primary);
        }

        .bento-card p {
            color: var(--text-dim);
            font-size: 0.95rem;
        }

        .icon {
            font-size: 2rem;
            margin-bottom: auto;
            opacity: 0.8;
        }

        /* --- Buttons --- */
        .btn {
            background: var(--primary);
            color: #000;
            padding: 14px 30px;
            border-radius: 14px;
            text-decoration: none;
            font-weight: 700;
            transition: 0.3s;
        }

        .btn:hover {
            box-shadow: 0 0 20px rgba(34, 197, 94, 0.4);
            transform: scale(1.02);
        }

        footer {
            text-align: center;
            padding: 60px 20px;
            border-top: 1px solid var(--border);
            font-size: 0.9rem;
            color: var(--text-dim);
        }

        @media (max-width: 900px) {
            .bento-grid { grid-template-columns: repeat(2, 1fr); }
        }

        @media (max-width: 600px) {
            .bento-grid { grid-template-columns: 1fr; }
            .large, .wide, .tall { grid-column: span 1; grid-row: span 1; }
        }
    </style>
</head>
<body>

<div class="glow"></div>

<header>
    <div class="tag">Novura Packaging</div>
    <h1>Echt nachhaltig.<br>Echt produziert.</h1>
    <p class="hero-desc">Wir beenden die Ära der Plastikverpackungen. Mit PHA stellen wir Produkte her, die dort verschwinden, wo sie nicht hingehören: in der Natur.</p>
    <a href="#kontakt" class="btn">Kontakt aufnehmen</a>
</header>

<div class="container">
    <div class="bento-grid">
        <!-- Main Card -->
        <div class="bento-card large">
            <div class="icon">🏭</div>
            <h3>Unsere Fertigung</h3>
            <p>Wir entwickeln keine Konzepte für andere – wir produzieren selbst. In unserer Werkstatt entstehen Prototypen, die zeigen, dass PHA der Kunststoff der Zukunft ist.</p>
        </div>

        <!-- Material Card -->
        <div class="bento-card tall">
            <div class="icon">🔬</div>
            <h3>PHA Material</h3>
            <p>Ein Biopolymer, das zu 100% biologisch abbaubar ist. Es verhält sich wie Plastik, ist aber keins.</p>
        </div>

        <!-- Pilot Card -->
        <div class="bento-card">
            <div class="icon">🎣</div>
            <h3>Pilot: Angelzubehör</h3>
            <p>Spezialverpackungen für die Fischerei – dort, wo Umweltschutz am wichtigsten ist.</p>
        </div>

        <!-- Team Card -->
        <div class="bento-card wide">
            <div class="icon">👥</div>
            <h3>Das Team</h3>
            <p>Jacob Niehus (Technik) & Luis Tann (Design). Gemeinsam bringen wir Novura Packaging vom Gymnasium Kronshagen in die reale Anwendung.</p>
        </div>

        <!-- Eco Card -->
        <div class="bento-card">
            <div class="icon">🌊</div>
            <h3>Meeresfest</h3>
            <p>Zersetzt sich rückstandslos in Salzwasser.</p>
        </div>
    </div>
</div>

<footer id="kontakt">
    <p>Novura Packaging | Profilseminar 2026 | Gymnasium Kronshagen</p>
    <p style="margin-top: 10px;">E-Mail: deine-mail@beispiel.de</p>
</footer>

</body>
</html>
