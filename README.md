<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HM Gooo Official | Biografía</title>
    <style>
        /* Reset básico y fondo futurista */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Orbitron', sans-serif;
            background: #0f0f1a;
            color: #e0e0e0;
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* Partículas de fondo */
        #particles {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            z-index: -1;
        }

        /* Header hero */
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.1), rgba(0, 200, 200, 0.05));
            position: relative;
        }

        .profile-img {
            width: 280px; /* Un poco más grande para que destaque */
            height: 280px;
            border-radius: 50%;
            border: 6px solid cyan;
            box-shadow: 0 0 40px rgba(0, 255, 255, 0.7);
            animation: glow 4s infinite alternate;
            margin-bottom: 2.5rem;
            object-fit: cover; /* Por si la imagen no es perfectamente cuadrada */
        }

        h1 {
            font-size: 4.5rem;
            background: linear-gradient(90deg, #00ffff, #00cccc, #ffffff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 1rem;
            animation: titlePulse 3s infinite;
        }

        .subtitle {
            font-size: 1.8rem;
            color: #00cccc;
            margin-bottom: 2.5rem;
        }

        .social-links a {
            display: inline-block;
            margin: 0 1.5rem;
            padding: 1rem 2.5rem;
            background: rgba(0, 255, 255, 0.15);
            border: 2px solid cyan;
            border-radius: 50px;
            color: white;
            text-decoration: none;
            font-size: 1.3rem;
            transition: all 0.4s ease;
        }

        .social-links a:hover {
            background: cyan;
            color: #0f0f1a;
            box-shadow: 0 0 25px cyan;
            transform: translateY(-8px);
        }

        /* Sección biografía */
        section {
            max-width: 900px;
            margin: 5rem auto;
            padding: 3rem;
            background: rgba(20, 20, 35, 0.7);
            border-radius: 20px;
            border: 1px solid #00cccc;
            box-shadow: 0 0 30px rgba(0, 255, 255, 0.4);
            animation: fadeIn 2s;
        }

        section h2 {
            font-size: 2.8rem;
            color: cyan;
            margin-bottom: 2rem;
            text-align: center;
        }

        section p {
            font-size: 1.3rem;
            line-height: 1.9;
            color: #ccc;
            margin-bottom: 1.5rem;
        }

        /* Animaciones */
        @keyframes glow {
            from { box-shadow: 0 0 30px rgba(0, 255, 255, 0.6); }
            to { box-shadow: 0 0 60px rgba(0, 255, 255, 1); }
        }

        @keyframes titlePulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(50px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Fondo de partículas -->
    <canvas id="particles"></canvas>

    <header>
        <!-- TU NUEVA IMAGEN AQUÍ -->
        <img src="https://bananapedia.wiki.gg/images/BR_Miku.png" alt="HM Gooo Official - Hatsune Miku" class="profile-img">

        <h1>HM Gooo Official</h1>
        <p class="subtitle">Fan Account dedicado a Hatsune Miku 💙</p>

        <div class="social-links">
            <a href="https://www.tiktok.com/@hmgooo_official" target="_blank">🔗 TikTok Oficial</a>
        </div>
    </header>

    <section>
        <h2>Sobre mí</h2>
        <p>
            ¡Hola! Soy <strong>HM Gooo Official</strong>, un fan account dedicado a la increíble <strong>Hatsune Miku</strong> y al mundo Vocaloid. 
            Aquí comparto edits, animaciones, memes y contenido creativo inspirado en la diva virtual turquesa más famosa del mundo. 💖🩵
        </p>
        <p>
            Se les agradece por su apoyo y mi diosa Hatsune Miku también lo agradece 😊🩵<br>
            ¡Gracias por los +483K seguidores y +31.7K likes en TikTok!
        </p>
        <p>
            Si te gusta el contenido futurista, cyber y todo lo relacionado con Miku, ¡este es tu lugar! 
            Subo videos regularmente en TikTok, así que sígueme para no perderte nada.
        </p>
        <p style="text-align:center; margin-top:3rem; font-size:1.8rem; color: cyan;">
            🎄🔔 ¡Buen 2026! 🔔🎄
        </p>
    </section>

    <!-- Partículas.js -->
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
        particlesJS("particles", {
            "particles": {
                "number": { "value": 100, "density": { "enable": true, "value_area": 800 } },
                "color": { "value": ["#00ffff", "#00cccc", "#ffffff"] },
                "shape": { "type": "circle" },
                "opacity": { "value": 0.6, "random": true },
                "size": { "value": 3, "random": true },
                "line_linked": { "enable": true, "distance": 150, "color": "#00ffff", "opacity": 0.3, "width": 1 },
                "move": { "enable": true, "speed": 2, "direction": "none", "random": false, "straight": false, "out_mode": "out" }
            },
            "interactivity": {
                "detect_on": "canvas",
                "events": { "onhover": { "enable": true, "mode": "repulse" }, "resize": true }
            },
            "retina_detect": true
        });
    </script>
</body>
</html>
