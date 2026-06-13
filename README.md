# QR Timbre Static

App 100% estática para Vercel. No usa Next, no usa npm, no usa build.

## Archivos raíz obligatorios

- index.html
- dueno.html
- visitante.html
- styles.css
- vercel.json

## URLs

- Panel dueño: `/dueno`
- Link QR visitante: `/h/casa?c=...`

## Deploy en Vercel

Subir estos archivos a la raíz del repo. Vercel debe desplegarlo como sitio estático sin build.

Si Vercel intenta correr npm/build, borrar `package.json` del repo.
