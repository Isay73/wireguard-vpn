# WireGuard VPN Infrastructure

## Overview

This repository documents my WireGuard VPN deployment used for secure remote access to a self-hosted infrastructure.

The VPN environment is managed through wg-easy and provides encrypted access to internal services such as Nextcloud, SSH and other infrastructure components.

The goal of this project was to build a secure, easy-to-manage VPN solution for remote administration and daily work.

---

## Architecture

```text
              Internet
                  │
             Public Server
                  │
            WireGuard VPN
                  │
              wg-easy UI
                  │
         VPN Clients (Windows)
                  │
        ┌─────────┴─────────┐
        │                   │
      Nextcloud            SSH
        │
    Docker Services
```

---

## Technology Stack

- Ubuntu Server 24.04
- WireGuard
- wg-easy
- Docker
- Docker Compose
- Linux Networking
- Nginx
- Firewall

---

## Features

- Secure VPN access
- Client management through wg-easy
- Docker deployment
- SSH access
- Internal service protection
- Encrypted communication

---

## Screenshots

### WireGuard Dashboard

![WireGuard](screenshots/wireguard-ui-redacted.png)

---

### Docker Containers

![Docker](screenshots/docker-running-containers.png)

---

### Server Overview

![Ubuntu](screenshots/ubuntu-server-overview.png)

---

## What I Built

I deployed and configured a WireGuard VPN environment using wg-easy running inside Docker.

The VPN provides secure access to my self-hosted infrastructure, allowing remote administration of Linux services and protected applications.

I also configured routing, firewall rules and client management while troubleshooting connectivity and networking issues.

---

## What I Learned

- WireGuard deployment
- VPN networking
- Docker networking
- Linux routing
- Firewall configuration
- Secure remote administration
- Infrastructure troubleshooting

---

## Security

Sensitive information has been removed.

The repository does not include:

- Private keys
- Public keys
- IP addresses
- VPN peers
- Passwords
- Tokens

---

## Future Improvements

- Multi-site VPN
- Monitoring
- High Availability
- Automatic client provisioning
