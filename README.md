# Ruta Andina: Machu Picchu

Página temática sobre Machu Picchu, construida con HTML y CSS. La fotografía se guarda junto al proyecto para que la página funcione sin depender de una imagen remota.

## Comandos de Git

- `git init`: crea el repositorio local y su historial.
- `git add`: prepara archivos para incluirlos en el siguiente commit.
- `git commit`: guarda una versión de los archivos preparados.
- `git push`: publica commits en el repositorio remoto de GitHub.
- `git clone`: descarga una copia del repositorio en otra carpeta.
- `git pull`: trae e integra en la copia local los cambios publicados en el remoto.
- `git branch`: permite trabajar en una línea de cambios separada; luego se integra con un merge a `main`.

## Flujo realizado

- Repositorio local inicializado en `main`; primer commit: `2627fa3`.
- Proyecto clonado en otra carpeta; se añadieron los lugares destacados y un enlace de navegación.
- Los cambios de la copia se guardaron y se enviaron al remoto local: `e6f8371`.
- Rama `mejora-cuidado-del-santuario` creada; se añadió una recomendación visible: `295bc69`.
- La rama se integró en `main` y la carpeta original se actualizó con `git pull`.

El remoto `origin` usado durante la práctica es una carpeta local llamada `machu-picchu-remoto.git`; todavía no es un repositorio de GitHub. Para publicar, crea un repositorio vacío en GitHub y reemplaza `URL_DEL_REPOSITORIO` en las dos carpetas:

```powershell
git remote set-url origin URL_DEL_REPOSITORIO
git push -u origin main
git push -u origin mejora-cuidado-del-santuario
```

En la carpeta original, configura también esa URL y ejecuta `git pull origin main`.

## Evidencias

- [x] Proyecto inicial: `evidencias/proyecto-inicial.png`.
- [x] Segunda copia con dos cambios visibles: `evidencias/copia-con-cambios.png`.
- [x] Mejora visible en la rama: `evidencias/mejora-en-rama.png`.
- [x] Merge a `main` y `git pull` en la carpeta original: ver commits e historial de Git.
- [x] Resultado final en escritorio y móvil: `evidencias/final-escritorio.png` y `evidencias/final-movil.png`.
- [ ] Repositorio y cambios publicados en GitHub; falta configurar una URL de GitHub.
