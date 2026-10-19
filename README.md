# Coopenae

Repositorio del sitio "Kit de Ventas Digital — COOPENAE".

## Publicar el sitio (GitHub Pages)

El sitio es una página estática de un solo archivo (`index.html`, con imágenes
embebidas en base64) y se publica automáticamente mediante el workflow
`.github/workflows/pages.yml` cada vez que se hace push a `main`.

Para habilitarlo (una única vez):

1. Ir a **Settings → Pages** en el repositorio de GitHub.
2. En **Build and deployment → Source**, seleccionar **GitHub Actions**.
3. Hacer push/merge a `main`; el workflow "Deploy static site to GitHub Pages"
   se ejecutará y publicará `index.html` en la URL de Pages del repositorio.
