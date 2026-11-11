# Keeper Cup 3 · Sorteo Fase 2

Página independiente para el sorteo de horarios de la Fase 2 (Copa Oro y Copa Plata, Fechas 8, 9 y 10).

- **`index.html`**: la página de los DT. Todos entran por el mismo link (`?g=…`), escriben el código de su club y sacan su rival, día, hora y estadio. Tiene panel En vivo y Mapa.
- **`organizador.html`**: solo para el organizador. Tabla final oficial, pedidos de los clubes, semilla, prueba, publicar / abrir / cerrar, link y mensajes de WhatsApp, y descarga del resultado (JSON / CSV).
- **`sorteo-core.js`**: el motor del sorteo (el mismo resultado para la misma semilla).
- **`sorteo-boot.js`**: la lógica de la página de los DT.

La configuración se guarda en un gist secreto de la cuenta del organizador (los DT solo la leen). Lo que saca cada DT viaja por ntfy.sh para el panel en vivo. El resultado lo fija la semilla anunciada.

Después del sorteo se puede desactivar GitHub Pages en *Settings → Pages* o archivar el repositorio.
