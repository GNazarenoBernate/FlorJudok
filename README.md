# Flor Judok 

Landing page para Flor Judok.

## Stack
- HTML5 (semántico)
- CSS3 (mobile-first, sin frameworks)
- JavaScript vanilla

## Estructura
- `index.html` — Estructura semántica
- `styles/` — CSS por sección
- `scripts/` — JS de interacciones
- `assets/` — Imágenes y logos

## Decisiones de diseño

> Aca voy agregando una línea cada vez que tome una decision.

- Usé `<section>` para cada bloque porque cada uno tiene un heading h2 y contenido temático propio.
- Mobile-first: empecé con el layout de 375px y agregué breakpoints en 768px y 1024px.
- Migré el entorno de desarrollo a WSL2 (Ubuntu) en vez de trabajar con Node/Git nativos de Windows. Motivos: Evité instalar Linux en dual boot. WSL2 da un entorno Unix real sin tocar particiones, y es compatible al 100% con las herramientas que uso (Node, Git, npm).

## Status
- [x] Wireframe (Figma)
- [x] Estructura HTML
- [x] CSS base
- [ ] CSS responsive
- [ ] JS (lightbox, smooth scroll, lazy load)
- [ ] Contenido real
- [ ] Test en dispositivos
- [ ] Deploy   