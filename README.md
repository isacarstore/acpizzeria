<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Con Amor y Sabor | Pizzas & Pizzetas</title>
    <style>
        /* Estilos Generales */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #121212;
            color: #ffffff;
            text-align: center;
        }

        /* Hero / Encabezado */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(18, 18, 18, 1)), url('https://i.postimg.cc/DzY0VgZv/Flayer.jpg') no-repeat center center/cover;
            padding: 60px 20px 40px;
        }

        .logo-img {
            max-width: 150px;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 2.2rem;
            color: #d4af37; /* Dorado */
            margin-bottom: 10px;
        }

        p.subtitle {
            font-size: 1.1rem;
            color: #cccccc;
            margin-bottom: 25px;
        }

        /* Botón de WhatsApp */
        .btn-whatsapp {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: #25d366;
            color: #ffffff;
            font-size: 1.2rem;
            font-weight: bold;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
            transition: transform 0.2s, background-color 0.2s;
        }

        .btn-whatsapp:hover {
            background-color: #1ebc57;
            transform: scale(1.05);
        }

        /* Menú / Productos */
        .menu-section {
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
        }

        .section-title {
            font-size: 1.8rem;
            color: #d4af37;
            margin-bottom: 30px;
            border-bottom: 2px solid #d4af37;
            display: inline-block;
            padding-bottom: 5px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #1e1e1e;
            border: 1px solid #333;
            border-radius: 12px;
            padding: 20px;
            text-align: left;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: #d4af37;
        }

        .card h3 {
            color: #ffffff;
            font-size: 1.3rem;
            margin-bottom: 8px;
        }

        .card p {
            color: #aaa;
            font-size: 0.95rem;
            margin-bottom: 12px;
        }

        .card .badge {
            display: inline-block;
            background-color: #d4af37;
            color: #000;
            font-weight: bold;
            font-size: 0.8rem;
            padding: 4px 8px;
            border-radius: 4px;
        }

        /* Pie de página */
        footer {
            background-color: #0a0a0a;
            padding: 20px;
            color: #777;
            font-size: 0.9rem;
            border-top: 1px solid #222;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Con Amor y Sabor</h1>
        <p class="subtitle">Pizzas artesanales y pizzetas para tus eventos y antojos</p>
        
        <a href="https://wa.me/5491178202863?text=Hola!%20Quiero%20hacer%20un%20pedido%20de%20pizzas" class="btn-whatsapp" target="_blank">
            💬 Pedir por WhatsApp
        </a>
    </header>

<!-- Menú -->
    <section class="menu-section">
        <h2 class="section-title">Nuestra Especialidad</h2>
        <div class="grid">
            <div class="card">
                <span class="badge">Individuales / Packs</span>
                <h3>Pizzetas Variadas</h3>
                <p>Ideales para reuniones, cumpleaños y eventos. Con los mejores ingredientes y masa casera.</p>
            </div>
            <div class="card">
                <span class="badge">Artesanal</span>
                <h3>Pizzas Grandes</h3>
                <p>Muzzarella, Napolitana, Pepperoni, Fugazzeta y especialidades de la casa horneadas a la perfección.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p><strong>Con Amor y Sabor</strong> — Pedidos al 11 7820 2863</p>
    </footer>

</body>
</html>
