# Desafío 2 - Condiciones

## Descripción

Este proyecto corresponde al **Desafío 2 - Condiciones** del curso de **JavaScript para la Web** de **Desafío Latam**.

El desafío tiene como objetivo validar conocimientos sobre la manipulación del DOM, el uso de estructuras condicionales (`if`, `else if`, `else`) y operadores lógicos mediante la resolución de tres ejercicios prácticos.

## 🚀 Link del Deploy

🔗 **Deploy:**

---

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- DOM (Document Object Model)

---

## Problema 1: Bordes de Imagen

Se desarrolló una página que contiene una imagen interactiva.

### Requerimientos

- Agregar un borde rojo de 2px al hacer clic sobre la imagen.
- Quitar el borde al volver a hacer clic.

### Solución

Se utilizó `addEventListener` para detectar el evento de clic sobre la imagen y una estructura condicional para alternar dinámicamente el borde mediante JavaScript.

---

## Problema 2: Stickers

Se construyó una página que permite seleccionar hasta 10 stickers entre tres opciones disponibles.

### Requerimientos

- Mostrar la cantidad total de stickers seleccionados.
- Indicar cuando la cantidad supera el límite permitido.

### Solución

Se capturan los valores ingresados en los inputs numéricos, se suman y se valida el resultado mediante estructuras condicionales:

- Si el total es menor o igual a 10, se muestra el mensaje:
  ```
  Llevas X stickers
  ```
- Si el total es mayor a 10, se muestra:
  ```
  Llevas demasiados stickers
  ```

---

## Problema 3: Password

Se desarrolló una página con tres elementos `select` que permiten generar una contraseña mediante la selección de dígitos.

### Requerimientos

- Mostrar **"password 1 correcto"** si la combinación es `911`.
- Mostrar **"password 2 correcto"** si la combinación es `714`.
- Mostrar **"password incorrecto"** para cualquier otra combinación.

### Solución

Se concatenan los valores seleccionados y se evalúan mediante una estructura `if - else if - else`, mostrando el mensaje correspondiente al usuario.

---

## Aprendizajes

Durante este desafío se reforzaron los siguientes conceptos:

- Manipulación del DOM.
- Eventos en JavaScript.
- Uso de condicionales.
- Operadores lógicos y de comparación.
- Captura y validación de datos de entrada.
- Actualización dinámica del contenido HTML.

---

## Autor

**Patricio Tapia**

Proyecto desarrollado para el curso **Desafío Latam - JavaScript para la Web**.
