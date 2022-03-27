# Nextcloud vps

## Requirements

- docker
- docker-compose

## How to start

Create a .env file

Here a template
```
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_DATABASE=
NEXTCLOUD_TRUSTED_DOMAINS=
NEXTCLOUD_ADMIN_USER=darth-vader
NEXTCLOUD_ADMIN_PASSWORD=password
```

You need to fill all the fields

```bash
docker-compose up
```
