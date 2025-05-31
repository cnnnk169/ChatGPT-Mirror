# ChatGPT Gateway

This repository contains documentation and compose files for running the [chatgpt-gateway](https://hub.docker.com/r/dairoot/chatgpt-gateway) service.

The gateway provides a simple API layer over ChatGPT. See `docs/chatapi-gateway.md` for detailed usage and all supported environment variables.

## Quick start

```bash
# copy and edit environment variables
cp .env.example .env

# start gateway with redis and watchtower
docker compose up -d
```

