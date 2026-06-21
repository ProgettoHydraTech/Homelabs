# Servizi — Federico S.

## Infrastruttura (Proxmox)

| ID | Nome | Tipo | Descrizione |
|----|------|------|-------------|
| 102 | vaultwarden | LXC | Password manager |
| 103 | nginxproxymanager | LXC | Reverse proxy |
| 104 | cloudflared | LXC | Cloudflare tunnel |
| 105 | n8n | LXC | Automazioni |
| 106 | affine | LXC | Note / knowledge base |
| 109 | docker | LXC | Host Docker + Portainer |
| 111 | plex | LXC | Media server |
| 113 | dawarich | LXC | Location history |
| 125 | seerr | LXC | Richieste media |
| 100 | homeassistant | VM | Smart home |
| 124 | pbs-mio | VM | Proxmox Backup Server |

> Node Proxmox: server personale — nome e storage omessi.

## Stack Docker (in LXC 109)

| Stack | Servizi | Compose |
|-------|---------|---------|
| [arr](../docker/arr/) | qBittorrent, Prowlarr, Sonarr, Radarr, Lidarr, Bazarr, Seerr, Tautulli, Maintainerr | ✅ |
| [immich](../docker/immich/) | Immich, ML, Redis, PostgreSQL | ✅ |
| [metube](../docker/metube/) | MeTube | ✅ |
| [paperless](../docker/paperless/) | Paperless-ngx, PostgreSQL, Redis | ✅ |
| [myvrmtovideo](../docker/myvrmtovideo/) | VRM Screenshotter, ONVIF, MediaMTX | ✅ |
| Hydra\*\*\*\* | 🔒 Classificato | — |
| Hydra\*\*\*\*\*\* | 🔒 Classificato | — |
| Hydra\*\*\*\*\*\*\*\* | 🔒 Classificato | — |
