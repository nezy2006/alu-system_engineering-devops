# Firewall Configuration on Web-01

This directory contains the answer file for the firewall task.

## Task

Configure UFW on web-01 to:

- Block all incoming traffic except TCP ports:
  - 22 (SSH)
  - 80 (HTTP)
  - 443 (HTTPS)

- Allow all outgoing traffic.

## Answer file

- 0-block_all_incoming_traffic_but
  Contains all the ufw commands used to configure the firewall.

## Verification

- sudo ufw status verbose confirms that only TCP ports 22, 80, 443 are open.
- All other incoming ports are blocked.
