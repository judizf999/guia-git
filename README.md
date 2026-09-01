# Navega a la carpeta donde quieras el proyecto
cd ~/Documentos

# Clona el repositorio
git clone https://github.com/judiz999/guia-git.git

# Entra a la carpeta
cd guia-git
# Desde la carpeta guia-git que acabas de clonar

# Copia el contenido del README.md que creamos en el archivo
# puedes usar:
# - VS Code: Abre el archivo README_GIT_GUIA.md y cópialo
# - Terminal: cp ~/ruta/README_GIT_GUIA.md ./README.md

# Si quieres usar la línea de comando:
curl https://raw.githubusercontent.com/usuario/repo/main/README.md > README.md
# Verifica el estado
git status

# Deberías ver algo como:
# On branch main
# Changes not staged for commit:
#   (use "git add <file>..." to update)
#   modified:   README.md

# Preparar el archivo
git add README.md

# Ver el staging
git status

# Crear el commit
git commit -m "Agregar guía completa de primeros pasos con Git"

# Verificar que todo está guardado
git status
