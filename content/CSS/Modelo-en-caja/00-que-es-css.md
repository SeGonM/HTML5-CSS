# 00. ¿Qué es CSS?

CSS (*Cascading Style Sheets*, "Hojas de estilo en cascada") es el lenguaje que define la apariencia visual de un documento HTML. Mientras HTML organiza la estructura y el contenido, CSS decide cómo se ve: colores, tipografías, espacios, tamaños, alineación, fondos, bordes, animaciones y comportamiento responsive.

Si HTML es el "esqueleto" y el contenido, CSS es la "ropa", la "distribución espacial" y la "estética". Sin CSS, la mayoría de las páginas web se verían con el aspecto básico del navegador: texto negro sobre fondo blanco, enlaces azules y una estructura muy poco elegante.

## La idea central: separar contenido de presentación

Uno de los principios más importantes del desarrollo web moderno es la separación de responsabilidades:

- HTML describe la estructura y el significado.
- CSS describe la presentación visual.
- JavaScript añade interactividad y lógica.

Esto tiene varias ventajas:

- reutilización: puedes usar el mismo HTML con distintos estilos;
- mantenimiento: cambiar el diseño no requiere reescribir el contenido;
- claridad: el código es más legible y más fácil de mantener;
- accesibilidad: puedes adaptar la experiencia visual sin cambiar la semántica;
- escalabilidad: un proyecto grande se vuelve más ordenado.

Por ejemplo, el mismo elemento puede tener una etiqueta semántica como `article`, y CSS puede decidir que se vea como una tarjeta con sombra, ancho limitado y fondo claro. La intención semántica del contenido sigue siendo la misma, pero la apariencia puede cambiar sin cambiar el significado.

## Un ejemplo muy simple

```html
<h1>Título principal</h1>
<p>Este texto tiene una presentación muy básica por defecto.</p>
```

Sin CSS, esto se ve como texto normal del navegador. Con CSS:

```css
h1 {
  color: #1f2937;
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
}

p {
  color: #4b5563;
  line-height: 1.6;
  max-width: 60ch;
}
```

Esto cambia completamente la lectura visual, sin tocar el contenido HTML original.

## Cómo llega CSS al navegador

Cuando el navegador carga una página, no simplemente “lee HTML y ya está”. Tiene que hacer varias etapas:

1. Analiza el HTML y crea el DOM (*Document Object Model*), una estructura de árbol con todos los elementos de la página.
2. Descubre y carga las hojas de estilo CSS.
3. Genera el CSSOM (*CSS Object Model*), una representación de todas las reglas CSS.
4. Combina ambos: toma el DOM y aplica las reglas CSS relevantes a cada elemento.
5. Calcula el diseño final: tamaños, posiciones, márgenes, paddings, flujo de contenido.
6. Pinta la página en pantalla.

Todo esto sucede de manera muy rápida, y es por eso que CSS parece una herramienta “inmediata” para diseñar páginas.

## Una regla de CSS: selector + declaraciones

La unidad básica de CSS es la regla. Tiene esta forma:

```css
selector {
  propiedad: valor;
  propiedad: valor;
}
```

Por ejemplo:

```css
h1 {
  color: oklch(45% 0.16 260);
  margin-block-end: 1rem;
  font-size: clamp(2rem, 4vw, 3rem);
}
```

Aquí:

- `h1` es el selector: indica qué elementos deben recibir esos estilos.
- `color`, `margin-block-end` y `font-size` son propiedades.
- `oklch(...)`, `1rem` y `clamp(...)` son sus valores.

El navegador interpreta que: “A todos los elementos `h1` aplícale estos estilos”.

## ¿Qué hace realmente CSS?

CSS no solo cambia colores. También controla:

- la tipografía: familia, tamaño, peso, espaciado, interlineado;
- la composición: ancho, alto, margen, padding, border;
- la posición: estáticos, relativos, absolutos, flexibles, en grid;
- la visualización: block, inline, none, flex, grid;
- el fondo: colores, degradados, imágenes, patrones;
- la respuesta móvil: cómo cambia el diseño según el ancho de pantalla;
- la accesibilidad: contrastes, foco, legibilidad, tamaños ajustables;
- animaciones y transiciones: movimiento suave entre estados.

Un diseño útil no se trata solo de “poner bonito”. Se trata de crear una experiencia legible, usable, consistente y funcional.

## Formas de incluir CSS

Hay varias formas de añadir estilos a una página:

### 1. Hoja de estilo externa

Es la forma más habitual y recomendable para proyectos reales:

```html
<link rel="stylesheet" href="styles.css">
```

Ventajas:

- el código se mantiene separado del HTML;
- se reutiliza entre varias páginas;
- se cachea mejor;
- es más fácil de mantener y escalar.

### 2. Estilos dentro del documento

