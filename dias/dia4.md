
![github-html](https://github.com/user-attachments/assets/7cf9a7f9-4354-4038-bcae-d19adbe48365)

# Día 4: Agregar imágenes y enlaces a tu portafolio

## 🛠️ Objetivo del día

Hoy aprenderás a:
- **Agregar imágenes** a tu portafolio usando la etiqueta `<img>`.
- **Incluir enlaces** internos y externos con la etiqueta `<a>`.

Al finalizar, tu portafolio será más atractivo y funcional.

---

## 📜 Introducción a imágenes y enlaces

### 🖼️ Agregar imágenes: `<img>`
La etiqueta `<img>` te permite insertar imágenes en tu página web.

**Atributos importantes de `<img>`:**
- **`src`**: Especifica la URL o la ruta del archivo de la imagen.
- **`alt`**: Proporciona un texto alternativo que describe la imagen (importante para accesibilidad y SEO).

Ejemplo:
```html
<img src="https://via.placeholder.com/150" alt="Imagen de ejemplo">
```

🔗 Crear enlaces: <a>
La etiqueta <a> se utiliza para agregar enlaces.

Atributos importantes de <a>:

href: Especifica la URL a la que apunta el enlace.
target="_blank": (Opcional) Abre el enlace en una nueva pestaña.
Ejemplo de enlace externo:
```html
<a href="https://github.com" target="_blank">Visita mi GitHub</a>
```
Ejemplo de enlace interno:
```html
<a href="#sobre-mi">Ir a la sección Sobre mí</a>
```
✍️ Actividad: Agregar imágenes y enlaces
Objetivo:
Actualizar tu portafolio con imágenes y enlaces.

Instrucciones:
Abre el archivo index.html que has estado construyendo.
Encuentra o crea una nueva sección llamada "Proyectos" dentro de <main> y agrega una imagen y un enlace para cada proyecto.
Ejemplo:
```html
<section id="proyectos">
  <h2>Mis Proyectos</h2>
  <div>
    <h3>Proyecto 1</h3>
    <img src="https://via.placeholder.com/300x200" alt="Vista previa del proyecto 1">
    <p>Este es un breve resumen de mi proyecto. <a href="https://github.com/mi-proyecto" target="_blank">Ver más</a>.</p>
  </div>
  <div>
    <h3>Proyecto 2</h3>
    <img src="https://via.placeholder.com/300x200" alt="Vista previa del proyecto 2">
    <p>Este es otro de mis proyectos. <a href="https://github.com/mi-proyecto-2" target="_blank">Ver más</a>.</p>
  </div>
</section>
```
Guarda los cambios y abre el archivo en tu navegador para ver cómo se ve.
🌟 Reto adicional (opcional)
Enlaza imágenes como botones: Haz que las imágenes sean clicables usando <a> para envolverlas. Ejemplo:

```html
<a href="https://github.com/mi-proyecto" target="_blank">
  <img src="https://via.placeholder.com/150" alt="Vista previa del proyecto">
</a>
```
🌱 ¿Qué sigue?
En el Día 5 aprenderás a usar tablas y listas para organizar contenido en tu portafolio. ¡Nos vemos mañana! 🚀
