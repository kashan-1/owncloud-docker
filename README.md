# owncloud-docker
This repository contains owncloud deployment with mysql for docker.

## Commands

This command is used to build and up the docker conainer | first run this command after writing on  <mark>compose-file.yml</mark>

``` bash
docker-compose up -d --build 
```

This command is used to check the details of <mark>docker container</mark>
In our case we want to check the <mark>IP address of mysql/mariadb</mark> container to connect with owncloud

``` bash
docker inspect image_name/image_ID 
```
This command is used to enter in container | in our case we want to enter in db container to create <mark>database</mark>
``` bash
docker exec -it container_name bash
```
``` bash
msql -uroot -p 
```
<mark>enter password root</mark>
``` bash
create database mydb;
```
This command is used to kill the running container
``` bash
docker-compose down
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.