
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maqueta de página web</title>

    <style>
        /* MODELO DE CAJA */
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        /* CONTENEDOR PRINCIPAL */
        .contenedor {
            width: 475px;
            max-width: 100%;
            margin: 20px auto;
            padding: 10px;
            background-color: #70ad47;
            border: 2px solid #4472c4;
        }

        /* ENCABEZADO */
        header {
            height: 80px;
            background-color: #ed7d31;
            border: 1px solid #4472c4;
            color: white;
            text-align: center;
            position: relative;
            margin-bottom: 10px;
            padding: 5px;
        }

        header p {
            margin-right: 140px;
            line-height: 1.8;
        }

        /* IMAGEN */
        .imagen {
            position: absolute;
            top: 2px;
            right: 4px;
            width: 32%;
            height: 72px;
            background-color: #ffc000;
            border: 1px solid #4472c4;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        /* NAVEGACIÓN */
        nav {
            background-color: #2f5597;
            color: white;
            text-align: center;
            padding: 10px;
            height: 35px;
            margin-bottom: 10px;
        }

        /* CONTENEDOR DE SECTION Y ASIDE */
        .contenido {
            display: flex;
            gap: 14px;
            margin-bottom: 10px;
        }

        /* SECTION */
        section {
            background-color: #ed7d31;
            border: 1px solid #4472c4;
            color: white;
            height: 123px;
            flex: 2;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 10px;
        }

        /* ASIDE */
        aside {
            background-color: #ffff00;
            border: 1px solid #4472c4;
            color: black;
            height: 123px;
            flex: 1;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 10px;
        }

        /* PIE DE PÁGINA */
        footer {
            background-color: #2f5597;
            color: white;
            text-align: center;
            padding: 9px;
            height: 35px;
        }

        /* DISEÑO PARA PANTALLAS PEQUEÑAS */
        @media (max-width: 450px) {
            .contenido {
                flex-direction: column;
            }

            section,
            aside {
                width: 100%;
            }
        }
    </style>
</head>

<body>

    <div class="contenedor">

        <header>
            <p>
                Esto es una etiqueta<br>
                &lt; header&gt;
            </p>

            <div class="imagen">
                Esto es una imagen
            </div>
        </header>

        <nav>
            Esto es una etiqueta nav
        </nav>

        <div class="contenido">

            <section>
                Esto es una etiqueta &lt;section&gt;
            </section>

            <aside>
                Esto es una etiqueta<br>
                &lt;aside&gt;
            </aside>

        </div>

        <footer>
            Esto es una etiqueta &lt;footer&gt;
        </footer>

    </div>

</body>
</html>
