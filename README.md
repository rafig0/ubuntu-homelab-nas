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
| Device | Dell Inspiron Laptop |
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

# Future Improvements

- Docker containers
- Pi-hole integration
- VPN setup
- Automated backups
- Monitoring dashboard

---
