# Docker-Container-Management
The purpose of this proof of concept will be to create and understand docker images, how data persistence works, how to work with communications across bridge networks and Docker networks, and last but not least, probably most important, coordinating containers with docker- compose defining services and their parameters.

First, we'll create a docker image to run the node app. By running the following command in the node project directory, all dependencies will be downloaded and the image will be built.

# docker build -t claudineicaetano/app-node:0.0.1 .