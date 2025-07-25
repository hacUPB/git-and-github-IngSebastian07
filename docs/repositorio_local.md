### Conceptos aprendidos sobre cómo crear un repositorio local con Git.

* **Repositorio local:** carpeta que guarda el historial de cambios de tu proyecto  
* **Staging area (índice):** espacio temporal donde añades cambios antes de guardarlos  
* **Commit:** punto de control que guarda el estado actual de los archivos añadidos  
* **Rama (branch):** línea de desarrollo independiente dentro del mismo repositorio  
* **HEAD:** indicador de la rama y commit en el que estás trabajando  

### Listado de comandos principales:

* (`git init`) inicializa un repositorio Git en la carpeta actual.
* (`git status`) muestra el estado de archivos (modificados, sin seguimiento)  
* (`git add`) añade uno o más archivos al área de staging.  
* (`git ad .`) añade todos los cambios de la carpeta actual.
* (`git commit -m "mensaje"`) crea un commit con los archivos en staging.
* (`git log`) muestra el historial de commits. 
* (`git branch`) lista las ramas locales.  
* (`git branch <nueva rama>`) crea una rama nueva.  
* (`git check out <rama>`) cambia a la rama indicada. 
* (`git checkouot -b <rama>`) crea y cambia a una rama nueva.  
* (`git remote add origin <URL>`) enlaza un repositorio remoto.   
* (`git push -u origin main`) sube la rama principal al remoto.
---
![En esta imagen se observan los comandos nombrados anteriormente de una manera más organizada](<Comandos repositorio local.png>)
