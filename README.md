# Docker-yii framework
Docker  for development in Yii framework 


1. First clone the yii repo inside the folder.

2. Create the runtime folder inside the yii repo. Give full privileges to assets and runtimefolder.

    chmod 777 runtime and
    chmod 777 runtime

3. Inside the docker-yii folder CMD "docker-compose build"

4. After completing the docker build do CMD "docker-compose up"


Important commands: 

1. To check the container is running : sudo docker ps 

2.  To kill the running container : sudo docker kill CONTAINER_ID

3. To run the same container CMD "docker-compose up" inside docker-yii folder. 



## Install docker and docker-compose in MAC 

1. Follow the steps : https://docs.docker.com/docker-for-mac/install/

## Install docker and docker-compose in Ubuntu

1. https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-16-04

2. https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-16-04

## Install docker and docker-compose in WINDOWS 

1. https://docs.docker.com/v17.09/docker-for-windows/install/
