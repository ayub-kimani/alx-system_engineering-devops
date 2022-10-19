# Networking basics #1

The aim of this project is to learn about what is localhost/127.0.0.1, what is 0.0.0.0, what is `/etc/hosts` and how to display the machine's active network interfaces.

## Technologies
* Scripts written in Bash 5.0.17(1)
* All files interpreted on Ubuntu 20.04 LTS
* Vi Editor

## Files

| Filename | Description |
| -------- | ----------- |
| `0-change_your_home_IP` | Bash script that configures an Ubuntu server as follows - * `localhost` resolves to `127.0.0.2` and * `facebook.com` resolves to `8.8.8.8` |
| `1-show_attached_IPs` | Bash script that displays all active IPv4 IPs on the machine it’s executed on |
| `100-port_listening_on_localhost` | Bash script that listens on port `98` on `localhost` |
