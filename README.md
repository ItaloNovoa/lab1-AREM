# lab1 de arem (media y desviacion estandar)
#
### este proyecto se encarga de ofrecer operaciones basicas para el manejo de datos a travez de un likendList 
#
### Clases
#
#### Menu --> es la clase con la que actua el usuario. por defecto lee el archivo entrada.txt en el cual podra ingresar los valores al cual el programa le sacara la media y la desviacion estandar
#
##### Si desea que el programa lea otro archivo en otra ubicacion, modificarlo en la clase menu en la variable que se muestra a continuacion:
![image](https://user-images.githubusercontent.com/42522754/63237434-93199e00-c207-11e9-908c-60670a9050b0.png)



#
#### likendList --> esta clase implementa la funcionalidad de una lista enlazada
#
#### nodo --> esta lista ayuda a complementar la implementacion de la lista enlazada por medio de los nodos declarados en esta clase
#
## ¿Como ejecutar el archivo?
#### dado que este es un provecto mvn, una forma de compilar y poder acceder al menu antes hablado se recomienda seguir los siguientes pasos:
##### 1. Descargar el proyecto
##### 2. Ingresar a la cmd o simbolo del sistema
##### 3. Dentro de la cmd ingresar a la ubicacion en la cual esta el proyecto
##### 4. digitar el siguiente codigo 'mvn compile'
##### 5. y finalmente digitamos 'mvn exec:java -D exec.mainClass="edu.escuelaing.arem.lab1.app.menu"'
# pruebas
##### para poder ejecutar las pruebas se sigue hasta el paso 3 de ¿Como ejecutar el archivo? " en caso de no estar ya ubicado en la terminal,cmd o simbolo del sistema y digitar "mvn package"
