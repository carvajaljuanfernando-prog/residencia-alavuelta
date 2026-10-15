# Ruta Residencia MI

Plataforma de preparación para el examen de admisión a residencia de Medicina Interna en Colombia.
Ruta de 16 semanas para quien trabaja, 140 preguntas tipo examen con retroalimentación y perla, simulacros cronometrados, repaso espaciado de errores y seguimiento de progreso.

Todo corre en el navegador: no requiere cuenta, servidor ni conexión después de cargar. El progreso se guarda en el dispositivo (localStorage) y puede exportarse/importarse entre dispositivos desde la pestaña Progreso.

## Publicar en GitHub Pages
1. Sube `index.html`, `banco.js` y este `README.md` a un repositorio.
2. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.
3. En 1-2 minutos la app queda en `https://<usuario>.github.io/<repositorio>/`.

## Ampliar el banco
`banco.js` es una lista de objetos: `{id, area, tema, dif, q, o:[4 opciones], a: índice correcto, e: explicación, p: perla}`. Agrega preguntas al final; la app las toma automáticamente.
