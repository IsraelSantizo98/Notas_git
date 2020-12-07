# Etiquetas
Estas sirven para marcar puntos especificos en la historia de nuestros archivos
## Ver etiquetas
+ git tag
    - Muestra que tag tenemos guardadas, este comando lo lista en forma alfabetica
+ git tag -l 'v0.1'
    - Muestra todos los tag con v0.1
## Crear etiquetas
+ git tag -a V0.1 -m "Firts version 0.1"
+ git show v0.1
    - Muestra que archivos tienen la etiqueta v0.1
## Etiquetas ligeras
+ git tag v0.1-lw
    - Este comando solo hace referencia al commit seleccionado y se añade lw para indicar que es una etiqueta ligera
## Etiquetas un commit ya antiguo en la historia
+ git tag -a v0.11 <id_commit> -m "Mensaje"
## Enviar etiquetas al remoto
+ git push origin v0.1
    - Enviar una etiqueta a la 
+ git push <nombre_remote> --tags
## Eliminar una etiqueta
+ git tag -d <nombre_tag>
+ git push origin --delete <nombre_etiqueta>
## Hacer cambios y ver el estado de un tag
Con esto podemos modificar o eliminar commits ya que crea un rama experimental, al final tenemos dos opciones o regresar a la historia mas actual (main) o hacer una rama para hacer este ultimo se debe escribir git switch -c <nombre_rama>
+ git checkout <nombre_tag>