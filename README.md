# Descendientes de Nahash

Biblioteca digital de análisis del Génesis: libros, artículos, mapas y recursos.

Sitio construido con [Jekyll](https://jekyllrb.com/) y publicado con GitHub Pages.

## Estructura

```
├── _config.yml          # configuración del sitio
├── _layouts/             # plantillas (home, default)
├── _includes/             # nav y footer reutilizables
├── assets/css/            # estilos
├── index.md               # página de inicio
├── libros.md               # libros completos
├── articulos.md             # artículos cortos
├── mapas.md                  # mapas
├── recursos.md                 # recursos de apoyo
└── libros/                      # (crear) PDFs de los libros
```

## Publicar

En **Settings → Pages**, elige la rama `main` como fuente. GitHub construye el sitio Jekyll automáticamente — no hace falta ningún paso manual.

Si el repositorio no se llama `usuario.github.io` (es decir, si la URL final va a tener una carpeta, ej. `usuario.github.io/nahash`), agrega esa carpeta como `baseurl` en `_config.yml`:

```yaml
baseurl: "/nahash"
```
