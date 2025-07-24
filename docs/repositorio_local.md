```vim
" Conceptos aprendidos sobre cómo crear un repositorio local con Git

" Repositorio local: carpeta que guarda el historial de cambios de tu proyecto  
" Staging area (índice): espacio temporal donde añades cambios antes de guardarlos  
" Commit: punto de control que guarda el estado actual de los archivos añadidos  
" Rama (branch): línea de desarrollo independiente dentro del mismo repositorio  
" HEAD: indicador de la rama y commit en el que estás trabajando  

" Listado de comandos principales

git init                      – inicializa un repositorio Git en la carpeta actual  
git status                    – muestra el estado de archivos (modificados, sin seguimiento)  
git add <archivo>             – añade uno o más archivos al área de staging  
git add .                     – añade todos los cambios de la carpeta actual  
git commit -m "mensaje"       – crea un commit con los archivos en staging  
git log                       – muestra el historial de commits  
git branch                    – lista las ramas locales  
git branch <nueva_rama>       – crea una rama nueva  
git checkout <rama>           – cambia a la rama indicada  
git checkout -b <rama>        – crea y cambia a una rama nueva  
git remote add origin <URL>   – (opcional) enlaza un repositorio remoto  
git push -u origin main       – (opcional) sube la rama principal al remoto  
```

