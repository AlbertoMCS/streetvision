Para linkar una carpeta en el escritorio con un repositorio en Guithub:

1- Crear un proyecto en Guithub en blanco
1- Abrimos Git Bash y nos vamos a la carpeta del escritorio que quiero vincular con el repositorio de Github
2- git init
3- git add -A #esto anade todo lo que tenemos en la carpeta y lo prepara para pushearlo
4-  git remote add origin "URL que se saca del repositorio nuevo que hemos creado en blanco"
5- git remote -v #verificar la URL
6- git push --all #manda todo al repositorio nuevo

Una vez que ya tenemos la carpeta vinculada al repositorio, cuando hacemos cambios en las carpetas o en los archivos
solo habria que seguir este proceso: 
1- git status  #con esto podemos ver lo que hemos cambiado, pero aarecera todo untracked (no podemos pushearlo)
2- git add -A # esto lo anade todo (ya no esta untracked) preparado para commitearlo
3- git push --all # esto hace que todo se renueve. 