# Dosis Pedia — instalar como app en Android

Esta carpeta es una PWA (app web instalable). Para que Chrome pueda instalarla
como app, primero tiene que estar publicada en una URL con HTTPS — no alcanza
con abrir el archivo `index.html` directamente desde el celular.

## Opción más simple y gratis: GitHub Pages

1. Creá una cuenta en https://github.com si no tenés una.
2. Creá un repositorio nuevo, por ejemplo `dosis-pedia`.
3. Subí los 6 archivos de esta carpeta (`index.html`, `manifest.json`,
   `service-worker.js`, los 3 `icon-*.png` y este `LEEME.md`) — con el botón
   "Add file → Upload files" alcanza, no hace falta usar la terminal.
4. Andá a Settings → Pages, y en "Branch" elegí `main` (carpeta `/root`) y
   guardá.
5. En un par de minutos vas a tener tu app en
   `https://tu-usuario.github.io/dosis-pedia/`.

## Instalarla en el celular

1. Abrí esa URL en Chrome desde tu Android.
2. Tocá el menú (⋮) → **"Instalar app"** (o "Agregar a pantalla de inicio").
3. Va a quedar con ícono propio, pantalla completa y funciona sin internet
   una vez que la abriste al menos una vez.

## Si más adelante querés un .apk real

Una vez que esté publicada con la URL de arriba, entrá a
https://www.pwabuilder.com, pegá esa URL y generá el paquete para Android
(.apk / .aab) sin escribir código. Sirve para compartirla por afuera de Play
Store o, si querés, subirla a Play Store más adelante.
