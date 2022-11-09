# Quicly Docker-Compose your services!

---
Tired of installing different databases whenever you needed?
You can try to run those in the docker, quickly and easily without the installing process hassle.

## Support services:

- PostgreSQL: default on port `5432`

```shell
docker-compose up -d postgre_db
```

- Redis: default on port `6379`

```shell
docker-compose up -d redis_cache
```

- CassandraDB: default on port `9042` (1 instance)

```shell
docker-compose up -d cassandra_db
```

- MySQL: default on port `3307`

```shell
docker-compose up -d mysql_db
```

or you can run all of them:

```shell
docker-compose up -d
```

---

## Environment

All the environment to config these services is included in `.env` file. Modify it to your needs.

---

## Contribution

You are welcome to contribute any service config. Just create a new
compose config of the service, test it, and create a PR.
