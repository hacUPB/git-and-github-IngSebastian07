" Proceso para crear un repositorio remoto en GitHub y sincronizarlo con el local

" Repositorio remoto: copia en la nube de tu proyecto, accesible desde cualquier parte  
" Origin: nombre por defecto que Git asigna al enlace remoto  
" Push: envía tus commits locales al remoto  
" Pull: trae actualizaciones del remoto a tu local  

" 1. En GitHub (web):
"    a) Inicia sesión y ve a https://github.com/new  
"    b) Escribe un nombre para el repositorio (ej. “mi-proyecto”)  
"    c) Opcional: añade descripción, elige público o privado  
"    d) No marques “Initialize with a README” (ya tienes tu repo local)  
"    e) Haz clic en “Create repository”  
"    f) Copia la URL que te muestra (HTTPS o SSH)

" 2. En tu carpeta local (con Git ya inicializado):
cd /ruta/a/mi-proyecto

" 3. Añadir el remoto origin:
git remote add origin <URL-que-copiaste>

" 4. Verificar que origin está apuntando bien:
git remote -v

" 5. Subir tu rama principal al remoto por primera vez:
git push -u origin main
"    Si tu rama se llama master en lugar de main:
"    git push -u origin master

" 6. Trabajando después de la configuración:
git status                    – ver cambios locales
git add .                     – preparar todos los cambios
git commit -m "mensaje"       – guardar cambios localmente
git push                      – enviar nuevos commits al remoto
git pull                      – actualizar tu copia local con los cambios del remoto

