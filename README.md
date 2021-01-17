# EjemplosGit
**Ejemplos de ejercicios para probar Git**

Recordad que la rama master ha sido reemplazada por main en Github

Por tanto es recomendable:
Usar main como rama principal en git.
Con el siguiente codigo podemos remplazar a master por main:

git branch -m master main    
git push -u origin main

git branch -m master main < – mandamos el historial de master a la nueva rama main
git push -u origin main <-- Hacemos push a la rama main para que github tenga todo el codigo que anteriormente teniamos en master
Ahora solo recordad que cuando en los cursos digan la rama master tú usaras “main”

También se puede colocar a master como rama principal en github.
En tu repositorio en github ir a:
Settings > Branches > en el menu que aparece seleccionar master y dar click en el boton de “update”

Fuente: https://platzi.com/tutoriales/1557-git-github/7585-problemas-ramas-main-master/
