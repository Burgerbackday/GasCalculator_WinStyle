# Trip range (PWA)

Archivos: index.html, manifest.webmanifest, sw.js, carpeta icons y carpeta fonts.
Todo debe quedar junto, en la misma carpeta, sin cambiar nombres.

## Subirla (GitHub Pages, gratis)
1. Crea una cuenta en github.com y un repositorio nuevo, por ejemplo "trip-range". Debe ser público.
2. Entra al repositorio, toca "Add file" y luego "Upload files". Arrastra TODO el contenido de esta carpeta (incluidas icons y fonts) y confirma con "Commit changes".
3. Ve a Settings, luego Pages. En "Source" elige "Deploy from a branch", rama main, carpeta /(root), y guarda.
4. Espera uno o dos minutos. Tu dirección será https://TU-USUARIO.github.io/trip-range/

Alternativas gratis: Cloudflare Pages o Netlify, subiendo esta misma carpeta.

## Instalarla en el iPhone
1. Abre la dirección en Safari (tiene que ser Safari).
2. Toca Compartir y luego "Añadir a pantalla de inicio".
3. Abre la app desde el icono nuevo y captura tus datos AHÍ. Los datos de Safari y los de la app instalada son independientes.

## Probar el modo sin internet
1. Abre la app instalada una vez con internet (así se guarda una copia).
2. Cierra la app, activa el modo avión y ábrela de nuevo. Debe funcionar igual.

## Actualizarla
Reemplaza index.html en el repositorio. La app descarga la versión nueva en segundo plano. Se ve al cerrarla y abrirla de nuevo, a veces dos veces.
Si cambias el nombre de los archivos o agregas otros, cambia también el nombre de versión "trip-range-v1" en sw.js.

## Notas
- Tus datos viven solo en tu iPhone, en el almacenamiento de la app. Si borras el icono, se pierden.
- La fuente es Pixelify Sans, con licencia OFL (fonts/LICENSE-OFL.txt).
