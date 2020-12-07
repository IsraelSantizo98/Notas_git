# --- Amend
Este es un comando que sirve para deshacer cosas, como cuando se realiza un commit o confirmacion con archivos faltantes o con modificaciones sin terminar.
- git commit --amend
    - Sin ejecutamos el comando justo cuando acabamos de comfirmar los cambios entonces podremos cambiar el mensaje, y nos abrira un editor para realizar cambio del mensaje
- git reset HEAD <nombre_archivo> o git restore --staged <nombre_archivo>
    - Al ejecutar este comando lo que hacemos es sacar del area de preparacion o staging el o los archivos seleccionados
- git restore <nombre_archivo> o git checkout -- <nombre_archivo>
    - Retrocede al estado anterior antes de añadir los cambios, eso quiere decir que elimina los cambios nuevos comparado al archivo donde se hizo el ultimo add 