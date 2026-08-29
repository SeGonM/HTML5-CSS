# 🚀 Ruta de Aprendizaje Web: HTML5 & CSS3

¡Bienvenido/a a este espacio! 

Este repositorio es mi ruta de aprendizaje personal. No pretendo ser un experto, pero estoy convencido de que todos podemos aprender y crecer aplicando esta ruta juntos. 

En Hispanoamérica no tenemos tan arraigada la cultura de crear repositorios colaborativos donde la comunidad participe de forma activa, transparente y asertiva (un formato de estudio público muy com[...] 

Si estás aprendiendo a programar, te cuesta estudiar en soledad o te abruma la presión de los entornos tradicionales, la mesa está servida. Todos son bienvenidos a participar.

---

## 🧭 Roadmap de Maquetación (Tabla de Contenidos) — Solo HTML & CSS

A continuación encontrarás una tabla de contenidos exhaustiva para aprender maquetación con HTML y CSS exclusivamente. Todo lo propuesto puede resolverse sin JavaScript; los retos y técnicas están limitados a HTML y CSS puros.

1) Fundamentos absolutos (lo más simple)
   - Estructura HTML básica: `<!doctype html>`, `html`, `head`, `body`
   - Etiquetas semánticas básicas: `header`, `main`, `footer`, `section`, `article`, `nav`
   - Texto y contenido: `h1-h6`, `p`, `span`, `strong`, `em`, listas (`ul`, `ol`, `li`)
   - Imágenes y medios: `img`, atributos `alt`, `width/height`
   - Enlaces: `a` y navegación básica
   - Mini reto: Página de perfil simple (CV estático)

2) CSS básico y modelo de caja
   - Selectores simples, herencia y cascada
   - Especificidad y `!important`
   - Box model: `content`, `padding`, `border`, `margin`
   - Display básico: `block`, `inline`, `inline-block`
   - Propiedades comunes: `color`, `background`, `font-size`, `line-height`
   - Mini reto: Tarjeta de presentación (bloque con imagen y texto)

3) Layouts con posicionamiento tradicional
   - `position`: `static`, `relative`, `absolute`, `fixed`, `sticky`
   - Floats y clearfix (histórico, entender por compatibilidad)
   - `z-index` y apilamiento
   - Mini reto: Cabecera fija y botón flotante (sin JS)

4) Tipografía y UI básica
   - Fuentes web (Google Fonts), `font-display`, rendimiento
   - Tipografía responsiva: unidades relativas (`em`, `rem`, `%`) y `clamp()`
   - Espaciado y vertical rhythm
   - Mini reto: Página de artículo con tipografía cuidada

5) Diseño responsivo esencial
   - Mobile-first vs desktop-first
   - Media queries básicas
   - Unidades fluidas: `vw`, `vh`, `%`, `rem`
   - Imágenes responsivas: `srcset`, `sizes`, `picture`
   - Mini reto: Landing responsiva básica

6) Flexbox (intermedio)
   - Contenedor flex: `display: flex` y ejes principales
   - Propiedades: `flex-direction`, `justify-content`, `align-items`, `flex-wrap`
   - Items: `flex`, `order`, `align-self`
   - Patrones: centrar contenido, nav horizontal, cards responsivas
   - Mini reto: Grid de tarjetas con Flexbox

7) CSS Grid (intermedio-avanzado)
   - Conceptos: track, gutter, implicit vs explicit grid
   - Sintaxis: `grid-template-columns`, `grid-template-rows`, `gap`
   - Áreas de grid, líneas nombradas y `grid-auto-flow`
   - Subgrid (cuando esté disponible en el navegador) y casos de uso
   - Mini reto: Layout de magazine con Grid

8) Sistemas de diseño y metodología
   - BEM, SMACSS, Atomic Design (aplicados con HTML/CSS)
   - Componentización con clases reutilizables
   - Variables CSS (Custom Properties) y theming (sin JS)
   - Mini reto: Biblioteca pequeña de componentes (botones, inputs, cards)

9) Avanzando en responsive y patrones adaptativos
   - Breakpoints razonables y estrategia de puntos de ruptura
   - Contenedores fluidos y layout adaptativo
   - Container queries (cuando estén disponibles en el navegador)
   - Técnicas de imágenes y assets para rendimiento
   - Mini reto: Layout que cambia radicalmente según ancho

10) Interactividad con CSS (sin JavaScript)
    - Transitions y transforms
    - Animaciones con `@keyframes`
    - Estados con pseudo-clases: `:hover`, `:focus`, `:active`, `:checked` (checkbox/radio hack)
    - `prefers-reduced-motion` y accesibilidad en animaciones
    - Mini reto: Menú desplegable y tarjetas interactivas usando solo HTML/CSS

