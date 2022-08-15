# kuma-compose
Deployment of kuma with docker compose and reverse proxy. 

## Generate SSL Certificate

```bash
openssl req -new -newkey rsa:4096 -x509 -sha256 -days 365 -nodes -out MyCertificate.crt -keyout MyKey.key
```

## Start Service

```
docker-compose up
```
