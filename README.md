# **Bitácora-de-Comandos-Sistemas-Operativos-**
|Comando         |Descripción                                                          |Ejemplo        |
|----------------|---------------------------------------------------------------------|---------------|
| adduser | Es para crear un usuario nuevo, se debe usar primero , sudo adduser y luego el nombre del usuario | adduser fcardenasm904 |
| cat | Imprime el contenido del archivo, se utiliza para visualizar el contenido de un archivo  | cat prueba.txt |
| cd | Cambiar directorio o cambiar a otra carpeta, se coloca cd y el nombre de la carpeta | cd carpeta1/ |
| cd .. | Se usa para regresar a la carpeta interior | Antes= fcardenas@ubuntu:-/carpeta1/carpeta$ cd .. Después= fcardenas@ubuntu:-/carpeta1$ |
| chmod | Para asignar o quitar permisos a directorios o archivos | chmod 700 nombre_archivo |
| chown | Para asignar propietarios a carpetas o archivos | chown fcardenasm904 archivo.txt |
| clear | Para limpiar la ventana de la terminal | Después de leer el contenido de un archivo con el comando cat, se utiliza "clear" para limpiar la terminal |
| cp | Comando para copiar archivos, se coloca cp luego el nombre del archivo a copiar y luego el nuevo nombre del archivo | cp [Origen] [Destino] |
| df -h | Permite ver los dispositivos instaladas en el sistema | ![image](https://user-images.githubusercontent.com/114049206/205988502-890c0ec7-c449-4b80-bf2b-99193c27a332.png) |
| echo "pipe" xargs | Sirve para copiar 1 archivo a más de una carpeta | echo -/carpeta1 -/carpeta2 "pipe" xargs -n 1 cp -n nombre del archivo a copiar.txt |
| exit | Nos permite regresarnos al usuario original o cerrar la terminal | si estoy en el usuario fcardenasm904 y cambio a root con sudo su, puedo usar "exit" para regresar al fcardenasm904 |
| find | Sirve para buscar archivos dentro de los directorios según el tipo de extensión del archivo | find . -name “asterisco.extension del archivo que queremos buscar (ejem .jpg, .txt, .png, etc)” |
| find -delete | Borra todos los archivos con la extensión indicada en el comando | find . -name “asterisco.extension del archivo que queremos buscar (ejem .jpg, .txt, .png, etc)” -delete |
| find y cp combinados | Se utiliza para copiar múltiples archivos a un directorio o carpeta a la vez | find -name 'asterisco.log ó .txt' -exec cp -t ~/nombre del directorio o carpeta/ {} + |
| free – h | Me muestra los datos de la memoria RAM y del SWAP | ![image](https://user-images.githubusercontent.com/114049206/205989326-2df061ad-ab71-4c56-a9a8-c5813007b4f9.png) |
| grep -n| Permite buscar en o directorios ciertas palabras o formato | ![image](https://user-images.githubusercontent.com/114049206/205989441-7a9d99b4-d4af-4b60-b405-3125e932f8a2.png) |
| head -n | Colocamos el número de líneas que queremos mostrar y el nombre del archivo | ![image](https://user-images.githubusercontent.com/114049206/205989552-fcbb7a83-e9fa-4bdf-a19a-1b1e3853a98f.png) |
| history | Nos muestra el historial de los comandos que hemos usado | ![image](https://user-images.githubusercontent.com/114049206/205989639-bc38a12b-5816-4f00-922b-1140c445f9f4.png) |
| history "pipe (no agrego el pipe porque me da error en la tabla)" grep y el nombre de un comando | Nos muestra cuantas veces hemos usado ese comando | ![image](https://user-images.githubusercontent.com/114049206/205989918-74f62c48-fd41-475f-9cb4-45d863dfffa1.png) |
| htop | Es otro controlador de procesos, pero más interactivo visualmente | ![image](https://user-images.githubusercontent.com/114049206/205989989-ac396689-d17d-405a-a9ce-f973303d52ae.png) |
| ip a | Nos permite ver la dirección IP de la máquina | ![image](https://user-images.githubusercontent.com/114049206/205990064-223ceb48-7f25-47b8-ae1e-d59b233dd212.png) |
| kill | Sirve para cerrar tareas o aplicaciones abiertas desde la terminal | Se usa el comando kill -9 y el process ID |
| ls | Muestra los archivos o carpetas | ![image](https://user-images.githubusercontent.com/114049206/205990193-61f00b9f-feee-49a9-afa4-feb74018d387.png) |
| ls > “nombre de archivo”.txt | Sirve para copiar el contenido de un comando a un archivo de texto | ![image](https://user-images.githubusercontent.com/114049206/205990797-f5207d41-7ca9-4a8a-a7d0-648ba4191c25.png) |
| ls > nombre del archivo a crear.txt | Me permite copiar la lista de contenidos de un directorio y crear un nuevo archivo de texto | ![image](https://user-images.githubusercontent.com/114049206/205991075-24373c38-4a39-42ac-b7fc-14f272f4d7a9.png) |
| man | Es para abrir un manual para entender como usar los comandos, se debe usar man y luego el nombre del comando a revisar | man cd |
| mkdir | Crea carpetas/directorios nuevos | mkdir carpeta |
| mkdir -p cadena /estructura de directorios | Para crear mas de un directorio (carpetas) con sub directorios (sub carpetas) adentro | ![image](https://user-images.githubusercontent.com/114049206/205991603-85eac8c7-f070-4251-b04c-ad594c73f760.png) |
| more + el nombre de un archivo de texto | Nos imprime el contenido del archivo en pantalla, hace lo mismo que el comando cat y el nombre del archivo, la diferencia es que more nos permite ver archivos que son muy largos | ![image](https://user-images.githubusercontent.com/114049206/205991753-890931b8-d7f1-447b-ab78-d91707f4577f.png) |
| mv | Comando para mover archivos, se coloca mv luego el nombre del archivo a mover y de ultimo el nombre de la carpeta a donde queremos mover el archivo con un slash al final para indicar que es una carpeta | mv copiaHome.txt Documents/ |
| nano | Crea documentos, editor de texto en consola | ![image](https://user-images.githubusercontent.com/114049206/205992010-b22c0aff-7ed8-4c50-9f02-92a688658afb.png) |
| pacman -s | Se usa para instalar aplicaciones o paquetes en Manjaro | sudo pacman -S neofetch |
| ping | Conexión de dos dispositivos | ping 10.8.0.5 |
| ps -aux | Es un visualizador de procesos | ![image](https://user-images.githubusercontent.com/114049206/205992558-7eb9ddf8-bce0-453d-80d0-d32e31472532.png) |
| pstree | Nos muestra los procesos como un árbol | ![image](https://user-images.githubusercontent.com/114049206/205992662-efb86b35-be1b-4b26-b396-1b03b112b43b.png) |
| pwd | Muestra la ruta de un archivo, carpeta, o donde uno esta posicionado | ![image](https://user-images.githubusercontent.com/114049206/205992708-36812cce-5115-4770-b5fe-9498886bae63.png) |
| q | Nos sirve para salir de un comando que ejecuté | Ejecutar htop, luego presion la tecla **q** para salir |
| rm | Sirve para eliminar archivos, se usa rm y el nombre del archivo | rm prueba.txt |
| rm -r | Para remover carpetas, se debe usar el rm -r y luego el nombre de la carpeta | rm -r carpeta/ |
| su – y el nombre de usuario | Para cambiar de usuario | ![image](https://user-images.githubusercontent.com/114049206/205993160-dade3f45-3bed-40c7-8e91-8d43059de4ed.png) |
| sudo | Permite ejecutar cualquier programa como administrador en ubuntu | sudo apt install neofetch |
| sudo apt update | Comando para refrescar los paquetes del sistema | ![image](https://user-images.githubusercontent.com/114049206/205993385-27458ea0-15e6-4e0e-829d-a5049e9671a3.png) |
| sudo apt upgrade | Comando para actualizar el sistema | ![image](https://user-images.githubusercontent.com/114049206/205993619-6d39d029-c9c6-4d80-a01e-5dc138f8bc74.png) |
| sudo dpkg -i y el nombre del archivo .deb | Este comando nos permite instalar archivos .deb que no se encuentran en los repositorios de Ubuntu | ![image](https://user-images.githubusercontent.com/114049206/205993907-f21f9ebc-0d79-4700-8283-f7e10f73a5dd.png) |
| sudo passwd y el nombre de un usuario | Nos permite cambiar la clave de un usuario | sudo passwd fcardenasm904 |
| sudo su | Nos permite cambiarnos al usuario ROOT | ![image](https://user-images.githubusercontent.com/114049206/205994075-09c7edbd-0813-49ab-b32d-a851f710fd24.png) |
| tail -n | “N” es donde colocamos el número de líneas que queremos mostrar y el nombre del archivo | ![image](https://user-images.githubusercontent.com/114049206/205994237-736a3d1c-4bd3-4e85-b26e-0cb92dcc3d71.png) |
| top | Para ver el Controlador de Procesos desde la terminal | ![image](https://user-images.githubusercontent.com/114049206/205994346-f5b2505b-9742-4e71-a5f6-c516b2fa9b98.png) |
| wc | Contar datos | sudo ls /var/spool/squid/00 "pipe" wc |
| unzip / tar -xvf | Descomprimir archivos | unzip mini.zip / tar -xvf carpeta.tar.gz |
| wget | Descargar archivos de una pagina web | wget https://manjaro.org/download/ |
| whoami | Nos dice el usuario en el que estamos conectados | ![image](https://user-images.githubusercontent.com/114049206/205994437-dfd9e23f-1d6c-436c-9d47-6d38b78bcfba.png) |
| zip / tar -czvf | Comprimir archivos | zip mini.zip archivo.txt / tar -czvf carpeta.tar.gz archivo2.txt |
## Notas: 
- En algunos casos se escribió "pipe" y "asterisco" porque al intentar colocar el símbolo me daba error en la tabla o me cambiana el formato
- En otros casos se agregó un símbolo de - en lugar ~ porque subyara la línea
## Comandos DOCKER
|Comando         |Descripción                                                          |Ejemplo        |
|----------------|---------------------------------------------------------------------|---------------|
| docker build | Crea una imagen a partir de un archivo tipo docker |	 |
|docker images|	Imagenes instaladas	|  |
|docker run	| Corre una imagen	docker run ubuntu |  |
|docker ps	| Instancias detenidas o en ejecución	|  |
|docker stop	| Detiene una instancia	sudo docker stop 124f |  |
|docker rm	| Elimina una instancia	docker rm ubuntudock |  |
|docker rmi	| Elimina la imagen	docker rmi ubuntu ubuntu |  |
|docker pull	| Descargar una imagen	docker pull manjaro |  |
|docker container ls -a	| Lista los contenedores	|  |
|docker start	| Inicia los contenedores	|  |
|docker container exec ls	| Ejecutar un comando en el contenedor	docker exec ubuntudock cat /etc/hosts |  |
|docker run -d --name nombre imagen	| Ponerle nombre al contenedor	docker run -d --name dockersito ubuntu |  |
|docker attach CONTAINER	| Entrar a la terminal de un docker	|  |
|docker run -d -p host:contenedor imagen	| Asignar un puerto al contenedor	docker run -d -p 80:40 archlinux |  |
|docker run -d -P imagen	| Puerto random	docker run -d -P manjaro |  |
