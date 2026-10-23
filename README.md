
#Laboratorio: archivos y recuperacion en Rocky Linux

#Objetivo: ## hacer copia de los archivos importantes y recuperar la
##	informacion desde el archivo copia despues de modificar el 
##	archivo original.

# entorno utilizado: ## estamos en una VM de Rocky Linux, en la que
##	trabajamos desde una macbook pro, y hemos creado una carpeta
##	para realizar nuestra practica y unos archivos ficticios
##	en los que desarrollamos el proceso satisfactoriamente 
##	entendiendo como funciona el sistema, algunos comandos basicos
##	como el cd, ls, cat, nano, mkdir, echo, cp. y tambien 
##	aprendimos la diferencia entre el printf y el echo.
##	vale aclarar que nos conectamos a la VM por medio de la terminal
##	de la mac con el comando ssh usuario@ip


# practicas realizadas: ## realizamos copia de un archivo llamado ventas.txt
##	y a ese archivo le hicimos una copia, el archivo original tenia
##	informacion de unas ventas ficticias y un valor en euros,
##	despues de hacer la copia, modificamos el archivo y en tema de
##	ejercicio teniamos que volver a la version anterior, entonces 
##	lo que hicimos fue cp copia_ventas.txt ventas.txt y asi la
##	informacion quedo restaurada la informacion que habia en 
##	ventas.txt

# como comprobe la recuperacion : ## fue muy sencillo, al no ser tanta 
##	informacion la que habia en el archivo, al leer el archivo
##	restaurado con cat ventas.txt nos pudimos dar cuenta que la 
##	restauracion habia sido un exito.

# limitaciones: ## en realidad no tuvimos limitaciones, ya que se trataba
##	de comandos que ya tenia conocimiento, asi que por suerte
##	pude hacerlo de manera sencilla.

##	una de las limitaciones que podemos tener al necesitar hacer
##	restauracion de archivos, es no tener copias de seguridad
##	fuera de la VM, o de la computadora en la que estamos trabajando
##	por eso hay que tener en cuenta tener copias de seguridad
##	y realizar backups periodicamente, dependiendo de la necesidad
##	de la empresa o negocio.
