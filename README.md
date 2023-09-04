# Tract site/api visit with nodejs and redis (Implemented with docker container)


# Run Node Server (optionl)

- docker build -t YOUR_DOCKER_ID/visits .
- docker run redis


with docker compose

- docker rm -f $(docker ps -aq) [remove all container]
- docker-compose up --build
- docker-compose ps [list]