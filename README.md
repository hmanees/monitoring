# Monitoring Stack

## Components
- Prometheus
- Grafana
- Alertmanager
- Blackbox Exporter
- Node Exporter
- cAdvisor (optional)

## Deploy
docker compose up -d

## Update Config
Edit prometheus.yml -> git commit -> push -> redeploy.

## Hot Reload
curl -X POST http://localhost:9090/-/reload
