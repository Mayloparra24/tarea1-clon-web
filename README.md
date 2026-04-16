# tarea1-clon-web

## Información general

- **Estudiante:** Maylo Daring Parra Aguirre
- **Curso:** Multimedios
- **Sitio clonado:** Blog de viajes y lifestyle

## Descripción

Clon de un blog de viajes y lifestyle estilo revista, desarrollado como parte de la Tarea 1 del curso. El objetivo fue replicar la estructura y el diseño visual de un blog moderno utilizando únicamente HTML semántico y CSS puro, sin frameworks ni JavaScript.

## Tecnologías usadas

### HTML
- Estructura completa con `<!DOCTYPE html>`, `<head>` y `<body>`
- Etiquetas semánticas: `<main>`, `<section>`, `<article>`, `<aside>`
- Etiquetas `<img>` con atributo `alt` descriptivo en cada imagen
- Formulario de newsletter con 2 campos: `<input>` texto y `<input>` email

### CSS
- Archivo externo separado (`index.css`), sin usar `style=""` ni `<style>` en el HTML
- 3 tipos de selectores: de elemento (`body`, `a`, `img`), de clase (`.container`, `.hero-card`), pseudo-selectores (`:hover`, `:focus`, `:last-child`, `::placeholder`)
- Tipografía Roboto importada desde Google Fonts
- Paleta de colores con variables CSS: `--color-primario`, `--color-texto`, `--color-fondo`, entre otras
- Layouts con CSS Grid (hero cards de 3 columnas, layout principal de 2 columnas) y Flexbox (formulario newsletter, lista de categorías, recent posts)
- Diseño responsive con 2 media queries (900px, 600px)
- Comentarios en el CSS explicando decisiones de especificidad y cómo actúa la cascada

## Comparativa visual

### Screenshot del original

![Screenshot del sitio original](img/original.png)
- Esta es la imagen del blog original que se tomó como referencia

### Screenshot del resultado

![Screenshot del resultado](img/resultado.png)
- El clon replica la estructura y diseño del original: las 3 tarjetas hero, el artículo principal con sidebar, y el grid de posts

## Estructura del proyecto

```
tarea1-clon-web/
├── index.html          # Página principal
├── index.css           # Hoja de estilos
├── img/
│   ├── sitios-turisticos.webp
│   ├── ejercicio.jpg
│   ├── gaming.jpg
│   ├── lago-canada.avif
│   ├── playa-amigos.jpg
│   ├── maravillas-guatemala.jpg
│   ├── bosque-bambu.webp
│   ├── entrenamiento.jpg
│   ├── escocia.avif
│   ├── islandia.jpg
│   ├── original.png    # Screenshot del sitio original
│   └── resultado.png   # Screenshot del clon
└── README.md
```
