# Wakapi setup

## Create .env file

```shell
WAKAPI_PASSWORD_SALT=your_salt_here
WAKAPI_DB_HOST=postgres
WAKAPI_DB_PORT=5432
WAKAPI_DB_USER=postgres
WAKAPI_DB_PASSWORD=postgres
WAKAPI_DB_NAME=wakapi
WAKAPI_DB_TYPE=postgres
WAKAPI_MAIL_ENABLED=true
WAKAPI_MAIL_SENDER="Notification <noreply@yourdomain.com>"
WAKAPI_MAIL_PROVIDER=smtp
WAKAPI_MAIL_SMTP_HOST=your_smtp_host
WAKAPI_MAIL_SMTP_PORT=465
WAKAPI_MAIL_SMTP_USER=your_smtp_username
WAKAPI_MAIL_SMTP_PASS=your_smtp_password
WAKAPI_MAIL_SMTP_TLS=false
```

## Start PostgreSQL

```shell
docker compose up -d
```

## Shut down PostgreSQL

```shell
docker compose down
```
