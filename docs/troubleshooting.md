# Troubleshooting

## VPN does not connect

Check:

```bash
docker ps
```

---

## Verify logs

```bash
docker logs wg-easy
```

---

## Verify WireGuard

```bash
wg
```

---

## Restart

```bash
docker restart wg-easy
```

---

## Firewall

Verify that UDP port 51820 is open.

---

## Check networking

```bash
ip route
```

---

## Verify Docker

```bash
docker network ls
```
