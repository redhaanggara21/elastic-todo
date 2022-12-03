
## Description

A simple TODO application under Docker environment.
* NestJS
* TypeORM
* PostgreSQL
* Swagger
* PGadmin4
* JWT
* Docker
* Elasticsearch
* Kibana
* GraphQl
* Grafana


# Running the app on docker
## Docker build & start

```bash
# docker env build
$ docker-compose build

# docker env start
$ docker-compose up

# remove docker container (services & networks)
$ docker-compose down
```
## Migration

```bash
# generate migration
$ docker-compose run nestjs npm run typeorm:generate AnyNameYouLike

# run migration
$ docker-compose run nestjs npm run typeorm:run
```
