
# Contribuir

¡Gracias por echar una mano en el repo! La idea es aprender juntos y mantener todo fácil de revisar.

## Antes de empezar

- No hagas commits ni `push` directamente a `main`.
- Crea una rama para cada aporte.
- Cuando termines, abre una Pull Request hacia `main`.

## Soluciones de ejercicios

Actualiza tu rama local y crea una rama con tu nombre:

```bash
git switch main
git pull origin main
git switch -c feature/solucion-NAME
```

Guarda tu solución dentro de `exercises/case#/NAME`, donde `NAME` es tu usuario de GitHub.
Cada caso tiene su propia carpeta y dentro de ella va una carpeta por participante.

Ejemplo:

```text
exercises/
└── case1/
	├── docs-case.md
	└── SeGonM/
		├── index.html
		└── styles.css
```

Cuando termines:

```bash
git add exercises/case#/NAME
git commit -m "feat: add weekend exercises solution for NAME"
git push -u origin feature/solucion-NAME
```

Después, abre una Pull Request desde `feature/solucion/NAME` hacia `feature/exercises`.

## Cambios en la documentación

Para modificar el README, la documentación o cualquier contenido relacionado, usa la rama `feature/content`:

```bash
git switch main
git pull origin main
git switch feature/content
```

Al terminar:

```bash
git add .
git commit -m "docs: improve project documentation"
git push -u origin feature/content
```

Después, abre una Pull Request desde `feature/content` hacia `main`.

## Para tenerlo en cuenta

- No modifiques las soluciones de otras personas.
- Revisa tus cambios con `git status` y `git diff` antes de hacer commit.
- Mantén los nombres de ramas y carpetas como se indican arriba.
- Si tienes dudas, comenta en la Pull Request. Lo vemos entre todos.


