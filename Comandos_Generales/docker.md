# Docker
## Descargar Docker en Máquina virtual
    
    apt-get install docker.io

## Comandos Básicos

        docker
* Ver imagenes del docker
        
        docker image ls
        docker images

* Ver procesos del docker
        
        docker ps 

* Ver procesos o contenedores del docker, pero los ve todos
        
        docker ps -a

* Baja la imagen (en este ejemplo de ubuntu) de la libreria en la nube
        
        docker pull ubuntu	

* Ejemplo de ejecución

        docker run --name ubu1 --hostname ubu1 -ti ubuntu:latest /bin/bash		

    * (-ti) //ingresa al modo interactivo, si no se coloca solo lo ejecuta
    * <repository:tag> : **repository** es la imagen que se esta usando, mientras que **tag** representa la versión de la imagen que se este usando. Ejemplo *ubuntu:lastest*


## Comandos de Ejecución de un Docker

docker start ubu1
docker stop ubu1
docker restart ubu1
docker inspect ubu1 | less
docker exec -ti ubu1