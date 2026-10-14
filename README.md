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
- Los cambios de la copia se guardaron en `e6f8371` y se publicaron en GitHub.
- Rama `mejora-cuidado-del-santuario` creada; se añadió una recomendación visible: `295bc69`.
- La rama se integró en `main`, se publicaron ambas ramas y la carpeta original se actualizó con `git pull`.

Repositorio público: https://github.com/nikitaleon1421-ux/machu-picchu-ruta-andina

El flujo de clonación y actualización se practicó primero con un remoto bare local. El remoto `origin` de las dos carpetas ahora apunta a GitHub:

```powershell
git push -u origin main
git push -u origin mejora-cuidado-del-santuario
```

Para actualizar la carpeta original desde GitHub, ejecuta `git pull origin main`.

## Evidencias

- [x] Proyecto inicial: `evidencias/proyecto-inicial.png`.
- [x] Segunda copia con dos cambios visibles: `evidencias/copia-con-cambios.png`.
- [x] Mejora visible en la rama: `evidencias/mejora-en-rama.png`.
- [x] Ramas publicadas y `main` predeterminada: `evidencias/ramas-github.png`.
- [x] Integración visible en el historial de `main`: `evidencias/integracion-main-github.png`.
- [x] Merge a `main` y `git pull` en la carpeta original: ver el historial y las capturas del resultado final.
- [x] Resultado final en escritorio y móvil: `evidencias/final-escritorio.png` y `evidencias/final-movil.png`.
- [x] Repositorio público y ramas publicados en GitHub: https://github.com/nikitaleon1421-ux/machu-picchu-ruta-andina
