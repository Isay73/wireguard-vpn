# Architecture

## Overview

This project documents a WireGuard VPN deployment used to securely access a self-hosted infrastructure.

The VPN runs inside Docker using wg-easy and provides encrypted communication between remote clients and internal services.

---

## Infrastructure

```text
Internet
      │
Public VPS
      │
WireGuard
      │
wg-easy
      │
VPN Clients
      │
├── SSH
├── Nextcloud
└── Docker Services
```

---

## Components

| Component | Purpose |
|-----------|---------|
| Ubuntu Server | Operating System |
| WireGuard | VPN |
| wg-easy | Client Management |
| Docker | Container Runtime |
| SSH | Remote Administration |
| Nextcloud | Private Cloud Storage |
