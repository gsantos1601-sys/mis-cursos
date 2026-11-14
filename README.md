# Repositorio de formación · Gerardo Narvaez De Los Santos

Página con mis cursos, diplomados y programas. Cada curso abre su certificado en PDF al hacer clic.

## Estructura

```
mis-cursos/
├── index.html
├── README.md
└── certificados/        # aquí van los PDF, con los nombres tal cual están en index.html
```

Los nombres de los PDF deben coincidir **exactamente** con los de `index.html`
(mayúsculas y minúsculas, espacios, tildes y paréntesis). GitHub distingue mayúsculas.

## Cómo publicarlo

1. En GitHub: **New repository** → nombre `mis-cursos` → público → **Create**.
2. Sube `index.html`, `README.md` y la carpeta `certificados/` con los PDF.
3. **Settings → Pages** → *Deploy from a branch* → rama `main`, carpeta `/ (root)` → **Save**.
4. En 1 o 2 minutos: `https://TU-USUARIO.github.io/mis-cursos/`

## Agregar un curso nuevo

En `index.html`, dentro de `var C=[ ... ]`, añade una línea. El último campo es el nombre
del PDF **sin** `.pdf`:

```js
["Nombre del curso","Institución","Mes Año",2026,"datos","Nombre exacto del PDF"],
```

Categorías: `datos`, `excel`, `sql`, `prog`, `idioma`.
