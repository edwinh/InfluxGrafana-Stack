
# InfluxDB & Grafana Stack
Thank you @huntabyte for the intial repo

Gain the ability to analyze and monitor telemetry data by deploying the stack within minutes using [Docker](https://docs.docker.com/engine/install/) and [Docker Compose](https://docs.docker.com/compose/install/).

## ⚡️ Getting Started

Clone the project

```bash
git clone https://github.com/edwinh/tig-stack
```

Navigate to the project directory

```bash
cd tig-stack
```

Change the environment variables define in `.env` that are used to setup and deploy the stack
```bash
├── .env         <---
├── docker-compose.yml
├── entrypoint.sh
└── ...
```

```bash
├── .env
├── docker-compose.yml
├── entrypoint.sh
└── ...
```

Start the services
```bash
docker-compose up -d
```
## Docker Images Used (Official & Verified)

[**InfluxDB**](https://hub.docker.com/_/influxdb) / `2.1.1`

[**Grafana-OSS**](https://hub.docker.com/r/grafana/grafana-oss) / `8.4.3`

## Contributing

Contributions are always welcome!

