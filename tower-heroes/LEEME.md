# Tower Heroes · Guía en Español

Landing page hecha solo con HTML y CSS (sin JavaScript), a partir del diseño de Figma.

## Estructura
- `index.html` – contenido de la página.
- `css/estilos.css` – todos los estilos. Las medidas usan `--u` (1 px del diseño de Figma), así la página conserva las proporciones del diseño en cualquier pantalla.
- `assets/img/` – imágenes (WebP) y vectores (SVG) exportados de Figma, con nombres descriptivos.
- `assets/fonts/` – Cal Sans, Nata Sans y los 4 íconos de las clases (Font Awesome Free).
- `assets/video/tower-heroes-trailer.mp4` – trailer del juego (con los controles propios del navegador).

## Pendiente
- Cuando tengas los enlaces reales: cambiar los `<button class="boton">` de "Ver Más" y los `<div class="pie__bloque">` del pie por `<a ... href="URL">` (los estilos ya funcionan con enlaces).

## Cómo funciona sin JavaScript
- Menú móvil: usa `:target`. El botón enlaza a `#menu` y lo abre; al tocar una sección o el botón de cerrar, el menú deja de ser el destino y se cierra solo.
- La cabecera queda fija arriba en móvil (`position: fixed`).
- Carrusel de estrategias: pasa solo cada 6 segundos y se pausa con el mouse encima. Al hacer clic en un punto se queda en esa estrategia (botones de opción ocultos).
