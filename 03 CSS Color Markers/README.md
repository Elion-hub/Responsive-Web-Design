🎨 CSS Color Markers

CSS Color Markers es un proyecto de práctica de CSS que crea marcadores de colores con capas y mangas, aplicando gradientes y sombras para un efecto más realista.

El proyecto está desarrollado únicamente con HTML y CSS.

🖥️ Vista previa

📂 Estructura del proyecto
CSS Color Markers/
│
├── index.html
├── styles.css
└── ColorMarkers.png

⚙️ Funcionalidades

Tres marcadores de colores: rojo, verde y azul.

Cada marcador tiene:

Cap (.cap): la “tapa” del marcador.

Sleeve (.sleeve): la “manga” del marcador.

Gradientes aplicados para simular profundidad y estilo visual.

Sombras aplicadas con box-shadow para realismo.

📖 HTML principal
<div class="marker red">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>
<div class="marker green">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>
<div class="marker blue">
  <div class="cap"></div>
  <div class="sleeve"></div>
</div>

🎨 CSS destacado
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
}

.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow: 0 0 20px 0 #3B7E20CC;
}

.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow: 0 0 20px 0 hsla(223, 59%, 31%, 0.8);
}

▶️ Cómo ejecutar

Abrir el archivo index.html en cualquier navegador moderno.

Observar los tres marcadores de colores con sus tapas, mangas y sombras aplicadas.

📌 Notas

Proyecto ideal para practicar gradientes, box-shadow y diseño de elementos inline-block.

Todo el estilo se gestiona desde styles.css.

![Color Markers](https://raw.githubusercontent.com/Elion-hub/Responsive-Web-Design/main/03%20CSS%20Color%20Markers/ColorMarkers.PNG)