# 1. Crea una carpeta con el nombre de tu proyecto
mkdir mi-pagina-web
cd mi-pagina-web

# 2. Inicializa Git en esa carpeta
git init

# 3. Crea un archivo README.md
echo "# Mi Página Web" > README.md

# 4. Añade los archivos al staging
git add .

# 5. Haz tu primer commit
git commit -m "Primer commit"

# 6. Conecta tu repositorio local con GitHub
# (Cambia TU_USUARIO y NOMBRE_REPO por tu usuario y nombre del repo en GitHub)
git remote add origin https://github.com/TU_USUARIO/NOMBRE_REPO.git

# 7. Cambia el nombre de la rama a main (si no existe ya)
git branch -M main

# 8. Sube el proyecto a GitHub
git push -u origin main
