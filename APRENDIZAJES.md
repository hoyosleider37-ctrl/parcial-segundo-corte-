# Aprendizajes, dificultades e interacción con la IA

**Taller práctico tipo Parcial – segundo corte**
**Integrantes:** Marco Obregón, Leider Marino Hoyos

## 1. Qué se hizo

Se maquetó una página inspirada en la portada de Disney a partir de la imagen de referencia `parcialII 1.png`, usando HTML semántico y CSS (sin frameworks). Secciones: barra de navegación, hero (Snow White), 4 tarjetas sobre fondo azul, bloque verde azulado "Explore More Disney+", fila de 5 pósters, 2 tarjetas de parques, bloque promocional con botón morado y pie de página.

## 2. Aprendizajes

- **Modelo de caja:** se usó `box-sizing: border-box` global para que padding y border no cambien el ancho total de los elementos.
- **Flexbox vs Grid:** Flexbox para la barra de navegación y el hero (una dimensión); CSS Grid para tarjetas, pósters y parques (`grid-template-columns: repeat(n, 1fr)`).
- **Diseño responsive:** una `media query` en 760 px apila las secciones en una columna y oculta el menú.
- **Etiqueta viewport:** `<meta name="viewport">` es necesaria para que la página se adapte al móvil.
- **Semántica:** `header`, `nav`, `main`, `section`, `article`, `figure` y `footer` en lugar de `div` para todo.
- **Pair programming:** alternar los roles de "piloto" (escribe) y "copiloto" (revisa) y hacer commits por separado, cada integrante con su usuario.

## 3. Inconvenientes y dificultades

- La imagen de referencia tenía baja resolución y estaba tomada con celular, así que algunos textos y medidas exactas no se leían bien. Los textos se aproximaron y los colores se tomaron a ojo.
- Las fotos y pósters originales no estaban disponibles, por lo que se usaron **degradados como marcadores de posición**. Para acercarse más al pixel perfect hay que recortar las imágenes del PNG, guardarlas en una carpeta `img/` y reemplazar los degradados por `background-image` o `<img>`.
- Ajustar alturas y espacios para que coincidan con el diseño requiere comparar la maqueta con la referencia superpuesta (por ejemplo con las herramientas de desarrollador del navegador).

## 4. Interacción con la inteligencia artificial

Herramienta usada: **Claude (Anthropic)**.

**Prompt 1 (resumen):** se compartió la captura del taller de Teams y la imagen de referencia, y se pidió hacer el trabajo siguiendo las indicaciones del profesor.

**Respuesta de la IA (resumen):** analizó la imagen, identificó las secciones y generó `index.html`, `styles.css` y este documento. Aclaró que, por la calidad de la foto, los textos eran aproximados y las imágenes quedaron como degradados.

**Cómo se usó la respuesta:** el equipo revisó el código, lo comparó con la referencia y ajustó medidas, colores y textos. _(Completar aquí los cambios reales que hicieron y pegar o resumir las conversaciones adicionales con la IA.)_

## 5. Commits por integrante

| Integrante | Aporte |
|---|---|
| Marco Obregón | _(ej. estructura HTML, hero y navegación)_ |
| Leider Marino Hoyos | _(ej. CSS de tarjetas, pósters y responsive)_ |
