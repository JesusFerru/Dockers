Descargar Docker en Máquina virtual
    
    *apt-get install docker.io

Comandos Básicos
    docker
    docker image ls	( docker images ) //ver imagenes del docker
    docker ps 		//Ver procesos del docker
    docker ps -a 		//Ver procesos o contenedores del docker, pero los ve todos
    docker pull ubuntu	// Baja la imagen (en este ejemplo de ubuntu) de la libreria en la nube
    docker run --name ubu1 --hostname ubu01 -ti ubuntu:latest /bin/bash		//ejecuta

(-ti) //ingresa al modo interactivo, si no se coloca solo lo ejecuta