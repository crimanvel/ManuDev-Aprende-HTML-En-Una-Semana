# Día 2: Estructura de la página: Header, Main y Footer

## 🛠️ Objetivo del día

Hoy aprenderás a organizar tu portafolio web utilizando las etiquetas **semánticas principales** de HTML:
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

