# Docker and WordPress Example 🐳

## Setup
- https://www.docker.com/get-started

## Access
- `http://localhost:8080` – Website
- `http://localhost:8080/admin/` – Website admin (`admin`/`password`)
- `http://localhost:8000` – PHPMyAdmin

## `docker-compose`
Používáme v adresáří, kde je umístěna konfigurace `docker-compose.yml`
- `docker-compose up` # Spuštění kontejnerů
- `docker-compose stop` # Zastavení kontejnerů
- `docker-compose down` # Zastaví a odstraní kontejnery
- `docker-compose ps` # Vypíše kontejnery v adresáři ("process status")

- `docker-compose rm` # Odstraní zastavené kontejnery
- `docker-compose exec name-of-the-container /bin/bash`
- `docker-compose build` # Znovu build z Dockerfile

## `docker`
- `docker ps` # Vypíše běžící kontejnery ("process status")
- `docker exec -it name-of-the-container /bin/bash`
- `docker stop [CONTAINER]` # Zastaví běžící kontejner [CONTAINER]
- `docker stop $(docker ps -a -q)` # Zastaví všechny běžící kontejnery

## Images
- `docker images` # Vypíše seznam image
- `docker rmi` # Odstraní image

## Containers
- `docker container ls --all` # Vypíše seznam všech kontejnerů
- `docker container rm [CONTAINER]` # Odstraní kontejner [CONTAINER]

## Volumes
- `docker volume ls`
- `docker volume prune`
