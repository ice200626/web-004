# web-004
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=5.0">
    <title>Catálogo de Precios</title>
    <style>
        .catalogo {
            width: 100%;
            margin: 0 auto;
            border-collapse: collapse;
        }
        .catalogo th, .catalogo td {
            border: 5px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .catalogo th {
            background-color: #f2f2f2;
        }
        .boton-consulta {
            display: inline-block;
            padding: 100px 100px;
            background-color: #4CAF50; /* Color del botón */
            color: white; /* Color del texto */
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .boton-consulta:hover {
            background-color: #45a049; /* Color al pasar el mouse */
        }
    </style>
</head>
<body>
    <h1>Catálogo de Precios</h1>
    <table class="catalogo">
        <tr>
            <th>Producto</th>
            <th>Precio</th>
            <th>Consulta</th>
        </tr>
        <tr>
            <td>Producto 1</td>
            <td>$150.00</td>
            <td><a href="https://ice200626.github.io/web-005/" class="boton-consulta">Consulta</a></td>
        </tr>
        <tr>
            <td>Producto 2</td>
            <td>$200.00</td>
            <td><a href="https://ice200626.github.io/web-005/" class="boton-consulta">Consulta</a></td>
        </tr>
        <tr>
            <td>Producto 3</td>
            <td>$250.00</td>
            <td><a href="https://ice200626.github.io/web-005/" class="boton-consulta">Consulta</a></td>
        </tr>
    </table>
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
