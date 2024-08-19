
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
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbogSGzP6wBTNYqehJkhc5mzUPIFGJ5LSCKA&s" alt="Coche 2">
                <h3>Lamborghini Aventador</h3>
                <p>Un superdeportivo con un potente motor V12 y diseño icónico.</p>
            </div>
            <div class="car-item">
                <img src="data:image/jpeg;base64,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" alt="Coche 3">
                <h3>Porsche 911</h3>
                <p>El clásico Porsche con un diseño atemporal y un rendimiento increíble.</p>
            </div>
        <a href="pagina2.html" class="next-button">Siguiente</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Galería de Coches. Todos los derechos reservados.</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Coches - Página 2</title>
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
        <h1>Galería de Coches - Página 2</h1>
        <p>Continúa explorando nuestra selección de coches de lujo</p>
    </header>

    <div class="container">
        <div class="car-list">
            <div class="car-item">
                <img src="https://via.placeholder.com/300x200" alt="Coche 4">
                <h3>McLaren 720S</h3>
                <p>Un superdeportivo británico con un motor V8 de doble turbo y una aceleración increíble.</p>
            </div>
            <div class="car-item">
                <img src="https://via.placeholder.com/300x200" alt="Coche 5">
                <h3>Aston Martin DB11</h3>
                <p>Un gran turismo elegante y potente, con un motor V12 y un diseño sofisticado.</p>
            </div>
            <div class="car-item">
                <img src="https://via.placeholder.com/300x200" alt="Coche 6">
                <h3>Bugatti Chiron</h3>
                <p>El coche más rápido del mundo, con un motor W16 y una velocidad máxima impresionante.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Galería de Coches. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
