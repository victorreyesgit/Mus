# Mus

Mus para movil y ordenador (4 jugadores, 8 reyes, a 40 piedras, vacas al mejor de 3 juegos).
Todo el juego esta en `index.html`. Funciona sin internet una vez abierto.

- `manifest.json`, `service-worker.js` e `icon-*.png`: solo sirven para instalarlo como app y jugar sin conexion.

## Publicar
1. Repositorio publico nuevo en GitHub y sube el contenido de esta carpeta (con `icons`).
2. Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Abre `https://TU_USUARIO.github.io/NOMBRE_REPO/` una vez con internet e instalalo
   (Android: menu > Instalar aplicacion. iPhone: Compartir > Anadir a pantalla de inicio).

Al subir cambios, sube el numero de `vr-mus-v9` en `service-worker.js` para que los moviles actualicen.

App ID: `/vr-mus` (manifest id, never change it)
