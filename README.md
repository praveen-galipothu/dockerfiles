### Dockerfiles 

Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.
file name should be Dockerfile
### How to build docker image from Dockefile
docker build -t [docker-hub-url]/[your-username]/[image-name]:version .

### How to push image to docker hub
docker push [docker-hub-url]/[your-username]/[image-name]:version 