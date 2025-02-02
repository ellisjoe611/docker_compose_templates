# docker_compose_templates

Docker-Compose templates that are runnable on localhost.<br/>
Each Image is linked with separate volume and network.


## command

* start (background)
```
docker-compose up -d -f {folder_name}/docker-compose.yaml
```

* stop
```
docker-compose down -f {folder_name}/docker-compose.yaml
```


## Images

* MongoDB
* Ollama
* PostgreSQL
* Redis
