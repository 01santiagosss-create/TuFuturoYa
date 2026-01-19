<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>TuFuturoYa | Estudia y Trabaja Mejor</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
    }

    header {
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      opacity: 0.9;
    }

    .boton {
      display: inline-block;
      margin: 15px;
      padding: 15px 30px;
      background: #00c6ff;
      background: linear-gradient(to right, #0072ff, #00c6ff);
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-size: 1.1em;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .boton:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.4);
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: rgba(255,255,255,0.1);
      border-radius: 15px;
      padding: 25px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card h3 {
      color: #00c6ff;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: rgba(0,0,0,0.3);
      margin-top: 40px;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2em;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>TuFuturoYa</h1>
    <p>Descubre qué estudiar, cómo conseguir trabajo y mejorar tu futuro</p>

    <a href="#estudiar" class="boton">📚 Qué estudiar</a>
    <a href="#trabajo" class="boton">💼 Conseguir trabajo</a>
    <a href="#test" class="boton">🧠 Test vocacional</a>
  </header>

  <section id="estudiar">
    <h2>📚 ¿Qué puedes estudiar?</h2>
    <div class="cards">
      <div class="card">
        <h3>Universidad</h3>
        <p>Carreras profesionales con alta demanda laboral.</p>
      </div>
      <div class="card">
        <h3>Técnicos y Tecnólogos</h3>
        <p>Opciones rápidas para trabajar y ganar experiencia.</p>
      </div>
      <div class="card">
        <h3>Cursos Online</h3>
        <p>Aprende programación, diseño, marketing y más.</p>
      </div>
    </div>
  </section>

  <section id="trabajo">
    <h2>💼 Cómo conseguir trabajo</h2>
    <div class="cards">
      <div class="card">
        <h3>Hoja de vida</h3>
        <p>Aprende a crear un CV atractivo y profesional.</p>
      </div>
      <div class="card">
        <h3>Entrevistas</h3>
        <p>Consejos para responder con seguridad.</p>
      </div>
      <div class="card">
        <h3>Primer empleo</h3>
        <p>Opciones para jóvenes sin experiencia.</p>
      </div>
    </div>
  </section>

  <section id="test">
    <h2>🧠 Test vocacional (Próximamente)</h2>
    <p>Muy pronto podrás descubrir qué carrera va mejor contigo.</p>
  </section>

  <footer>
    © 2026 TuFuturoYa | Creado por Santiago 🚀
  </footer>

</body>
</html>

