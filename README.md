# WordPress con Docker

`docker-compose.yml` para levantar WordPress con MariaDB 11, pensado para desplegarse en Coolify.

Las credenciales de la base se toman de variables de entorno (`DB_USER`, `DB_PASSWORD`, `DB_NAME` y `DB_ROOT_PASSWORD`) y los datos quedan en volúmenes de Docker.

```bash
docker compose up -d
```
