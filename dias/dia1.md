![DIA1](https://github.com/user-attachments/assets/4331b9c9-ac68-4bc0-98b3-cadb3e6017a5)

Día 1: Introducción al HTML y la estructura de tu portafolio
🛠️ Objetivo del día
Hoy aprenderás a construir la estructura básica de tu portafolio utilizando HTML. Además, descubrirás cómo HTML interactúa con CSS y JavaScript.

Al final del día, habrás creado el esqueleto de tu sitio web personal. 🎉

📜 ¿Qué es HTML?
HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas web. Es como el esqueleto de tu página: sin él, no tendrías ninguna estructura.

🌟 Relación entre HTML, CSS y JavaScript
HTML: Proporciona la estructura del contenido (el esqueleto).
CSS: Da estilo al contenido (colores, tipografías, tamaños, diseño responsivo).
JavaScript: Añade funcionalidad (interactividad, formularios dinámicos, etc.).
Con estas tres herramientas, podrás crear sitios web completos y funcionales. 🖥️

🛠️ Herramientas necesarias
Para empezar a escribir código HTML, necesitas:

Un editor de texto (puedes usar el bloc de notas, pero recomiendo Visual Studio Code).
Un navegador web (Chrome, Edge, Firefox, etc.).
💡 Si necesitas instalar Visual Studio Code, revisa este https://www.youtube.com/watch?v=qEtTU5eNR7M&list=PLd4M2wjDKXtZa1fzvT-y2I-FQK8_tVB0l


## 📜 ¿Cómo puedo ver el código HTML de una página?

## Ver el código HTML de una página web

Para ver el código HTML de una página web en tu navegador, sigue estos pasos:

1. **Abre la página web** en tu navegador favorito (Google Chrome, Firefox, etc.).

2. **Accede a las herramientas de desarrollo**:
   - En **Google Chrome** o **Microsoft Edge**, haz clic derecho sobre cualquier parte de la página y selecciona **"Inspeccionar"** o **"Ver código fuente de la página"**.
   - En **Mozilla Firefox**, haz clic derecho sobre la página y selecciona **"Inspeccionar"** o **"Ver código fuente de la página"**.
     ![image](https://github.com/user-attachments/assets/540b6e90-926b-42c5-baef-42b594d98bc7)


3. **Ver el código HTML completo**:
   - Si seleccionas **"Ver código fuente"**, verás todo el HTML de la página en una nueva pestaña.
   - Si seleccionas **"Inspeccionar"**, se abrirá un panel con el código HTML estructurado de manera más dinámica.
     ![image](https://github.com/user-attachments/assets/2cc450b3-20d9-4471-be26-fbcfcfe67191)


4. **Modifica el código en vivo**:
   - Dentro de las herramientas de inspección, puedes hacer clic en los elementos de la página y ver su código HTML correspondiente.
   - Puedes cambiar el HTML o CSS temporalmente y ver cómo se afectan visualmente los cambios en la página.
   - ![image](https://github.com/user-attachments/assets/45256ff2-49ca-4341-9764-7be79ebde304)
     ![image](https://github.com/user-attachments/assets/78a18f0a-218a-441e-8f56-3d943adea3d9)



5. **Copiar el código HTML**:
   - Si solo necesitas copiar el código HTML, abre el código fuente (Ctrl + U en Chrome) y copia todo el contenido de la página.
   - En las herramientas de inspección, puedes hacer clic derecho sobre cualquier elemento y seleccionar **"Copiar"** > **"Copiar elemento"**.
     ![image](https://github.com/user-attachments/assets/6d44d545-a200-476e-b83a-61652aec4b04)


## Comprendiendo la Estructura de un Archivo HTML

En esta lección, aprenderemos cómo se compone un archivo HTML. Para facilitar la comprensión, usaremos la analogía de un **árbol**, donde las diferentes partes del archivo HTML serán comparadas con **ramas** y **etiquetas**.

Las etiquetas por lo general se componen de: 
![image](https://github.com/user-attachments/assets/c9edfada-c257-4f43-b6b5-70f5207312cc)

![image](https://github.com/user-attachments/assets/bef90b78-85f2-4d4a-8fe9-fd6b5c2642a2)

Aunque existen etiquetas que no es necesaria cerrar con la etiqueta a:

![image](https://github.com/user-attachments/assets/9b932315-ab2c-4e41-acba-3d27267f5c87)


## HTML Como un Árbol

Imagina que un archivo HTML es como un árbol. Al igual que un árbol tiene un **tronco** y **ramas**, un archivo HTML tiene una estructura jerárquica, donde cada parte está conectada y organizada de manera que el navegador pueda entender y mostrar la página correctamente.

### 1. El Tronco del Árbol: `<!DOCTYPE html>`

El primer paso en cualquier archivo HTML es la declaración `<!DOCTYPE html>`. Esta es la **base** de todo, el tronco que sostiene todo el documento. Esta declaración le indica al navegador que se está utilizando la versión HTML5.

Es otra etiqueta que tampoco es necesaria cerrar.


El Contenedor Principal: <html>
Después de la declaración <!DOCTYPE html>, la siguiente parte es la etiqueta <html>, que se podría comparar con la raíz del árbol. Esta etiqueta envuelve todo el contenido de la página HTML.

Ejemplo de como puede estructurarse dentro de la etiqueta html 
![image](https://github.com/user-attachments/assets/fa92b4aa-c933-48e3-8ac9-bdce736e68ef)

```html
<html lang="es">
  <!-- Aquí va todo el contenido del documento -->
</html>
```
Dentro de la etiqueta <html>, encontramos dos ramas principales: <head> y <body>.

1) Ramas Principales: "<head>" y "<body>"
   
Las etiquetas <head> y <body> son las ramas principales del árbol HTML. 

Cada una tiene un propósito diferente:

"<head>": Contiene información sobre la página que no es visible para los usuarios, como el título de la página, el conjunto de caracteres, y enlaces a hojas de estilo (CSS).

Ejemplo:
```html
<head>
  <meta charset="UTF-8">
  <title>Mi Página Web</title>
</head>
```
"<body>": Contiene todo el contenido visible de la página, como los encabezados, párrafos, imágenes, enlaces, etc.

Ejemplo:
```html
<body>
  <h1>Bienvenido a mi página web</h1>
  <p>Este es un párrafo de texto.</p>
</body>
```
Las Etiquetas (Ramas y Sub-ramas):
Dentro de las ramas "<head>" y "<body>", encontramos muchas sub-ramas. Estas son las etiquetas que definen los diferentes elementos de la página. Algunas de las etiquetas más comunes son:

Dentro de "<head>":
"<meta>": Define los metadatos de la página, como la codificación de caracteres.
"<title>": Establece el título que aparece en la pestaña del navegador.
Dentro de "<body>":
"<h1>" a "<h6>": Son las etiquetas de encabezado, donde "<h1>" es el encabezado principal (más grande) y "<h6>" es el más pequeño.

Ejemplo:
```html
<h1>Mi primer encabezado</h1>
<p>: Es una etiqueta de párrafo que contiene texto.
```
Ejemplo:
```html
<p>Este es un párrafo de texto en mi página.</p>
<a>: Es una etiqueta de enlace, usada para vincular a otras páginas.
```
Ejemplo:
```html
<a href="https://github.com">Visita mi GitHub</a>
```
Anidación de Etiquetas (Cómo se Organizan las Ramas)
Al igual que un árbol puede tener ramas dentro de otras ramas, las etiquetas HTML pueden estar anidadas. Esto significa que una etiqueta puede estar contenida dentro de otra.

Por ejemplo:
```html
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Portafolio</title>
  </head>
  <body>
    <h1>Bienvenido a mi portafolio</h1>
    <p>Este es el primer paso de mi página web.</p>
    <a href="https://github.com">Visita mi GitHub</a>
  </body>
</html>
```
     
# Actividad 1: Crear tu primer portafolio en HTML

## Objetivo:
Crear una página web sencilla que contenga un título y un mensaje de bienvenida. Este es el primer paso para construir tu portafolio web.

## Instrucciones:

1. **Crear un archivo `index.html`** en tu proyecto. (es importante que se llame index.html por que es el primer archivo que los navegadores abren)

2. **Escribe el siguiente código en el archivo `index.html`:**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi Portafolio</title>
  </head>
  <body>
    <h1>Bienvenido a mi portafolio</h1>
    <p>Este es el primer paso de mi página web.</p>
    <a href="https://github.com">Visita mi GitHub</a>
  </body>
</html>
