## Comandos comunes
1. **git config (--global) user.name "usuario"** = Para configurar el nombre del usuario que va a trabajar en el repo, puede ser global o solo dentro del entorno del repo.
2. **git config (--global) user.email "correo"** = Para configurar el correo de la persona qye va a trabajar en el repo, puede ser global o solo dentro del entorno del repo.
3. **git config (--global) alias.nombreAlias "comando Git"** = Comando para configurar un acceso directo a algun comando que nos tome mucho escribir.
4. **git init** = Inicializa un repositorio local.
5. **git status** = Para ver el estado del repositorio local.
6. **git add (archivo o .)** = Para agregar al area de pre-commit todos los archivos con los que hemos trabajado o solo los que deseemos.
7. **git commit -m "mensaje del commit"** = Para crear un commit junto un mensaje que lo ayude a identificar.
8. **git log** = Para ver el historial de commits que hemos realizado en el repo local.
9. **git checkout** =
   1. Para restaurar el estado original del commit realizado anteriormente. **git checkout** --> Se realiza en el commit en donde queremos restaurar el estado original del mismo.
   2. Para situarnos a un commit en especifico. **git checkout (hash)**
10. **Archivo ".gitignore"**= Archivo para indicar que files no seran tenidos en cuenta por Git. Esto a la hora de realizar commits.
11. **git diff**= Para ver los cambios que hemos realizado en comparacion con el commit mas reciente. O tambien funciona para comparar cambios entre ramas.
12. **git reset + hash** = Es como resetear el flujo de git indicando en que commit deseamos posicionarnos, lo cual tomara como el commit mas reciente y no se vera lo que este adelante de este, pero no los elimina.
13. **git reflog**= Es muy similar a **log** pero muestra mucha mas informacion de nuestro flujo de trabajo.
14. **git tag + nombreTag** = Es para asignarle un tag "nombre" a cualquier commit que deseemos y acceder a este.
15. **git stash**= Para guardar temporalmente cambios que aun no estan listos para ser agregados ni commiteados.
    1. **git stash list**= Para ver la lista de stash guardados temporalmente.
    2. **git stash pop**= Restaurar el ultimo estado guardado.
    3. **git stash drop**= Elimina los cambios temporales que tengamos guardados.


## Ramas
1. **git branch + nombreNuevaRama**= Es para crear una nueva rama basada en donde estemos. (se trae esos cambios).
2. **git branch**= Para ver todas las ramas del repositorio local.
3. **git switch + nombreRama**= Para cambiar a una rama especifica.
4. **git merge + nombreRamaUnir**= Para unir la rama en donde estemos a una que se le indique.
5. **git branch -d nombreRamaBorrar**= Para eliminar una rama especifica. Es importante realizar un merge antes.


## Git and GitHub
1. **git remote add origin + urlRepo**= Es para asociar al repositorio local un repositorio remoto "con la URL".
2. **git push origin "ramaSubir"**= Es para empujar los cambios que se han realizado en el repositorio local al remoto.
3. **git fetch**= Es para traer el historial que existe de forma remota a forma local, solo el **historial (log)**.
4. **git pull**= Similar al fetch, pero este si obtiene los cambios que estan en el **repo remoto** en el repo local. No solo los cambios.
   



    

