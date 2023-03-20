# Solution

1. Whenever commit is done, github actions pipeline runs and does sonarqube analysis and uploads to sonarqube http://20.108.177.199:9000/dashboard?id=rsa-nodejs-cicd
2. It also builds docker image and pushes to dockerhub.

## To run container

```bash
$ docker run -p 8080:80 -d vamshi825232/rsa-nodejs:latest
```

## Access the application

```bash
$ curl http://localhost:8000/
```
