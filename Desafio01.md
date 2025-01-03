# Docker_DevopsPro_Desafio01

docker container run --name postgresql -d -p 3307:5432 -e POSTGRESQL_DATABASE="curso_docker" -e POSTGRESQL_USERNAME="docker-usr" -e POSTGRESQL_PASSWORD="docker_pwd" bitnami/postgresql:latest
