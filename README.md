# postgresql & pgAdmin4 docker compose


## Requirements:
* docker >= 19.03.0+
* docker-compose



## Quick Start
```console
foo@bar:~$ git pull https://github.com/sumanmitra97/postgres-pgadmin4-docker-compose
foo@bar:~/postgres-pgadmin4-docker-compose$ mv sample.env .env
```
* Fill up the sensitive information in ***.env*** file
```console
foo@bar:~/postgres-pgadmin4-docker-compose$ cd postgres-pgadmin4-docker-compose
foo@bar:~/postgres-pgadmin4-docker-compose$ docker-compose up -d
```


## Access to pgAdmin4: 
* **URL:** `http://localhost:5050`


**postgres configurations(postgresql.conf) can be changed by adding or modifying the contents in *postgres.cfg* file**