# Helpful Docker/Docker Compose Commands
A list of useful docker commands

| Description        | Command |         
| ------------- |:-------------:|
| List all containers (only IDs)      | ```docker ps -aq``` |
| Stop all running containers | ```docker stop $(docker ps -aq)```|
| Remove all containers| ```docker rm $(docker ps -aq)```|
| Remove all images|```docker rmi $(docker images -q)```|
| Tail and follow last 50 logs|```docker logs --tail 50 -f <container id>```|
| Run containers in background| ```docker-compose up -d```|
