LA CASA DEL HINCHA - PWA FIDELIDAD
NIVEL 1 FINAL - FONDO ESTADIO + LOGOS CORREGIDOS

Contenido:
- index.html
- manifest.json
- service-worker.js
- logo-color.png (logo a color, transparente, usado en la cabecera)
- logo-bn.png (logo B/N, transparente, usado para los sellos)
- icon-192.png (icono PWA a color, transparente)
- icon-512.png (icono PWA a color, transparente)
- apple-touch-icon.png (icono para iPhone/iPad, transparente)
- fondo-app.jpg (fondo vertical de estadio)

Cambios de esta versión:
1. Se conserva la lógica de los 10 sellos, IndexedDB y funcionamiento offline.
2. Los sellos muestran el logo B/N sin rectángulo negro de fondo.
3. El icono de instalación usa el logo a color sin fondo sólido.
4. Se añade fondo de estadio detrás de la tarjeta.
5. El fondo se incluye en el Service Worker para que funcione offline.
6. Service Worker actualizado a caché v5 para forzar la nueva versión.

IMPORTANTE:
- Reemplazar los archivos del repositorio por los de esta carpeta.
- No borrar logo-color.png ni logo-bn.png: ambos ya están corregidos.
- Después de publicar en GitHub Pages, puede ser necesario cerrar/reabrir la PWA o borrar la caché del sitio para que el Service Worker v5 tome los nuevos archivos.
