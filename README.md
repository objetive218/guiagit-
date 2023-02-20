# guiagit-

Bienvenidos a esta guia sobre como subir repositorios a git.

crearemos un repositorio en git preferiblemente con el mismo nombre de la carpeta de la cual queremos hacer un repositorio.
seguido de esto damos clic derecho sobre la carpeta seleccionada y buscamos la opcion "git bash here" y colocamos nuetro primer comando:
![image](https://user-images.githubusercontent.com/109116521/220129559-65794683-b80d-4cba-91b6-e3fbd1b29cff.png)

1.git init -- este comando incializa el repositorio.

2.git remote add origin (url del repositorio en este caso lo que sale en github llave ssh)
![image](https://user-images.githubusercontent.com/109116521/220127194-c51d2970-806b-40a6-aa67-3ba59350e2a0.png)

3.git fecht origin main --este comando sincroniza con el reposito, revisa el repositorio local , luego en la nube y me avisa si hay archivos que estan
en un lado pero no en el otro. 

4.git pull origin main --este comando se trae lo que hace falta desde el repositorio.

5.git add . -- este comando selecciona todos los archivos dentro de la carpeta.

6.git commit -m "mensaje " -- este comando deja listo todos lo archivos para subirlos a git, en la parte de mensaje colocaremos informacion relevante segun el tipo de commit enviado, por ejemplo "primer commit" o "tercera correccion"

7.git push -u origin main -- este commando sube los archivos a git.

---------------------------------------------------------------------------------------------------------------------------


seguiremos estos pasos cuando queramos modificar los archivos:

 nos situaremos en la carpeta la cual buscamos subir a git y damos clic derecha en ella seguidamente buscamos "git bash here"
 ![image](https://user-images.githubusercontent.com/109116521/220129512-45c0d512-d702-49d4-befe-bf61e26948ea.png)
seguido de esto usaremos nuestro primer comando:
1 - git fetch origin main --este comando sincroniza con el reposito, revisa el repositorio local , luego en la nube y me avisa si hay archivos que estan
en un lado pero no en el otro.

2 - git pull origin main --este comando se trae lo que hace falta desde el repositorio.

3 - git add . -- este comando selecciona todos los archivos dentro der la carpeta seleccionada.

4 - git commit -m "primer cambio" - este comando alista todos los archivos y los deja listos para enviar.

5 - git push -u origin main -- este comando sube los archivos al repositorio de git. 


muchas gracias por leer :)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
