<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


# Actividad: Propiedades de espaciado y unidades de medida

Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
3. En el archivo CSS, agrega el siguiente código:
```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.
5. Practicar el uso de las propiedades de espaciado.
- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```css
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
- Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border: Agrega un borde de 5 píxeles de color rojo.


```css
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
- Border-radius: Agrega un radio de esquina de 10 píxeles.


```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
- Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
# Preguntas: 
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


# Solución

## index.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"><p>hola prueba prueba prueba prueba prueba prueba</p></div>
  </div>
</body>
</html>

```

## style.css

```css
.contenedor {
    width: 200px;
    height: 200px;
    background-color: pink;
    padding: 20px;
  }
  
  .elemento {
    width: 100px;
    height: 100px;
    background-color: blue;
   margin: 10px;
    padding: 20%;
    border: 6px solid green;
    border-radius: 40px;
  }


```

## Respuestas preguntas:

1. ¿Qué es la propiedad margin?
 
 La propiedad margin es una propiedad CSS que se utiliza para controlar el espacio exterior alrededor de un elemento HTML. En otras palabras, define el espacio en blanco o el espacio vacío que rodea un elemento en todas direcciones: arriba, abajo, izquierda y derecha. El valor que se le asigna a la propiedad margin determina la cantidad de espacio que se debe dejar fuera del elemento en cada uno de estos lados.

La propiedad margin se puede aplicar a elementos HTML como divs, párrafos, imágenes, entre otros, y es ampliamente utilizada en diseño web para controlar el espaciado entre elementos y mejorar la maquetación de una página.

2. ¿Qué es la propiedad padding?

La propiedad padding es una propiedad CSS que se utiliza para controlar el espacio interno o el espacio dentro de los bordes de un elemento HTML. En otras palabras, define la cantidad de espacio en blanco o espacio vacío que debe haber entre el contenido del elemento y sus bordes.

La propiedad padding se utiliza para ajustar el espaciado interno de un elemento y puede aplicarse a una variedad de elementos HTML, como divs, párrafos, encabezados, imágenes, etc. Esta propiedad es fundamental para controlar la presentación y el diseño de una página web.

3. ¿Qué es la propiedad border?

La propiedad border es una propiedad CSS que se utiliza para definir y estilizar los bordes alrededor de un elemento HTML. Los bordes son líneas o áreas visibles que rodean el contenido de un elemento y se utilizan para separar visualmente un elemento de su entorno, resaltar o enmarcar elementos y proporcionar un aspecto visual específico.

4. ¿Qué es la propiedad border-radius?

La propiedad border-radius es una propiedad CSS que se utiliza para controlar la curvatura o redondez de las esquinas de un elemento con bordes, como divs, cajas, imágenes u otros elementos HTML. Esta propiedad permite crear esquinas redondeadas en lugar de esquinas afiladas, lo que puede dar un aspecto más suave y estilizado a los elementos en una página web.

5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

En CSS, puedes utilizar diversas unidades de medida para especificar valores en las propiedades de espaciado, como margin, padding, border-width, entre otras. Algunas de las unidades de medida más comunes incluyen:

- Píxeles (px): Esta es una unidad de medida absoluta y se utiliza ampliamente. Un píxel representa un punto en la pantalla del dispositivo y es una unidad fija. Por ejemplo, 10px representa 10 píxeles.

- Porcentaje (%): Esta unidad de medida es relativa al tamaño del elemento contenedor. Por ejemplo, si estableces un margen del 10% en un elemento, se calculará como el 10% del ancho del contenedor.

- Em (em): Esta unidad de medida es relativa al tamaño de fuente del elemento padre. Por defecto, 1em es igual al tamaño de fuente actual del elemento. Por ejemplo, si el tamaño de fuente del elemento padre es de 16px, entonces 1em será igual a 16px.

- Rem (rem): Similar a em, esta unidad de medida es relativa al tamaño de fuente del elemento raíz (generalmente el elemento <html>). Esto significa que 1rem es igual al tamaño de fuente del elemento raíz, lo que lo hace más predecible y evita problemas de cascada.

- Centímetros (cm), milímetros (mm), pulgadas (in): Estas son unidades de medida absolutas que se utilizan para especificar tamaños físicos en el mundo real, como dimensiones de impresión. Por ejemplo, 1cm representa un centímetro.

- Puntos (pt) y Picas (pc): Estas son unidades de medida relativas al tamaño de fuente. Un punto es aproximadamente igual a 1/72 de pulgada, y una pica es igual a 12 puntos.

- Viewport units (vw, vh, vmin, vmax): Estas unidades de medida son relativas al tamaño de la ventana gráfica del navegador. Por ejemplo, 1vw es igual al 1% del ancho de la ventana gráfica, y 1vh es igual al 1% de la altura de la ventana gráfica.

- Fracciones (fr): Esta unidad se utiliza en el contexto de distribución de espacio en contenedores flexibles y de cuadrícula. Una fracción (1fr) representa una parte igual del espacio disponible.
