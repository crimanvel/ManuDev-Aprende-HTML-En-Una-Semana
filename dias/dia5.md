# Día 5: Usar tablas y listas para organizar contenido

## 🛠️ Objetivo del día

Hoy aprenderás a:
- Crear y usar **tablas** para mostrar información estructurada.
- Utilizar **listas ordenadas** y **no ordenadas** para organizar contenido.

Al final del día, tu portafolio será más organizado y fácil de leer.

---

## 📜 Introducción a tablas y listas

### 📋 Listas en HTML
Existen dos tipos principales de listas:
- **Listas ordenadas** (`<ol>`): Se usan para elementos que tienen un orden específico.
- **Listas no ordenadas** (`<ul>`): Se usan para elementos sin un orden específico.

Cada elemento de la lista se define con `<li>`.

Ejemplo:
```html
<h3>Habilidades</h3>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

<h3>Paso a paso:</h3>
<ol>
  <li>Diseñar el portafolio</li>
  <li>Escribir el código HTML</li>
  <li>Agregar estilos con CSS</li>
</ol>
```
📊 Tablas en HTML
Las tablas se crean con la etiqueta <table> y se estructuran en:

Filas: Definidas por <tr> (table row).
Celdas de datos: Definidas por <td> (table data).
Celdas de encabezado: Definidas por <th> (table header).
Ejemplo:
```html
<table>
  <thead>
    <tr>
      <th>Proyecto</th>
      <th>Descripción</th>
      <th>Enlace</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Proyecto 1</td>
      <td>Un proyecto increíble</td>
      <td><a href="https://github.com/proyecto-1" target="_blank">Ver más</a></td>
    </tr>
    <tr>
      <td>Proyecto 2</td>
      <td>Otro proyecto genial</td>
      <td><a href="https://github.com/proyecto-2" target="_blank">Ver más</a></td>
    </tr>
  </tbody>
</table>
```
✍️ Actividad: Organiza la sección de "Proyectos"
Objetivo:
Organizar la sección de "Proyectos" usando una tabla para mostrar información y una lista para destacar tecnologías.

Instrucciones:
Abre tu archivo index.html.
Encuentra o crea una sección llamada "Proyectos" dentro de <main>.
Reemplaza o agrega el contenido para que se vea como este ejemplo:
```html
<section id="proyectos">
  <h2>Mis Proyectos</h2>
  <table>
    <thead>
      <tr>
        <th>Proyecto</th>
        <th>Descripción</th>
        <th>Enlace</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Proyecto 1</td>
        <td>Un proyecto increíble</td>
        <td><a href="https://github.com/proyecto-1" target="_blank">Ver más</a></td>
      </tr>
      <tr>
        <td>Proyecto 2</td>
        <td>Otro proyecto genial</td>
        <td><a href="https://github.com/proyecto-2" target="_blank">Ver más</a></td>
      </tr>
    </tbody>
  </table>
  <h3>Tecnologías utilizadas:</h3>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ul>
</section>
```
Guarda los cambios y abre el archivo en tu navegador para ver cómo se ve.
🌟 Reto adicional (opcional)
Agrega otra tabla con tus hobbies o intereses. Por ejemplo:
```html
<table>
  <thead>
    <tr>
      <th>Hobby</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Lectura</td>
      <td>Disfruto leer libros sobre tecnología y ciencia ficción.</td>
    </tr>
    <tr>
      <td>Música</td>
      <td>Escuchar y explorar diferentes géneros musicales.</td>
    </tr>
  </tbody>
</table>
```
Experimenta con estilos CSS simples para mejorar el diseño de tus tablas.

🌱 ¿Qué sigue?
En el Día 6 aprenderás a crear formularios de contacto para que las personas puedan comunicarse contigo desde tu portafolio. ¡Nos vemos mañana! 🚀
