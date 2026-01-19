<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>TuFuturoYa | Orientación vocacional y primer empleo</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Guía completa para jóvenes: qué estudiar, cómo elegir carrera, test vocacional y cómo conseguir el primer trabajo.">

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f4f6f9;
      color: #222;
    }

    header {
      background: linear-gradient(135deg, #ffffff, #e8f0ff);
      text-align: center;
      padding: 80px 20px;
    }

    header h1 {
      font-size: 3em;
      color: #1e6cff;
    }

    header p {
      max-width: 800px;
      margin: auto;
      font-size: 1.2em;
      color: #555;
    }

    .botones {
      margin-top: 35px;
    }

    .boton {
      display: inline-block;
      margin: 10px;
      padding: 15px 35px;
      background: linear-gradient(to right, #1e6cff, #4fa3ff);
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-size: 1.05em;
      transition: transform 0.3s, box-shadow 0.3s;
      border: none;
      cursor: pointer;
    }

    .boton:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 25px rgba(0,0,0,0.2);
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 70px 20px;
    }

    h2 {
      text-align: center;
      color: #1e6cff;
      margin-bottom: 45px;
      font-size: 2.3em;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      border-radius: 18px;
      padding: 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card h3 {
      color: #1e6cff;
    }

    .card p, .card ul {
      color: #555;
      line-height: 1.6;
    }

    ul {
      padding-left: 20px;
    }

    hr {
      margin: 20px 0;
    }

    footer {
      background: #e9edf3;
      text-align: center;
      padding: 30px;
      color: #555;
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

<!-- HERO -->
<header>
  <h1>TuFuturoYa</h1>
  <p>
    Una plataforma creada para ayudar a jóvenes a decidir qué estudiar,
    descubrir su vocación y conseguir su primer trabajo.
  </p>

  <div class="botones">
    <a href="#estudiar" class="boton">📚 Qué estudiar</a>
    <a href="#trabajo" class="boton">💼 Primer empleo</a>
    <a href="#habilidades" class="boton">🛠 Habilidades</a>
    <a href="#test" class="boton">🧠 Test vocacional</a>
  </div>
</header>

<!-- ESTUDIAR -->
<section id="estudiar">
  <h2>📚 Opciones para estudiar</h2>

  <div class="cards">
    <div class="card">
      <h3>Universidad</h3>
      <p>Formación profesional a largo plazo.</p>
      <ul>
        <li>Ingenierías</li>
        <li>Salud</li>
        <li>Educación</li>
        <li>Derecho</li>
      </ul>
    </div>

    <div class="card">
      <h3>Técnico / Tecnólogo</h3>
      <p>Estudios cortos con salida laboral rápida.</p>
      <ul>
        <li>SENA</li>
        <li>Informática</li>
        <li>Mecánica</li>
        <li>Salud</li>
      </ul>
    </div>

    <div class="card">
      <h3>Cursos Online</h3>
      <p>Aprende desde casa habilidades modernas.</p>
      <ul>
        <li>Programación</li>
        <li>Diseño</li>
        <li>Marketing</li>
        <li>Idiomas</li>
      </ul>
    </div>
  </div>
</section>

<!-- TRABAJO -->
<section id="trabajo">
  <h2>💼 Cómo conseguir tu primer trabajo</h2>

  <div class="cards">
    <div class="card">
      <h3>Hoja de vida</h3>
      <ul>
        <li>Datos claros</li>
        <li>Estudios y cursos</li>
        <li>Habilidades personales</li>
      </ul>
    </div>

    <div class="card">
      <h3>Entrevistas</h3>
      <ul>
        <li>Buena presentación</li>
        <li>Seguridad al hablar</li>
        <li>Honestidad</li>
      </ul>
    </div>

    <div class="card">
      <h3>Trabajos para empezar</h3>
      <ul>
        <li>Auxiliar</li>
        <li>Practicante</li>
        <li>Medio tiempo</li>
        <li>Call center</li>
      </ul>
    </div>
  </div>
</section>

<!-- HABILIDADES -->
<section id="habilidades">
  <h2>🛠 Habilidades importantes</h2>

  <div class="cards">
    <div class="card">
      <h3>Habilidades blandas</h3>
      <ul>
        <li>Comunicación</li>
        <li>Responsabilidad</li>
        <li>Trabajo en equipo</li>
      </ul>
    </div>

    <div class="card">
      <h3>Habilidades digitales</h3>
      <ul>
        <li>Computadores</li>
        <li>Internet</li>
        <li>Herramientas digitales</li>
      </ul>
    </div>

    <div class="card">
      <h3>Idiomas</h3>
      <p>El inglés abre muchas oportunidades laborales.</p>
    </div>
  </div>
</section>

<!-- TEST VOCACIONAL -->
<section id="test">
  <h2>🧠 Test Vocacional</h2>

  <div class="card" style="max-width:800px; margin:auto;">
    <form id="testForm">

      <p><strong>1. ¿Qué disfrutas más?</strong></p>
      <label><input type="radio" name="p1" value="tecnologia"> Tecnología</label><br>
      <label><input type="radio" name="p1" value="salud"> Ayudar personas</label><br>
      <label><input type="radio" name="p1" value="creatividad"> Crear</label><br>
      <label><input type="radio" name="p1" value="negocios"> Negocios</label>

      <hr>

      <p><strong>2. ¿Qué materia te gusta más?</strong></p>
      <label><input type="radio" name="p2" value="tecnologia"> Matemáticas</label><br>
      <label><input type="radio" name="p2" value="salud"> Biología</label><br>
      <label><input type="radio" name="p2" value="creatividad"> Arte</label><br>
      <label><input type="radio" name="p2" value="educacion"> Explicar</label>

      <hr>

      <p><strong>3. ¿Cómo te ves en el futuro?</strong></p>
      <label><input type="radio" name="p3" value="tecnologia"> Creando soluciones</label><br>
      <label><input type="radio" name="p3" value="salud"> Ayudando</label><br>
      <label><input type="radio" name="p3" value="negocios"> Liderando</label><br>
      <label><input type="radio" name="p3" value="educacion"> Enseñando</label>

      <br><br>

      <button type="button" class="boton" onclick="calcularResultado()">Ver resultado</button>

      <div id="resultado" style="margin-top:30px;"></div>
    </form>
  </div>
</section>

<footer>
  © 2026 TuFuturoYa | Creado por Santiago 💙  
</footer>

<script>
function calcularResultado() {
  const respuestas = document.querySelectorAll('input[type="radio"]:checked');

  if (respuestas.length < 3) {
    document.getElementById("resultado").innerHTML =
      "<p style='color:red;'>Responde todas las preguntas.</p>";
    return;
  }

  let puntos = { tecnologia:0, salud:0, creatividad:0, negocios:0, educacion:0 };

  respuestas.forEach(r => puntos[r.value]++);

  let area = Object.keys(puntos).reduce((a,b) => puntos[a] > puntos[b] ? a : b);

  let texto = {
    tecnologia: "🔧 Área tecnológica: programación, informática, ingeniería.",
    salud: "🩺 Área de la salud: enfermería, medicina, primeros auxilios.",
    creatividad: "🎨 Área creativa: diseño, arte, contenido digital.",
    negocios: "💼 Área de negocios: administración, ventas, emprendimiento.",
    educacion: "👩‍🏫 Área educativa: docencia y pedagogía."
  };

  document.getElementById("resultado").innerHTML =
    "<div class='card'>" + texto[area] + "</div>";
}
</script>

</body>
</html>
