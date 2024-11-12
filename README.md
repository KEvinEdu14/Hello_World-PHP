# PHP Project

This is a simple PHP project that prints "Hola Mundo" to the browser.

## Technologies Used
- Language: PHP
- Container: Docker

## Prerequisites
- Docker installed
- PHP installed locally (optional for direct execution without Docker)

## Project Files
- *index.php*: Main file of the project that prints "Hola Mundo" to the browser.
- *Dockerfile*: Docker file for building the Docker image.

## Create Docker Image

Run the following command in the project directory:
~~~
docker build -t kevineduardo14/helloworldphp .
~~~
## Run the Docker Container
~~~
docker run kevineduardo14/helloworldphp
~~~

##Login the Docker Hub
~~~
docker login
~~~
## Docker Desktop pull in Docker Hub
~~~
docker pull kevineduardo14/helloworldphp
~~~

## Imagen in Docker Hub

https://hub.docker.com/repository/docker/kevineduardo14/helloworldphp/general

# RailWay
We log in and link to GitHub to deploy the repositories.
