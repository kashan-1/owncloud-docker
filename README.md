# owncloud-docker
This repository contains owncloud deployment with mysql for docker.

## Commands

<!-- a normal html comment -->
``` bash
#This command is used to build and up the docker conainer | first run this command after writing 
#on compose-file.yml

docker-compose up -d --build 
```

``` bash
#This command is used to check the detials of docker container 
#In our case we want to check the IP address of mysql/mariadb container to connect with owncloud
docker inspect image_name/image_ID 
```

``` bash
#This command is used to kill the running container
docker-compose down
```