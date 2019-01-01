# Angular7 Deploy Production in Docker

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.0-rc.0.

## Clone Repository
git clone https://github.com/sutin1234/angular7-deploy-docker.git

## build image in docker

docker build --rm -f "Dockerfile" -t angular7-deploy-docker:latest .

## run images with map port in docker
docker run -d -p 8888:80 angular7-deploy-docker

## see images build
docker ps

## Serve in browser
http://localhost:8888
