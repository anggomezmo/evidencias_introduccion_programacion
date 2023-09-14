<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

## Solución

### index.html

```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi pagina bacana la mejor del mundo</title>
</head>

<body>
    <main>
        <header>
            <h1><span style="color: rgb(182, 40, 211);"><i>
                        <center>Página principal</center>
                    </i></span></h1>
        </header>

        <figure>
            <center><img src="gatos.jpeg" width="400" height="400" /></center>
        </figure>
        <p><span style="color: rgb(76, 112, 18);">
                <FONT SIZE=5>Estos son mis gatos: El de atras es Julieto, y la de adelante es Mila. Julieto tiene 1 año
                    y Mila 7 meses.
                </FONT>
            </span></p>

        <figure>
            <center><img src="juana.jpeg" width="400" height="400" /></center>
        </figure>
        <p><span style="color: rgb(76, 112, 18);">
                <FONT SIZE=5>Esta es mi perra: Se llama Juana y tiene entre 11 y 12 años.
                </FONT>
            </span></p>
    </main>



    <nav>
        <ul>
            <li><a href="about.html">
                    <h2>Acerca de</h2>
                </a></li>
            <li><a href="contact.html">
                    <h2>Contacto</h2>
                </a></li>
        </ul>
    </nav>

    <footer>

        <p>Copyright 2023 - Angello Gómez</p>
        <p>luisitogomez540@gmail.com</p>
    </footer>
</body>

</html>


```

### About.html

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

### contact.html

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






