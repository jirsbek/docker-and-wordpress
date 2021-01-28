# Docker and WordPress Example 🐳

## Setup
-

## Access
- `http://localhost:8080` – Website
- `http://localhost:8080/admin/` – Website admin (`admin`/`password`)
- `http://localhost:8000` – PHPMyAdmin


## `docker`
- `docker ps` # Vypíše běžící kontejnery ("process status")
- `docker exec -it name-of-the-container /bin/bash`
- `docker stop [CONTAINER]` # Zastaví běžící kontejner [CONTAINER]
- `docker stop $(docker ps -a -q)` # Zastaví všechny běžící kontejnery

## `docker-compose`
- `docker-compose ps` –
- `docker-compose stop`
- `docker-compose down` # Zastaví a odstraní kontejnery
- `docker-compose up`
- `docker-compose rm` # Odstraní zastavené kontejnery
- `docker-compose exec name-of-the-container /bin/bash`
- `docker-compose build` # Znovu build z Dockerfile

## Images
- `docker images` # Vypíše seznam image
- `docker rmi` # Odstraní image

## Containers
- `docker container ls --all` # Vypíše seznam všech kontejnerů
- `docker container rm [CONTAINER]` # Odstraní kontejner [CONTAINER]

## Volumes
- `docker volume ls`
- `docker volume prune`
