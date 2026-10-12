# Mis lucas

App personal de finanzas: cuánto puedes gastar hoy para llegar a tu meta del mes.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (por ejemplo `mi-dinero`) y sube todos estos archivos a la raíz.
2. En el repositorio: Settings → Pages → Source: "Deploy from a branch", rama `main`, carpeta `/ (root)` → Save.
3. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/mi-dinero/`.

## Instalar
- Android (Chrome): menú ⋮ → "Instalar app".
- iPhone (Safari): Compartir → "Agregar a inicio".
- Laptop (Chrome o Edge): ícono de instalar en la barra de direcciones, o úsala como página normal.

## Actualizar
Cambia los archivos y sube el número en la primera línea de `sw.js` (`mis-lucas-v3.2` → `mis-lucas-v3.3`) y `VERSION` en `index.html`.
Los datos de cada dispositivo no se pierden al actualizar.

## Datos
Sin sesión, todo queda en el navegador de cada dispositivo. Con sesión de Google (Ajustes → Sincronización), los datos se guardan en Firebase (proyecto mis-lucas-c6c6a) y se comparten entre tus dispositivos. Las fotos de boletas quedan solo en el equipo donde se tomaron.
