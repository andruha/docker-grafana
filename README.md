# docker-grafana

Grafana with consul agent 

```
docker run --rm -e CONSUL_HOST=consul -p 3000:3000 devopsftw/grafana:latest 
```

Base image: [grafana/grafana](https://hub.docker.com/r/grafana/grafana)

Additional available envs:

- CONSUL_JOIN
- CONSUL_DC
- CONSUL_SERVICE_NAME
- HTTP_HOST
