# Dev Stack

Ce répository permet de lancer le reverse proxy en mode dev.

## Prérequis

- Docker

## Lancement

Le backend et le front end doivent être lancés localement en mode dev.
- https://github.com/Admiralis/backend
- https://github.com/Admiralis/front-ionic

Lancer le reverse proxy en mode dev:

```bash
docker-compose up
```

## Accès

La stack sera accessible sur le port 80.

- Frontend: http://localhost
- Backend: http://localhost/api
    - /courses
    - /loans
    - /computers