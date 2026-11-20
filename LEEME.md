# Portfolio — Mia González (escritorio Mac)

Está hecho con [Astro](https://astro.build). Necesitás Node 22 o más nuevo.

La primera vez (o después de clonar el repo), instalá las dependencias:

    npm install

Para verlo en tu compu mientras editás (se recarga solo):

    npm run dev

y abrí http://localhost:4321

Para generar la versión final (queda en `dist/`) y probarla:

    npm run build
    npm run preview

## Dónde está cada cosa
- **HTML de la página:** `src/pages/index.astro`.
- **Estilos:** `src/styles/style.css`.
- **Textos (ES y EN):** `src/scripts/content.js`. Buscá `[completar]` (mail, Instagram, LinkedIn, Behance) y `[confirmar]` (tu rol en Dead Silence, tu nivel de inglés).
- **Íconos del escritorio** (qué carpeta o foto va y dónde): lista `DESK` al principio de `src/scripts/main.js`. `x` e `y` van de 0 a 1.
- **Imágenes de proyectos:** `public/assets/img/`. Para sumar una, ponela ahí y agregá `{ src: 'assets/img/tu-archivo.webp', name: 'nombre.png' }` en los `files` de ese proyecto en `src/scripts/content.js`.
- **Moodboard:** `public/assets/mood/` (sacado de tu Figma). La lista está en `MOOD` dentro de `src/scripts/content.js`. Las fotos que pasan en el widget están en `WIDGET_PICS` (en `src/scripts/main.js`).
- **Íconos de Mac:** `public/assets/icons/`, sacados de tu propia Mac.
- **Tipografía de tu nombre:** Positions, en `public/assets/fonts/`.
- **Tu foto:** hoy hay un cuadrito rosa "tu foto acá" en Notas y en "Acerca de Mia".

## Links directos
Podés mandar el link con una ventana ya abierta: `#c3po`, `#coopid`, `#planify`, `#dead`, `#kate`, `#skills`, `#notes`, `#keynote`, `#reminders`, `#terminal`, `#mail`, `#photos`, `#about`. Se pueden juntar con coma: `#c3po,notes`.
