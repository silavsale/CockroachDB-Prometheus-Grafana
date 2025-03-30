# CockroachDB-Prometheus-Grafana

1. Create Docker network

```sh
docker network create cockroach-net
```

2. Run Cockroach db 

```sh
docker compose -f cockroach-compose.yml up -d
```

3. Run Monitoring Stack

```sh
docker compose -f monitoring-compose.yml up -d
```