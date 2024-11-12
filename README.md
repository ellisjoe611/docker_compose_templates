# docker_compose_templates

Docker-Compose templates that are runnable on localhost.

Each Image is linked with separate volume and network.

## command
```
# run on background
docker-compose up -d {folder_name}/docker-compose.yaml

# stop
docker-compose down {folder_name}/docker-compose.yaml
```

## Images
* MongoDB
* PostgreSQL
* Redis
