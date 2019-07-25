# Prometheus + Grafana + Netdata in Docker

### Running the example

Container names:
- grafana
- prometheus
- netdata

```
- clone this repository
$ docker-compose up -d grafana
$ docker-compose up -d netdata
$ docker-compose up -d prometheus
or just $ docker-compose up -d
```

Open a browser and:
- Grafana: http://localhost:3000
- Prometheus: http://localhost:9090
- Netdata: http://localhost:19999

Netdata metrics endpoint:
- Netdata: http://localhost:19999/api/v1/allmetrics?format=prometheus
