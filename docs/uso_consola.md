Conceptos aprendidos sobre la consola después de algunas clases:

* Ruta actual: indica en qué carpeta estás parado (`pwd`).
* Ruta absoluta vs. relativa:

  * Absoluta: empieza desde la raíz, ej. `/home/usuario/proyecto`
  * Relativa: parte de tu ubicación actual, ej. `../otra_carpeta`
* Directorios vs. archivos:

  * Directorio = carpeta
  * Archivo = documento
* Permisos básicos: necesitas permiso de lectura/escritura para crear, borrar o entrar en carpetas.

Listado de comandos principales:

pwd                  – muestra la ruta actual
ls \[-l] \[-a]         – lista archivos; `-l` detalla, `-a` incluye ocultos
cd <carpeta>         – cambia de directorio
cd ..                – sube un nivel
cd /ruta/completa    – va a una ruta absoluta
mkdir <nombre>       – crea un directorio
touch <archivo>      – crea un archivo vacío
rm <archivo>         – borra un archivo
rmdir <carpeta>      – borra un directorio vacío
rm -r <carpeta>      – borra un directorio con todo dentro
mv <origen> <dest>   – mueve o renombra archivos/carpetas

