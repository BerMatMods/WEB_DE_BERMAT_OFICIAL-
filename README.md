<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Presentación BerMatModZ</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      background: #0f0f0f;
      font-family: 'Orbitron', sans-serif;
      color: #ffffff;
      overflow-x: hidden;
    }

    h1 {
      text-align: center;
      font-size: 2.2em;
      color: #08f7fe;
      margin-top: 20px;
      text-shadow: 0 0 15px #08f7fe;
    }

    .intro {
      text-align: center;
      font-size: 1.2em;
      margin: 20px;
      color: #f2f2f2;
      animation: glowText 5s ease-in-out infinite alternate;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin: 40px auto;
      max-width: 1100px;
    }

    .card {
      background: rgba(30, 30, 30, 0.9);
      border: 2px solid #08f7fe;
      border-radius: 20px;
      padding: 25px;
      width: 300px;
      box-shadow: 0 0 20px #08f7fe55;
      transition: transform 0.6s ease, box-shadow 0.6s ease;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 30px #08f7fe;
    }

    .card h2 {
      color: #ff26a8;
      margin-bottom: 15px;
      font-size: 1.4em;
    }

    .card p {
      line-height: 1.5;
      color: #ccc;
    }

    .social-icons {
      position: fixed;
      bottom: 30px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 25px;
      animation: floatIcons 6s ease-in-out infinite;
    }

    .social-icons a {
      color: #08f7fe;
      font-size: 1.8em;
      transition: transform 0.5s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
      color: #ff26a8;
    }

    @keyframes glowText {
      0% { text-shadow: 0 0 10px #08f7fe; }
      100% { text-shadow: 0 0 20px #ff26a8; }
    }

    @keyframes floatIcons {
      0%, 100% { transform: translate(-50%, 0); }
      50% { transform: translate(-50%, -10px); }
    }
  </style>
</head>
<body>

<h1>⚡BerMatModZ - Presentación Oficial🔥</h1>
<p class="intro">Bienvenid@ al universo de BerMatModZ: Programación, Bots, Ciberseguridad y Revolución Digital</p>

<div class="container">
  <div class="card">
    <h2>Sobre Mí</h2>
    <p><strong>Alias:</strong> BerMatModZ<br>
    <strong>Nombre:</strong> Anth'Zz Berrocal<br>
    <strong>Ubicación:</strong> Andahuaylas, Perú<br>
    <strong>Profesión:</strong> Desarrollador, hacker ético, experto en IA y bots</p>
  </div>

  <div class="card">
    <h2>Proyectos</h2>
    <p>- ⚡BerMat-Bot MD🔥 (WhatsApp Bot)<br>
    - BerMat_Mods (Mods de sistemas y apps)<br>
    - Simuladores hackers para Termux<br>
    - FAMA: Fuerza Anónima de Mentes Avanzadas</p>
  </div>

  <div class="card">
    <h2>Habilidades</h2>
    <p>- Programación en Python, JS y Bash<br>
    - Automatización en Termux y VPS<br>
    - Ciberseguridad y anonimato digital<br>
    - Diseño y personalización de bots IA</p>
  </div>

  <div class="card">
    <h2>Contacto</h2>
    <p><strong>WhatsApp:</strong> +51 937556459<br>
    <strong>Email:</strong> anthzzdev@gmail.com<br>
    <strong>Alias de equipo:</strong> Grupo BerMat, Extensión F.A.M.A</p>
  </div>
</div>

<div class="social-icons">
  <a href="https://wa.me/51937556459" target="_blank"><i class="fab fa-whatsapp"></i></a>
  <a href="https://github.com/Anthzberrocal" target="_blank"><i class="fab fa-github"></i></a>
  <a href="https://www.facebook.com/anthzzberrocal" target="_blank"><i class="fab fa-facebook"></i></a>
  <a href="https://www.instagram.com/anthzzdev" target="_blank"><i class="fab fa-instagram"></i></a>
</div>

</body>
</html>
