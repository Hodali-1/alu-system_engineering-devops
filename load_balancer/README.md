# load_balancer

Bash scripts that set up redundant nginx web servers behind an HAproxy
load balancer.

## Files

- 0-custom_http_response_header: configures nginx with an X-Served-By header
- 1-install_load_balancer: installs and configures HAproxy on lb-01
