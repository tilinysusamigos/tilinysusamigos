<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Escuela Federal Por Cooperación "Gral. Domingo Arenas"</title>
  <style>
    body {
      background-color: #b8f1b1; /* Verde pastel */
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      overflow: hidden; /* Para evitar que las flores salgan del área visible */
    }
    header {
      background-color: #ffdde1; /* Rosa */
      color: #000000;
      padding: 10px;
      position: relative;
      overflow: hidden; /* Para evitar que las imágenes de las flores sobresalgan del encabezado */
    }
    header h1 {
      display: inline-block;
      position: relative;
      z-index: 1; /* Para que el texto esté encima de las imágenes */
    }
    header h1::after {
      content: '';
      display: inline-block;
      width: 100%;
      height: 100%;
      background: linear-gradient(45deg, #ffffff, #f368e0, #ffffff, #f368e0);
      position: absolute;
      top: 0;
      left: 0;
      opacity: 0.6;
      z-index: -1;
      animation: shine 3s infinite linear;
    }
    @keyframes shine {
      0% {
        background-position: -200% 0;
      }
      100% {
        background-position: 200% 0;
      }
    }
    .flower-left, .flower-right {
      position: absolute;
      width: 3cm; /* Tamaño de las flores */
      height: 3cm; /* Tamaño de las flores */
      top: 50%;
      transform: translateY(-50%);
      z-index: 0;
    }
    .flower-left {
      left: 10px;
    }
    .flower-right {
      right: 10px;
    }
    nav {
      background-color: #f9e79f; /* Amarillo pastel */
      color: #333;
      padding: 10px;
      text-align: left;
      width: 20%;
      position: fixed;
      height: 100%;
      overflow: auto;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    nav li {
      margin-bottom: 10px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffdde1; /* Rosa */
    }
    section {
      margin-left: 25%;
      padding: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    video {
      max-width: 100%;
      border: 5px solid #ffdde1; /* Marco rosa */
      border-radius: 10px;
    }
    .flower-rain {
      position: absolute;
      width: 1cm; /* Tamaño más pequeño */
      height: 1cm; /* Tamaño más pequeño */
      animation: falling 6s linear infinite;
    }
    @keyframes falling {
      0% {
        transform: translateY(-100vh) rotate(0deg);
        opacity: 0;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 3;
      }
    }
  </style>

  <script>
    function mostrarHora() {
      const fecha = new Date();
      const hora = fecha.getHours();
      const minutos = (fecha.getMinutes() < 10 ? '0' : '') + fecha.getMinutes();
      const horaActual = ${hora}:${minutos};
      
      const horaElement = document.getElementById('hora');
      if (horaElement) {
        horaElement.textContent = horaActual;
      }
      
      setTimeout(mostrarHora, 1000); // Actualizar la hora cada segundo
    }

    document.addEventListener('DOMContentLoaded', function () {
      mostrarHora();
    });
  </script>
</head>
<body>

  <header>
    <img class="flower-left" src="flower.png" alt="Flor">
    <h1>Feliz Primavera - Escuela Federal Por Cooperación<br>"Gral. Domingo Arenas"</h1>
       <img src="escudo.jpg" alt="Escudo de la escuela">
    <img class="flower-right" src="flower.png" alt="Flor">
    <div id="hora" style="position: absolute; top: 10px; right: 10px; color: #ffffff; font-size: 18px;"></div>
  </header>

  <nav>
    <ul>
      <li><a href="index.html">Inicio</a></li>
      <li><a href="misionvision.html">Misión y Visión</a></li>
      <li><a href="areasdeestudio.html">Áreas de estudio</a></li>
      <li><a href="instalaciones.html">Instalaciones</a></li>
      <li><a href="beneficiosqueofrecemos.html">¿Qué ofrecemos?</a></li>
      <li><a href="requisitos.html">Requisitos</a></li>
      <li><a href="fotosdeeventos.html">Fotografías de eventos</a></li>
      <li><a href="anunciosinformes.html">Anuncios e Informes</a></li>
      <li><a href="mistrabajos.html">Mis trabajos</a></li>
    </ul>
  </nav>

  <section id="inicio">
    <!-- Contenido de la sección -->
  </section>

  <!-- Lluvia de flores -->
  <div class="flower-rain" style="top: -10vh; left: 5%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 25%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 45%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 65%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 85%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 15%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 35%;"><img src="flor.png" alt="Flor"></div>
  <div class="flower-rain" style="top: -10vh; left: 30%;"><img src="flor.png" alt="Flor"></div>

  <section id="inicio">
    <h2>Bienvenido a la Escuela Federal Por Cooperación "Gral. Domingo Arenas"</h2>
    <p style="text-align: justify; line-height: 1.6;">
      ¡Bienvenidos a nuestra página escolar, un espacio lleno de aprendizaje, descubrimiento y comunidad! Estamos emocionados de tenerte aquí, formando parte de nuestra familia educativa. En este rincón virtual, encontrarás información relevante, y momentos destacados de la vida escolar.

      Nos esforzamos por fomentar un ambiente donde cada estudiante pueda crecer académica y personalmente. Nuestra página es un reflejo de la diversidad de talentos, intereses y logros que caracterizan a nuestra comunidad estudiantil.

      Gracias por ser parte de nuestro viaje educativo. Juntos, construimos un espacio donde cada estudiante puede alcanzar su máximo potencial. ¡Bienvenido a un emocionante año escolar lleno de aprendizaje y logros!
    </p>
  
    <div style="margin-top: 20px;">
      <video width="600" height="400" controls autoplay>
        <source src="videoes.mp4" type="video/mp4">
        
      </video>
    </div>
  </section>

</body>
</html>
