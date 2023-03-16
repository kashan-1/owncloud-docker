# owncloud-docker
This repository contains owncloud deployment with mysql for docker.

## Commands

This command is used to build and up the docker conainer | first run this command after writing on compose-file.yml
``` bash
docker-compose up -d --build 
```

This command is used to check the detials of docker container 
In our case we want to check the IP address of mysql/mariadb container to connect with owncloud

``` bash
docker inspect image_name/image_ID 
```

``` bash
#This command is used to kill the running container
docker-compose down
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.