11) Accesibilidad y buenas prácticas (A11y)
    - Roles ARIA básicos y atributos útiles (sin dependencias JS)
    - Estados focus visibles, contraste de color
    - Skip links y navegación por teclado
    - Validación semántica y SEO básico
    - Mini reto: Revisar y mejorar la accesibilidad de una página existente

12) Técnicas y trucos avanzados de maquetación
    - `clip-path`, `mask`, `object-fit`, `aspect-ratio`
    - CSS Shapes y wrapping alrededor de imágenes
    - CSS blend modes y filtros
    - Mini reto: Cabecera con máscara y texto sobre imagen

13) Layouts complejos y patrones difíciles (CSS puro)
    - Masonry con soluciones puramente CSS (columnas múltiples, CSS Grid experimental)
    - Multi-column layout (`column-count`, `column-gap`)
    - Sticky footers complejos y sidebars flexibles (sin JS)
    - Overlapping/stacked layouts y contenido dimensional usando `position` y Grid
    - Mini reto: Dashboard complejo con múltiples zonas (sin JS)

14) Rendimiento y producción (en contexto HTML/CSS)
    - Critical CSS, carga diferida de assets (rel=preload, rel=preconnect)
    - Minimizar repaints/reflows y optimizar estilos
    - Gestión de fuentes y carga de assets eficientes
    - Mini reto: Optimizar una página con Lighthouse (centrado en CSS/HTML)

15) Testing, debugging y compatibilidad
    - DevTools: inspección de layout, inspector de Grid/Flex, paint flashing
    - Fallbacks y degradación elegante para navegadores antiguos (polyfills no-code cuando sean solo CSS)
    - Pruebas visuales básicas (capturas/compare) enfocadas en HTML/CSS
    - Mini reto: Validar compatibilidad en distintos navegadores y anchos

16) Herramientas y preprocesadores (centrado en estilos)
    - Preprocesadores: Sass (variables, mixins, nesting) — genera CSS final
    - PostCSS, Autoprefixer y herramientas de build que producen CSS
    - Bundlers y live reload (solo para servir archivos; no incluir lógica JS)
    - Mini reto: Migrar estilos a Sass y compilar a CSS puro

17) CSS moderno y futuro (avanzado/experto)
    - Container Queries y nuevas capacidades de layout solo con CSS
    - Houdini (conceptos; evitar dependencias JS — investigar limitaciones)
    - Custom layouts y APIs CSS que no requieran escribir JavaScript
    - Utility-first con CSS puro (crear utilidades propias)
    - Mini reto: Prototipar un layout avanzado usando solo CSS moderno

18) Design Systems, componentes accesibles y escalables
    - Tokens de diseño con variables CSS
    - Documentación y catálogo de componentes solo HTML/CSS
    - Theming dinámico usando `prefers-color-scheme` y variables CSS
    - Mini reto: Crear un mini design system con tokens y componentes reutilizables

19) Casos especiales y formatos difíciles
    - Emails HTML (limitaciones de maquetación en clientes; sin JS)
    - Páginas imprimibles y CSS para print (`@media print`)
    - Integración con SVG y animaciones SVG con CSS
    - Mini reto: Newsletter responsive compatible con clientes limitados

20) Proyectos finales sugeridos (sin JavaScript)
    - Portfolio completo con diseño responsive, accesible y optimizado (HTML/CSS)
    - Dashboard visual estático con layout complejo y responsive (sin comportamientos dinámicos con JS)
    - Tienda o catálogo estático: fichas de producto, grid adaptativo y páginas de producto simples

---

## 🛠️ ¿Cómo participar o usar este repo?

Tienes total libertad para usar este material como mejor te convenga:

1. **A tu propio ritmo:** Lee los archivos Markdown de cada semana y resuelve los retos por tu cuenta usando únicamente HTML y CSS.
2. **Practicando Git:** Haz un *Fork* de este repositorio, crea una rama con tu nombre y sube tu solución para recibir retroalimentación asertiva y sin ego.
3. **Aportando a la comunidad:** Si ves un error de ortografía, una explicación confusa o quieres añadir un mejor ejemplo en la teoría (siempre en HTML/CSS), ¡los *Pull Requests* son súper bienvenidos!

---

## 🤝 Comunidad y Acompañamiento

Para apoyarnos en el proceso, resolver dudas por chat de texto o simplemente reunirnos a programar en silencio:

* 💬 **Discord Comunitario:** [Unirse al servidor de Discord](https://discord.gg/TU_ENLACE_AQUI) *(Llamadas opcionales, espacio tranquilo y sin presiones).* 

---

## 📝 Licencia

Este proyecto es de código abierto bajo la licencia [MIT](LICENSE). Siéntete libre de usar la documentación y los ejercicios para tu propio estudio o portafolio personal.
