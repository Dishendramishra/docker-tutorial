# docker-tutorial

## Installing Docker
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-from-a-package


## list docker images
docker images

## list docker containers
docker ps -a

## save changes to a container as a image
docker commit <CONTAINER ID> <name of your choice>

## save image file
docker save <image name> > <name of your choice>.tar

## load a tar image file
docker load < <filename>.tar

## required first to start daemon
sudo dockerd
