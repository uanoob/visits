# visits

Express server and Redis and Docker and Docker-Compose

# lists running docker containers

docker ps

# lists all docker containers

docker ps --all

# build

docker build -t <dockerID>/<appname> .

# run app

docker run -p 8080:8080 <dockerID>/<appname>

# run app with shell

docker run -it <dockerID>/<appname> sh

# run a command in a running container with shell

docker exec -it <containerID> sh

# run containers with docker-compose

docker-compose up

# build containers with docker-compose

docker-compose build

# run containers with docker-compose in background

docker-compose up -d

# stop containers with docker-compose

docker-compose down

# list running containers with docker-compose

docker-compose ps
