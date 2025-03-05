# -mi-primer-repositorio
resumen
es como una caja fuerte para guardar tu código, pero también una herramienta para trabajar en equipo sin enredos. Te deja hacer cambios sin miedo, probar ideas en paralelo y regresar si
algo sale mal.
Puedes colaborar con otros, proponer mejoras y automatizar tareas aburridas. Es el punto de encuentro de programadores de todo el mundo, donde nacen y crecen miles de proyectos.
Aquí tienes un listado con los comandos más importantes de Git y su función:  
Configuración y estado 
git config --global user.name "Tu Nombre" → Configura tu nombre en Git.  
git config --global user.email "tu@email.com" → Configura tu correo.  
git status → Muestra el estado de los archivos (cambios, nuevos, etc.).  
Inicialización y clonación  
git init → Crea un nuevo repositorio en la carpeta actual.  
git clone URL_DEL_REPO → Descarga un repositorio existente.  
Trabajando con cambios  
git add → Agrega todos los cambios al área de preparación.  
git commit -m "Mensaje" → Guarda los cambios con un mensaje descriptivo.  
git diff` → Muestra las diferencias entre cambios no confirmados.  
git log → Muestra el historial de commits.  
Ramas y versiones
git branch → Muestra las ramas disponibles.  
git branch nombre-rama → Crea una nueva rama.  
git checkout nombre-rama → Cambia a otra rama.  
git merge nombre-rama → Une una rama con la principal.  
git rebase nombre-rama → Reaplica cambios de una rama sobre otra. 
Trabajo en equipo  
git remote -v → Muestra los repositorios remotos vinculados.  
git pull origin main → Descarga los cambios más recientes del repositorio remoto.  
git push origin main → Sube tus cambios al repositorio remoto.  
Revertir cambios
git reset --hard HEAD → Revierte todos los cambios no confirmados.  
git checkout -- archivo → Deshace cambios en un archivo específico.  
git revert ID_DEL_COMMIT → Revierte un commit sin perder el historial.  
Eliminación y limpieza
git rm archivo → Elimina un archivo del repositorio.  
git clean -f → Borra archivos no rastreados.  
