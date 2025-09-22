# Luz-de-luna
Luz de luna es un bazar y regaleria, donde puedes encontrar productos con variedad para regalar o para uso mismo. Nuestros productos te ayudarán para que tu vida diaria sea más confortable
<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luz de Luna - Bazar y Regalería</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #333;
    }
    header {
      text-align: center;
      background: #fbeaf2;
      padding: 20px;
    }
    header img {
      max-width: 200px;
    }
    nav {
      background: #f4c2d7;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .producto {
      background: #fff0f6;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #f4c2d7;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: #fff;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      text-decoration: none;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Luz de Luna Logo">
    <h1>Luz de Luna</h1>
    <p>Bazar y Regalería</p>
  </header>  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#sobre">Sobre Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>  <section id="inicio">
    <h2>Bienvenidos a Luz de Luna</h2>
    <p>Tu lugar especial para encontrar regalos únicos y artículos de bazar que iluminan cada momento.</p>
  </section>  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
      <div class="producto">Taza personalizada</div>
      <div class="producto">Velas aromáticas</div>
      <div class="producto">Decoración para el hogar</div>
      <div class="producto">Regalos especiales</div>
    </div>
  </section>  <section id="sobre">
    <h2>Sobre Nosotros</h2>
    <p>En Luz de Luna trabajamos con amor para ofrecerte detalles únicos que transmiten cariño y estilo. Nuestro bazar y regalería está pensado para acompañarte en cada ocasión especial.</p>
  </section>  <section id="contacto">
    <h2>Contacto</h2>
    <p>📍 Dirección: Tu dirección aquí</p>
    <p>📞 Teléfono: +54 9 0000 0000</p>
    <p>📧 Email: contacto@luzdeluna.com</p>
  </section>  <footer>
    <p>&copy; 2025 Luz de Luna - Todos los derechos reservados</p>
  </footer><a href="https://wa.me/5490000000000" class="whatsapp">💬</a>

</body>
</html>
