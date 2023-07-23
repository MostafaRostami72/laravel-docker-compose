
# docker-compose-laravel
With this repository, you can run Laravel with Docker

## Getting started

### 1 - clone project
```bash
git clone https://github.com/MostafaRostami72/laravel-docker-compose
```


### install docker and docker compose on your os

windows or mac
<br />
https://www.docker.com/get-started/

ubuntu:
<br />
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04
<br />
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04

run docker
```bash
docker-compose up -d --build
```


### Install laravel
```
 cd ./src
 
 docker-compose run --rm composer create-project laravel/laravel .
```


If you have a port error when running, you should edit the docker-compose.yml file of the ports



for use composer or npm or artisan or ... use like this command
```bash
docker-compose run --rm composer
```
