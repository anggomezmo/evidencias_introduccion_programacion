<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan.

## Solución

### index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table border="3" cellpadding="8" cellspacing="8">

        <thead>
            <tr>
                <th>Code</th>
                <th>Name</th>
                <th colspan="3">Description</th>
                <th>Price</th>
                <th>Stock</th>
                <th>Relase date</th>
            </tr>



        </thead>
        <tbody>
            <tr>
                <td rowspan="2">001</td>
                <td rowspan="2">PlayStation 5</td>
                <td colspan="3">The PlayStation 5 (PS5) is a home video game console developed by Sony Interactive
                    Entertainment.</td>
                <td>$499.99 USD</td>
                <td>5</td>
                <td>11/12/2020</td>


            </tr>
            <tr>
                <td colspan="3">The base model includes an optical disc drive compatible with Ultra HD Blu-ray discs.
                    The Digital
                    Edition lacks this
                    drive, as a lower-cost model for buying games only through download. The two variants were launched
                    simultaneously.</td>
                <td><img src="ps5.webp" alt="" width="90"></td>

            </tr>


            <tr>
                <td rowspan="2">002</td>
                <td rowspan="2">Xbox Series X</td>
                <td colspan="3">The Xbox Series X and Xbox Series S are, collectively, the fourth generation of the Xbox
                    series of home video game
                    consoles developed and sold by Microsoft.</td>
                <td>$499.99 USD</td>
                <td>10</td>
                <td>11/10/2020</td>


            </tr>
            <tr>
                <td colspan="3">The higher-end Xbox Series X and lower-end Xbox Series S are part of the ninth
                    generation of video game consoles, which
                    also includes Sony's PlayStation 5</td>
                <td><img src="consola-xbox-series-x-1tb-microsoft.webp" alt="" width="90"></td>

            </tr>


            <tr>
                <td rowspan="2">003</td>
                <td rowspan="2">Nintendo Switch Pro</td>
                <td colspan="3">The Nintendo Switch is a video game console developed by Nintendo The console itself is
                    a tablet that can either be docked for home console use or used as a portable device, making it a
                    hybrid console.</td>
                <td>$300 USD</td>
                <td>18</td>
                <td>03/03/2017</td>


            </tr>
            <tr>
                <td colspan="3">There are more than 1000 games for the Nintendo Switch. Some notable titles include The
                    Legend of Zelda: Breath of the
                    Wild, Super Mario Odyssey, Kirby Star Allies,etc.</td>
                <td><img src="consola-nintendo-switch-oled-45496883386.webp" alt="" width="90"></td>

            </tr>

            <tr>
                <td rowspan="2">004</td>
                <td rowspan="2">Avocado</td>
                <td colspan="3">An avocado is a bright green fruit with a large pit and dark leathery skin.</td>
                <td>$0.5 USD</td>
                <td>9</td>
                <td>03/03/1010</td>


            </tr>
            <tr>
                <td colspan="3">Avocados are in the same family as cinnamon. Seriously.</td>
                <td><img src="https://cdn.britannica.com/72/170772-050-D52BF8C2/Avocado-fruits.jpg" alt="" width="90">
                </td>

            </tr>


            <tr>
                <td rowspan="2">005</td>
                <td rowspan="2">partially used masking tape</td>
                <td colspan="3">Partially used duct tape is a trusted resource that adapts to a variety of tasks. From
                    temporary repairs to arts and crafts projects, this tape can adhere to a wide variety of surfaces,
                    from paper and cardboard to plastic and metal. Its ability to join and hold makes it an essential
                    tool.</td>
                <td>$3.99 USD</td>
                <td>1</td>
                <td>02/05/1925</td>


            </tr>
            <tr>
                <td colspan="3">Partially Used Duct Tape: Because Sometimes, You Just Need a Little Piece to Fix the
                    World (Or At Least Your Day)</td>
                <td><img src="cinta-enmascarar.jpg.webp" alt="" width="90"></td>

            </tr>

            <tr>
                <td rowspan="2">006</td>
                <td rowspan="2">Son kokun teddy</td>
                <td colspan="3">Son kokun is the protagonist of the manga and anime series Dragon Ball. It was created
                    by Akira Toriyama in 1984.</td>
                <td>$10 USD</td>
                <td>5</td>
                <td>11/20/ 1984</td>


            </tr>
            <tr>
                <td colspan="3">

                    The name 'kokun' means 'awakened from the void'; the syllable 'Go' means 'Enlightenment', and the
                    syllable 'Ku' means 'sky' or 'empty'.</td>
                <td><img src="images.jpg" alt="" width="90" height="90"></td>

            </tr>
            <tr>
                <td rowspan="2">007</td>
                <td rowspan="2">Iphone 14 pro max</td>
                <td colspan="3">iPhone 14 Pro Max are high-end smartphones designed and marketed by Apple Inc.</td>
                <td>$1500 USD</td>
                <td>20</td>
                <td>09/16/2022</td>


            </tr>
            <tr>
                <td colspan="3">

                    The iPhone 14 Pro and iPhone 14 Pro Max are the first to have a new type of "Dynamic Island" cut-out
                    screen.</td>
                <td><img src="IMG-7380043_823x.webp" alt="" width="90" height="90"></td>
            <tr>
                <td rowspan="2">008</td>
                <td rowspan="2">PC gaming</td>
                <td colspan="3">PC gaming" is a type of PC designed and specialized to run and play all kinds of video
                    games.</td>
                <td>$2000 USD</td>
                <td>6</td>
                <td>11/21/2001</td>


            </tr>
            <tr>
                <td colspan="3">

                    Gaming PCs are also used for other demanding tasks like video editing.</td>
                <td><img src="https://controltechinc.co/wp-content/uploads/2021/11/PC-COMPUMAX-GTX-1050TI-M22.png"
                        alt="" width="90" height="90"></td>

            </tr>
            <tr>
                <td rowspan="2">009</td>
                <td rowspan="2">Shirt</td>
                <td colspan="3">A shirt to use when you go outside.</td>
                <td>$10 USD</td>
                <td>10</td>
                <td>11/21/1800</td>


            </tr>
            <tr>
                <td colspan="3">

                    Usefull tu cover you body from spectators.</td>
                <td><img src="7242524711_2_6_8.jpg" alt="" width="90" height="90"></td>

            </tr>
            <tr>
                <td rowspan="2">010</td>
                <td rowspan="2">Apple</td>
                <td colspan="3">Apple is a fruit very delicious.</td>
                <td>$0.2 USD</td>
                <td>15</td>
                <td>1/30/20 A.c</td>


            </tr>
            <tr>
                <td colspan="3">

                    It's also a helathy food.</td>
                <td><img src="red-apple-isolated-clipping-path-19130134.webp" alt="" width="90" height="90"></td>

            </tr>

        </tbody>

    </table>
</body>

</html>

```






