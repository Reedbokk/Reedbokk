<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sobre mí - Elias Guardia</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .container {
      max-width: 800px;
      padding: 2rem;
      background: white;
      margin-top: 50px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 {
      font-size: 2rem;
      color: #007acc;
    }

    .bio {
      margin: 1rem 0;
      font-size: 1.1rem;
    }

    .technologies {
      margin: 2rem 0;
    }

    .technologies ul {
      list-style: none;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }

    .technologies li {
      background: #007acc;
      color: white;
      padding: 8px 16px;
      border-radius: 20px;
      font-size: 0.95rem;
    }

    .links a {
      margin: 0 10px;
      text-decoration: none;
      color: #007acc;
      font-weight: bold;
    }

    .whatsapp-btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 10px 20px;
      background: #25D366;
      color: white;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
    }

    @media (max-width: 600px) {
      .technologies ul {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>¡Hola! Soy Elias Guardia</h1>
    <p class="bio">
      💻 Programo, diseño y hablo varios idiomas.<br>
      🚀 Siempre aprendiendo y mejorando cada día.<br>
      🎨 Apasionado por la tecnología y la creatividad.
    </p>

    <div class="technologies">
      <h2>Tecnologías que manejo</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Python</li>
        <li>SQL (básico)</li>
        <li>Diseño Gráfico</li>
        <li>Git & GitHub</li>
      </ul>
    </div>

    <div class="links">
      <a href="https://github.com/tuUsuario" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/tuUsuario" target="_blank">LinkedIn</a>
      <a href="https://facebook.com/tuUsuario" target="_blank">Facebook</a>
      <a href="https://instagram.com/tuUsuario" target="_blank">Instagram</a>
      <a href="https://vk.com/tuUsuario" target="_blank">VK</a>
    </div>

    <a class="whatsapp-btn" href="https://wa.me/543865752421" target="_blank">
      💬 Contactar por WhatsApp
    </a>
  </div>
</body>
</html>

