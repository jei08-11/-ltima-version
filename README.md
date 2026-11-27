# JEI ESTIRAR

Aplicación web instalable (PWA) para Android.

## Archivos
- `index.html`: pantalla y controles de vista previa.
- `manifest.webmanifest`: configuración de instalación.
- `sw.js`: funcionamiento básico sin conexión.
- `icon.svg`: icono.

## Publicar con GitHub Pages
1. Sube **todos** los archivos de esta carpeta a la raíz del repositorio.
2. En GitHub abre **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
5. Abre la dirección publicada con Chrome en Android.
6. Menú ⋮ → **Instalar aplicación** o **Añadir a pantalla principal**.

## Límite importante
Esta PWA solo cambia la vista previa dentro de la propia app. No puede cambiar la resolución global de Android ni modificar cómo se ven otros juegos o aplicaciones.