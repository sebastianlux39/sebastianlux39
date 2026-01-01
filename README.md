<!DOCTYPE html>
<html lang="es" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HM Gooo! 💙</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome (Social Icons) -->
  <script src="https://kit.fontawesome.com/a2e0e6ad65.js" crossorigin="anonymous"></script>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <script>
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            primary: "#3b82f6",
            darkbg: "#0f172a"
          },
          fontFamily: {
            display: ["Plus Jakarta Sans", "sans-serif"]
          }
        }
      }
    }
  </script>
</head>

<body class="bg-darkbg text-white font-display min-h-screen flex justify-center">

  <main class="w-full max-w-md px-4 py-10">

    <!-- Avatar -->
    <div class="flex flex-col items-center text-center">
      <div class="relative">
        <div class="absolute inset-0 rounded-full bg-primary blur-xl opacity-40 animate-pulse"></div>
        <img
          src="https://i.imgur.com/8Km9tLL.png"
          alt="HM Gooo"
          class="relative w-32 h-32 rounded-full border-4 border-darkbg object-cover"
        />
      </div>

      <h1 class="mt-4 text-3xl font-extrabold">
        HM Gooo! <span class="text-primary">💙</span>
      </h1>
      <p class="text-slate-400 mt-1">
        Creator · Streams · Comunidad
      </p>
    </div>

    <!-- Social Icons -->
    <div class="mt-6 flex justify-center gap-4">
      <a href="#" class="social"><i class="fab fa-instagram"></i></a>
      <a href="#" class="social"><i class="fab fa-tiktok"></i></a>
      <a href="#" class="social"><i class="fab fa-youtube"></i></a>
      <a href="#" class="social"><i class="fab fa-x-twitter"></i></a>
      <a href="#" class="social"><i class="fab fa-whatsapp"></i></a>
    </div>

    <!-- Links -->
    <div class="mt-8 flex flex-col gap-4">

      <a href="#" class="link-btn">
        🔥 Último Video
      </a>

      <a href="#" class="link-btn">
        🎮 Directos en Vivo
      </a>

      <a href="#" class="link-btn">
        🛒 Tienda Oficial
      </a>

      <a href="#" class="link-btn">
        💬 Únete a la Comunidad
      </a>

    </div>

    <!-- Footer -->
    <footer class="mt-10 text-center text-xs text-slate-500">
      © 2026 · HM Gooo!
    </footer>

  </main>

  <!-- Styles -->
  <style>
    .social {
      width: 48px;
      height: 48px;
      border-radius: 9999px;
      background: #020617;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 20px;
      transition: all 0.3s ease;
    }
    .social:hover {
      background: #3b82f6;
      transform: translateY(-4px);
    }

    .link-btn {
      width: 100%;
      padding: 14px;
      border-radius: 9999px;
      background: #020617;
      text-align: center;
      font-weight: 600;
      transition: all 0.25s ease;
      border: 1px solid #1e293b;
    }
    .link-btn:hover {
      background: #3b82f6;
      border-color: #3b82f6;
      transform: scale(1.02);
    }
  </style>

</body>
</html>
