LA CASA DEL HINCHA - PWA NIVEL 1

Version: Nivel 1 definitivo / offline-first / multiplataforma

Archivos que deben estar en la raiz de GitHub Pages:
- index.html
- manifest.json
- service-worker.js
- logo-color.png
- logo-bn.png
- icon-192.png
- icon-512.png
- apple-touch-icon.png

Compatibilidad objetivo:
- Android: Chrome/Edge y navegadores compatibles con PWA
- iPhone/iPad: Safari y navegadores basados en WebKit compatibles con web apps
- Windows/macOS/Linux/ChromeOS: navegadores modernos compatibles

Funciones:
- 10 sellos
- IndexedDB offline
- Migracion de puntos/nombre antiguos desde localStorage
- Identificador local de dispositivo y marca de ultima modificacion, preparados para Nivel 2
- Service Worker offline
- Instalacion PWA en navegadores compatibles
- Guia de instalacion para iPhone/iPad
- Responsive y safe-area para pantallas con notch

IMPORTANTE:
Nivel 1 NO sincroniza datos entre dispositivos. Cada dispositivo mantiene su propia informacion local.
Nivel 2 agregara una base de datos en la nube y sincronizacion.
