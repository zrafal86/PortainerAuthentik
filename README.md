# PortainerAuthentik


## Authentik:

`wget https://goauthentik.io/docker-compose.yml`

`echo "PG_PASS=$(openssl rand 36 | base64)" >> .env`

`echo "AUTHENTIK_SECRET_KEY=$(openssl rand 60 | base64)" >> .env`

`echo "AUTHENTIK_ERROR_REPORTING__ENABLED=true" >> .env`