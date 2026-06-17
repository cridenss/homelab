# Homelab

Serveur personnel auto-hébergé sous Ubuntu Server, tournant sur un ancien Mac reconverti.

## Stack

| Service | Rôle |
|---|---|
| Pi-hole | DNS local et blocage de publicités |
| Nginx Proxy Manager | Reverse proxy et gestion des domaines locaux |
| Portainer | Gestion des conteneurs Docker |
| Beszel | Supervision et monitoring système |
| Homepage | Dashboard centralisé |
| Home Assistant | Domotique et suivi consommation électrique |
| Jellyfin | Streaming média |
| Samba | Partage de fichiers réseau |
| Wireshark | Analyse du trafic réseau |
| RomM | Gestion de bibliothèque de ROMs |

## Stack technique

- OS : Ubuntu Server
- Conteneurisation : Docker / Docker Compose
- Configuration : YAML + variables d'environnement centralisées
- Accès distant : SSH / VS Code Remote SSH
- Analyse réseau : Wireshark
