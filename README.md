# Web de clases de Matemáticas y Física (Sagunto · online)

Landing page en un único archivo: `index.html` (HTML5 + Tailwind CSS vía CDN).

## Antes de publicar

1. **Tu foto**: guarda tu foto como `foto.jpg` en esta misma carpeta, junto a `index.html`.
   Si no está, la página muestra un avatar con tu inicial.
2. **Tus datos**: abre `index.html` y edita el bloque `const PROFE = { ... }` del principio:
   `nombre`, `whatsapp` (prefijo 34 + móvil, sin `+` ni espacios) y `email`.
   Los precios, la ciudad y el enlace de Superprof ya están rellenados.

Para previsualizarla, haz doble clic en `index.html`.

## Publicar gratis

- **GitHub Pages**: en el repositorio, *Settings → Pages → Source: Deploy from a branch*,
  elige la rama y la carpeta `/ (root)`. En 1-2 minutos estará en `https://<usuario>.github.io/<repositorio>/`.
- **Netlify Drop**: entra en https://app.netlify.com/drop y arrastra la carpeta (con `index.html` y `foto.jpg`).
- **Vercel / Cloudflare Pages**: importa el repositorio, sin comando de build.
