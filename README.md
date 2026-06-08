# Mi-proyecto-Peque-os-ingenieros-
Pequeños Ingenieros es una plataforma educativa interactiva diseñada para introducir a niños y niñas en el mundo de la ciencia y la ingeniería. A través de retos prácticos, juegos de lógica y un sistema de medallas, transforma conceptos técnicos complejos en experiencias sencillas y divertidas que estimulan el pensamiento crítico 


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pequeños Ingenieros - Aprendizaje Divertido</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #ff6b6b;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2rem;
        }
        nav {
            background-color: #4ecdc4;
            display: flex;
            justify-content: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .welcome-section {
            text-align: center;
            padding: 20px;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .card {
            background-color: #ffe66d;
            border-radius: 8px;
            width: 30%;
            min-width: 250px;
            padding: 20px;
            margin: 10px;
            text-align: center;
            box-sizing: border-box;
        }
        .card h3 {
            color: #2f2fa2;
            margin-top: 0;
        }
        .btn-start {
            display: inline-block;
            background-color: #ff6b6b;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            margin-top: 20px;
            transition: transform 0.2s;
        }
        .btn-start:hover {
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2f2fa2;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>👷‍♂️ Pequeños Ingenieros 🚀</h1>
        <p>¡Construyendo, experimentando y aprendiendo el futuro!</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#desafios">Desafíos</a>
        <a href="#progreso">Mi Progreso</a>
        <a href="#biblioteca">Biblioteca</a>
    </nav>

    <div class="container" id="inicio">
        <section class="welcome-section">
            <h2>¡Hola, Futuro Ingeniero!</h2>
            <p>Bienvenido al lugar donde tus ideas se convierten en inventos reales. Resuelve retos, acumula medallas y descubre cómo funciona el mundo.</p>
            <a href="#desafios" class="btn-start">¡Comenzar mi primer reto!</a>
        </section>

        <section class="features" id="desafios">
            <div class="card">
                <h3>🧩 Módulo de Desafíos</h3>
                <p>Completa misiones interactivas de construcción, lógica y física adaptadas a tu nivel.</p>
            </div>
            <div class="card">
                <h3>🏆 Panel de Progreso</h3>
                <p>Mira tus logros obtenidos, tus estadísticas y las medallas que has ganado.</p>
            </div>
            <div class="card">
                <h3>📚 Biblioteca Didáctica</h3>
                <p>Aprende palabras de ingeniería con dibujos y ejemplos muy fáciles de entender.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Pequeños Ingenieros - Plataforma Educativa.</p>
    </footer>

</body>
</html>
