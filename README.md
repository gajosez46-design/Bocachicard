<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boca Chica RD - Guía Turística 2026 | Qué hacer, Hoteles y Tours</title>
  <meta name="description" content="Descubre Boca Chica como un local. Mejores playas, hoteles, tours y restaurantes. Descarga nuestra guía gratis.">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f8ff; color: #333; line-height: 1.6; }
    .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
    
    /* HEADER */
    header { background: linear-gradient(135deg, #0077be, #00a8e8); color: white; padding: 15px 0; position: sticky; top: 0; z-index: 100; }
    nav { display: flex; justify-content: space-between; align-items: center; }
    .logo { font-size: 24px; font-weight: bold; }
    .menu a { color: white; text-decoration: none; margin-left: 20px; font-weight: 500; }
    
    /* HERO */
    .hero { background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=2070') center/cover; color: white; text-align: center; padding: 100px 20px; }
    .hero h1 { font-size: 42px; margin-bottom: 15px; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
    .hero p { font-size: 18px; margin-bottom: 30px; }
    .btn { background: #ff9f1c; color: white; padding: 14px 28px; border-radius: 8px; text-decoration: none; font-weight: bold; display: inline-block; transition: 0.3s; }
    .btn:hover { background: #e08a00; transform: scale(1.05); }
    
    /* SECCIONES */
    section { padding: 60px 0; }
    h2 { text-align: center; font-size: 32px; margin-bottom: 40px; color: #0077be; }
    
    /* TARJETAS HOTELES */
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; }
    .card { background: white; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1); transition: 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .card img { width: 100%; height: 200px; object-fit: cover; }
    .card-content { padding: 20px; }
    .card h3 { color: #0077be; margin-bottom: 10px; }
    .btn-aff { background: #28a745; width: 100%; text-align: center; margin-top: 10px; }
    
    /* GUIA PDF */
    .guia { background: #fff3cd; text-align: center; padding: 50px 20px; border-radius: 12px; }
    .guia h2 { color: #856404; }
    
    /* FORMULARIO */
    .newsletter { background: #0077be; color: white; text-align: center; padding: 50px 20px; }
    .newsletter input { padding: 12px; width: 300px; max-width: 80%; border: none; border-radius: 6px; margin-right: 10px; }
    
    /* FOOTER */
    footer { background: #333; color: white; text-align: center; padding: 20px; font-size: 14px; }
    @media(max-width: 768px) { .hero h1 { font-size: 28px; } .menu { display: none; } }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <nav>
        <div class="logo">🌴 BocaChicaRD</div>
        <div class="menu">
          <a href="#hoteles">Hoteles</a>
          <a href="#blog">Blog</a>
          <a href="#guia">Guía PDF</a>
        </div>
      </nav>
    </div>
  </header>

  <section class="hero">
    <h1>Descubre Boca Chica como un Local</h1>
    <p>Playas, tours, comida y los mejores secretos de Boca Chica en 2026</p>
    <a href="#hoteles" class="btn">Ver Mejores Hoteles</a>
  </section>

  <section id="hoteles" class="container">
    <h2>Hoteles y Tours Recomendados</h2>
    <div class="cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1540541338287-41794eaa0682?q=80&w=2070" alt="Hotel">
        <div class="card-content">
          <h3>Todo Incluido Frente al Mar</h3>
          <p>Con piscina, barra libre y a 2 min de la playa. El favorito de los turistas.</p>
          <a href="TU-LINK-DE-AFILIADO-BOOKING-1" class="btn btn-aff">Ver Precio y Reservar</a>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1559827260-dc66d52bef19?q=80&w=2070" alt="Tour">
        <div class="card-content">
          <h3>Tour Isla Saona + Piscina Natural</h3>
          <p>El tour #1 de Boca Chica. Incluye almuerzo y transporte.</p>
          <a href="TU-LINK-DE-AFILIADO-VIATOR-1" class="btn btn-aff">Reservar Tour</a>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1571896349842-33c89424de2d?q=80&w=2080" alt="Restaurante">
        <div class="card-content">
          <h3>Pescado con Coco en la Playa</h3>
          <p>Los 3 mejores sitios donde comen los locales. Barato y buenísimo.</p>
          <a href="#blog" class="btn btn-aff">Leer Guía de Comida</a>
        </div>
      </div>
    </div>
  </section>

  <section id="guia" class="container">
    <div class="guia">
      <h2>Descarga la Guía "48h en Boca Chica" por solo $9 USD</h2>
      <p>Itinerario exacto, mapas, lugares secretos y cómo ahorrar en tu viaje.</p>
      <a href="TU-LINK-DE-PAGO-HOTMART-O-PAYPAL" class="btn" style="background:#856404; margin-top:15px;">Comprar Guía Ahora</a>
    </div>
  </section>

  <section id="blog" class="container">
    <h2>Artículos para Planear tu Viaje</h2>
    <div class="cards">
      <div class="card"><div class="card-content"><h3>10 Cosas que hacer en Boca Chica</h3><p>Además de la playa...</p></div></div>
      <div class="card"><div class="card-content"><h3>Cómo llegar desde el Aeropuerto SDQ</h3><p>Las 3 formas más baratas...</p></div></div>
      <div class="card"><div class="card-content"><h3>Playas cerca de Boca Chica</h3><p>Juan Dolio, Guayacanes...</p></div></div>
    </div>
  </section>

  <section class="newsletter">
    <h2>Recibe Ofertas de Tours y Hoteles</h2>
    <p>1 correo a la semana. Sin spam.</p>
    <form>
      <input type="email" placeholder="Tu correo">
      <button class="btn">Suscribirme</button>
    </form>
  </section>

  <footer>
    <p>BocaChicaRD.com © 2026 | Este sitio contiene links de afiliado. Si compras, ganamos una comisión sin costo para ti.</p>
  </footer>

</body>
</html>
