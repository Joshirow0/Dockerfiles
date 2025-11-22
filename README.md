## Description
Dockerfiles that I use in my personal server (rasp5). For backup and share c:
Use the containers that you need.

## Estructure
- Each directory have its own `docker-compose.yml` and `.env.template` when it's necessary.
- Read the `docker-compose.yml` file of each containter that you will use; there may be variables that you may need to change.

## Requirements
- Docker and Docker compose installed.

## Quick set up
1. Move to the service that you want:
   - cd service-folder/
2. Edit and rename .env ; if there is one:
   - cp ./.env.template ./.env
3. Start a service:
   - docker compose up -d
4. Stop service:
   - docker compose down

### Aclaration
- the minecraft server was made just for fun and to learn how to make a Dockerfile c: