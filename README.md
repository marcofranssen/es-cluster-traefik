# Elasticsearch Cluster using Traefik

This repository contains the example setup of the Elasticsearch cluster which I explained in the following blog.

[https://marcofranssen.nl/building-a-elasticsearch-cluster-using-docker-compose-and-traefik/](https://marcofranssen.nl/building-a-elasticsearch-cluster-using-docker-compose-and-traefik/)

## Run

```bash
docker-compose up -d
```

## Endpoints

| Tool              | URL                                              |
| ----------------- | ------------------------------------------------ |
| [Kibana][]        | [http://localhost](http://localhost)             |
| [Elasticsearch][] | [http://localhost/es](http://localhost/es)       |
| [Cerebro][]       | [http://localhost/admin](http://localhost/admin) |

[Kibana]: https://www.elastic.co/guide/en/kibana/current/index.html "Kibana 7.7 documentation"
[Elasticsearch]: https://www.elastic.co/guide/en/elasticsearch/reference/7.7/index.html "Elasticsearch 7.7 documentation"
[Cerebro]: https://github.com/lmenezes/cerebro "Cerebro Elasticsearch admin interface"
