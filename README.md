# La Casa de Jenni — web premium 3D (demo)

Pollo payés relleno y tartas caseras por encargo. Web de una sola página con la tarta en 3D,
la carta con precios y pedido por WhatsApp.

- `index.html` — la web
- `antes-despues.html` — comparación con la web estándar
- `aviso-legal.html`, `privacidad.html`, `cookies.html` — páginas legales (faltan los datos del titular)
- `motor-3d/` — motor 3D y pedido por WhatsApp · `libs/` — librerías y fuentes locales (sin CDN ni Google)
- `assets/` — fotos, logo y modelo 3D (`producto.glb`)

Es una DEMO: lleva `noindex` y `robots.txt` para que Google no la indexe todavía.
La versión definitiva se genera con el Kit Webs 3D: `empaquetar-web.mjs --final`.

Pendiente: número de WhatsApp, alérgenos, zona de recogida, datos legales del titular y registro sanitario.
