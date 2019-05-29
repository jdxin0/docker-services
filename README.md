# docker-services

multiple docker docker-compose and command lines services for development usage


## command line services
* portainer
```
docker run --restart=always -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer
```
* redis
```
docker run --restart=always -d -p 3306:3306 redis-server --save ''
```
* mysql
```
docker run -e MYSQL_ROOT_PASSWORD=root -d mysql
```
