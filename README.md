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

### Stack complète (mode dev)

Pour démarrer le projet en mode développement : 

- Clonez le backend du projet : `git clone https://github.com/Admiralis/backend --recurse`
- Démarrez le backend en suivant les instructions du README.md

- Clonez la gateway du projet : `git clone https://github.com/Admiralis/dev_stack`
- Démarrez la gateway en suivant les instructions du README.md

- Clonez le front du projet : `git clone https://github.com/Admiralis/front-ionic`
- Démarrez le front PWA avec `npm run dev` ou le web uniquement avec `npm start`

Le projet sera alors accessible sur `localhost:80`
Le backend sera accessible sur `localhost:80/api`

## Accès

La stack sera accessible sur le port 80.

- Frontend: http://localhost
- Backend: http://localhost/api
    - /courses
    - /loans
    - /computers
