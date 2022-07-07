### Create docker network

```bash
 docker network create -d bridge traefik-net

```

### Run with compose mode

```bash
docker-compose up -d

```

### Run with swarm mode

```bash
 docker stack deploy -c docker-stack.yml docker-elk

```
