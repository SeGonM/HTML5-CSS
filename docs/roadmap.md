# Roadmap de HTML5 y CSS - Aprendizaje desde Cero - PariaDevs

> **Nota:** Este roadmap está optimizado para desarrolladores que aprenden en 2026. Enfatiza prácticas modernas y omite patrones desactualizados.

---

## 📍 Índice de Navegación

### Fundamentos
1. [01. Fundamentos de HTML](#01-fundamentos-de-html)
2. [02. CSS y Modelo de Caja](#02-css-y-modelo-de-caja)
3. [03. Layout y Posicionamiento](#03-layout-y-posicionamiento)
4. [04. Tipografía y Composición Visual](#04-tipografía-y-composición-visual)
5. [05. Responsive Design](#05-responsive-design)

### Layouts Modernos
6. [06. Flexbox](#06-flexbox)
7. [07. CSS Grid](#07-css-grid)

### Técnicas Avanzadas
8. [08. CSS Moderno y Arquitectura](#08-css-moderno-y-arquitectura)
9. [09. Componentes y Design Systems](#09-componentes-y-design-systems)
10. [10. Interactividad y Animaciones](#10-interactividad-y-animaciones)
11. [11. Accesibilidad y Calidad Web](#11-accesibilidad-y-calidad-web)
12. [12. Layouts y Técnicas Avanzadas](#12-layouts-y-técnicas-avanzadas)

### Profesionalización
13. [13. Rendimiento, Debugging y Compatibilidad](#13-rendimiento-debugging-y-compatibilidad)
14. [14. Landing Page de la Comunidad](#14-landing-page-de-la-comunidad)

### Recursos
- [🎯 Estructura de Aprendizaje](#-estructura-de-aprendizaje)
- [📌 Notas Importantes](#notas-importantes)
- [⚠️ Contenido Desactualizados (No Incluidos)](#contenido-desactualizados-no-incluidos)

---

## 01. Fundamentos de HTML

### Sesión 1.1: Estructura de un documento HTML
- Concepto de etiquetas y elementos
- Estructura básica: `<!DOCTYPE>`, `<html>`, `<head>`, `<body>`
- Propósito de meta tags y atributos
- HTML5 y su importancia

### Sesión 1.2: HTML Semántico
- Etiquetas semánticas vs genéricas
- Elementos estructurales: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Semántica y SEO
- Semántica y accesibilidad

### Sesión 1.3: Texto, enlaces y navegación
- Párrafos, saltos de línea, espaciado
- Listas: ordenadas, desordenadas, definiciones
- Enlaces y comportamiento
- Navegación semántica

### Sesión 1.4: Imágenes y multimedia
- Elemento `<img>` y atributos
- Formatos modernos (webp, avif)
- Atributo `alt` y accesibilidad
- Audio y video semántico

### Sesión 1.5: Formularios
- Estructura y elementos básicos
- Tipos de inputs modernos
- Labels y asociación
- Validación HTML5 conceptual

### Sesión 1.6: HTML moderno y atributos
- Atributos globales: `id`, `class`, `data-*`
- Atributos de accesibilidad: `aria-*`
- Custom attributes
- Evolución de HTML5

---

## 02. CSS y Modelo de Caja

### Sesión 2.1: Selectores y Cascada
- Selectores básicos: elemento, clase, id
- Combinadores: descendiente, hijo, hermano adyacente
- Cascada y peso de selectores
- Herencia en CSS

### Sesión 2.2: Especificidad
- Cálculo de especificidad
- Selectores modernos: `:is()`, `:where()`, `:not()`
- Impacto en el orden de aplicación
- Resolviendo conflictos

### Sesión 2.3: Modelo de Caja
- Content, padding, border, margin
- Box-sizing: content-box vs border-box
- Margen colapsable
- Cálculo de dimensiones

### Sesión 2.4: Unidades CSS Modernas
- Unidades absolutas: píxeles
- Unidades relativas: em, rem, %
- Viewport units: vw, vh, dvw, dvh
- Viewport relativo vs absoluto

### Sesión 2.5: Colores y Fondos
- Sistemas de color: hex, rgb, hsl
- Formatos modernos: oklch, color()
- Propiedades de fondo
- Gradientes lineales y radiales

### Sesión 2.6: Funciones CSS
- calc() para dimensiones dinámicas
- min(), max(), clamp()
- var()
- Funciones avanzadas

---

## 03. Layout y Posicionamiento

### Sesión 3.1: Flujo Normal
- Block vs inline vs inline-block
- Comportamiento por defecto
- Collapsing margins
- Document flow

### Sesión 3.2: Display
- Display: block, inline, inline-block
- Display: none vs visibility
- Impacto en el flujo
- Combinaciones modernas

### Sesión 3.3: Position
- Static (por defecto)
- Relative (relativo al flujo)
- Absolute (removido del flujo)
- Fixed vs sticky
- Stacking context

### Sesión 3.4: Contexto de Apilamiento
- z-index y niveles
- Stacking order
- Creando nuevos contextos
- Debugging visual

### Sesión 3.5: Overflow y Contención
- Overflow: visible, hidden, scroll, auto
- Text-overflow
- Contención de contenido
- Scrolling behavior

### Sesión 3.6: Composición y Espaciado
- Espaciado vertical rítmico
- Proporción y alineación
- Espacios en blanco (whitespace)
- Alineación visual

---

## 04. Tipografía y Composición Visual

### Sesión 4.1: Tipografía Fundamental
- Familias de fuentes: serif, sans-serif, monospace
- Font-weight, font-style, font-size
- Line-height para legibilidad
- Espaciado de texto: letter-spacing, word-spacing

### Sesión 4.2: Fuentes Web
- Importación de fuentes
- Fallback fonts y font stacks
- Performance de fuentes
- Formatos modernos

### Sesión 4.3: Jerarquía y Legibilidad
- Contraste de tamaños
- Pesos y énfasis
- Longitud de línea óptima
- Tamaño mínimo accesible

### Sesión 4.4: Alineación y Transformación
- Text-align
- Text-decoration, text-transform
- Uppercase, lowercase, capitalize
- Dirección de texto

### Sesión 4.5: Composición Visual
- Escala tipográfica
- Ritmo y armonía
- Contraste visual
- Espacios en blanco efectivos

---

## 05. Responsive Design

### Sesión 5.1: Principios Mobile-First
- Enfoque mobile-first
- Progresión a pantallas más grandes
- Breakpoints y puntos de quiebre
- Estrategia de diseño

### Sesión 5.2: Media Queries
- Sintaxis de media queries
- Features: width, height, orientation
- Combinaciones lógicas
- Testing en diferentes resoluciones

### Sesión 5.3: Viewport y User Preferences
- Meta viewport
- Device pixel ratio
- Prefers-reduced-motion
- Prefers-color-scheme

### Sesión 5.4: Imágenes y Multimedia Responsivos
- Imágenes escalables
- Formatos responsivos
- Density descriptors
- Optimización moderna

### Sesión 5.5: Fluid Design
- Unidades relativas
- Escalado fluido
- Transiciones suaves entre breakpoints
- Contenido flexible

---

## 06. Flexbox

### Sesión 6.1: Conceptos Fundamentales
- Contenedor flex
- Ejes: main axis, cross axis
- Flex direction: row, column
- Wrap y comportamiento

### Sesión 6.2: Distribución de Espacio
- justify-content (eje principal)
- align-items (eje transversal)
- align-self (elemento individual)
- align-content (múltiples líneas)

### Sesión 6.3: Tamaño Flexible
- flex-grow: crecimiento
- flex-shrink: encogimiento
- flex-basis: tamaño base
- Shorthand flex

### Sesión 6.4: Orden y Visualización
- Order para reordenar
- Cambio visual vs cambio del DOM
- Implicaciones de accesibilidad
- Flex-direction

### Sesión 6.5: Casos de Uso Prácticos
- Navegación horizontal
- Centrado perfecto
- Barras laterales
- Distribuciones adaptables

---

## 07. CSS Grid

### Sesión 7.1: Conceptos de Grid
- Grid container e items
- Líneas, tracks, células
- Expl de grid: filas y columnas
- Definición básica de grid

### Sesión 7.2: Definición de Pistas
- grid-template-columns, rows
- Unidad `fr` (fracciones)
- repeat() y patrones
- auto, minmax(), fit-content()

### Sesión 7.3: Colocación de Items
- grid-column, grid-row
- Named areas
- grid-area
- Alineación en celda

### Sesión 7.4: Alineación en Grid
- justify-items, justify-self
- align-items, align-self
- justify-content, align-content
- Distribución de espacio

### Sesión 7.5: Subgrid y Avanzado
- Subgrid para herencia de pistas
- Auto-placement
- Nombres de líneas
- Grillas complejas y nested

---

## 08. CSS Moderno y Arquitectura

### Sesión 8.1: Custom Properties (Variables CSS)
- Definición de variables
- Scope y herencia
- Valores por defecto (fallback)
- Reutilización y mantenibilidad

### Sesión 8.2: Selectores Modernos
- `:is()` para simplificar
- `:where()` sin especificidad
- `:not()` con múltiples selectores
- `:has()` para selectores ancestro

### Sesión 8.3: CSS Nesting
- Nesting nativo en CSS
- Sintaxis &
- Readabilidad del código
- Organización modular

### Sesión 8.4: @layer y Especificidad
- Capas de cascada
- Reorder de capas
- Especificidad dentro de capas
- Arquitectura con @layer

### Sesión 8.5: Propiedades Lógicas
- Logical properties: inline, block
- margin-inline, padding-block
- Internacionalización
- Dirección de escritura

### Sesión 8.6: Container Queries
- Container queries por tamaño
- Container units (cqw, cqh)
- Componentes verdaderamente independientes
- Query de estilo

---

## 09. Componentes y Design Systems

### Sesión 9.1: Concepto de Design System
- Qué es un Design System
- Componentes reutilizables
- Consistencia y escalabilidad
- Documentación

### Sesión 9.2: Componentes Base
- Botones y variantes
- Inputs y campos
- Cards y contenedores
- Badges y etiquetas

### Sesión 9.3: Navegación y Menús
- Menú principal
- Submenús conceptualmente
- Breadcrumbs
- Paginación

### Sesión 9.4: Componentes de Tipografía
- Encabezados
- Párrafos y bloques de texto
- Citas y énfasis
- Listas estilizadas

### Sesión 9.5: Tokens y Escalas
- Escala de espaciado
- Paleta de colores
- Tokens de diseño
- Sistema de documentación

---

## 10. Interactividad y Animaciones

### Sesión 10.1: Estados Interactivos
- Pseudo-clases: :hover, :focus, :active
- :visited para enlaces
- :disabled, :checked
- Indicadores visuales claros

### Sesión 10.2: Transiciones CSS
- Propiedades transicionables
- Duration y delay
- Timing functions (ease, linear, cubic-bezier)
- Performance

### Sesión 10.3: Transformaciones 2D
- rotate, scale, translate, skew
- Transform-origin
- Composición de transformaciones
- Casos de uso

### Sesión 10.4: Keyframe Animations
- Definición de keyframes
- Animation properties
- Iteración y dirección
- Timing y sincronización

### Sesión 10.5: Interactividad Pura CSS
- Checkboxes y toggles
- Accordions expandibles
- Validación visual
- UX cuando no es necesario JS

---

## 11. Accesibilidad y Calidad Web

### Sesión 11.1: Principios WCAG
- Perceptible, operable, comprensible, robusto
- Niveles: A, AA, AAA
- Pautas generales
- Responsabilidad del desarrollador

### Sesión 11.2: Contraste y Percepcióibilidad
- Ratio de contraste mínimo
- Paletas accesibles
- No confiar solo en color
- Daltonismo y consideraciones visuales

### Sesión 11.3: Navegación y Estructura
- Orden lógico
- Focus visible y keyboard navigation
- Skip links
- Estructura semántica

### Sesión 11.4: Textos Alternativos y Etiquetas
- Alt text descriptivo
- Labels en formularios
- ARIA labels cuando sea necesario
- Accesibilidad de imágenes

### Sesión 11.5: Pruebas y Validación
- Herramientas de validación
- Pruebas manuales
- Testing con usuarios
- Auditorías de accesibilidad

---

## 12. Layouts y Técnicas Avanzadas

### Sesión 12.1: Multi-Columnas
- column-count, column-width
- column-gap, column-rule
- Distribución de contenido
- Balance de columnas

### Sesión 12.2: Posicionamiento Sticky
- Sticky vs fixed
- Casos de uso
- Contexto de stacking
- Comportamiento en scroll

### Sesión 12.3: Formas y Clipping
- clip-path para figuras
- Shape-outside
- Máscaras visuales
- Animaciones geométricas

### Sesión 12.4: Aspect Ratio y Object-Fit
- Aspect-ratio para proporciones
- object-fit: cover, contain, fill
- object-position
- Imágenes responsivas avanzadas

### Sesión 12.5: Blend Modes y Efectos
- mix-blend-mode
- background-blend-mode
- Saturación y filtros
- Capas visuales complejas

### Sesión 12.6: Anchor Positioning
- Anchor positioning
- Posicionamiento anclado
- Tooltip y popovers
- Layouts dinámicos

---

## 13. Rendimiento, Debugging y Compatibilidad

### Sesión 13.1: Rendimiento CSS
- Critical rendering path
- Reflow y repaint
- Optimización de selectores
- Minimización y compresión

### Sesión 13.2: DevTools y Debugging
- Inspector de elementos
- Estilos computados
- Cascada visual
- Resolución de conflictos

### Sesión 13.3: Compatibilidad Moderna
- Soporte de navegadores
- Graceful degradation
- Feature queries (@supports)
- Testing multiplataforma

### Sesión 13.4: Validación y Calidad
- Validadores W3C
- Linters y herramientas
- Estándares de código
- Buenas prácticas

### Sesión 13.5: Optimización Avanzada
- Critical CSS
- Lazy loading de recursos
- Bundling y assets
- Métricas de performance

---

## 14. Landing Page de la Comunidad

### Sesión 14.1: Planeación y Estrategia
- Estructura y secciones
- Objetivos de conversión
- User flow
- Wireframing conceptual

### Sesión 14.2: Hero Section
- Concepto y propósito
- Imagen y contenido
- Call-to-action
- Jerarquía visual

### Sesión 14.3: Secciones de Contenido
- Presentación de la comunidad
- Beneficios y features
- Testimonios
- Galerías y portfolio

### Sesión 14.4: Formularios e Interacción
- Newsletter signup
- Formulario de contacto
- Validación visual
- Feedback de usuario

### Sesión 14.5: Optimización Final
- Performance
- SEO básico
- Responsividad completa
- Testing y compatibility

---

## 🎯 Estructura de Aprendizaje

```
Fundamentos (01-05)
    ↓
Layouts Modernos (06-07)
    ↓
Técnicas Avanzadas (08-12)
    ↓
Calidad y Rendimiento (13)
    ↓
Proyecto Integrador (14)
```

### Notas Importantes

- **Cada sesión es conceptual**, sin código
- **Progresión ordenada**: no saltes módulos
- **Módulos 01-05** establecen las bases
- **Módulos 06-07** son pivotales (Flexbox y Grid)
- **Módulos 08-12** profundizan en técnicas modernas
- **Módulo 13** asegura calidad profesional
- **Módulo 14** integra todo lo aprendido

### Contenido Desactualizados (No Incluidos)

- Float y clearfix (legacy patterns)
- Prefijos de navegador (-webkit-, -moz-)
- Polyfills de navegador
- CSS preprocesadores como obligatorio
- Desktop-first como enfoque primario
- Unidades pt, cm (fuera de print)
- CSS-in-JS, bundling, tree-shaking (fuera de alcance)
