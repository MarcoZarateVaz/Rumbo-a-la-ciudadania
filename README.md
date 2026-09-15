# Rumbo a la ciudadanía — PWA

Versión preparada para publicar en GitHub Pages e instalarse como aplicación desde un navegador compatible.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube **todo el contenido de esta carpeta** manteniendo la estructura de `icons/` y `assets/`.
3. En el repositorio entra a **Settings → Pages**.
4. Selecciona **Deploy from a branch**.
5. Selecciona la rama que contiene estos archivos y la carpeta `/ (root)`.
6. Abre la URL HTTPS que GitHub Pages te proporcione.
7. Desde el navegador, usa **Instalar aplicación / Add to Home screen**.

> La instalación PWA y el Service Worker requieren HTTPS (GitHub Pages lo proporciona automáticamente).

## Estructura

- `index.html` — aplicación principal.
- `standalone.html` — versión standalone existente.
- `manifest.webmanifest` — configuración PWA, nombre, colores e iconos.
- `sw.js` — Service Worker y caché offline.
- `icons/` — iconos para navegador, Android y dispositivos Apple.
- `assets/logo-source.png` — logo original generado para el proyecto.

## Nota

Esta versión conserva la aplicación sin las funciones de micrófono/reconocimiento de voz y utiliza la versión corregida de la interfaz de **Mi estado**.
