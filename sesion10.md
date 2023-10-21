<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


# Actividad: Propiedades de posicionamiento de CSS

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```
Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.


Preguntas:

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?
Previous
Actividad Sesión 9
Next
Actividad Sesión 11
Actividad: Propiedades de posicionamiento de CSS

# Solución



## index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div class="div1">
        <div class="div2">
            <div class="div3">
                
                <div class="div4" >
                    
                </div>
            </div>
        </div>
    </div>

  
</body>
</html>
```
## style.css

```css
.div1{
    position: absolute;
    top: 20px;
    left: 450px;
    background-color: red;
    height: 100px;
    width:250px;
     z-index: 0;
    
}
.div2{
   position: relative;
    top:56px;
    background-color: green;
    height: 1000px;
    width:250px;	
    
    z-index: 1;
}
.div3{
   
    top: 56px;
   position: relative;
   background-color: yellow;
    height: 1000px;
    width:250px;	
    z-index: 2;
}
.div4{
    position: relative;
    top:56px;
  background-color: blueviolet;
    height: 1000px;
    width:250px;	
    z-index: 3;
}
```

## RESPUESTAS PREGUNTAS

1.  
La diferencia principal entre los valores position: absolute y position: relative en CSS tiene que ver con cómo se posiciona un elemento con respecto a su contexto y cómo interactúa con otros elementos en la página. Aquí hay una explicación de cada uno:

position: relative:

Con position: relative, un elemento se posiciona con respecto a su posición original en el flujo normal del documento.
Si aplicas valores de desplazamiento (como top, right, bottom o left) a un elemento con position: relative, se moverá con respecto a su posición original en el flujo del documento, pero dejará un espacio vacío en su posición original en el diseño.
Los elementos con position: relative no afectan la posición de otros elementos en la página, ya que mantienen su espacio original en el diseño.
position: absolute:

Con position: absolute, un elemento se posiciona con respecto a su ancestro más cercano que tenga una propiedad position diferente de static (que es el valor predeterminado).
Si aplicas valores de desplazamiento a un elemento con position: absolute, se moverá con respecto a su ancestro posicionado más cercano. Si no hay un ancestro posicionado, se basará en el cuerpo ```<body>``` como su referencia.
Los elementos con position: absolute pueden superponerse a otros elementos, y no dejan un espacio vacío en su posición original en el diseño. Pueden solapar otros elementos si sus posiciones se superponen.
En resumen, position: relative mantiene el flujo normal del documento y se desplaza con respecto a su posición original, mientras que position: absolute se posiciona con respecto a un ancestro posicionado o al cuerpo y puede superponerse a otros elementos. La elección entre estos valores depende de cómo quieras que un elemento se comporte en tu diseño y de su relación con otros elementos en la página.

2. 
La propiedad z-index se utiliza para controlar el orden de apilamiento de los elementos posicionados (aquellos con position: relative, position: absolute, o position: fixed) en una página web. Puedes utilizarla para determinar cuál elemento se superpone a otros cuando se superponen en el diseño. Aquí hay una descripción de cómo se usa la propiedad z-index:

Valores de z-index:

z-index toma valores numéricos enteros y también puede tomar valores negativos.
Cuanto mayor sea el valor de z-index, más arriba se colocará un elemento en el orden de apilamiento. Si dos elementos se superponen y uno tiene un valor de z-index mayor que el otro, el elemento con el valor más alto se mostrará por encima del elemento con el valor más bajo.
Los elementos con valores de z-index más altos se superponen a los elementos con valores más bajos.

3. 

La propiedad display en CSS se utiliza para controlar cómo se muestra un elemento en una página web. Esta propiedad determina el tipo de caja de representación que se utiliza para el elemento, lo que a su vez afecta su comportamiento y apariencia en el diseño. Aquí tienes algunos de los valores más comunes de la propiedad display y cómo se utilizan:

display: block:

Los elementos con display: block se muestran en un bloque rectangular que ocupa todo el ancho disponible. Cada elemento comienza en una nueva línea y ocupa todo el ancho disponible, empujando otros elementos hacia abajo.
display: inline:

Los elementos con display: inline se muestran en línea con el texto circundante y solo ocupan el ancho necesario. Varios elementos con display: inline se pueden mostrar en la misma línea.
display: inline-block:

Similar a display: inline, pero los elementos con display: inline-block se comportan como bloques en términos de la caja de modelo, pero aún se muestran en línea con otros elementos.
display: none:

Con display: none, el elemento se oculta por completo y no ocupa espacio en el diseño. Es como si el elemento no existiera en la página.
display: flex:

Con display: flex, el elemento se convierte en un contenedor flexible que permite organizar sus elementos secundarios en filas o columnas, distribuyendo el espacio de manera equitativa.
display: grid:

Similar a display: flex, pero permite organizar elementos secundarios en un sistema de cuadrícula bidimensional. Es especialmente útil para diseños más complejos y estructurados.
display: table, display: table-row, display: table-cell:

Estos valores se utilizan para simular la estructura de una tabla HTML utilizando elementos no tabulares, como divs y spans. Puedes crear diseños de tabla sin necesidad de etiquetas de tabla reales.
display: inline-table:

Similar a display: table, pero se muestra en línea con el texto circundante.
display: list-item:

Con display: list-item, el elemento se trata como un elemento de lista, mostrando un marcador antes del contenido.
display: initial y otros valores iniciales:

Puedes usar display: initial para restablecer la propiedad display a su valor predeterminado, que depende del tipo de elemento.
display: inherit:

display: inherit heredará la propiedad display del elemento padre.