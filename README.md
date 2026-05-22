# Coffee Day · Salta 2026

Landing page del evento Coffee Day — café, música y cultura cafetera.
Domingo 24 de mayo · Kokoro Café · Salta, Argentina.

Sitio estático construido con [Astro](https://astro.build). Sin frameworks JS,
HTML semántico, CSS separado por componente.

## Estructura

```text
/
├── public/
│   ├── assets/       imágenes, fuentes, logos de sponsors
│   └── styles/       CSS — tokens, global, nav, hero, sections
├── src/
│   ├── layouts/      Layout.astro — base HTML, meta, fuentes
│   ├── components/   secciones de la página (.astro)
│   └── pages/        index.astro — ensambla la página
└── package.json
```

## Comandos

| Comando           | Acción                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Instala dependencias                         |
| `npm run dev`     | Dev server en `localhost:4321`               |
| `npm run build`   | Build de producción a `./dist/`              |
| `npm run preview` | Previsualiza el build local                  |

## Deploy

El build genera estáticos en `dist/`. Compatible con Netlify, Vercel,
Cloudflare Pages o GitHub Pages — apuntar el build command a `npm run build`
y el output directory a `dist`.
