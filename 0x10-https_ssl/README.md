# HTTPS SSL

This project focuses on HTTPS SSL, encrypting traffic and SSL termination.

## Technologies used
* Bash 5.0.17(1)
* Files interpreted on Ubuntu 16.04 LTS
* Vi editor

## Files

| Filename | Description |
| -------- | ----------- |
| `0-world_wide_web` | Configures domain zone so that the subdomain `www` points to your `load-balancer IP (lb-01)` |
| `1-haproxy_ssl_termination` | Creates a certificate using certbot and configures HAproxy to accept encrypted traffic for your subdomain `www.` |
| `100-redirect_http_to_https` | Configure HAproxy to automatically redirect HTTP traffic to HTTPS. |
