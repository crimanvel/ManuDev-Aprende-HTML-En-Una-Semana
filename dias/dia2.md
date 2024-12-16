
![DIA1 (3)](https://github.com/user-attachments/assets/8f792db2-7b33-4709-959f-b51e85310843)

# Día 2: Estructura de la página: Header, Main y Footer!



## 🛠️ Objetivo del día

Hoy aprenderás a organizar tu portafolio web utilizando las etiquetas **semánticas principales** de HTML (dentro de la etiqueta body):
- `<header>`  
- `<main>`  
- `<footer>`  

Al finalizar, tu portafolio tendrá una estructura organizada y profesional. 🖥️

---

## 📜 ¿Qué son las etiquetas semánticas?

Las etiquetas semánticas son aquellas que **describen el propósito del contenido** que contienen. Esto no solo facilita la lectura del código para desarrolladores, sino que también mejora el SEO y la accesibilidad de tu página.

### 🏗️ Principales etiquetas semánticas:
1. **`<header>`**: Se usa para el encabezado de la página o sección.  
   - Suele incluir el título, logotipo o menú de navegación.
2. **`<main>`**: Contiene el contenido principal de la página.  
   - Solo debe haber un `<main>` por documento HTML.
3. **`<footer>`**: Se usa para el pie de página.  
   - Incluye información como derechos de autor, enlaces a contacto o redes sociales.

---

## ✨ Estructura básica del portafolio

Aquí tienes un ejemplo de cómo organizar el contenido de tu portafolio con estas etiquetas:

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Portafolio</title>
  </head>
  <body>
    <header>
      <h1>Mi Portafolio</h1>
      <nav>
        <ul>
          <li><a href="#sobre-mi">Sobre mí</a></li>
          <li><a href="#proyectos">Proyectos</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="sobre-mi">
        <h2>Sobre mí</h2>
        <p>¡Hola! Soy un desarrollador web en formación. Este es mi portafolio.</p>
      </section>

      <section id="proyectos">
        <h2>Mis proyectos</h2>
        <p>Pronto agregaré más contenido aquí.</p>
      </section>
    </main>

    <footer>
      <p>© 2024 Mi Nombre. Todos los derechos reservados.</p>
    </footer>
  </body>
</html>
```
✍️ Actividad: Continúa tu portafolio
Objetivo:
Ampliar el archivo index.html creado en el Día 1, añadiendo las etiquetas semánticas principales.

Instrucciones:
Abre el archivo index.html que creaste en el Día 1.
Modifica la estructura para incluir las siguientes etiquetas:

`<header>`: Usa esta etiqueta para envolver el título de tu página y un menú de navegación.

`<main>`: Aquí irá el contenido principal (ej. "Sobre mí", "Proyectos").

`<footer>`: Añade un pie de página con derechos de autor.

Asegúrate de que tu código se vea como este ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Portafolio</title>
  </head>
  <body>
    <header>
      <h1>Mi Portafolio</h1>
      <nav>
        <ul>
          <li><a href="#sobre-mi">Sobre mí</a></li>
          <li><a href="#proyectos">Proyectos</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="sobre-mi">
        <h2>Sobre mí</h2>
        <p>¡Hola! Soy un desarrollador web en formación. Este es mi portafolio.</p>
      </section>

      <section id="proyectos">
        <h2>Mis proyectos</h2>
        <p>Pronto agregaré más contenido aquí.</p>
      </section>
    </main>

    <footer>
      <p>© 2024 Mi Nombre. Todos los derechos reservados.</p>
    </footer>
  </body>
</html>

```
Guarda los cambios y abre el archivo en tu navegador para ver cómo luce la estructura.

Listas en HTML
Las listas en HTML permiten organizar contenido en forma de elementos enumerados o agrupados. Hay dos tipos principales de listas:

Listas ordenadas (<ol>): Se utilizan cuando el orden de los elementos es importante. Cada elemento se numera automáticamente.
Listas no ordenadas (<ul>): Se utilizan para agrupar elementos sin un orden específico. Se marcan con viñetas.
Cada elemento de una lista se define con la etiqueta <li>.

🌟 Reto adicional (opcional)
Agrega una lista adicional en el footer con enlaces a tus redes sociales. Por ejemplo:
```html
<footer>
  <p>© 2024 Mi Nombre. Todos los derechos reservados.</p>
  <ul>
    <li><a href="https://twitter.com/tuusuario">Twitter</a></li>
    <li><a href="https://github.com/tuusuario">GitHub</a></li>
    <li><a href="https://linkedin.com/in/tuusuario">LinkedIn</a></li>
  </ul>
</footer>

```
🌱 ¿Qué sigue?
En el Día 3 aprenderás a trabajar con texto y encabezados, dando más estilo y estructura a tu portafolio. ¡Nos vemos mañana! 🚀
