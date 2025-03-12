<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarey Travel & Tours</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #00509E;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background: #FFC107;
            color: black;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?travel') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
            font-size: 2em;
            font-weight: bold;
            text-align: center;
        }
        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sarey Travel & Tours</h1>
        <p>Descubre el mundo con nosotros</p>
    </header>
    <nav>
        <a href="#about">Sobre Nosotros</a>
        <a href="#destinos">Destinos</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="hero">
        Tu viaje soñado comienza aquí
    </div>
    <div class="container">
        <section id="about">
            <h2>Sobre Nosotros</h2>
            <p>Sarey Travel & Tours ofrece experiencias inolvidables con paquetes de viaje personalizados.</p>
        </section>
        <section id="destinos">
            <h2>Destinos Populares</h2>
            <p>Explora los lugares más increíbles con nuestras ofertas exclusivas.</p>
        </section>
        <section id="servicios">
            <h2>Nuestros Servicios</h2>
            <p>Ofrecemos paquetes completos, asesoría personalizada y más.</p>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>¿Listo para tu próxima aventura? Contáctanos hoy mismo.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Sarey Travel & Tours - Todos los derechos reservados</p>
    </footer>
</body>
</html>
