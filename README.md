# Ubuntu Homelab NAS Server

A self-hosted Ubuntu Server setup built using a repurposed laptop for NAS storage, media streaming, and remote administration.

---

# Features

- Ubuntu Server 24.04 LTS
- SSH remote administration
- Samba NAS configuration
- Jellyfin media server
- Headless server workflow
- Local hostname-based access

---

# Hardware

| Component | Details |
|---|---|
| Device | Dell Inspiron 15-3567 |
| CPU | Intel i3 |
| RAM | 12 GB |
| Storage | 500 GB |
| OS | Ubuntu Server 24.04.4 LTS |

---

# Services

| Service | Purpose |
|---|---|
| SSH | Remote administration |
| Samba | NAS / file sharing |
| Jellyfin | Media streaming |

---

# Network Architecture

```text
Main PC
   │
   ├── SSH
   │
Router ─── Ubuntu Homelab Server
               ├── Samba NAS
               └── Jellyfin
```

---

# Learning Outcomes

- Linux server administration
- SSH remote management
- Samba configuration
- Media server deployment
- Self-hosting fundamentals
- Network service management

---

# Screenshots

## Setup

![setup](screenshots/hw-setup.jpg)

## System Monitoring and SSH login

![htop](screenshots/htop-ssh.jpg)

## Samba NAS Access

<img src="screenshots/samba-share.png" width="700">

The Samba share is mounted on a Windows machine over the local network.

## Details of Server and currently running services

![SSH](screenshots/details-and-service-run.jpg)

## Active Services

![active](screenshots/active-services.jpg)

---

# Future Improvements

- Docker containers
- VPN setup
- Automated backups
- Monitoring dashboard

---
