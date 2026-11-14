# Portafolio de ryuuseinan

Sitio personal construido con [Astro](https://astro.build) y Tailwind CSS, basado en la
plantilla [porfolio.dev](https://github.com/midudev/porfolio.dev) de
[midudev](https://midu.dev) (licencia CC BY-NC 4.0 — ver `LICENSE.md`).

## Comandos

| Comando | Acción |
| --- | --- |
| `pnpm install` | Instala dependencias |
| `pnpm dev` | Servidor de desarrollo en `localhost:4321` |
| `pnpm build` | Genera el sitio estático en `dist/` |
| `pnpm preview` | Previsualiza el build |

## Contenido

- Proyectos: `src/data/projects.json`
- Experiencia: `src/data/experience.json`
- Perfil (Hero) y "Sobre mí": `src/components/Hero.astro` y `src/components/AboutMe.astro`

## Deploy

Publicado en GitHub Pages mediante GitHub Actions (`.github/workflows/deploy.yml`) al hacer
push a `main`.

URL: https://ryuuseinan.github.io/
