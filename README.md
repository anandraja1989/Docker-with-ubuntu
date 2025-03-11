# Docker-with-ubuntu
Docker commands for personal use

## all docker containers running !!
```bash
docker ps -a       #show all containers
```
## docker pull ubuntu command !!
```bash
docker pull ubuntu:latest   #pull ubuntu latest container
```
## docker show all images !!
```bash
docker images ps -a       #show docker all images
```
## `find` docker running command !!
```bash
docker run -it image id   # image running in docker
```
## docker exec command !!
```bash
docker exec -it image id /bin/bash  # getting into running container
```
## docker image remove cammand !!
```bash
docker rmi -f image id  # remove container image
docker rm container id  # remove container
```
## SSH one container to another container connect command
```bash
sudo apt update
sudo apt install openssh-server
service ssh start
docker inspect d303519f91b4
useradd Rajasekar
passwd ....
ssh username@ ip address  # ssh username and ip address of another container
```

- [x] sample
- [ ] test

