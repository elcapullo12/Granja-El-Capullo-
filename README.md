# Granja-El-Capullo-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Granja El Capullo</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: #003366; color: white; padding: 20px; text-align: center; }
    nav { background-color: #006699; padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .hero { background: url('https://via.placeholder.com/1200x400?text=Granja+El+Capullo') center/cover; height: 300px; display: flex; justify-content: center; align-items: center; color: white; font-size: 2em; text-shadow: 1px 1px 2px black; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .productos { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .producto { border: 1px solid #ccc; padding: 20px; width: 250px; text-align: center; border-radius: 10px; box-shadow: 2px 2px 8px rgba(0,0,0,0.1); }
    .producto img { max-width: 100%; border-radius: 10px; }
    footer { background-color: #003366; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>

  <header>
    <h1>Granja El Capullo</h1>
    <p>Huevos y pollo de calidad directo de nuestra granja</p>
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="hero">
    Frescura que se nota
  </div>

  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
      <div class="producto">
      <div class="producto">
        <img src="https://via.placeholder.com/250x180?text=Huevo+Blanco" alt="Huevo Blanco">
        <h3>Huevo Blanco</h3>
        <p>Frescura y sabor directo de nuestra granja.</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/250x180?text=Pollo+Entero" alt="Pollo Entero">
        <h3>Pollo Entero</h3>
        <p>Listo para cocinar, ideal para toda la familia.</p>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>En Granja El Capullo nos dedicamos a ofrecer productos frescos y de la más alta calidad. Nuestro compromiso es contigo y tu familia, brindando alimentos sanos, nutritivos y con sabor casero.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Puedes hacer tus pedidos y resolver dudas directamente con nosotros:</p>
    <ul>
      <li>📞 Teléfono: 899 000 0000</li>
      <li>📍 Ubicación: Río Bravo, Tamaulipas</li>
      <li>📱 <a href="https://wa.me/5218990000000">Haz tu pedido por WhatsApp</a></li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Granja El Capullo. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
