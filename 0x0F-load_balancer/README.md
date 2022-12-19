# Load balancer

This project focuses on `Load balancer` and `Web stack debugging`.

## Technologies
* Scripts written in Bash 5.0.17(1)
* Files interpreted on Ubuntu 16.04 LTS
* Vi editor

## Files

| Filename | Description |
| -------- | ----------- |
| `0-custom_http_response_header` | Bash script that installs and configures Nginx on a server with a custom HTTP response header. |
| `1-install_load_balancer` | Bash script that installs and configures HAproxy on a `lb-01` server. |
| `2-puppet_custom_http_response_header.pp` | Automate the task of creating a custom HTTP header response, but with Puppet. |
