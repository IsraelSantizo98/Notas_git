# Log
- git log -p muestra los cambios que hemos realizado en cada archivo
- git log -2 muestra los ultimos dos commits
- git log --stat muestra las estadisticas de cada commit
- git log --pretty=<oneline, short, full, fuller> sirven para modificar el estilo de la salida en consola
- git log --pretty=format"%h - %an, %ar : %s" sirve para personalizar la salida de informacion en consola
- git log --pretty=format:"%h %s" --graph
- git log --since=2.weeks sirve para especificar la fecha de busqueda de commits
    - git log --since="2021-12-01"
    - git log --since="1 day"
- git log -S<texto clave> se usa para buscar una cadena especifica en los commits
- git log --author="Israel" busca por nombre de autor
## Tabla con opciones de git log pretty=format
![Imgur](https://imgur.com/R3Nl6fm.png "Tabla 1")
## Opciones para formteo de salida
![Imgur](https://imgur.com/oWvp4mu.png "Tabla 2")
## Opcines para limitar la salida de la terminal de git
![Imgur](https://imgur.com/pzmONdn.png "Tabla 3") 
> Tabla 3   