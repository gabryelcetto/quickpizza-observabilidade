# QuickPizza Observabilidade

Ambiente com QuickPizza + cAdvisor + Prometheus + Grafana + Uptime Kuma (Docker Compose).

## Pré-requisitos
- Docker e Docker Compose

## Como executar
```bash
git clone https://github.com/grafana/quickpizza app && rm -rf app/.git
cp .env.example .env     # edite a senha do Grafana
docker compose up -d --build
```

| Serviço | Endereço |
|---|---|
| QuickPizza | http://localhost:3333 |
| cAdvisor | http://localhost:8080 |
| Prometheus | http://localhost:9090 |
| Grafana | http://localhost:3000 |
| Uptime Kuma | http://localhost:3001 |

## Arquitetura
(TODO: diagrama e explicação de cada componente)

## Evidências
(TODO: prints do dashboard, monitor, alertas e JMeter)
