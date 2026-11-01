# Taller práctico tipo Parcial segundo corte: Maquetación página Disney

## Integrantes
- Marco Obregón
- Leider Marino Hoyos

## Descripción
Maquetación en HTML y CSS de una página tipo Disney (sección de Blancanieves), tomando como referencia el diseño del repositorio `maquetacion-profesional-web-page`. El trabajo se hizo en pareja, practicando pair programming: cada integrante hizo commits con su propia cuenta de GitHub.

## Estructura del proyecto
```
parcial-segundo-corte/
├── index.html
├── css/
├── images/
└── APRENDIZAJES.md
```

## Aprendizajes
- Las rutas relativas de imágenes y CSS deben coincidir exactamente con los nombres de las carpetas (mayúsculas, tildes y extensión).
- Un HTML abierto desde dentro de un `.zip` usa una carpeta temporal; hay que extraerlo para que los cambios se guarden.
- Una imagen pequeña estirada se ve pixelada; es mejor usar las originales y `background-size: cover` u `object-fit: cover` para no deformarla.
- Se debe subir a GitHub el contenido extraído del proyecto y no el archivo `.zip`.
- En pair programming, uno escribe y el otro revisa; así detectamos errores de rutas y de estilos más rápido.

## Inconvenientes y dificultades
- Imágenes que no cargaban por rutas incorrectas.
- El banner de Blancanieves se veía estirado y con baja calidad.
- Lograr que la maqueta se pareciera lo más posible al diseño de referencia.
- Organizar los archivos y subirlos al repositorio de GitHub.

## Interacción con la inteligencia artificial
Nos apoyamos en Claude (Anthropic) durante el taller.

1. **Estructura inicial:** le compartimos capturas del repositorio base y de la carpeta de imágenes. Generó una primera versión de `index.html` y `styles.css` con los nombres reales de las imágenes.
2. **Imágenes rotas:** al ver las imágenes sin cargar, nos explicó que las rutas deben coincidir con la carpeta real (`images/`) y que el HTML debe abrirse extraído del zip.
3. **Subida a GitHub:** nos guió para cargar los archivos con **Agregar archivo → Cargar archivos**, sin subir el `.zip`, y para agregar al compañero como colaborador.
4. **Calidad del banner:** al notar la imagen estirada, nos recomendó revisar las dimensiones reales y usar `cover` en lugar de forzar el tamaño.
5. **Entrega:** nos recordó verificar que el repositorio fuera público, que ambos integrantes tuvieran commits y pegar el enlace en Teams.

## Enlace del repositorio
https://github.com/yanmarcos21-lgtm/parcial-segundo-corte
