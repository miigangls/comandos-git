📘 Guía de Comandos Básicos de Git

🧱 Creación y manejo de repositorios

### Inicializar un repositorio local
git init

### Clonar un repositorio remoto
git clone <URL>

### Añadir archivos o directorios al área de preparación (staging)
git add <NombreArchivo> [<OtroArchivo>]

### Confirmar los cambios
git commit -m "Mensaje del commit"
git commit -am "Mensaje"   # Añade y confirma archivos modificados directamente

### Eliminar archivos del repositorio
git rm <archivo>

### Eliminar archivos del repositorio Mover o renombrar archivos
git mv <origen> <destino>

### Eliminar archivos del repositorio Mostrar el estado actual del repositorio
git status

# Ver diferencias entre archivos no indexados
git diff

### Eliminar archivos del repositorio Ver el historial de commits
git log
git log -n 1             # Muestra solo el último commit
git log --oneline        # Resumen corto de commits
git log --stat           # Archivos modificados y líneas añadidas/eliminadas
git log --author="Nombre" # Commits de un autor específico
git log --decorate       # Muestra ramas y etiquetas asociadas

### Eliminar archivos del repositorio Mostrar los detalles de un commit específico
git show

### Eliminar archivos del repositorio Resetear archivos o commits
git reset HEAD <archivo>      # Quita un archivo del área de staging
git reset --soft HEAD         # Deshace el último commit, mantiene los cambios
git reset --hard HEAD         # Restaura el estado del último commit (pierdes cambios)

### Eliminar archivos del repositorio Limpiar archivos no rastreados
git clean -f

🌿 Manejo de ramas
### Eliminar archivos del repositorio Mostrar todas las ramas
git branch

### Eliminar archivos del repositorio Crear una nueva rama
git branch <NombreRama>

### Eliminar archivos del repositorio Cambiar de rama
git checkout <NombreRama>

### Eliminar archivos del repositorio Crear y moverse a una nueva rama
git checkout -b <NombreRama>

### Eliminar archivos del repositorio Combinar ramas (merge)
git merge <NombreRama>

🚀 Subir repositorios a GitHub
### Eliminar archivos del repositorio Subir todas las ramas al repositorio remoto
git push origin --all

### Eliminar archivos del repositorio Subir una rama específica
git push origin <NombreRama>

### Eliminar archivos del repositorio Clonar un repositorio de GitHub
git clone <link>

### Eliminar archivos del repositorio Mostrar los orígenes remotos configurados
git remote -v

### Eliminar archivos del repositorio Actualizar los commits del repositorio remoto sin fusionar
git fetch

### Eliminar archivos del repositorio Descargar y fusionar los cambios del remoto
git pull origin <NombreRama>

🌐 Crear hosting con GitHub Pages
### Eliminar archivos del repositorio Crear una rama especial para hosting en GitHub Pages
git branch gh-pages


⚡ Nota: GitHub reconoce automáticamente la rama gh-pages para publicar sitios web estáticos.
