# homelab

A self-hosted Linux server running on a Lenovo ThinkPad, built for learning purposes and personal use.

## Hardware (as of 2026/06/13)
- **Device** - Lenovo Thinkpad T430
- 

## Services

| Service | Purpose |
|---|---|
| Docker | Container runtime for all services |

## Setup Notes

- Installed Ubuntu Server 24.04 via USB
- Configured static IP via Netplan
- All services containerized with Docker Compose
- Remote access configured with Tailscale (no open ports)
