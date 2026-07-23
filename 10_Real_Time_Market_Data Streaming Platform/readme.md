# Real-TIme  Market Data Streaming Planform
---

## Business Case
1. Streams live market data continiously
2. Normalizes data from broker APIs.
3. Generates real-time technical indicators.
4. Updates dashboards instantly.
5. Power BI agents with live imformation.
6. Supprtts low-latency financial applications.
7. Enables real-time alerts.
8. Maintaisn high data availailbility.
9. Supplies live feeds to downstream AI systems.
10. Creates the foundation for future algorithm trading
---

## Technology Stack

| Category | Technologies |
|---|---|
| Market Feed | Upstox WebSocket API |
| Event Streaming | Apache Kafka |
| Stream Processing | Apache Flink |
| Event Serialization | Avro / Protobuf |
| Schema Registry | Confluent Schema Registry |
| Backend | Python, FastAPI |
| Live Client Communication | FastAPI WebSockets |
| Cache | Redis |
| Time-Series Database | TimescaleDB |
| Analytics Database | ClickHouse |
| Object Storage | MinIO / Amazon S3 |
| Frontend | React, TypeScript, Vite |
| Live Charts | TradingView Lightweight Charts |
| Technical Indicators | pandas-ta, Custom Stream Calculations |
| Alerts | Kafka Events, Email, Telegram |
| API Gateway | Traefik / NGINX |
| Metrics | Prometheus |
| Monitoring Dashboards | Grafana |
| Logging | Loki |
| Distributed Tracing | OpenTelemetry |
| Testing | Pytest, Testcontainers, k6 |
| CI/CD | GitHub Actions |
