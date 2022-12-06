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
| echo -/carpeta1 -/carpeta2 | xargs -n 1 cp -n nombre del archivo a copiar.txt | Sirve para copiar 1 archivo a más de una carpeta |  |
| exit | Nos permite regresarnos al usuario original |  |
| find . -name “asterisco.extension del archivo que queremos buscar (ejem .jpg, .txt, .png, etc)” | Sirve para buscar archivos dentro de los directorios según el tipo de extensión del archivo |  |
| find . -name “asterisco.extension del archivo que queremos buscar (ejem .jpg, .txt, .png, etc)” -delete | Borra todos los archivos con la extensión indicada en el comando |  |
| find -name 'asterisco.log ó .txt' -exec cp -t ~/nombre del directorio o carpeta/ {} + | Se utiliza para copiar múltiples archivos a un directorio o carpeta a la vez |  |
| free – h | Me muestra los datos de la memoria RAM y del SWAP |  |
| grep | Permite buscar en o directorios ciertas palabras o formato |  |
| head -n | Colocamos el número de líneas que queremos mostrar y el nombre del archivo |  |
| history | Nos muestra el historial de los comandos que hemos usado |  |
| history "pipe (no agrego el pipe porque me da error en la tabla)" grep y el nombre de un comando | Nos muestra cuantas veces hemos usado ese comando |  |
| htop | Es otro controlador de procesos, pero más interactivo visualmente |  |
| ip a | Nos permite ver la dirección IP de la máquina |  |
| kill | Sirve para cerrar tareas o aplicaciones abiertas desde la terminal, se usa el comando kill -9 y el process ID |  |
| ls | Muestra los archivos o carpetas |  |
| ls > “nombre de archivo”.txt | Sirve para copiar el contenido de un comando a un archivo de texto |  |
| ls > nombre del archivo a crear.txt | Me permite copiar la lista de contenidos de un directorio y crear un nuevo archivo de texto |  |
| man | Es para abrir un manual para entender como usar los comandos, se debe usar man y luego el nombre del comando a revisar |  |
| mkdir | Crea carpetas/directorios nuevos |  |
| mkdir -p cadena /estructura de directorios | Para crear mas de un directorio (carpetas) con sub directorios (sub carpetas) adentro |  |
| more + el nombre de un archivo de texto | Nos imprime el contenido del archivo en pantalla, hace lo mismo que el comando cat y el nombre del archivo, la diferencia es que more nos permite ver archivos que son muy largos |  |
| mv | Comando para mover archivos, se coloca mv luego el nombre del archivo a mover y de ultimo el nombre de la carpeta a donde queremos mover el archivo con un slash al final para indicar que es una carpeta |  |
| nano | Crea documentos, editor de texto en consola |  |
| pacman -s | Se usa para instalar aplicaciones o paquetes en Manjaro |  |
| ping | Conexión de dos dispositivos | ping 10.8.0.5 |
| ps -aux | Es un visualizador de procesos |  |
| pstree | Nos muestra los procesos como un árbol |  |
| pwd | Muestra la ruta de un archivo, carpeta, o donde uno esta posicionado |  |
| q | Nos sirve para salir de un comando que ejecuté |  |
| rm | Sirve para eliminar archivos, se usa rm y el nombre del archivo |  |
| rm -r | Para remover carpetas, se debe usar el rm -r y luego el nombre de la carpeta |  |
| su – y el nombre de usuario | Para cambiar de usuario |  |
| sudo | Permite ejecutar cualquier programa como administrador en ubuntu |  |
| sudo apt update | Comando para refrescar los paquetes del sistema |  |
| sudo apt upgrade | Comando para actualizar el sistema |  |
| sudo dpkg -i y el nombre del archivo .deb | Este comando nos permite instalar archivos .deb que no se encuentran en los repositorios de Ubuntu |  |
| sudo passwd y el nombre de un usuario | Nos permite cambiar la clave de un usuario |  |
| sudo su | Nos permite cambiarnos al usuario ROOT |  |
| tail -n | “N” es donde colocamos el número de líneas que queremos mostrar y el nombre del archivo |  |
| top | Para ver el Controlador de Procesos desde la terminal |  |
| wc | Contar datos | sudo ls /var/spool/squid/00 "pipe" wc |
| unzip / tar -xvf | Descomprimir archivos | unzip mini.zip / tar -xvf carpeta.tar.gz |
| wget | Descargar archivos de una pagina web | wget https://manjaro.org/download/ |
| whoami | Nos dice el usuario en el que estamos conectados |  |
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
