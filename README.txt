
# calculadora-btc365 (deploy web)

Sitio estático listo para Netlify o GitHub Pages.

## Archivos
- `index.html` – la calculadora completa (jurada/no jurada, % extra de palabras).
- `manifest.json` – para añadir a pantalla de inicio en móviles.
- `sw.js` – service worker: permite usar la app offline tras la primera carga.

## Deploy en Netlify (recomendado, 1 minuto)
1. Ve a https://app.netlify.com/drop
2. Arrastra la carpeta o el ZIP de este proyecto.
3. Netlify te dará una URL tipo `https://*.netlify.app`. Luego en Site Settings → Domain, cambia el nombre a `calculadora-btc365` si está libre.

## Deploy en GitHub Pages
1. Crea un repo (por ejemplo `calculadora-btc365`), sube estos 3 archivos.
2. Settings → Pages → Branch: `main` / root → Save.
3. Accede en `https://TU_USUARIO.github.io/calculadora-btc365/`.

## Importar tus tarifas
- Pestaña **Editar tarifas** → pega tu JSON → **Importar**.
- Las tarifas se guardan en el navegador (localStorage, clave `translation_rates_v3`).

