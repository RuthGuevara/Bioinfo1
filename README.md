# 1.10.3 Plant–Pollinator Networks
Saavedra y Stouffer (2013) estudiaron varios polinizadores de plantas. Estos se pueden representar como matrices rectangulares donde las filas son polinizadores, las columnas plantas, un 0 indica la ausencia y 1 la presencia de una interacción entre planta y polinizador.
## Write a script that takes one of these files and determines the number of rows (pollinators) and columns (plants).
Escriba un script que tome uno de estos archivos y determine el número de filas (polinizadores) y columnas (plantas), tenga en cuenta que las columnas están separadas por espacios y que hay un espacio en al final de cada línea.
### Para realizar el ejercicio 1
 - Necesitamos abrir GitBash. 
 - Ubicamos la ruta de nuestro computador en donde estè la carpeta Saavedra2013 utilizando el codigo "cd Saavedra"
 - Con el terminal Cat n1.txt se imprime el contenido de Saavedra2013
 - Se obtiene el numero de filas y columnas con el codigo echo "El numero de colunmas es: " ; head -n1 n1.txt | grep -o "  "  | wc -l ;  echo  " El numero de filas es: "  ; wc -l n1.txt ;  echo  " Fin de la ejecucion "
 - El numero de columnas es: 80
 - El numero de filas es: 97
 ## [Advanced]
 ## Write a script that prints the numbers of rows and columns for each network:
 Escriba un guión que imprima el número de filas y columnas para cada archivo.
 ### Para realizar el ejercicio 2
 - Necesitamos abrir el directorio de la cartepa Saavedra2013
 - Con el terminal Cat n1.txt se imprime el contenido de Saavedra2013
 - Se ejecuta el codigo git bush
 para  archivo  en  $ ( ls * .txt ) ;  hacer wc -l $ archivo ; head -n1 $ archivo  | grep -o "  "  | wc -l ;  hecho
 - Finalmente se obtienen todos los valores de fila y colunma para los archivos n59.txt 
### SE CREO UNA CARPETA CON LOS RESULTADOS 
