# Servidor thingsboard Docker

Antes de levantar los servicios

```
mkdir -p ./data/.mytb-data && sudo chown -R 799:799 ./data/.mytb-data
mkdir -p ./data/.mytb-logs && sudo chown -R 799:799 ./data/.mytb-logs
```

Luego, ejecutamos

```
docker compose down
```
