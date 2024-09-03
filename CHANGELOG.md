# CHANGELOG

## 1. Dockerfile
The Dockerfile includes steps to deploy the *housing-api* as well as the dependencies needed to run the code. Apart from the python base image it also downloads *Poetry* to manage dependencies required within the container by the application. Finally it exposes port 3000 to act as an entry point for the application

## 2. docker-compose.yml
Changed the *housing-api* service to use the above `Dockerfile` to run the service and migrated dependencies from the `docker-compose.yml` to the `Dockerfile` to decouple housing-api deployment from the database.