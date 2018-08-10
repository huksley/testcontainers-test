# Testcontainers example

Runs following containers:

  * Redis
  * Alpine with bashttpd HTTP server on port 80
  * Postgres

Use it as PoC or ensuring your local environment is OK. Compatible with Windows.

## Configuring Windows

Disable TLS (reconfigure boot2docker and unset DOCKER_TLS_VERIFY, change port). 
More info here: https://coderwall.com/p/siqnjg/disable-tls-on-boot2docker

