<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio - Tu Nombre</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            color: white;
            padding: 100px 0;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        .subtitle {
            font-size: 1.5em;
            opacity: 0.9;
        }
        .section {
            background: white;
            margin: 40px 0;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        h2 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 2em;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }
        .skill {
            background: #667eea;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: bold;
        }
        footer {
            text-align: center;
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
        @media (max-width: 768px) {
            h1 { font-size: 2em; }
            .section { padding: 20px; }
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Hola! Soy [Tu Nombre]</h1>
        <p class="subtitle">Desarrollador Web | Diseñador Creativo</p>
    </header>

    <div class="container">
        <section class="section">
            <h2>👋 Sobre Mí</h2>
            <p>Soy un apasionado por la tecnología y el diseño. Me encanta crear experiencias web increíbles que impacten a los usuarios. ¡Hablemos de tu proyecto!</p>
        </section>

        <section class="section">
            <h2>🛠️ Habilidades</h2>
            <div class="skills">
                <span class="skill">HTML5</span>
                <span class="skill">CSS3</span>
                <span class="skill">JavaScript</span>
                <span class="skill">React</span>
                <span class="skill">Node.js</span>
                <span class="skill">Python</span>
            </div>
        </section>

        <section class="section">
            <h2>📧 Contáctame</h2>
            <p>Email: <a href="mailto:tuemail@example.com">tuemail@example.com</a></p>
            <p>LinkedIn: <a href="#">linkedin.com/in/tunombre</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 [Tu Nombre]. Hecho con ❤️ por Blackbox AI.</p>
    </footer>
</body>
</html>
