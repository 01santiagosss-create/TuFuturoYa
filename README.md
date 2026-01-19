[index.html](https://github.com/user-attachments/files/24683444/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>TuFuturoYA</title>

    <!-- ESTILOS (CSS) -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }

        header {
            background: #1e90ff;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
        }

        section {
            padding: 20px;
            background: white;
            margin: 15px;
            border-radius: 8px;
        }

        .hero {
            text-align: center;
        }

        .boton {
            display: inline-block;
            background: #1e90ff;
            color: white;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }

        .oculto {
            display: none;
        }
    </style>
</head>
<body>

<header>
    <h1>TuFuturoYA</h1>
    <p>Descubre qué estudiar y cómo conseguir tu primer trabajo</p>
</header>

<nav>
    <a onclick="mostrar('inicio')">Inicio</a>
    <a onclick="mostrar('test')">Test Vocacional</a>
    <a onclick="mostrar('empleo')">Primer Empleo</a>
    <a onclick="mostrar('carreras')">Carreras con Futuro</a>
</nav>

<!-- INICIO -->
<section id="inicio">
    <div class="hero">
        <h2>¿No sabes qué estudiar?</h2>
        <p>Haz nuestro test vocacional y descubre tu camino en minutos.</p>
        <a class="boton" onclick="mostrar('test')">Hacer el test</a>
    </div>

    <h3>¿Qué encontrarás aquí?</h3>
    <ul>
        <li>✔ Test vocacional rápido</li>
        <li>✔ Carreras con futuro en Colombia</li>
        <li>✔ Cómo conseguir trabajo sin experiencia</li>
    </ul>
</section>

<!-- TEST VOCACIONAL -->
<section id="test" class="oculto">
    <h2>Test Vocacional</h2>

    <p><strong>1. ¿Qué te gusta más?</strong></p>
    <p>A) Ayudar a personas</p>
    <p>B) Resolver problemas</p>
    <p>C) Crear cosas</p>

    <p><strong>2. ¿Cómo te ves en el futuro?</strong></p>
    <p>A) Trabajando con personas</p>
    <p>B) Frente a un computador</p>
    <p>C) Dirigiendo proyectos</p>

    <p><em>Próximamentes resultados automáticos</em></p>
</section>

<!-- PRIMER EMPLEO -->
<section id="empleo" class="oculto">
    <h2>Cómo conseguir tu primer trabajo</h2>
    <ul>
        <li>Haz una hoja de vida sencilla</li>
        <li>No mientas sobre experiencia</li>
        <li>Aplica a trabajos básicos primero</li>
        <li>Prepárate para entrevistas</li>
    </ul>
</section>

<!-- CARRERAS -->
<section id="carreras" class="oculto">
    <h2>Carreras con futuro</h2>
    <ul>
        <li>Ingeniería de Software</li>
        <li>Salud</li>
        <li>Tecnologías del SENA</li>
        <li>Marketing digital</li>
    </ul>
</section>

<footer>
    <p>© 2026 TuFuturoYA</p>
</footer>

<!-- JAVASCRIPT -->
<script>
    function mostrar(seccion) {
        let secciones = document.querySelectorAll("section");
        secciones.forEach(s => s.classList.add("oculto"));

        document.getElementById(seccion).classList.remove("oculto");
    }
</script>

</body>
</html>
