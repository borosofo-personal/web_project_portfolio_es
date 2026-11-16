# Portafolio personal

Proyecto del sprint 4 de TripleTen: sitio web de portafolio personal, creado a partir de un diseño responsivo en Figma.

**Sitio publicado:** https://borosofo-personal.github.io/web_project_portfolio_es/

## Descripción

El portafolio es mi tarjeta de presentación en la web. Tiene cuatro secciones:

- **Perfil:** nombre, rol, descripción profesional, foto y enlaces para descargar el CV, ir a GitHub y escribirme.
- **Habilidades y herramientas:** iconos de las tecnologías que uso.
- **Proyectos destacados:** tarjetas con imagen, tecnologías, descripción y enlaces a la demo y al repositorio.
- **Contacto:** correo electrónico y redes sociales.

El sitio se adapta a tres estados de diseño: escritorio (1440px), tableta (768px) y móvil (320px), y no se rompe en las resoluciones intermedias.

## Tecnologías y técnicas

- **HTML5 semántico:** `main`, `section`, `footer`, listas `ul`/`li` y una jerarquía de encabezados de `h1` a `h3`.
- **CSS3:**
  - Flexbox y CSS Grid para la maquetación.
  - Diseño responsivo con media queries en los puntos de ruptura de 1023px y 767px.
  - `max-width` para centrar el contenido, y `aspect-ratio: 16 / 9` con `object-fit: cover` para las imágenes de los proyectos.
  - Variables CSS (custom properties) para el color de acento verde neón `#00FF7B`.
  - Fondo con luces creadas con `radial-gradient`, posicionadas con `calc()` respecto al centro de la pantalla.
  - Velo oscuro sobre las imágenes de los proyectos con `position: absolute` y `linear-gradient`.
  - Subrayado con degradado en los enlaces del perfil, hecho con propiedades de `background`.
  - Estados `:hover` con transiciones de opacidad.
- **Metodología BEM** para nombrar las clases.
- **Fuentes locales** Open Sans y Archivo Black en formatos `.woff2` y `.woff`, con fuentes del sistema como alternativa.
- **Imágenes optimizadas:** fotos comprimidas en JPG e iconos en SVG exportados desde Figma.
- **Herramientas:** Figma, Git, GitHub Pages, Prettier y EditorConfig.

## Estructura

```
├── index.html
├── styles/      # normalize.css, fonts.css y style.css
├── fonts/       # Open Sans y Archivo Black
├── images/      # fotos e iconos
└── files/       # CV descargable
```
