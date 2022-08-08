# Read Me First


## Build the app using gradle tasks *build* and *jar*

## Docker your java app

``docker build --build-arg JAR_FILE=build/libs/spring-boot-docker-0.0.1-SNAPSHOT.jar -t 712900013610/spring-rest .``

## Run your docker 

L'image existe sur DockerHub en publique, il est possible de la run avec la ligne de commande : 

``docker run -p 8080:8080 712900013610/spring-rest``

ou bien à travers le fichier *docker-compose.yml* avec la commande 
 
``docker compose up``

### La présentation se trouve à la racine du projet