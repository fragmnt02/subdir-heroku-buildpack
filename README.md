Como usar:
1. Ir a heroku -> `settings` -> `Buildpacks` y borrarr todos los buildpacks que hayan posiblemente uno de heroku/nodejs
2. Click en agregar build pack y pegar en el input `https://github.com/fragmnt02/subdir-heroku-buildpack`
3. Click en agregar build pack de nuevo y seleccionar node js
4. Ir a la sección `Config Vars` y agregar esto en KEY `PROJECT_PATH` y en VALUE la carpeta donde esta el proyecto.
