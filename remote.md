# Remote
Esto se refiere a repositorios remotos como Github, con remote podemos acceder a distintos repositorios no hay limite
- git remote
    - Muestra que remotos tenemos
- git remote -v
    - Muestra la URL de los remote
## Añadir remotos
- git remote add <nombre_repositorio> <URL>
    - Ya con añadir el remoto, al subir o enviar los cambios al repositorio remote lo hacemos con su nombre
    - Para subir los archivos se usa git pull <nombre_remote> <nombre_rama>
    - git fech <nombre_remote> 
> La diferencia entre estos dos es que fetch trae los archivos pero los guarda en otra rama la cual no es main (git branch -a) y debemos hacer un merge para añadirlo a la rama que deseemos y pull es un shortcut ya que en donde lo ejecutemos traera los archivos y el merge
## Enviar remote
- git push origin main
    - Este comando envia modificaciones o archivos nuevos al repositorio remoto, cabe mencionar que se enviaran si tienes permisos de escritura de lo contrario se debe realizar un fork
## Inspeccionar un remoto
- git remote show <nombre_remoto>
    - Muestra informacion del remoto sobre la URL, la rama donde se estan guardando los archivos y al final si se esta enviando o no los archivos remotos
## Renombrar y eliminar remotos
- git remote rename <nombre_actual> <nuevo_nombre>
    - Al renombrar un remoto tambien renombramos la ramas remotas
- git remote -rm
    - Se usa cuando ya no queremos utilizarlo, cambiamos de repositorio remoto o algun colaborardor ya no trabajar en el proyecto
