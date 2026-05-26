zad 1
docker run -d --name apache -p 8090:80 httpd
docker ps

http://localhost:8090/

docker exec -it apache bash

docker logs apache

docker stop apache

docker rm apache

docker rmi httpd


