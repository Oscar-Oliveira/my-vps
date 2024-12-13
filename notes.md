
## Available endpoints

* http://57.129.79.215:8000
* http://57.129.79.215:8001

* http://57.129.79.215

## Docker commands

```bash
docker-compose up --build

docker-compose down

docker-compose logs

docker ps
docker ps -a

docker image ls
docker image rm 9778328a3f0d

docker build --tag 'test_api1' .
docker run -p 8000:80 test_api1

docker run -d -p 8000:80 test_api1

docker stop c5b8e0e711c3

docker system prune -a -f --volumes

```

on moodle instalation
server: postgres!
port: 5432


https://www.youtube.com/watch?v=V3ZuwaZ4bLM
