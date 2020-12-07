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