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

---

# Default ports

- cockroachdb Web UI + Prometheus metrics :8080
- cockroachdb SQL :26257
- prometheus :9090
- grafana :3000

---

