# docker-compose-example
Example repo for Docker Compose and Docker Machine

Does the following
- run 1 redis container
- run 3 nodejs containers linked to redis
- run 1 nginx container exposing port 80 and linked to the 3 nodejs containers

To run with docker-compose
```
docker-compose up
```
Original example from,
- http://anandmanisankar.com/posts/docker-container-nginx-node-redis-example/
