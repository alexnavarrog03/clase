
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Coches</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        h1 {
            margin: 0;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        .car-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }

        .car-item {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: calc(33.333% - 20px);
            box-sizing: border-box;
            text-align: center;
        }

        .car-item img {
            width: 100%;
            height: auto;
        }

        .car-item h3 {
            margin: 0;
            padding: 15px;
            background-color: #333;
            color: white;
        }

        .car-item p {
            padding: 15px;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Galería de Coches</h1>
        <p>Explora nuestra selección de coches de lujo</p>
    </header>

    <div class="container">
        <div class="car-list">
            <div class="car-item">
                <img src="https://hips.hearstapps.com/es.h-cdn.co/cades/contenidos/10258/ferrari-488-gtb-1.jpg?crop=0.888888888888889xw:1xh;center,top&resize=1200:*" alt="Coche 1">
                <h3>Ferrari 488</h3>
                <p>Un coche deportivo de alto rendimiento con un motor V8 turbo.</p>
            </div>
            <div class="car-item">
                <img src="https://via.placeholder.com/300x200" alt="Coche 2">
                <h3>Lamborghini Aventador</h3>
                <p>Un superdeportivo con un potente motor V12 y diseño icónico.</p>
            </div>
            <div class="car-item">
                <img src="https://via.placeholder.com/300x200" alt="Coche 3">
                <h3>Porsche 911</h3>
                <p>El clásico Porsche con un diseño atemporal y un rendimiento increíble.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Galería de Coches. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
