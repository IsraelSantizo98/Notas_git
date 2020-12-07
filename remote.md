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