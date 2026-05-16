# Initial Server Setup

## Install Ubuntu Server

Installed Ubuntu Server 24.04 LTS using a bootable USB drive.

## Enable SSH

```bash
sudo apt install openssh-server
```

## Verify SSH

```bash
systemctl status ssh
```

## Connect From Another Device

```bash
ssh username@computer.local
```
