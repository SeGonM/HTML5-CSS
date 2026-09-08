# 00. ¿Qué es HTML?

HTML (*HyperText Markup Language*) es el lenguaje de marcado que describe la estructura y el significado del contenido de una página web. HTML no es un lenguaje de programación: organiza títulos, textos, enlaces, imágenes, formularios y otras piezas para que el navegador, los buscadores y las tecnologías de asistencia puedan interpretarlos.

## HTML, CSS y JavaScript

En una página web cada tecnología tiene una responsabilidad principal:

- **HTML:** estructura y significado.
- **CSS:** presentación visual y distribución.
- **JavaScript:** comportamiento e interacción.(No esta incluido en la documentación)

Por ejemplo, HTML indica que un texto es un botón mediante `<button>`, CSS define su apariencia y JavaScript puede reaccionar cuando la persona lo activa.

## Tu primer documento

```html
<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Mi primera página</title>
  </head>
  <body>
    <h1>Hola, web</h1>
    <p>Esta es mi primera página HTML.</p>
  </body>
</html>
```

Guarda el código como `index.html` y ábrelo en un navegador o la extensión live server. La extensión `.html` le indica al sistema y a las herramientas que se trata de un documento HTML.

## Etiquetas, elementos y atributos

Una etiqueta suele escribirse entre signos menor y mayor:

```html
<p>Un elemento de párrafo.</p>
```

En este ejemplo:

- `<p>` es la etiqueta de apertura.
- `Un elemento de párrafo.` es el contenido.
- `</p>` es la etiqueta de cierre.
- Todo el conjunto es un **elemento**.

Los atributos agregan información o configuración:

```html
<a href="https://developer.mozilla.org/es/" target="_blank" rel="noopener">
  Consultar MDN
</a>
```

`href`, `target` y `rel` son atributos del enlace. Usa nombres descriptivos y valores entre comillas.

## Ideas importantes

1. Escribe HTML con una jerarquía clara y una indentación consistente.
2. Usa la etiqueta que describe el contenido, no la que solo cambia su apariencia.
3. Mantén un idioma correcto en `<html lang="...">`.
4. Valida tu documento y prueba la navegación con teclado.
5. Usa CSS para estilos y HTML para significado.

