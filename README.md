
# Docker Cheat File

Contain all the cheat for using Docker

## Deployment

To install docker 

```bash
  sudo apt-get install docker.io
```

To change the USER mode

```bash
  sudo usermod -aG docker $USER
```
To Refresh Docker

```bash
  newgrp docker
```
To check if the docker is running or not

```bash
  sudo systemctl status docker
```
To check the container running

```bash
  docker ps
```
To check the container running or exited

```bash
  docker ps -a
```
To Pull image from the docker hub

```bash
  docked pull image_name
```
To create the container from the image                                               

```bash
  docker run image_name
```
To run the container in a detached mode.                                             

```bash
  docker run -d image_name
```
To remove the container and image                                              

```bash
  docker rm container_ID
  docker rmi image_name
```
To remove the container after stopping it

```bash
  docker run -d --rm -name The_name, caontainer_name
```
To stop and start the docker                                            

```bash
  docker start name_container
  docker stop name_container
```

