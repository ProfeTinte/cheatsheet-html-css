# Cheat Sheet de HTML y CSS

Este documento proporciona un cheat sheet para HTML y CSS, incluyendo ejemplos básicos y sintaxis común.

## Tabla de Contenidos

1. [HTML Cheat Sheet](#html-cheat-sheet)
2. [CSS Cheat Sheet](#css-cheat-sheet)

## HTML Cheat Sheet

| Elemento        | Descripción                           | Ejemplo                                                                 |
|-----------------|---------------------------------------|-------------------------------------------------------------------------|
| Encabezado      | Define los títulos de diferentes niveles | `<h1>Título 1</h1>`                                                     |
| Párrafo         | Define un párrafo                      | `<p>Este es un párrafo.</p>`                                            |
| Enlace          | Crea un hipervínculo                   | `<a href="https://www.ejemplo.com">Texto del enlace</a>`                |
| Imagen          | Inserta una imagen                     | `<img src="ruta/a/la/imagen.jpg" alt="Descripción de la imagen">`       |
| Lista no ordenada | Crea una lista con viñetas             | `<ul><li>Elemento 1</li><li>Elemento 2</li></ul>`                       |
| Lista ordenada  | Crea una lista numerada                | `<ol><li>Elemento 1</li><li>Elemento 2</li></ol>`                       |
| Tabla           | Define una tabla                       | `<table><tr><th>Encabezado 1</th><th>Encabezado 2</th></tr><tr><td>Dato 1</td><td>Dato 2</td></tr></table>` |

## CSS Cheat Sheet

| Propiedad         | Descripción                             | Ejemplo                          |
|-------------------|-----------------------------------------|----------------------------------|
| `color`           | Define el color del texto               | `color: red;`                    |
| `background-color`| Define el color de fondo                | `background-color: yellow;`      |
| `font-size`       | Define el tamaño de la fuente           | `font-size: 16px;`               |
| `font-weight`     | Define el grosor de la fuente           | `font-weight: bold;`             |
| `text-align`      | Alinea el texto                         | `text-align: center;`            |
| `margin`          | Define el margen exterior               | `margin: 10px;`                  |
| `padding`         | Define el relleno interior              | `padding: 20px;`                 |
| `border`          | Define el borde                         | `border: 1px solid black;`       |
| `border-radius`   | Define el radio del borde               | `border-radius: 5px;`            |
| `display`         | Define el tipo de caja de un elemento   | `display: flex;`                 |
| `position`        | Define la posición de un elemento       | `position: absolute; top: 50px; left: 100px;` |
| `float`           | Flota un elemento hacia un lado         | `float: right;`                  |
| `flex`            | Define un contenedor flexible           | `display: flex; justify-content: center; align-items: center;` |

### Ejemplo Integrado de HTML y CSS

```html
<!DOCTYPE html>
<html>
<head>
    <title>Ejemplo de Página</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f0f0f0;
        }
        h1 {
            color: blue;
            text-align: center;
        }
        p {
            font-size: 16px;
            line-height: 1.5;
            color: #333;
        }
        .enlace-rojo {
            color: red;
            text-decoration: none;
        }
        .contenedor {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
    </style>
</head>
<body>
    <div class="contenedor">
        <div>
            <h1>Bienvenidos a Mi Página Web</h1>
            <p>Este es un párrafo de ejemplo.</p>
            <a class="enlace-rojo" href="https://www.ejemplo.com">Visita Ejemplo</a>
        </div>
    </div>
</body>
</html>
