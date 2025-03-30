# CockroachDB-Prometheus-Grafana

1. Create Docker network

```js
docker network create cockroach-net
```

2. Run Cockroach db 

```js
docker compose -f cockroach-compose.yml up -d
```