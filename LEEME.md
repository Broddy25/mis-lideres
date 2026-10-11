# Mis Líderes: cómo publicarla e instalarla

La app es una página web instalable (PWA). Una vez publicada, tus líderes la abren con un enlace y la instalan en su celular. No hace falta un archivo APK.

## 1. Publicar con GitHub Pages (gratis, unos 5 minutos)

1. Entra a https://github.com y crea una cuenta, o inicia sesión.
2. Toca **New repository** (nuevo repositorio). Ponle de nombre `mis-lideres`, déjalo en **Public** y toca **Create repository**.
3. Toca **uploading an existing file** y arrastra **todo el contenido de la carpeta descomprimida**:
   `index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons`. Los archivos deben quedar en la raíz del repositorio, no dentro de otra carpeta.
4. Toca **Commit changes**.
5. Ve a **Settings**, luego **Pages**. En **Branch** elige `main` y la carpeta `/ (root)`, y toca **Save**.
6. Espera uno o dos minutos y recarga. Arriba aparecerá tu enlace, con este formato:
   `https://TU-USUARIO.github.io/mis-lideres/`

## 2. Instalar en el celular (cada líder)

**Android (Chrome):** abrir el enlace y tocar **Instalar app** (botón arriba a la derecha de la página). Si no aparece, tocar los tres puntos de Chrome y elegir **Instalar aplicación** o **Agregar a pantalla de inicio**.

**iPhone (Safari):** abrir el enlace, tocar el botón de compartir y elegir **Agregar a pantalla de inicio**.

## 3. Cosas a tener en cuenta

- Cada líder tiene su propia lista, guardada en su teléfono. Si borra los datos del navegador o desinstala la app, la lista se pierde.
- Funciona sin internet después de la primera vez que se abre.
- Para cambiar la app más adelante, sube el archivo nuevo a GitHub y cambia `mis-lideres-v1` por `mis-lideres-v2` en `sw.js`, para que los teléfonos descarguen la versión nueva.
- Los botones **Llamar** y **Mensaje** abren la app de llamadas y de mensajes del teléfono. **WhatsApp** abre WhatsApp.
