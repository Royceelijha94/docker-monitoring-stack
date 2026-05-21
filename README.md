# Docker Monitoring Stack

## What is this project?
A monitoring stack running Prometheus and Grafana as Docker containers, 
managed with Docker Compose.

## Why Docker Compose?
Instead of running containers manually one by one, Docker Compose lets you 
define and run multiple containers with a single command.

## How to run
```bash
docker compose up -d
```

## Services
- **Prometheus** - Metrics collection on port 9090
- **Grafana** - Visualization dashboard on port 3000

## What I learned
- Docker containers vs manual installation
- Docker Compose for multi-container management
- Container networking
- Infrastructure as code basics
