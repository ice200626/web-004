#web 004
<!DOCTYPE html> 
<html  lang="es"> 
<head> 
    <meta  charset="UTF- 8">
    <meta  name="ventana gráfica"  content="ancho=dispositivo-width, initial-scale=1.0">
    <title>Catálogo de Precios</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .catalogo {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .producto {
            background: white;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 20px;
            width: 200px; /* Ancho de cada producto */
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .producto h2 {
            font-size: 1.5em;
            margin: 0;
        }
        .precio {
            font-size: 1.2em;
            color: #28a745; /* Color verde para el precio */
            margin: 10px 0;
        }
        .boton {
            display: inline-block;
            background: #007bff; /* Color del botón */
            color: white;
            padding: 10px 20px; /* Alto y ancho del botón */
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1em;
            transition: background 0.3s;
        }
        .boton:hover {
            background: #0056b3; /* Color del botón al pasar el ratón */
        }
    </style>
</head>
<body>
    <h1>Catálogo de Precios</h1>
    <div class="catalogo">
        <div class="producto">
            <h2>Producto 1</h2>
            <p class="precio">$10.00</p>
            <a href="#" class="boton">Añadir al carrito</a>
        </div>
        <div class="producto">
            <h2>Producto 2</h2>
            <p class="precio">$15.00</p>
            <a href="#" class="boton">Añadir al carrito</a>
        </div>
        <div class="producto">
            <h2>Producto 3</h2>
            <p class="precio">$20.00</p>
            <a href="#" class="boton">Añadir al carrito</a>
        </div>
        <div class="producto">
            <h2>Producto 4</h2>
            <p class="precio">$25.00</p>
            <a href="#" class="boton">Añadir al carrito</a>
        </div>
        <div class="producto">
            <h2>Producto 5</h2>
            <p class="precio">$30.00</p>
            <a href="#" class="boton">Añadir al carrito</a>
        </div>
    </div>
</body>
</html>


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botón con Hipervínculo</title>
</head>
<body>
    <a href="https://www.ejemplo.com" style="display: inline-block; padding: 10px 20px; background-color: #008CBA; color: white; text-decoration: none; border-radius: 5px;">Haz clic aquí</a>
</body>
</html>
