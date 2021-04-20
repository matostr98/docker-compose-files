# MySQL

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd docker-compose-files\mysql`
* Run this command `docker-compose up -d`

## Environments
This Compose file contains the following environment variables:
* `COMPOSE_PROJECT_NAME` the default value is **example**

MySQL variables:
* `MYSQL_IMAGE` the default value is **mysql:8.0.24**
* `MYSQL_DBNAME` the default value is **example-db**
* `MYSQL_PASSWORD` the default value is **password**
* `MYSQL_PORT` the default value is **3306**


## Default access to postgres: 
* **URL:** as `localhost:MYSQL_PORT` by default `localhost:3306`
* **Username:** `root`
* **Password:** as `MYSQL_PASSWORD`, by default `password`

