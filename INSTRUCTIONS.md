# Question1:
To run sample-api use `docker compose up`. It will automatically use the new Dockerfile to ensure *housing-api* gets deployed along with migration and postgres.

# Question2:
To pull the image run:
```
docker pull ghcr.io/nalin28/sample-api:latest
```

To run complete setup run:
```
docker compose up
``` 
Note: In the [docker-compose.yml](./docker-compose.yml) lines 52-53 can be commented out and 54-57 can be uncommented to use the Dockerfile directly as well.

# Question3:
The *pdf* file [Answer_3.pdf](./Answer_3.pdf) contains the answer to question 3.