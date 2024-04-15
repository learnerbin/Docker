```
docker build -t imageName .
docker images
docker run -it imageName
docker run -it imageName sh

docker run -p 5173:5173 imageName
docker ps
docker ps -a
docker container prune

docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules imageName

docker tag imageName username/imageName
docker push username/imageName

docker init
docker compose up

```
