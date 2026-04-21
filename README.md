<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avanza CR - Soluciones Digitales</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Arial', sans-serif; 
            line-height: 1.6; 
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4);
        }
        .hero {
            background: rgba(0,0,0,0.7);
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        h1 { font-size: 3.5em; margin-bottom: 20px; }
        .btn {
            background: #ff6b6b;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            display: inline-block;
            margin-top: 20px;
        }
        .container { max-width: 1200px; margin: 0 auto; padding: 40px 20px; }
        .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .card { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.2); text-align: center; }
        @media (max-width: 768px) { h1 { font-size: 2.5em; } }
    </style>
</head>
<body>
    <div class="hero">
        <h1>🚀 Avanza CR</h1>
        <p style="font-size: 1.5em;">Soluciones Digitales para tu Negocio en Costa Rica</p>
        <a href="#servicios" class="btn">Ver Servicios</a>
    </div>

    <div class="container">
        <section id="servicios" class="services">
            <div class="card">
                <h2>🌐 Páginas Web</h2>
                <p>Sitios modernos, rápidos y optimizados para Google.</p>
            </div>
            <div class="card">
                <h2>📱 Apps Móviles</h2>
                <p>Aplicaciones nativas para iOS y Android.</p>
            </div>
            <div class="card">
                <h2>💼 Marketing Digital</h2>
                <p>Google Ads, SEO, Redes Sociales.</p>
            </div>
        </section>
    </div>
</body>
</html>
