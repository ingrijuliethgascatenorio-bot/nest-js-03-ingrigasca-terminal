# Solucion de Conflicto

**Conflicto:** Se modifico la misma linea en `src\controllers\user.controller.js` desde `main` y `dev`.

**Resolucion:** Abri el archivo y combine los cambios manualmente, eliminando los marcadores `<<<<<<<`, `=======`, `>>>>>>>` y dejando la funcion y los mensajes que desee.

**Comandos utilizados:**
git checkout dev
git commit -m "Cambio en dev"
git checkout main
git commit -m "Cambio en main"
git merge dev
git add src\controllers\user.controller.js
git commit -m "Resuelto conflicto entre main y dev"
code solucion-conflicto.md
