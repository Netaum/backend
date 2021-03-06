# Configurando o ambiente de desenvolvimento

## Docker

A maneira mais fácil de começar a desenvolver é utilizar o Docker como base para o projeto.

- [docker](https://docs.docker.com/get-docker/)
- [docker-compose](https://docs.docker.com/compose/gettingstarted/)

Tenha certeza que o docker está instalado na sua máquina (comando `docker -v`), juntamente com o docker compose (comando `docker-compose -v`) 

e utilize os seguintes comandos:

Linux e Mac: `make buid` e `make up`

Windows: `docker-compose build` e `docker-compose up -d`

O container node irá subir no [http://localhost:30101][3] (faça um teste abrindo o browser na url).

[1]:https://docs.docker.com/get-docker/
[2]:https://docs.docker.com/compose/gettingstarted/
[3]:http://localhost:30101
