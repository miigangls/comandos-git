/*Comando para crear repositorios en Git */

git init -- para iniciar el git.  
git clone direccion URL -- Para clonar el directiorio.
git add  NombreArchivo [] --se gerenra captura o añade un archivo o directorio.
git commit --	 -m "Mensaje" es para todos archivos ya modificados.
		-am "Mensaje" + "Archivo" Es para cambiar el Archivo con la carpeta.
git rm [archivo] - Para la eliminacion de los diferentes archivos.
git mv origen Destino -Para renombrar o   mover un archivo.
git status -- Mostra el estado actual de los directorios de trabajos.
git diff -- Muestra la diferencia los que no estan estegin index
git log -- Muestra toda la informacionn.
git log -n 1 --Nos muestra el primer commit o depende del numero de que quereamos.
git log -oneline -- Resumen de todos los commit que existen.
git log -stat -- Que archivos se han cambiado y el numero de lineas que a se añadido o cambiado de cada archivo.
git log --author="NOMBRE-DEL-AUTOR" --Muestra los commit echos por esa persona.
git log --decorte  añade los nombre de las ramas o de las etiquetas.
git show Muestra los metadatos.
git reset head nombreArchivo  --Marcar el archivo para que no sea incliudo en el proximo commit 
git reset --soft head --Desase el commit y conserva los cambios el area local
git reset --hard head --Restablce el arbol de area local con el ultimo commit 
git clean  --limipiar 

/* Comandos para Ramas */

git branch  --Muestra todas las ramas que exiten en el momento.
git branch "NombreRama"  --Creacion de una Rama.
git checkout "NombreRama" --Posiciona la rama.
git checkout -b "NombreRama" -- Creacion una rama y lo posiciona en la rama.
git meter "NombreRama" -- Combinar dos ramas en una sola rama. 


/* Subir los repositorios a githup */

git push origin --Subir todos los ramas del repositorio.
git push origin "NombreRama" --Subir los cambios realizados a solo esa rama.
git clone link --Clonar un repositorio de githup.
git remote -v --muestra los fetch y el pull para actualizar los archivos locales.
git fetch  --Actuliza los commit de mi repositorio local.
git pull origin --Actualiza el repositorio local.

/* Creacion de un Hosting con gitHup  */

git branch gh-page -- se crea una rama con ese nombre para que gitHup lo crea como un hosting
