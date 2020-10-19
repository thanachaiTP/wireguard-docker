# WireGuard VPN docker deployment

## Requirements
- Docker
- Docker Compose
- *Tested on Linux Ubuntu*

## Start WireGuard VPN Server

```
docker-compose up -d
```

## Connecting to WireGuard VPN Server

Install WireGuard for your platform [https://www.wireguard.com/install/](https://www.wireguard.com/install/). Then import `config/peer1/peer1.conf`
