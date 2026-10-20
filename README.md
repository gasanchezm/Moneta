# MONETA — Personal Finance (PWA)

Archivos: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` y la carpeta `icons/`.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `moneta`).
2. Sube TODOS los archivos manteniendo la carpeta `icons/` (Add file → Upload files).
3. Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. En 1–2 minutos estará en `https://TU-USUARIO.github.io/moneta/`.

## Instalar
- iPhone (Safari): Compartir → "Añadir a pantalla de inicio".
- Android (Chrome): menú ⋮ → "Instalar aplicación".

## Actualizar
Cambia archivos y sube el número de `VERSION` en `sw.js` (`moneta-v2`, …) para que los dispositivos se actualicen.

## Importante
Los datos se guardan en el navegador (localStorage). La app instalada y la pestaña de Safari pueden tener almacenamiento distinto: exporta una copia JSON desde Ajustes antes de reinstalar o cambiar de dispositivo.
