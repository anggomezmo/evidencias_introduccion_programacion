<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 imagenes
- 2 videos
- 4 audios
- 2 Inline frames

Utiliza encabezados para títulos en cada elemento `<h1>...<h6>`.

Crea una descripción para cada elemento utilizando párrafos `(<p>)`.

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa `<strong>` para resaltar texto importante.
- Utiliza `<br>` para insertar saltos de línea si es necesario.
- Agrega `<span>` para aplicar estilos específicos a porciones de texto.
- Emplea `<i>` para enfatizar o dar énfasis a palabras o frases.
- Utiliza `<u>` para subrayar texto cuando sea necesario.
- Considera el uso de `<div>` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Solución.

### Index.html

```html
<!DOCTYPE html>
<html>

<head>
    <title>Temas varios
    </title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #1f7a9e;
            color: rgb(37, 8, 8);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #620a0a;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        h3 {
            color: rgb(28, 179, 108);
        }


        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Cositas varias</h1>
        <h3>Un mixeo de cosas interesantes y no tan interesantes.</h3>
    </header>

    <section>
        <h2>Videojuegos</h2>
        <p>Estos son cuatro de mis juegos favoritos</p>
        <u>
            <h3>Hollow knight</h3>
        </u>
        <p>El
            videojuego de acción
            lateral en 2D para Windows, macOS, Linux, Switch, PlayStation 4 y Xbox One estrenado en el año 2017. Su
            secuela, Hollow
            Knight: Silksong, está siendo desarrollada para Windows, macOS, Linux y Switch y se pondrá a la venta en una
            fecha aún sin determinar.
            Hollow Knight, una aventura épica a través de un vasto reino de insectos y héroes que se encuentra en
            ruinas. Explora
            cavernas tortuosas, combate contra criaturas corrompidas y entabla amistad con extraños insectos, todo en un
            estilo
            clásico en 2D dibujado a mano.
        </p>
        <img src="hollow knight.jpg" alt="videojuego hollow knight" height="200">

        <u>
            <h3>Sekiro: Shadows Die Twice</h3>
        </u>
        <p>Sekiro: Shadows Die Twice es un videojuego de acción y aventura desarrollado por From Software y distribuido
            por
            Activision. El juego fue lanzado el 22 de marzo de 2019 en las plataformas PlayStation 4, Xbox One y
            Microsoft
            Windows.El juego sigue a un shinobi del Período Sengoku, conocido como Lobo, que intenta vengarse de un clan
            de
            samuráis que atacó y secuestró a su maestro.
        </p>
        <img src="sekiro.avif" alt="videojuego sekiro" height="200">

        <u>
            <h3>Terraria</h3>
        </u>
        <p>Terraria es un videojuego de acción, aventura y de sandbox producido de forma independiente por el estudio
            Re-Logic.
            Tiene características tales como la exploración, la artesanía, la construcción de estructuras y el
            combate.​Se lanzó el
            16 de mayo de 2011.
        </p>
        <img src="terraria.jpg" alt="videojuego terraria" height="200">

        <u>
            <h3>God of war</h3>
        </u>
        <p>God of War es una franquicia de videojuegos hack and slash creada por SCE Santa Monica Studio y distribuida
            por Sony
            Computer Entertainment. Se basa en las aventuras de un semidiós espartano, Kratos, quien se enfrenta a
            diversos
            personajes de la mitología griega y nórdica, tanto héroes como (Heracles, Teseo, Perseo, etc.); especies
            mitológicas
            (gorgonas, arpías, o minotauros); dioses griegos (Ares, Poseidón, Zeus, entre otros), titanes (como Cronos)
            y dioses
            primordiales (como Gaia). Aunque el guerrero espartano acostumbra enemistad con la mayoría de los dioses,
            recibe ayuda
            de muchos de ellos en algún momento de cada entrega, en especial de Atenea.
        </p>
        <img src="god of war.jpeg" alt="videojuego terraria" height="200">




    </section>

    <section>
        <h2>Videos inspiradores</h2>
        <p>En esta sección habran videos que me inspiraron y me cambiaron la vida por siempre y para siempre</p>

        <u>
            <h3>Glorieta de algún lugar del mundo.</h3>
        </u>
        <p>
            Esta increible glorieta en algún lugar del mundo, es increible porque pasan autos y es simplemente
            maravilloso.
        </p>
        <video src="video1.mp4" alt="autos" height="400" controls></video><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>

        <u>
            <h3>La rana.</h3>
        </u>
        <p>
            A contiuación podemos observar la magnifica, impenetrable, y luminiscente rana existiendo.
        </p>
        <video src="video2.mp4" alt="autos" height="400" controls></video><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>
    </section>

    <section>
        <h2>Audios para la transformación humana y el progreso social.</h2>
        <p>Un par de canciones creadas por increibles artistas que te dejaran atonito tras escuchar su dulce melodia.
        </p>
        <u>
            <h3>Good night</h3>
        </u>
        <p>
            Una canción para dormir, su función es dormirte, y probablemente duermas.
        </p>
        <audio src="goonight.mp3" controls></audio><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>

        <u>
            <h3>Futuristic beat</h3>

        </u>
        <p>
            El futuro inminente llega al presente trayendo un ritmo fluyente.
        </p>
        <audio src="futuristic-beat-146661.mp3" controls></audio><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>

        <u>
            <h3>My universe</h3>

        </u>
        <p>
            El universo tiene planetas, en uno o mas planetas hay musica, en esta canción se representa el universo.
        </p>
        <audio src="my-universe-147152.mp3" controls></audio><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>
        <u>
            <h3>Smoke</h3>

        </u>
        <p>
            Simplemente humo, nada que comentar, solo humo, es humo.
        </p>
        <audio src="smoke-143172.mp3" controls></audio><br>
        <a href="https://pixabay.com/es/" target="_blank">Más información</a>





    </section>

    <section>
        <h2>iFrames que te volaran la cabeza</h2>
        <p>alucinas con los iframes que se encuentran </p>
        <u>
            <h3>WIKIPEDIA</h3>

        </u>
        <p>
            Necesitas buscar algo? bueno, en este iframe puedes usar wikipedia facil.
        </p>
        <iframe src="https://es.wikipedia.org/wiki/Wikipedia:Portada" width="600" height="415" frameborder="0"></iframe>
        <br>

        <a href="https://es.wikipedia.org/wiki/Wikipedia:Portada" target="_blank">Más información</a>

        <u>
            <h3>Una no-hit del monton</h3>

        </u>
        <p>
            Presenciemos como Angello del pasado, logró una hazaña en un videojuego.
        </p>
        <br>

        <iframe width="660" height="415" src="https://www.youtube.com/embed/4bEE2u4dAMg" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
    </section>

    <footer>
        Angello Gómez Monsalve
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

```






