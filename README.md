📘 Guía de Comandos Básicos de Git
🧱 Creación y manejo de repositorios
# Inicializar un repositorio local
git init

# Clonar un repositorio remoto
git clone <URL>

# Añadir archivos o directorios al área de preparación (staging)
git add <NombreArchivo> [<OtroArchivo>]

# Confirmar los cambios
git commit -m "Mensaje del commit"
git commit -am "Mensaje"   # Añade y confirma archivos modificados directamente

# Eliminar archivos del repositorio
git rm <archivo>

# Mover o renombrar archivos
git mv <origen> <destino>

# Mostrar el estado actual del repositorio
git status

# Ver diferencias entre archivos no indexados
git diff

# Ver el historial de commits
git log
git log -n 1             # Muestra solo el último commit
git log --oneline        # Resumen corto de commits
git log --stat           # Archivos modificados y líneas añadidas/eliminadas
git log --author="Nombre" # Commits de un autor específico
git log --decorate       # Muestra ramas y etiquetas asociadas

# Mostrar los detalles de un commit específico
git show

# Resetear archivos o commits
git reset HEAD <archivo>      # Quita un archivo del área de staging
git reset --soft HEAD         # Deshace el último commit, mantiene los cambios
git reset --hard HEAD         # Restaura el estado del último commit (pierdes cambios)

# Limpiar archivos no rastreados
git clean -f

🌿 Manejo de ramas
# Mostrar todas las ramas
git branch

# Crear una nueva rama
git branch <NombreRama>

# Cambiar de rama
git checkout <NombreRama>

# Crear y moverse a una nueva rama
git checkout -b <NombreRama>

# Combinar ramas (merge)
git merge <NombreRama>

🚀 Subir repositorios a GitHub
# Subir todas las ramas al repositorio remoto
git push origin --all

# Subir una rama específica
git push origin <NombreRama>

# Clonar un repositorio de GitHub
git clone <link>

# Mostrar los orígenes remotos configurados
git remote -v

# Actualizar los commits del repositorio remoto sin fusionar
git fetch

# Descargar y fusionar los cambios del remoto
git pull origin <NombreRama>

🌐 Crear hosting con GitHub Pages
# Crear una rama especial para hosting en GitHub Pages
git branch gh-pages


⚡ Nota: GitHub reconoce automáticamente la rama gh-pages para publicar sitios web estáticos.
