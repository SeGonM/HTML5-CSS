# 🚀 Ruta de Aprendizaje Web: HTML5 & CSS3

¡Bienvenido/a a este espacio! 

Este repositorio es mi ruta de aprendizaje personal. No pretendo ser un experto, pero estoy convencido de que todos podemos aprender y crecer aplicando esta ruta juntos. 

En Hispanoamérica no tenemos tan arraigada la cultura de crear repositorios colaborativos donde la comunidad participe de forma activa, transparente y asertiva (un formato de estudio público muy com[...] 

Si estás aprendiendo a programar, te cuesta estudiar en soledad o te abruma la presión de los entornos tradicionales, la mesa está servida. Todos son bienvenidos a participar.

---

## 🗺️ Estructura del Contenido

El aprendizaje se divide por semanas. En cada carpeta encontrarás la documentación teórica explicada de forma sencilla y el ejercicio práctico correspondiente:

| Semana | Tema Principal | Proyecto / Reto | Estado |
| :--- | :--- | :--- | :---: |
| **Semana 1** | Estructura base y HTML Semántico | Documento personal / CV Web | 🟢 Disponible |
| **Semana 2** | CSS Base, Selectores y Modelo de Caja | Tarjeta de Perfil Interactiva | ⏳ En proceso |
| **Semana 3** | Flexbox a fondo y Layouts | Menú de navegación y Landing Page | 🔒 Próximamente |
| **Semana 4** | CSS Grid y Diseño Responsive | Galería / Dashboard Adaptativo | 🔒 Próximamente |

---

## 🧭 Roadmap de Maquetación (Tabla de Contenidos)

A continuación encontrarás una tabla de contenidos exhaustiva para aprender maquetación con HTML y CSS, ordenada desde los temas más básicos ("los más simples y tontos") hasta los más complejos y avanzados. Cada bloque incluye temas concretos y retos/proyectos sugeridos.

1) Fundamentos absolutos (lo más simple)
   - Estructura HTML básica: `doctype`, `html`, `head`, `body`
   - Etiquetas semánticas básicas: `header`, `main`, `footer`, `section`, `article`, `nav`
   - Texto y contenido: `h1-h6`, `p`, `span`, `strong`, `em`, listas (`ul`, `ol`, `li`)
   - Imágenes y medios: `img`, atributos `alt`, `width/height`
   - Enlaces: `a` y navegación básica
   - Mini reto: Página de perfil simple (CV estático)

2) CSS básico y modelo de caja
   - Selectores simples, herencia y cascada
   - Especificidad y !important
   - Box model: `content`, `padding`, `border`, `margin`
   - Display básico: `block`, `inline`, `inline-block`
   - Propiedades comunes: `color`, `background`, `font-size`, `line-height`
   - Mini reto: Tarjeta de presentación (bloque con imagen y texto)

3) Layouts con posicionamiento tradicional
   - Position: `static`, `relative`, `absolute`, `fixed`, `sticky`
   - Floats y clearfix (histórico, entender por compatibilidad)
   - Z-index y apilamiento
   - Mini reto: Cabecera fija y botón flotante

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
   - BEM, SMACSS, Atomic Design
   - Componentización con clases reutilizables
   - Variables CSS (Custom Properties) y theming
   - Mini reto: Biblioteca pequeña de componentes (botones, inputs, cards)

9) Avanzando en responsive y patrones adaptativos
   - Breakpoints razonables y estrategia de puntos de ruptura
   - Contenedores fluidos y layout adaptativo
   - Container queries (cuando estén disponibles)
   - Técnicas de imágenes y assets para rendimiento
   - Mini reto: Layout que cambia radicalmente según ancho

10) Interactividad con CSS
    - Transitions y transforms
    - Animaciones con `@keyframes`
    - Preferencias de usuario: `prefers-reduced-motion`
    - Hover, focus, active y estados accesibles
    - Mini reto: Menú desplegable con animación suave

