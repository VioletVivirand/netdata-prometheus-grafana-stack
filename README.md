# netdata-prometheus-grafana-stack

A [Docker-compose](https://github.com/docker/compose) stack for [Netdata](https://www.netdata.cloud) &amp; [Prometheus](https://prometheus.io) &amp; [Grafana](https://grafana.com)

Read this [article](https://docs.netdata.cloud/backends/walkthrough/) first in order to get the official introdeuction of this stack.

## Usage

Start:

```bash
docker-compose up -d
```

Stop & Remove:

```bash
docker-compose stop && docker-compose rm -f
```

## File Structure

```
.
├── README.md
├── data
│   ├── grafana
│   ├── prometheus
│   └── prometheus.yml
└── docker-compose.yml
```

