# flyway-docker-migration

### create postgresql container

```
docker-compose up -d db
```

### flyway-migration
- clean

```
docker-compose run --rm flyway-clean
```

- migrate

```
docker-compose run --rm flyway-migrate
```

- info

```
docker-compose run --rm flyway-info
```