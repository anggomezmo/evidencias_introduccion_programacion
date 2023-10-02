<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

# Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado ```header```
- Tres párrafos ```<p>```
- Una imagen ```<img>```
- Un pie de página ```footer>```

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados ```h1```
- Color azul a los párrafos ```<p>```
- Borde grueso negro a la imagen ```<img>```

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

-Color amarillo al elemento con ID "#principal"
-Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un ```<div>```
- Centrar el contenido de la sección ```<section>```

# Solución.

## index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stylesheet.css">
</head>

<body>
    <header>
        <h1>Videojuegos</h1>
    </header>


    <p id="principal">Un videojuego o juego de video es un juego electrónico en el que uno o más jugadores interactúan
        por medio de
        un controlador, con un dispositivo electrónico que muestra imágenes de video.</p>

    <p>Este dispositivo, conocido genéricamente como «plataforma», puede ser una computadora, una máquina de arcade,
        una consola de videojuegos o un dispositivo portátil, como por ejemplo un teléfono móvil, teléfono
        inteligente, tableta o una consola de videojuegos portátil.</p>

    <p class="destacado">La industria de los videojuegos es un sector en constante crecimiento y se ha convertido en una
        forma de
        entretenimiento muy popular a nivel mundial.</p>

    <section id="centrar">
        <img src="https://firebasestorage.googleapis.com/v0/b/recursos-cesde.appspot.com/o/Sekiro_28.webp?alt=media&token=6bf5adf4-62b1-4276-975a-455919e1ca96&_gl=1*fb5lvt*_ga*MTg4NTI1Njk1OS4xNjk0NzA5ODcw*_ga_CW55HF8NVT*MTY5NjIxNzU2OS41LjEuMTY5NjIxNzY5MC4xNC4wLjA."
            alt="" height="300">
    </section>
    <div>
        <p>Los jugadores interactúan con los videojuegos a través de dispositivos de entrada a los que se les conoce
            como controladores o mandos. Mediante estos dispositivos, los jugadores controlan los movimientos y acciones
            de los personajes del juego y varía dependiendo de la plataforma. Por ejemplo, un controlador podría
            únicamente consistir de un botón y una palanca de mando o joystick, mientras otro podría presentar una
            docena de botones y una o más palancas, lo que llamamos mando.</p>

        <p>Los primeros juegos informáticos solían hacer uso de un teclado para llevar a cabo la interacción, o bien
            requerían que el usuario adquiriera un mando con un botón como mínimo.​ Muchos juegos de computadora
            modernos permiten o exigen que el usuario utilice un teclado y un ratón de forma simultánea.</p>
    </div>
    <section>
        <p>
            Generalmente los videojuegos hacen uso de otras maneras, aparte de la imagen, de proveer la interactividad e
            información al jugador. El audio es casi universal, usándose dispositivos de reproducción de sonido, tales
            como altavoces y auriculares.

        </p>
        <p id="sombras">
            Otro tipo de realimentación se hace a través de periféricos hápticos que producen vibración o
            retroalimentación de fuerza.
        </p>
    </section>
    <footer>

        <p class="grande">Copyright 2023 - Angello Gómez</p>
        <p>luisitogomez540@gmail.com</p>
    </footer>
</body>

</html>

```

## stylesheet.css

```css
h1{
    color: red;
}
p{
    color:blue;
}
img{
    border: 10px solid black;
}
.destacado{
    color: green;
}
.grande{
    font-size: 35px;
}
#principal{
    color:yellow;

}
#sombras{
    box-shadow: 0px 0px 10px rgba(183, 16, 16, 0.5);
}
div p{
    color: gray;
}
section#centrar {
 display: flex;
 align-items: center;
 justify-content: center;

}section p{
    text-align: center;
}
```



