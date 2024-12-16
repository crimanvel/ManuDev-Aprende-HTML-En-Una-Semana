# Día 6: Crear formularios de contacto en tu portafolio

## 🛠️ Objetivo del día

Hoy aprenderás a:
- Crear un **formulario de contacto** con HTML.
- Usar etiquetas como `<form>`, `<input>`, `<textarea>`, y `<button>`.

Al finalizar, tu portafolio permitirá que las personas te contacten directamente.

---

## 📜 Introducción a formularios

Los formularios son esenciales para recopilar información del usuario. En un portafolio, un formulario de contacto permite a los visitantes enviarte un mensaje.

### 📝 Elementos básicos de un formulario
Un formulario en HTML se crea con la etiqueta `<form>`. Dentro de esta etiqueta se incluyen campos como:
- **`<input>`**: Para entradas de texto, correos electrónicos, contraseñas, etc.
- **`<textarea>`**: Para mensajes largos.
- **`<button>`**: Para enviar el formulario.

Ejemplo básico:
```html
<form action="https://example.com/enviar" method="POST">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>
  
  <label for="email">Correo electrónico:</label>
  <input type="email" id="email" name="email" required>
  
  <label for="mensaje">Mensaje:</label>
  <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
  
  <button type="submit">Enviar</button>
</form>
```
Atributos importantes de `<form>`:

-action: URL donde se enviará la información.
-method: Define cómo se enviará la información (GET o POST).
-required: Hace que un campo sea obligatorio.

✍️ Actividad: Crear tu formulario de contacto

Objetivo:
Agregar un formulario de contacto funcional a tu portafolio.

Instrucciones:
1. Abre tu archivo `index.html`.
2. Crea una nueva sección llamada "Contacto" dentro de <main>.
3. Agrega el siguiente formulario de contacto:
   
```html
<section id="contacto">
  <h2>Contáctame</h2>
  <form action="#" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
    
    <label for="email">Correo electrónico:</label>
    <input type="email" id="email" name="email" placeholder="Tu correo electrónico" required>
    
    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe tu mensaje aquí..." required></textarea>
    
    <button type="submit">Enviar</button>
  </form>
</section>
```
Guarda los cambios y abre el archivo en tu navegador para verificar que el formulario se muestra correctamente.

🌟 Reto adicional (opcional)

Agrega validaciones básicas: Usa atributos como pattern o maxlength en los campos de entrada. 

Ejemplo:

```html
<input type="text" id="nombre" name="nombre" pattern="[A-Za-z ]+" title="Solo se permiten letras y espacios" required>
```
🌱 ¿Qué sigue?

En el Día 7 revisaremos tu portafolio completo, haremos ajustes finales y aprenderemos cómo publicarlo para que esté disponible en internet. ¡Nos vemos mañana! 🚀
