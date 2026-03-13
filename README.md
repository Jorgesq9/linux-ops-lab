# Linux Ops Lab

Self-hosted Linux operations laboratory built on an Ubuntu server.

This project simulates a real production monitoring environment used by Linux / DevOps engineers.

## Stack

- Docker Compose
- Nginx
- Prometheus
- Node Exporter
- Grafana
- Uptime Kuma

## Architecture

Monitoring stack deployed with containers:

Server
│
├── Prometheus (metrics collection)
├── Node Exporter (system metrics)
├── Grafana (visualization)
├── Uptime Kuma (service monitoring)
└── Nginx (reverse proxy)

## Purpose

Practice real Linux systems administration tasks:

- service monitoring
- troubleshooting
- infrastructure documentation
- incident simulation
- observability

## Run

```bash
docker compose up -d
