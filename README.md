🍨 **Monte Bianco – Website Project**

Este repositorio contiene el desarrollo del sitio web Monte Bianco, una heladería artesanal reconocida por sus sabores tradicionales, productos de calidad y elaboración propia.
El proyecto incluye la estructura completa del sitio, diseño 100% responsive, y una arquitectura de estilos escalable implementada con Sass (SCSS), siguiendo buenas prácticas de organización y reutilización de código.


**Tecnologías utilizadas**
- HTML5
- CSS3
- Sass / SCSS
- Bootstrap 5
- Google Fonts
- Íconos SVG
- Diseño responsive mobile-first
- Figma
- Adobe Illustrator


**Diseño y mockups**

El diseño visual del sitio fue trabajado previamente en wireframes y mockups de alta fidelidad para mantener coherencia estética y funcional.
Enlace al mockup: https://drive.google.com/file/d/1cXkZC5-bYOKcfgc_xSEiDlZdnk-TU6BT/view?usp=sharing


**Estructura del proyecto**

/img                → Imágenes del sitio  

/css                → styles.css (archivo compilado)
                    → styles.css.map

/SCSS
  /utilities
                    → _variables.scss
                    → _mixins.scss
                    → _extends.scss

  /layout
                    → _navbar.scss
                    → _footer.scss

  /pages
                    → _index.scss
                    → _historia.scss
                    → _sabores.scss
                    → _contacto.scss

  styles.scss       → archivo principal SCSS

index.html          → Página principal

contacto.html       → Página de contacto

historia.html       → Página "Nuestra Historia"

sabores.html        → Página "Nuestros Sabores"


**Arquitectura SCSS**

El proyecto utiliza Sass (SCSS) con una estructura modular basada en partials, que permite mantener el código ordenado, reutilizable y escalable.

INCLUYE
Variables
- Colores
- Tipografías
- Breakpoints
- Sombras y opacidades

Mixins
- Layouts flex
- Botones
- Transiciones
- Media queries responsive

Extends
- Headers
- Cards
- Párrafos base

Partials organizados por responsabilidad
- Utilities
- Layout
- Pages


**Funcionalidades principales**
- Navbar responsiva con estilos propios.
- Hero con imagen + overlay para mejorar la legibilidad.
- Secciones informativas diseñadas con identidad visual consistente.
- Página de sabores con grillas adaptativas.
- Página de contacto con formulario y card interactiva de ubicación.
- Footer reutilizable y adaptativo en todas las páginas.
- Uso de Sass (variables, mixins y extends) para evitar repetición de código.
- Diseño 100% responsive, optimizado para mobile, tablet y desktop.


**Estado del proyecto**

✅ Estructura SCSS completa
✅ Variables, mixins y extends implementados
✅ Layout y pages separadas en partials
✅ Diseño responsive en todas las vistas