# Elasticsearch Cluster using Traefik

This repository contains the example setup of the Elasticsearch cluster which I explained in the following blog.

[https://marcofranssen.nl/building-a-elasticsearch-cluster-using-docker-compose-and-traefik/](https://marcofranssen.nl/building-a-elasticsearch-cluster-using-docker-compose-and-traefik/)

## Run

```bash
docker-compose up -d
```

## Endpoints

| Tool          | URL                                              |
| ------------- | ------------------------------------------------ |
| Kibana        | [http://localhost](http://localhost)             |
| Elasticsearch | [http://localhost/es](http://localhost/es)       |
| Cerebro       | [http://localhost/admin](http://localhost/admin) |
