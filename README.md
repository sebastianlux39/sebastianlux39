<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HM Gooo! 💙</title>

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700;900&display=swap" rel="stylesheet">

<!-- Icons -->
<script src="https://kit.fontawesome.com/a2e0e6ad65.js" crossorigin="anonymous"></script>

<style>
:root {
  --blue: #3b82f6;
  --dark: #020617;
  --soft: #0f172a;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  background: radial-gradient(circle at top, #020617, #000);
  color: white;
  overflow-x: hidden;
}

/* HERO */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
}

.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at center, rgba(59,130,246,.25), transparent 60%);
}

.hero-content {
  position: relative;
  z-index: 2;
}

.avatar {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  margin: 0 auto 30px;
  background: url("https://i.imgur.com/8Km9tLL.png") center/cover;
  box-shadow: 0 0 80px rgba(59,130,246,.6);
}

.hero h1 {
  font-size: clamp(3rem, 6vw, 5rem);
  font-weight: 900;
}

.hero span {
  color: var(--blue);
}

.hero p {
  margin-top: 15px;
  font-size: 1.2rem;
  opacity: .8;
}

/* SOCIAL BAR */
.socials {
  margin-top: 40px;
  display: flex;
  justify-content: center;
  gap: 25px;
}

.socials a {
  font-size: 26px;
  color: white;
  transition: .3s;
}

.socials a:hover {
  color: var(--blue);
  transform: translateY(-6px);
}

/* SECTION */
.section {
  padding: 120px 10vw;
}

.section h2 {
  font-size: 3rem;
  margin-bottom: 30px;
}

.section p {
  max-width: 600px;
  opacity: .75;
  font-size: 1.1rem;
}

/* CARDS */
.cards {
  margin-top: 60px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap: 30px;
}

.card {
  background: linear-gradient(180deg, #020617, #020617aa);
  border: 1px solid #1e293b;
  border-radius: 24px;
  padding: 40px;
  transition: .4s;
}

.card:hover {
  transform: translateY(-10px);
  border-color: var(--blue);
}

.card i {
  font-size: 32px;
  color: var(--blue);
  margin-bottom: 20px;
}

/* CTA */
.cta {
  text-align: center;
  padding: 120px 20px;
  background: linear-gradient(180deg, transparent, #020617);
}

.cta h2 {
  font-size: 3rem;
}

.cta a {
  display: inline-block;
  margin-top: 30px;
  padding: 18px 40px;
  border-radius: 999px;
  background: var(--blue);
  color: white;
  text-decoration: none;
  font-weight: 700;
  transition: .3s;
}

.cta a:hover {
  transform: scale(1.05);
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <div class="hero-content">
    <div class="avatar"></div>
    <h1>HM Gooo! <span>💙</span></h1>
    <p>Creator · Streams · Comunidad</p>

    <div class="socials">
      <a href="#"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-tiktok"></i></a>
      <a href="#"><i class="fab fa-youtube"></i></a>
      <a href="#"><i class="fab fa-x-twitter"></i></a>
      <a href="#"><i class="fab fa-discord"></i></a>
    </div>
  </div>
</section>

<!-- IDENTIDAD -->
<section class="section">
  <h2>No es un link.<br>Es un <span style="color:#3b82f6">universo.</span></h2>
  <p>
    HM Gooo! es contenido, streams, ideas y una comunidad que crece.
    Este no es un perfil. Es el punto de entrada.
  </p>

  <div class="cards">
    <div class="card">
      <i class="fas fa-video"></i>
      <h3>Contenido</h3>
      <p>Videos, clips y momentos destacados.</p>
    </div>
    <div class="card">
      <i class="fas fa-gamepad"></i>
      <h3>Streams</h3>
      <p>Directos con la comunidad.</p>
    </div>
    <div class="card">
      <i class="fas fa-users"></i>
      <h3>Comunidad</h3>
      <p>Personas reales, no números.</p>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <h2>¿Entramos?</h2>
  <a href="#">Únete a la Comunidad</a>
</section>

</body>
</html>
