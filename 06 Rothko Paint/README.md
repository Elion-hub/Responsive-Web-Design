# Rothko Painting

Este proyecto recrea un **estilo de pintura abstracta al estilo Rothko** utilizando HTML y CSS. Se compone de un lienzo (`.canvas`) con tres bloques de color (`.one`, `.two`, `.three`) dentro de un marco (`.frame`). Cada bloque tiene efectos de **desenfoque (blur)**, **sombra (box-shadow)** y **bordes redondeados (border-radius)** para lograr un efecto visual similar a las pinturas de Rothko.

## Contacto
- LinkedIn: [www.linkedin.com/in/josem-garcia-](https://www.linkedin.com/in/josem-garcia-)

## Vista previa

![Rothko Painting](https://raw.githubusercontent.com/Elion-hub/Responsive-Web-Design/main/06%20Rothko%20Paint/RothkoPaint.PNG)

## Estructura del proyecto

- `index.html` → contiene la estructura HTML de la pintura.
- `styles.css` → contiene los estilos CSS aplicados a la pintura y al marco.
- `RothkoPaint.png` → imagen de referencia del resultado (opcional).

## HTML principal

```html
<div class="frame">
  <div class="canvas">
    <div class="one"></div>
    <div class="two"></div>
    <div class="three"></div>
  </div>
</div>