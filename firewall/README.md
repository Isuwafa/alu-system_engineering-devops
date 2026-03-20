# Firewall

This directory contains firewall configuration scripts using UFW (Uncomplicated Firewall).

## 0-block_all_incoming_traffic_but

Installs and configures UFW on web-01 to block all incoming traffic except:
- Port 22 (SSH)
- Port 80 (HTTP)
- Port 443 (HTTPS SSL)
