# Wordpress on docker

Dockerized wordpress on mysql 5.7

## Requirements

- [docker](https://docs.docker.com/install/)
- [docker-compose](https://docs.docker.com/compose/install/)

## Running

> The default port is 8000 but you can change it in the `.env` file

```
docker-compose up -d
```

## Stop

```
docker-compose down
```

> Database data is saved in the `database/data` folder
