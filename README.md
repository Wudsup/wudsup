<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wudsup | Portafolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #0d1117;
      color: #e6edf3;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 3rem 1rem;
      background: #161b22;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
      color: #8b949e;
    }
    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
    }
    h2 {
      border-bottom: 2px solid #30363d;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
      color: #58a6ff;
    }
    .skills, .projects, .contact {
      display: grid;
      gap: 1rem;
    }
    .skill, .project {
      background: #161b22;
      padding: 1rem;
      border-radius: 8px;
      transition: transform 0.2s;
    }
    .skill:hover, .project:hover {
      transform: scale(1.02);
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      background: #161b22;
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #8b949e;
    }
  </style>
</head>
<body>
  <header>
    <h1>Wudsup</h1>
    <p>Programador de 17 años | Desarrollador Web & Bots de Discord</p>
  </header>

  <section>
    <h2>🛠️ Habilidades</h2>
    <div class="skills">
      <div class="skill">Desarrollo Web</div>
      <div class="skill">Conocimiento y mantenimiento en bots de Discord</div>
    </div>
  </section>

  <section>
    <h2>🚀 Proyectos</h2>
    <div class="projects">
      <div class="project">
        <h3>E-commerce Básico</h3>
        <p>Tienda online sencilla con carrito y sistema de usuarios.</p>
      </div>
      <div class="project">
        <h3>Bot de Discord</h3>
        <p>Bot personalizado para moderación y comandos divertidos en servidores.</p>
      </div>
      <div class="project">
        <h3>App Móvil de Memes</h3>
        <p>
          Una app sencilla para ver y compartir imágenes divertidas con amigos. 
          Incluye un sistema básico de me gusta y categorías.
        </p>
      </div>
    </div>
  </section>

  <section>
    <h2>📬 Contacto</h2>
    <div class="contact">
      <p>Email: <a href="mailto:culonaavispa214@gmail.com">culonaavispa214@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/wudsup" target="_blank">github.com/wudsup</a></p>
    </div>
  </section>

  <footer>
    © 2025 Wudsup. Todos los derechos reservados.
  </footer>
</body>
</html>
