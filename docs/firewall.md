# Firewall

## Required Ports

| Port | Protocol | Purpose |
|------|----------|---------|
| 51820 | UDP | WireGuard VPN |
| 51821 | TCP | wg-easy Web Interface |
| 22 | TCP | SSH |
| 443 | TCP | HTTPS |

---

## Notes

The VPN interface is used to securely access internal services without exposing them directly to the Internet.

Only required ports are opened.

Sensitive infrastructure remains accessible only through the VPN.
