Mi pimer repositorio
1) git --version (ver la version )
2) git config --global user.name "Tu Nombre" (Configura el nombre en entorno local)
3) git config --global user.email "Tu Mail" 
4) git config --global core.editor "code --wait" (cambiar a vs code)
5) git config --list (ver los datos del git)
6) cd (navegar 'change directory cambiar')
7) mkdir (crear carpeta 'make directory')
8) cd.. (volver)
9) ls (mirar el contenido en la carpeta)
10) clear (limpiar pantalla)
11) git init (inicializar el repositorio)
12) git status (verifica el estado del repositorio)
13) git add "nombre del archivo"(agregar un archivo)
14) git add . (agregar todos los archivos)
15) git commit -m "nota referencial cambio del commit '-m message' ".
16) git log (se muestan los commits realizados)
17) q para salir cuando aparezca (END)
19) git branch -M main (Renombra la rama actual a "main". Si ya existe una rama "main" '-M move/mover(renombrar) ')
20) git remote add origin "https://github.com/user/laborartorio-2026.git"
(agrega el repo local con el de la nube 'Crea un remote llamado origin que apunta a esa URL. Un remote es un alias para un repositorio en otro lado (ej: GitHub)')
21) git push -u origin main (sube todos los cambios a la nube)
Comandos para Ramas nuevas en Git
22) git checkout -b nueva-rama (crear y moverme a la rama '-b de branch')
23) git checkout main ('checkout como salirse de' cambiar o moverse a main' checkout para moverse entre ramas)
24) git merge nueva-rama ('merge fusionar' esta funcion permite traer los cambios 'intgrarlos' de nueva-rama a la main 'la main tiene lo viejo+lo nuevo)
25) git branch -d nueva-rama (elimina la referencia de la rama.Solo permite borrar si ya fue fusionada 'mergeada' '-d delete' los cambios ya estan en la main no quita cambios vinculados)

# SI HAY CONFLICTO:
# → abrir el archivo
# → elegir qué versión conservar
# → borrar los marcadores <<<<, ====, >>>>
# → git add + git commit
