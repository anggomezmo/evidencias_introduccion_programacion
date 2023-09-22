<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 7 


## Actividad: Proyecto web, git y Github.

Crea un repositorio Git en GitHub y clonalo en tu computadora local. Luego, crea un proyecto web utilizando la información de las sesiones 1, 2, 3, 4 y 5. Realiza algunas modificaciones al proyecto y sube los cambios al repositorio remoto.

Requerimientos del proyecto:
- Crea un proyecto web de diseño libre.
- Documentar el repositorio en el archivo README.md

## Solución

Se diseñó una página web y su contenido principal, se subieron los cambios al repositorio, y luego se subieron los cambios del archivo README.md y se añadió la sección nav a la página principal.

URL repositorio: https://github.com/anggomezmo/Actividad7Intro

Código de la página:

index.html
```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Páginas de naime favoritas</title>
</head>

<body>
    <header>
        <h1>Animes favoritos</h1>

        <nav>
            <ul>
                <li> <a href="about.html" rel="noopener noreferrer">About</a></li>
                <li><a href="contact.html" rel="noopener noreferrer">Contact</a></li>
            </ul>
           

        </nav>

    </header>
    <section>
        <header>
            <h2>Dragon ball</h2>
        </header>
        <p>Dragon Ball es un manga escrito e ilustrado por Akira Toriyama. Fue publicado originalmente en la revista
            Shōnen Jump, de la editorial japonesa Shūeisha, entre 1984 y 1995.​​</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/recursos-cesde.appspot.com/o/db.jpg?alt=media&token=8f1902f9-0b83-448e-8662-ef262f0b77b8"
            alt="Db image" width="350">
    </section>
    <section>
        <header>
            <h2>Kaguya-sama: Love Is War</h2>
        </header>
        <p>Kaguya es hija de una familia muy importante y millonaria. Shirogane es también hijo de buena familia y
            presidente del consejo. Ambos son admirados por todos en la Academia Shuchiin, y ambos están enamorados el
            uno del otro, pero no se rebajarán a admitirlo y ambos intentan que sea el otro el que declare primero su
            amor.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/recursos-cesde.appspot.com/o/Kaguya-sama-Love-is-War-pelicula-trailer-estreno-Latinoamerica-900x506.jpg?alt=media&token=96ace4ac-af72-4b21-b60c-2f9d3ba4ffaf"
            alt="Kaguya" width="350">
    </section>

    <section>
        <header>
            <h2>Gotoubun no Hanayome</h2>
        </header>
        <p>Fuutarou Uesugi es un estudiante de segundo año de preparatoria/instituto cuya familia siempre ha sido muy pobre. Un día recibe una suculenta oferta de trabajo como tutor a medio tiempo... ¡pero sus estudiantes resultan ser unas chicas de su propia clase! Para complicar más las cosas, son quintillizas... Las cinco hermanas son todas muy atractivas, pero no es lo único que tienen en común: todas odian estudiar y sus calificaciones siempre están al límite de la catástrofe. Tendrá que conseguir que las cinco estudien, pero primero tendrá que estudiar él cómo ganarse su confianza.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/recursos-cesde.appspot.com/o/SOVPLKB6LZFUXICS5SKPLJZSRM.jpg?alt=media&token=92852cd4-a4bb-4b4f-8275-f98fa40b383e"
            alt="Kaguya" height="350">
    </section>
<br><br><br>
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
contact.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>

<body>
    <header>
        <h1><span style="color: rgb(182, 40, 211);"><i>
                    <center>Contacto</center>
                </i></span></h1>
    </header>


    <main>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre"><br><br>
            <label for="email">Email:</label>
            <input type="text" id="email"><br><br>
            <label for="mensaje">Mensaje:</label>
            <input type="text" id="mensaje"><br><br>
            <input type="submit" value="Enviar">

        </form>

        <aside>

<h3>Ubicación</h3>
<p>mi casa</p>

<h3>Email</h3>
<p>luisitogomez540@gmail.com</p>
        </aside>


    </main>

    <nav>
        <ul>
            <li><a href="index.html">
                    <h2>Página principal</h2>
                </a></li>
            <li><a href="about.html">
                    <h2>Acerca de</h2>
                </a></li>
        </ul>
    </nav>
<br><br><br>

    <footer>

        <p>Copyright 2023 - Angello Gómez</p>
    </footer>
</body>

</html>

```

about.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p><span style="color: rgb(76, 112, 18);">
        <FONT SIZE=5>Esta es mi primera página web, aquí podrás encontrar mis mascotas,
            información sobre mi, y mi contacto.</FONT>
    </span></p>

    <h1><span style="color: rgb(182, 40, 211);"><u>Sobre mi:</u></span></h1>
    <p><span style="color: rgb(76, 112, 18);">
        <FONT SIZE=5>Mi nombre es Angello Gómez Monsalve, tengo 21 años. Estudié parte de la carrera de ingenieria de sitemas en la universidad nacional de colombia.
            Me apasionan los videojuegos, conversar con amigos, pasar tiempo en familia, y en mi experiencia con el mundo de la programación puedo afirmar que tambien me apasiona.
        </FONT>
    </span></p>

    <nav>
        <ul>
          <h2> <li> <a href="index.html">Volver a la pagina principal</a></li></h2>
          <h2><li> <a href="contact.html">Contacto</a></li></h2> 


        </ul>

    </nav>
    <footer>

        <p>Copyright 2023 - Angello Gómez</p>
        <p>luisitogomez540@gmail.com</p>
    </footer>
</body>
</html>
```






