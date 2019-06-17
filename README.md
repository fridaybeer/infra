# GoT - Game of Trades

## Run
```
docker swarm init
docker stack deploy -c deploy.yml got
docker stack rm got
```

## Debug service
```
docker service ls
docker service ps --no-trunc
```
