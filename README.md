A simple Hello World app written in Node.js (Express).

Contains Dockerfiles for Development (with Hot Reloading) and Production.

Build and run using any dockerfile:

```
$ docker build -f [dockerfile] -t node-docker .
$ docker run --rm -it -p 8080:8080 node-docker
```
