# formacion-web-dev-booststrap-grid-system

Material básico de formación sobre el sistema Grid de Bootstrap y utilidades.

Contenido incluido:

- `index.html`: Página con demos en vivo y la galería original. La página muestra ejemplos simples de Grid y utilidades.
- `css/style.css`: Estilos personalizados mínimos para las demos.

Breve guía (integrada):

## Estructura del Grid

- Contenedor: `.container` o `.container-fluid`
- Fila: `.row` (agrupa columnas)
- Columnas: `.col`, `.col-{n}`, y variantes por breakpoint `.col-md-6`, `.col-sm-4`, etc.

Bootstrap divide el ancho en 12 columnas. Combina clases para diseños responsivos.

## Breakpoints (v5)

- xs: <576px (sin sufijo)
- sm: ≥576px
- md: ≥768px
- lg: ≥992px
- xl: ≥1200px
- xxl: ≥1400px

## Ejemplos rápidos (ver `index.html`)

- Columnas de igual ancho: `.col` dentro de `.row`.
- Columnas fijas: `.col-6` para 50%.
- Responsive: `col-12 col-md-6` (apila en móvil, dos columnas en md+).

## Utilidades comunes

- Espaciado: `m-`, `p-` (ej. `p-3`, `mb-2`).
- Display: `.d-flex`, `.d-none`.
- Alineación: `.justify-content-*`, `.align-items-*`.
- Texto y color: `.text-center`, `.text-primary`, `.bg-light`.

## Recursos

- Documentación oficial: https://getbootstrap.com/docs/5.3/layout/grid/

Nota: El archivo `formacion.md` fue integrado en este README y se eliminará del repositorio para mantener una sola fuente de referencia básica.