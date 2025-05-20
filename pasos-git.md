paso 1
crear git-init

paso 2
dar seguimiento a los archivos de nuestro repositorio
U significa sin seguimiento (área sin seguimiento)
 git add . da seguimiento a todos nuestros archivos.
los archivos con cambios git add "nombre del archivo"

paso 3
versionar (commit)
git commit -m 'nombre de los cambios'

añadir un cambio, primero lo añado, despues commit
git add .
git commit -m ''

PASO 4
GIT BRUNCH renombra la rama master a main
git branch -M main

paso 5
conectar nuestro repo local con un origen remoto
git remote add origin https://github.com/Marinalej/Repo---TP1-UTN2025
git pusg -u origin main

Paso 6
subir nuestros cambios al repositorio remoto
git push -u origin main


