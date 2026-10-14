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

## Evidencias por capturar

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

## Evidencias por capturar

- [ ] Página final abierta en el navegador.
- [ ] Dos cambios visibles en la segunda copia.
- [ ] Rama y mejora visible.
- [ ] Integración a `main` y actualización de la carpeta original.
- [ ] Repositorio y cambios publicados en GitHub.