11) Accesibilidad y buenas prácticas (A11y)
    - Roles ARIA básicos y atributos útiles
    - Estados focus visibles, contraste de color
    - Skip links y navegación por teclado
    - Validación semántica y SEO básico
    - Mini reto: Revisar y mejorar la accesibilidad de una página existente

12) Técnicas y trucos avanzados de maquetación
    - `clip-path`, `mask`, `object-fit`, `aspect-ratio`
    - CSS Shapes y wrapping alrededor de imágenes
    - CSS blend modes y filtros
    - Mini reto: Cabecera con máscara y texto sobre imagen

13) Layouts complejos y patrones difíciles
    - Masonry (pure CSS vs JS), multi-column layout
    - Sticky footers complejos, layouts con sidebar flexible
    - Overlapping/stacked layouts y contenido dimensional
    - Mini reto: Dashboard complejo con múltiples zonas redimensionables

14) Rendimiento y producción
    - Critical CSS, carga diferida y async
    - Minimizar repaints/reflows y optimizar repaints
    - Gestión de fuentes y carga de assets
    - Mini reto: Optimizar una página con Lighthouse

15) Testing, debugging y compatibilidad
    - DevTools: layout, grid/flex inspectors, paint flashing
    - Polyfills y fallbacks para navegadores antiguos
    - Visual regression testing (Percy, Chromatic, etc.)
    - Mini reto: Crear pruebas visuales para un componente

16) Herramientas y preprocesadores
    - Preprocesadores: Sass (variables, mixins, nesting)
    - PostCSS, Autoprefixer, herramientas de build
    - Bundlers y live reload (Vite, webpack, parcel)
    - Mini reto: Migrar estilos a Sass y compilar

17) CSS moderno y futuro (avanzado/experto)
    - CSS Houdini y Paint API
    - CSS Container Queries y Layout API
    - Custom layout with CSS (experimental)
    - CSS-in-JS vs CSS tradicional vs Utility-First (Tailwind)
    - Mini reto: Prototipar una idea con Houdini (o investigar si no está disponible)

18) Design Systems, componentes accesibles y escalables
    - Tokens de diseño con variables CSS
    - Documentación y catálogo de componentes
    - Theming dinámico y dark mode
    - Mini reto: Crear un mini design system con tokens y componentes

19) Casos especiales y formatos difíciles
    - Emails HTML (limitaciones de maquetación en clientes)
    - Páginas imprimibles y CSS para print
    - Integración con SVG y animaciones avanzadas
    - Mini reto: Newsletter responsive compatible con clientes limitados

20) Proyectos finales sugeridos (integración de todo lo aprendido)
    - Portfolio completo con diseño responsive, accesible y optimizado
    - Dashboard interactivo con reordenamiento, filtros y layout complejo
    - E-commerce minimal: fichas de producto, grid adaptativo y checkout simple

---

## 🛠️ ¿Cómo participar o usar este repo?

Tienes total libertad para usar este material como mejor te convenga:

1. **A tu propio ritmo:** Lee los archivos Markdown de cada semana y resuelve los retos por tu cuenta.
2. **Practicando Git:** Haz un *Fork* de este repositorio, crea una rama con tu nombre y sube tu solución para recibir retroalimentación asertiva y sin ego.
3. **Aportando a la comunidad:** Si ves un error de ortografía, una explicación confusa o quieres añadir un mejor ejemplo en la teoría, ¡los *Pull Requests* son súper bienvenidos!

---

## 🤝 Comunidad y Acompañamiento

Para apoyarnos en el proceso, resolver dudas por chat de texto o simplemente reunirnos a programar en silencio:

* 💬 **Discord Comunitario:** [Unirse al servidor de Discord](https://discord.gg/TU_ENLACE_AQUI) *(Llamadas opcionales, espacio tranquilo y sin presiones).* 

---

## 📝 Licencia

Este proyecto es de código abierto bajo la licencia [MIT](LICENSE). Siéntete libre de usar la documentación y los ejercicios para tu propio estudio o portafolio personal.
