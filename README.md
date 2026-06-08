# Dashboard físico — deploy estático

Esta carpeta queda lista para subir a **GitHub Pages** o **Cloudflare Pages**.

## Contenido
- `index.html` → dashboard principal
- `404.html` → copia de respaldo para hosting estático
- `.nojekyll` → evita transformaciones de GitHub Pages

## Opción 1 — GitHub Pages
1. Crear un repo nuevo en GitHub.
2. Subir el contenido de esta carpeta al root del repo.
3. Ir a **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Elegir branch `main` y carpeta `/ (root)`.
6. Esperar el link final.

## Opción 2 — Cloudflare Pages
1. Crear un proyecto nuevo en Cloudflare Pages.
2. Subir esta carpeta o conectar un repo con este contenido.
3. Build command: dejar vacío.
4. Output directory: `/` o root del upload.
5. Publicar.

## Nota
El archivo fuente original sigue en:
- `../dashboard-fisico.html`

Si editamos el dashboard fuente, conviene volver a copiarlo a `index.html` y `404.html`.
