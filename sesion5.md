<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


# Actividad: Diseñar un formulario de pedido de un producto

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crearun nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
    - Nombre del producto
    - Cantidad
    - Precio unitario
    - Precio total
    - Dirección de envío
    - Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
    - Método de pago
    - Fecha de entrega
    - Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

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
    <form action="">


        <header>

            <h1>
                <center>Formulario</center>
            </h1>
        </header>
        <div>
            <label for="idproducto">* Nombre del Producto: </label>
            <input type="text" name="producto" id="idproducto" required>
        </div>
        <br>
        <div>
            <label for="idcantidad">* Cantidad: </label>
            <input type="number" name="cantidad" id="idcantidad" min="0" required>

        </div>
        <br>
        <div>
            <label for="idpreciounitario">* Precio unitario: </label>
            <input type="number" name="preciounitario" id="idpreciounitario">

        </div>
        <br>
        <div>
            <label for="idpreciototal">Precio total: </label>
            <input type="number" name="preciototal" id="idpreciototal">

        </div>
        <br>
        <div>
            <label for="iddireccion">* Dirección del produto: </label>
            <input type="text" name="direccion" id="iddirec" required>

        </div>

        <h2>
            Informarción de contacto
        </h2>
        <br>
        <div>
            <label for="idnombre">* Nombre: </label>
            <input type="text" name="nombre" id="idnombre" required>

        </div>
        <br>
        <div>
            <label for="idapellido">* Apellido: </label>
            <input type="text" name="apellido" id="idapellido" required>

        </div>
        <br>
        <div>
            <label for="idemail">* Correo electronico: </label>
            <input type="email" name="email" id="idsemail" placeholder="pepito@dominio.hola" required>


        </div>

        <br>
        <div>
            <label for="idnumero">* Número telefónico: </label>
            <input type="tel" name="telefono" id="idnumero" required maxlength="10">


        </div>
        <h2>Mas Informarción</h2>
        <div>

            <label for="idmetodopago">Metodo de pago: </label>
            <select name="Metodopago" id="idmetodopago" required>

                <option value="tarjetaCredito">Tarjeta de credito</option>
                <option value="pse">PSE</option>
                <option value="efecty">Efecty</option>
                <option value="embargo">Mis pertenencias</option>

            </select>
        </div>

        <br>

        <div>

            <label for="idfechadeentrega">Fecha de entrega: </label>
            <input type="date" name="fechadeentrega" id="idfechadeentrega" required>


        </div>
        <br>
        <div>
            <label for="comentariosid">Comentarios, sugerencias, inquietudes: </label>
            <br>
            <textarea name="" id="" cols="50" rows="5"></textarea>


        </div>
        <br><br>
        <div>

            <button type="reset">Reiniciar formulario</button>
            <input type="submit" value="Enviar">

        </div>
    </form>
</body>

</html>
```






