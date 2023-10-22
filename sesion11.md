<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

# Solución

## index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad 11</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>soy un h1</h1>
    <h1>otro h1</h1>
    <div>
    <p class="p1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur, quas dicta? Ut temporibus alias velit nam eveniet corporis labore dolorem, inventore harum sit ea molestias ab odio dolores dolor. Neque!
    
    </p>
    </div>
    <a href="#">hola</a>
    <p class="hola">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam, repellat voluptates. Eaque exercitationem, vitae consequatur odit beatae minima dolor nihil tempore porro laboriosam veritatis pariatur in quidem dolorum ut atque.

    </p>
</body>
</html>
```

## style.css

```css
body {
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
    color: #000;
    background-color: #fff;
    font-family: sans-serif;
    font-size: 16px;
    border: 4px solid black;
}

h1 {
    width: 50%;
    height: 100px;
    margin: 10px auto;
    padding: 20px;
    color: #fff;
    background-color: #000;
    font-family: 'Times New Roman', serif;
    font-size: 24px;
    font-weight: bold;
    text-align: center;
    border-width: 5px;
    border-style: dotted;
    border-color: rgb(255, 0, 119);
}

.p1 {
    float: left;

    margin: 10px;
    padding: 20px;
    background-image: url(https://c0.klipartz.com/pngpicture/537/682/gratis-png-perros.png);
    background-repeat: repeat;
    background-position: center;
    background-size: 10%;

    font-style: italic;
    font-variant: small-caps;
    font-weight: bolder;
    color: rgb(216, 81, 57);

    border-radius: 10px;
}

div {
    width: 400px;

}

a {
    color: rgb(47, 0, 255);
}

a:link {
    background-color: rgb(255, 0, 0);
}

a:active {
    background-color: green;
}

.hola {
    background-color: rgb(189, 149, 149);

}

.hola:hover {
    background-color: rgb(163, 10, 10);
}

p::first-line {
    font-weight: bold;
    color: red;
}
```




