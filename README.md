# Docker Playground for Node.js
This is very simple docker compose project with a node.js service connecting to a cloudant database service

## Run in swarm
```
> docker swarm init
> docker stack deploy -c docker-compose.yml node
```
