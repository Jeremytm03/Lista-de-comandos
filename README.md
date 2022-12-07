# Lista-de-comandos-LINUX
|Comandos| Descipción| Ejemplos|
|-------|-----------|---------|
|sudo |permite actuar como superusuario o usuario root mientras ejecutas un comando específico.  |sudo apt install *aplicacion* |
|sudo apt update |actualiza la lista de paquetes disponibles y sus versiones, pero no instala o actualiza ningún paquete. |sudo apt update |
|sudo adduser |Agrega un usuario | |
|sudo apt updgrade |este busca y baja los nuevos paquetes que haya disponibles para poner nuestra distro al día. |sudo apt updgrade |
|pwd |se usa para mostrar el nombre de su directorio actual, lo que puede ser útil al navegar por el sistema de archivos. |pwd |
|cd |se usa para cambiar el directorio de trabajo actual de un usuario.  |cd *carpeta* |
|ls |Se utiliza para enumerar archivos y directorios en sistemas operativos Unix y similares a Unix, incluido Linux. |ls -la |
|nano |crea  un archivo |nano helloworld.txt |
|more |muestra el conteido de archivos de texto grandes |more *archivo* |
|cat |se usa para mostrar lo que hay dentro de un archivo de texto. |cat *archivo.txt* |
|cp |se utiiliza para copiar archivos o directorios a otro directorio |cp foto.jpg public_html/imagenes/ |
|tail |Imprime las últimas líneas que se especifiquen en un archivo |tail [parámetros] <archivos> |
|mv |se usa para mover y renombrar archivos. |mv foto.jpg nombrecambiado.jpg |
|mkdir |se usa para crear directorios y subdirectorios que son una parte integral del sistema operativo Linux.  |mkdir /home/imagenes |
|rmdir |se usa para eliminar un directorio vacío y su contenido del sistema de archivos. |rmdir *carpeta* |
|rm |se usa en sistemas Linux para eliminar archivos y directorios. |rm imagen.jpg |
|locate |se utiliza para buscar archivos en la computadora, la red o Internet.  |locate archivo.txt |
|grep |Se utiliza para encontrar patrones en un archivo o en el sistema. |grep texto archivo.txt |
|chmod |se usa para cambiar los permisos de un archivo. Los permisos están representados por letras, y cada letra representa un tipo diferente de acceso. |chmod 755 archivo.jpg |
|chown |se usa para extraer y archivar archivos |chown -R usuario:grupo carpeta |
|ps |se utiliza para listar los procesos que se ejecutan en el sistema. |ps -a |
|kill |Se puede utilizar para eliminar procesos en ejecución, enviar señales a procesos en ejecución o finalizar todos los procesos asociados con un usuario determinado. |kill colorpd |
|wget |se usa para descargar archivos de internet |wget http://ejemplo.com/programa.tar.gz |
|uname |muestra información sobre el sistema, como el nombre del kernel, el nombre del host, el sistema operativo, la fecha de lanzamiento y la versión. |uname |
|echo |sirve para la impresión de un texto en pantalla. |echo "Hola Mundo" |
|zip |este comando sirve para comprimir archivos |zip archivocomprimido.zip archivo1 |
|unzip |eset comadno sirve para descomprimir archivos |unzip archivocomprimido.zip |
|vi |vi es el editor de modo de texto de linux, funciona para ingresar y crear archivos de texto |vi archivo.txt |
|exit |sirve para salir del modo root o de la terminal en si  |exit |
|clear |Limpia la pantalla de la terminal |clear |
|ip a |Muestra la direccion ip de la máquina |ip a |
|history |	Muestra el historial de todos los comandos que hemos usado |history |
# Lista-de-comandos-DOCKER
|Comandos| Descipción| Ejemplos|
|-------|-----------|---------|
|sudo yay -S --needed base-devel|Muestra el repositorio core |36,0 k |
|docker images|visualizar las imagenes descargadas |images docker: ubuntu, Id:60987653 |
|docker search|Busca en el repositorio de Docker Hub una imagen con ese nombre|docker search ubuntu |
|docker pull|Descarga la imagen del contenedor | docker pull ubuntu:latest|
|docker run|Ejecuta un nuevo contenedor usando una imagen|docker run ubuntu |
|sudo docker ps -a| observar el estado actual de los contendeores |contendor up 17min ago, contendor2 exited |
|sudo  docker start |inicializa un contendor detenido | sudo docker start cinnamonCandy (nombre del contenedor) |
|sudo  docker stop| detiene un contenedor en estado run |sudo docker stop cinnamonCandy |
|docker rmi image|Elimina una imagen dentro de docker|docker rmi image ubuntu |
|docker rmi image + ID|elimina un contenedor |docekr rmi 8765rt |
|docker run --rm + imagen|Elimina una imagen de un contenedor que ya fue cerrado |docker run --rm ubuntu |
|docker networ ls|Conocer la red de docker |NETWORK ID, Name, driver and scope |
|vim Dockerfile|crear un archivo Docker |vim Dockerfile 1|
|FROM|Indica la imagen sobre que se ejeuta el contenedor |FROM ubuntu |
|RUN|indica los comandos a ejecutar |RUN echo "Hello world" |
|ADD|añade elementos |ADD ficheros /index.html |
|:wq|Guardar un archivo vim y sale del archivo |vim Dockerfile 1 <ctrl o> :wq|
# Lista-de-comandos-MABJARO
|Comandos| Descipción| Ejemplos|
|-------|-----------|---------|
|sudo pacman -Syy|Actualizar el sistema |sudo pacman -Syy|
|sudo pacman -S| Instalación de un programa en manjaro|sudo pacman -S paquete|
|sudo pacman -Scc| Limpiar el sitema en manjaro|sudo pacman -Scc: emepieza a limpira cache y demás basura|
|pacman -R|Elimina el paquete que se indique en manjaro |pacman -R (paquete)|
|pacman -Q|Muestra los paquetes instalados|pacman -Q|
|yay -S google-chrome|instala google chrome | yay -S google-chrome|
|sudo pacMan -S apache|instala apache |nano /svr/html/index.html|
|neofetch| muestra infromación del SO| neofetc|
|sudo pacman -S unrar zip unzip p7zip gzip bzip2 | instala zip| zip students.txt |


































































