Se colocan dentro de una etiqueta `<style>` en la cabecera del documento:

```html
<style>
  body {
    font-family: sans-serif;
  }
</style>
```

Esto es útil para páginas pequeñas o ejemplos aislados, pero es menos reusable.

### 3. Estilos en línea

Se aplican directamente en un elemento con el atributo `style`:

```html
<p style="color: red; font-weight: bold;">Texto destacado</p>
```

No es la mejor práctica para proyectos grandes, porque mezcla contenido y estilo. Es útil para pruebas rápidas o casos muy puntuales.

## La cascada: ¿por qué CSS se llama “en cascada”?

El nombre CSS viene de “Cascading Style Sheets”, y la cascada es uno de los conceptos clave. Cuando varias reglas afectan al mismo elemento, el navegador debe decidir cuál tiene prioridad.

Por ejemplo:

```css
p {
  color: black;
}

.destacado {
  color: red;
}
```

```html
<p class="destacado">Texto</p>
```

En este caso, la clase `.destacado` probablemente gana porque es más específica que el selector general `p`. La idea no es que CSS sea caótico, sino que está diseñado para combinar reglas de forma ordenada y predecible.

En las siguientes sesiones aprenderás a controlar:

- cuál regla tiene prioridad;
- cómo seleccionar elementos con precisión;
- cómo evitar conflictos entre estilos;
- cómo calcular el tamaño real de cada elemento.

## Herencia: algunas propiedades se transmiten

Algunas propiedades CSS se heredan de un elemento padre a sus hijos. Por ejemplo, `color`, `font-family`, `line-height` y `font-size` suelen heredarse.

```css
body {
  font-family: system-ui, sans-serif;
  color: #222;
}
```

Entonces, si un párrafo no define `color`, heredará el del `body`.

Esto hace que el estilo base sea más consistente y reduce la repetición. Pero no todas las propiedades son heredables; por ejemplo `margin`, `padding`, `border` o `width` normalmente no se heredan.

## El principio de especificidad

Cuando dos reglas apuntan al mismo elemento, el navegador compara qué tan específicos son los selectores. Un selector más específico suele tener más prioridad.

Por ejemplo:

```css
p { color: blue; }
.card p { color: green; }
```

Si hay un párrafo dentro de un elemento con clase `.card`, probablemente se aplicará el verde porque el selector `.card p` es más específico que `p`.

La especificidad es un tema fundamental; entenderla ayuda a evitar depuraciones frustrantes. Se tratará con detalle en la siguiente sesión.

## El flujo visual: de la estructura al diseño final

CSS se aplica a la estructura HTML y produce un resultado visual. Pensar en esto ayuda a visualizar cómo funciona:

```html
<main>
  <section>
    <h1>Mi artículo</h1>
    <p>Contenido del texto.</p>
  </section>
</main>
```

Con CSS:

```css
main {
  max-width: 60rem;
  margin: 0 auto;
  padding: 2rem;
}

section {
  background: #f9fafb;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
}

h1 {
  font-size: 2rem;
}
```

El navegador toma esos bloques, calcula su tamaño, los coloca dentro del flujo de la página y los dibuja en pantalla.

## CSS como herramienta de diseño, no solo de decoración

Muchas personas piensan que CSS es solo “poner color y fuente”. Pero en realidad es una herramienta central para el diseño web:

- establece jerarquías visuales;
- guía la atención del usuario;
- mejora la legibilidad;
- organiza contenidos complejos;
- adapta el diseño a móviles, tablets y escritorio;
- hace que la interfaz sea coherente.

No es un detalle cosmético; es una parte esencial del producto digital.

## Buenas prácticas iniciales

Estas reglas te ayudarán desde el principio:

- usa clases descriptivas que expresen intención, no apariencia temporal;
- mantén HTML semántico y CSS para presentación;
- prioriza la legibilidad sobre la complejidad innecesaria;
- evita usar `!important` salvo en casos muy extremos;
- usa propiedades lógicas como `margin-inline` cuando el diseño pueda cambiar de dirección;
- prueba el diseño en pantallas pequeñas y grandes;
- revisa el contraste y la accesibilidad visual.

Un buen CSS no es el que tiene más líneas, sino el que comunica mejor la intención del diseño.

## En resumen

CSS es el lenguaje que convierte un documento HTML en una interfaz visual. Su objetivo no es “decorar” al azar, sino definir cómo se presenta, se organiza y se comporta la información. Para dominarlo, necesitas entender tres ideas clave:

1. cómo se seleccionan los elementos;
2. cómo funciona la cascada y la especificidad;
3. cómo el navegador calcula la caja, el espacio y la posición de cada elemento.

Esas tres ideas serán la base de todo lo que verás a continuación.

[Siguiente sesión: Selectores y cascada](2.1-selectores-y-cascada.md)
