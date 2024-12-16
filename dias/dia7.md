
# Día 7: Agregar video, Google Maps y personalizar tu portafolio con CSS
## 🛠️ Objetivo del día

Hoy aprenderás a:

-Incorporar un video de YouTube en tu portafolio utilizando la etiqueta `<iframe>`.

-Agregar un mapa de Google Maps usando un `<iframe>`.

Introducción a CSS: Cambiar el fondo de tu portafolio.

#📜 Teoría
##🎥 Agregar video de YouTube: `<iframe>`

La etiqueta `<iframe>` te permite embeber contenido externo, como videos, dentro de tu página web. 

En este caso, agregarás un video de YouTube.

Ejemplo de código:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

🌍 Agregar Google Maps: `<iframe>`

Puedes integrar un mapa de Google Maps directamente en tu página usando también la etiqueta `<iframe>`. Asegúrate de obtener el código de inserción desde Google Maps.

Ejemplo de código:
```html
<iframe src="https://www.google.com/maps/embed?pb=..." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
```

🎨 Introducción a CSS
CSS (Cascading Style Sheets) te permite personalizar el diseño de tu portafolio.

Hoy aprenderás cómo cambiar el fondo de tu página con una propiedad simple.

Ejemplo de código CSS para cambiar el fondo:
```css
body {
  background-color: #f0f0f0; /* Color de fondo */
}
```

✍️ Actividad: Personaliza tu portafolio
1. Abre tu archivo index.html.
2. Agrega una sección con un video de YouTube usando la etiqueta `<iframe>`.
3. Agrega un mapa de Google Maps de tu ubicación o una de tus preferencias usando otro <iframe>.
4. Crea un archivo de estilo style.css y vincúlalo a tu archivo HTML para cambiar el fondo del portafolio.

Código ejemplo:
```html
<!-- Video -->
<section id="video">
  <h2>Mi Video</h2>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>

<!-- Mapa -->
<section id="mapa">
  <h2>Mi Ubicación</h2>
  <iframe src="https://www.google.com/maps/embed?pb=..." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</section>

<!-- Enlace al archivo CSS, dentro del head -->
<link rel="stylesheet" href="style.css">
```
🌟 Reto adicional (opcional)

Agrega más personalización con CSS. Cambia colores de texto, bordes, o agrega una imagen de fondo.

🌱 ¿Qué sigue?

Hasta llegamos con HTML, te invito proximamente a mi repo de css para sumarle diseño a tu portafolio, pero te dejo un extra!

En el Día Extra, revisaremos tu portafolio completo, haremos ajustes finales y aprenderemos cómo publicarlo para que esté disponible en internet

