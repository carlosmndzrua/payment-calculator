# Mendoza Cars — Calculadora de Pagos (PWA)

## Qué hay en esta carpeta
- `index.html` — la app completa (funciona sola, sin necesidad de instalar nada ni compilar)
- `manifest.json` — hace que el teléfono la reconozca como app instalable
- `service-worker.js` — permite que funcione offline y se actualice sola
- `icon-192.png` / `icon-512.png` — ícono de la app

## Cómo publicarla (elige una opción, todas son gratis)

### Opción A — Netlify (la más simple)
1. Ve a https://app.netlify.com/drop
2. Arrastra esta carpeta completa a la página
3. Netlify te da una URL (ej. `mendoza-cars-calc.netlify.app`) — ya está en línea

### Opción B — Vercel
1. Crea cuenta en https://vercel.com
2. "Add New Project" → sube esta carpeta (o conéctala a un repositorio de GitHub)
3. Despliega — te da una URL similar

### Opción C — GitHub Pages
1. Crea un repositorio en GitHub y sube estos archivos
2. Ve a Settings → Pages → selecciona la rama principal como fuente
3. GitHub te da una URL tipo `tuusuario.github.io/tu-repo`

## Cómo instalarla en tu teléfono
1. Abre la URL que te dio el hosting, en Chrome (Android) o Safari (iPhone)
2. **Android (Chrome):** menú (⋮) → "Agregar a pantalla de inicio" o aparecerá un banner de instalación automático
3. **iPhone (Safari):** botón de compartir (□↑) → "Agregar a pantalla de inicio"
4. Listo — queda como ícono de app, se abre a pantalla completa

## Cómo actualizarla cuando quieras un ajuste
1. Pídeme el cambio en el chat, te entrego el `index.html` actualizado
2. Vuelve a subir el archivo actualizado al mismo hosting (arrastrar de nuevo en Netlify, hacer push en GitHub, etc.)
3. La próxima vez que abras la app con internet, se actualiza sola — no necesitas reinstalarla ni borrar la anterior

## Nota
Esta app corre completamente en el navegador — no envía ni guarda datos de clientes en ningún servidor. Los números que metas solo existen en la pantalla mientras la usas.
