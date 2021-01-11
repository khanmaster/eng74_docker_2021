
# Containerisation with Docker
## What is Docker
### Why Docker
### Demand and future of Docker
### Docker API

- What is docker?
- Docker is an open source platform **docker hub documentation**
- It helps and enables us to separate applications from the infrastructure
- It allows us to deliver software faster
- Docker is written in GO language

## WHY DOCKER
- Multi billion dollar companies are using or adapting Docker i.e Ebay - Netfilx - Sky and many more
- Docker adoption is anticipated by 50% by the end of 2020

### What is the diff between VM and Docker
- Docker is light weight and user friendly
- Docker shares the rescourse of OS as opposed to using the OS completely 
- Docker engine connects the container with OS and only use the resources required

- VM works with Hypervisor to connect guest OS/VM with Host OS/server


# Docker Commands:
- ``` docker pull name_of_image```
- ``` docker run name_of_image```
- ``` docker build -t name_of_image```
- ``` docker commit name_of_image/container-id```

- ``` docker start container-id```
- ``` docker stop conainer-id/name ```
- ``` docker rm container-id/name```
- ``` docker ps and ps -a``` to check the existing containers

### logging into a running container
``` docker exec -it name_of_container/id``i`


### Making docker docs available on our local host 
``` docker run -d -p 4000:4000 docs/docker.github.io```

- **Port mapping in our containers with localhost**
``` docker run -d -p localhost-port:container-port```
``` docker run -d -p 4001:4000 name_of_the_image
