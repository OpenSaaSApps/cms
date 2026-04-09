# cms

> Click To Deploy WordPress CMS

[![Sync](https://github.com/opensaasapps/cms/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/cms/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/cms/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/cms/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/cms)](https://hub.docker.com/r/thefractionalpm/cms)

Upstream: [WordPress/WordPress](https://github.com/WordPress/WordPress) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `WORDPRESS_DB_HOST` | ⚪ | |
| `WORDPRESS_DB_USER` | ⚪ | |
| `WORDPRESS_DB_PASSWORD` | ✅ | |
| `WORDPRESS_DB_NAME` | ⚪ | |

## Image

```
docker pull wordpress:latest
docker pull thefractionalpm/cms:latest
```

## Ports

| Port | Service |
|---|---|
| `80` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
