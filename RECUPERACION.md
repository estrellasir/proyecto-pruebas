# Ejercicio de recuperación de archivo borrado
#¿qué error simulé?
cree un archivo llamado errores.sh y accidentalmente lo borré con: rm y realicé un commit de ese error.
#¿Qué comandos usé para recuperarlo?
 git reflog: para ver los commits hechos y ver el de mi archivo borrado.
 git checkout (mi commit)-- errores.sh: para recuperar sólo mi archivo borado sin afectar al resto
#¿Qué aprendistes de la experiencia?
 Aprendí a recuperar archivos borrados porque Git guarda todo el historial y es útil por si ocurre algún error.
