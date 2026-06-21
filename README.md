# Página de cumpleaños para Sara 🤍

Todo listo para subir a GitHub y compartir el link por QR.

## 📁 Qué hay aquí

```
index.html        ← la página completa (HTML + CSS + JS en un solo archivo)
assets/
  foto1.jpg ... foto6.jpg   ← tus 6 fotos, ya optimizadas para web
  video1.mp4                ← tu video
  voznota.mp3                ← tu nota de voz, suena de fondo al abrir la página
```

## 🎙️ Sobre tu nota de voz (audio de fondo de la carta)

Tu nota de voz arranca sola apenas Sara toca el botón **Abrir** de la
portada — ese toque es justo lo que el navegador necesita para permitir
que suene audio automáticamente. Queda en loop mientras ella navega la
página, y hay un botoncito flotante abajo a la derecha (con un
ecualizador animado) por si quiere pausarla o reanudarla.

## 🎵 Sobre la canción

La canción **"Halley's Comet" de Billie Eilish** está integrada aparte,
como un reproductor de Spotify embebido, en su propia sección titulada
"Nuestra canción" debajo de la carta. No es un archivo dentro del repo —
se carga desde Spotify, que sí tiene los derechos para reproducirla.

Por las reglas del propio Spotify, ese reproductor no arranca solo ni
salta automáticamente al minuto 1:43 — Sara tiene que darle play y
arrastrar la barra ella misma (dejé una nota indicándolo).

## 🚀 Cómo subirlo a GitHub Pages (para tener el link)

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratis).
2. Arriba a la derecha, click en **+** → **New repository**.
3. Ponle un nombre, por ejemplo `para-sara` (puede ser cualquier nombre).
4. Déjalo en **Public** y crea el repositorio (no marques ningún checkbox extra).
5. En la página del repo recién creado, click en **uploading an existing file**
   (o el botón **Add file → Upload files**).
6. Arrastra **todo el contenido** de esta carpeta: `index.html` y la carpeta
   `assets` completa (con las 6 fotos, el video y la nota de voz).
   - Importante: que `assets` quede como carpeta dentro del repo, no sueltos
     los archivos.
7. Click en **Commit changes**.
8. Ve a la pestaña **Settings** del repositorio → en el menú izquierdo
   **Pages**.
9. En "Build and deployment" → **Source**, selecciona **Deploy from a branch**.
10. En "Branch" selecciona **main** y la carpeta **/ (root)** → **Save**.
11. Espera 1-2 minutos y recarga la página. Arriba te va a aparecer un link
    así: `https://tu-usuario.github.io/para-sara/`
12. ¡Ese es el link que va en tu QR! 🎉

## 🔍 Antes de generar el QR

Abre el link en tu celular y revisa:
- Que las fotos carguen bien y en el orden correcto.
- Que el video se reproduzca al tocarlo.
- Que tu nota de voz suene sola al darle "Abrir" en la portada.
- Que el reproductor de Spotify cargue y suene al darle play.
- Pruébalo con el wifi apagado (datos móviles) para asegurarte que carga rápido.

Para generar el QR puedes usar cualquier generador gratuito, por ejemplo
qr-code-generator.com, pegando el link de GitHub Pages.

## ✏️ Si quieres cambiar algo

Todo el texto y las rutas de las imágenes están directo en `index.html`,
buscando el texto correspondiente. Si quieres que te ayude a ajustar algo
(colores, textos, agregar otra foto), dime y lo hacemos.
