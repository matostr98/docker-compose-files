# Postgres with pgadmin

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd docker-compose-files\postgres-with-pgadmin`
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

Pgadmin variables:
* `PG_ADM_IMAGE` the default value is **dpage/pgadmin4:5.1**
* `PG_ADM_NAME` the default value is **example-pgadmin**
* `PG_ADM_USER` the default value is **admin@pgadmin.dev**
* `PG_ADM_PASSWORD` the default value is **password**
* `PG_ADM_PORT` the default value is **5050**

## Default access to postgres: 
* **URL:** as `localhost:PG_PORT` by default `localhost:5432`
* **Username:** as `PG_USER`, by default: `postgres`
* **Password:** as `PG_PASSWORD`, by default `password`

## Default access to PgAdmin: 
* **URL:** as `localhost:PG_ADM_PORT` by default `localhost:5050`
* **Username:** as `PG_ADM_USER`, by default: `admin@pgadmin.dev`
* **Password:** as `PG_ADM_PASSWORD`, by default: `password`

## Add a new default server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `PG_USER`, by default: `postgres`
* **Password** as `PG_PASSWORD`, by default `password`