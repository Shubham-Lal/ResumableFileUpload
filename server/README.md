### Setup
1. Make sure Node.js & Docker is installed.

2.  docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest

    docker ps -a

3.  docker start `CONTAINER ID`

4. Run `npm run dev`