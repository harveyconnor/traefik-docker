# traefik-docker
A simple reverse proxy docker compose setup using traefik.

## Usage
Simply `cp .env.example .env` and edit `.env` with your paramaters.
To use htpasswd, cd into the dir and run:
```
htpasswd -Bc .htpasswd <username here>
```
