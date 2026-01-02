<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HM Gooo Official</title>
    <meta name="description" content="Fan Account dedicado a Hatsune Miku 🩵 Edits, memes y contenido Vocaloid">
    
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg: #0a0e17;
            --card: rgba(15, 20, 35, 0.6);
            --cyan: #00ffff;
            --turquesa: #00cccc;
            --text: #e0e0e0;
            --text-light: #a0a0a0;
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Roboto', sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        /* Fondo de partículas */
        #particles {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            z-index: -1;
        }
        
        /* Sección Hero */
        .hero {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            position: relative;
        }
        
        .hero-img {
            width: 320px;
            height: 320px;
            border-radius: 50%;
            border: 6px solid var(--cyan);
            box-shadow: 0 0 50px rgba(0, 255, 255, 0.6);
            animation: glow 5s ease-in-out infinite alternate;
            margin-bottom: 2rem;
        }
        
        .hero h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 4rem;
            background: linear-gradient(90deg, var(--cyan), var(--turquesa), white);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 1rem;
        }
        
        .hero .subtitle {
            font-size: 1.8rem;
            color: var(--turquesa);
            margin-bottom: 2rem;
        }
        
        .btn-tiktok {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            padding: 14px 32px;
            background: rgba(0, 255, 255, 0.15);
            border: 2px solid var(--cyan);
            border-radius: 50px;
            color: white;
            font-size: 1.4rem;
            font-weight: bold;
            text-decoration: none;
            transition: all 0.4s;
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
        }
        
        .btn-tiktok:hover {
            background: var(--cyan);
            color: var(--bg);
            transform: translateY(-5px);
            box-shadow: 0 0 40px rgba(0, 255, 255, 0.7);
        }
        
        /* Sección Sobre Mí */
        .about {
            max-width: 900px;
            margin: 6rem auto;
            padding: 3rem;
            background: var(--card);
            border-radius: 20px;
            border: 1px solid var(--turquesa);
            box-shadow: 0 0 30px rgba(0, 255, 255, 0.2);
            backdrop-filter: blur(10px);
        }
        
        .about h2 {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.8rem;
            color: var(--cyan);
            text-align: center;
            margin-bottom: 2rem;
        }
        
        .about p {
            font-size: 1.3rem;
            color: var(--text-light);
            margin-bottom: 1.5rem;
            text-align: center;
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin: 2rem 0;
            flex-wrap: wrap;
        }
        
        .stat {
            text-align: center;
        }
        
        .stat-number {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.5rem;
            color: var(--cyan);
        }
        
        .stat-label {
            color: var(--text-light);
            font-size: 1.1rem;
        }
        
        .greeting {
            text-align: center;
            font-size: 2rem;
            color: var(--turquesa);
            margin-top: 3rem;
            font-family: 'Orbitron', sans-serif;
        }
        
        /* Animaciones */
        @keyframes glow {
            from { box-shadow: 0 0 40px rgba(0, 255, 255, 0.5); }
            to { box-shadow: 0 0 70px rgba(0, 255, 255, 0.9); }
        }
        
        @media (max-width: 768px) {
            .hero-img { width: 250px; height: 250px; }
            .hero h1 { font-size: 3rem; }
            .hero .subtitle { font-size: 1.5rem; }
            .about { margin: 3rem 1rem; padding: 2rem; }
        }
    </style>
</head>
<body>

    <canvas id="particles"></canvas>

    <!-- Sección Hero -->
    <section class="hero">
        <img src="https://bananapedia.wiki.gg/images/BR_Miku.png" alt="Hatsune Miku - HM Gooo Official" class="hero-img">
        
        <h1>HM Gooo Official</h1>
        <p class="subtitle">Fan Account dedicado a Hatsune Miku 💙</p>
        
        <a href="https://www.tiktok.com/@hmgooo_official" target="_blank" class="btn-tiktok">
            🎵 TikTok Oficial
        </a>
    </section>

    <!-- Sección Sobre Mí -->
    <section class="about">
        <h2>Sobre mí</h2>
        <p>
            ¡Hola! Soy <strong>HM Gooo Official</strong>, un fan account 100% dedicado a la diva virtual más icónica: <strong>Hatsune Miku</strong>.
        </p>
        <p>
            Comparto edits, animaciones, memes, transiciones y todo tipo de contenido creativo inspirado en Miku y el mundo Vocaloid 🩵
        </p>
        <p>
            Se les agradece por su apoyo y mi diosa Hatsune Miku también lo agradece 😊🩵
        </p>
        
        <div class="stats">
            <div class="stat">
                <div class="stat-number">483K+</div>
                <div class="stat-label">Seguidores</div>
            </div>
            <div class="stat">
                <div class="stat-number">31.7K+</div>
                <div class="stat-label">Me gusta totales</div>
            </div>
        </div>
        
        <p class="greeting">🎄🔔 ¡Buen 2026! 🔔🎄</p>
    </section>

    <!-- Partículas.js -->
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
        particlesJS("particles", {
            "particles": {
                "number": { "value": 60 },
                "color": { "value": ["#00ffff", "#00cccc"] },
                "shape": { "type": "circle" },
                "opacity": { "value": 0.4, "random": true },
                "size": { "value": 3, "random": true },
                "line_linked": { "enable": true, "distance": 180, "color": "#00ffff", "opacity": 0.2, "width": 1 },
                "move": { "enable": true, "speed": 1.5 }
            },
            "interactivity": {
                "events": { "onhover": { "enable": true, "mode": "repulse" } }
            },
            "retina_detect": true
        });
    </script>
</body>
</html>
