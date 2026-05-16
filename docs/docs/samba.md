# Samba NAS Setup

## Install Samba

```bash
sudo apt install samba
```

## Create Shared Directory

```bash
mkdir ~/shared
```

## Edit Samba Configuration

```bash
sudo nano /etc/samba/smb.conf
```

Example share:

```ini
[Shared]
path = /home/rafigo/shared
browseable = yes
read only = no
guest ok = no
```

## Restart Samba

```bash
sudo systemctl restart smbd
```
