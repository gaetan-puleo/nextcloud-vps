# Nextcloud vps

## Requirements

- docker
- docker-compose

## How to start

Create a .env file

Here a template
```
# Mysql
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_DATABASE=

# nextcloud
NEXTCLOUD_TRUSTED_DOMAINS=
NEXTCLOUD_ADMIN_USER=
NEXTCLOUD_ADMIN_PASSWORD=

# timezone
TZ=Europe/Paris

# NGINX
VIRTUAL_HOST=

# Letsencrypt
LETSENCRYPT_HOST=
DEFAULT_EMAIL=
```

You need to fill all the fields

```bash
docker-compose up
```

## informations

- nextcloud files are stored in `./files`
- user files are stored in `./files/data` 
- the db is stored in `./db`

## Todo before stable release

- [ ] backup database 
- [ ] backup files
- [ ] automate install
- [ ] automate restore database
- [ ] automate restore files
