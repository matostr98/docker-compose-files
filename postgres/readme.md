# Postgres

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd docker-compose-files\postgres`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:
* `COMPOSE_PROJECT_NAME` the default value is **example**

Postgres variables:
* `PG_IMAGE` the default value is **postgres:13.2**
* `PG_NAME` the default value is **example-db**
* `PG_USER` the default value is **postgres**
* `PG_PASSWORD` the default value is **password**
* `PG_PORT` the default value is **5432**


## Default access to postgres: 
* **URL:** as `localhost:PG_PORT` by default `localhost:5432`
* **Username:** as `PG_USER`, by default: `postgres`
* **Password:** as `PG_PASSWORD`, by default `password`

