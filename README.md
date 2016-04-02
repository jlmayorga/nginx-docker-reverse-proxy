# nginx-docker-reverse-proxy
Docker container running nginx as a reverse proxy

## Instructions

* docker build -t nginx-reverse-proxy .
* docker run -P -d nginx-reverse-proxy
* docker ps -a
* docker-machine ip
* curl http://192.168.99.100:32777
