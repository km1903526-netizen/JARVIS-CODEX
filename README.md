# JARVIS CODEX v1.0

Interfaz web futurista de un asistente personal tipo JARVIS.

## Contenido

- `index.html` — estructura de la interfaz.
- `styles.css` — diseño futurista responsive.
- `app.js` — chat local, comandos, memoria local y reconocimiento de voz.
- `README.md` — documentación.

## Cómo probarlo

No requiere instalación para la versión básica.

1. Extrae el ZIP.
2. Abre `index.html` en un navegador moderno.
3. En Android, puedes usar Chrome.
4. Para el micrófono, concede el permiso cuando el navegador lo solicite.

## Comandos

- `/help`
- `/status`
- `/code`
- `/debug`
- `/research`
- `/clear`

También puedes guardar información con:

`recuerda [texto]`

La memoria de esta versión se guarda únicamente en `localStorage` del navegador.

## Próxima fase

La interfaz está preparada para conectar un backend y un modelo de IA. Para una aplicación real, la clave/API debe mantenerse en un servidor o backend seguro y no incrustarse directamente en el navegador.
