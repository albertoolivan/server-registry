# ch.server.registry


1) Maven install to get server-registry-1.0.0-SNAPSHOT.jar

$ mvn install

2) Create a docker image server-registry

$ docker build -t server-registry .

3) Execute docker container

$ docker run -p 8761:8761 server-registry

4) Test in browser

http://localhost:8761