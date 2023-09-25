# Database setup

## PostgreSQL

### Create postgres.env file

```shell
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_DB=postgres
```

### Start PostgreSQL

```shell
docker compose -p your_project_name -f docker-compose.yml up -d
```

### Shut down PostgreSQL

```shell
docker compose -p your_project_name -f docker-compose.yml down
```
