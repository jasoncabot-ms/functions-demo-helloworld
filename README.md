# Hello World Functions - Docker

```
docker build -t functions-demo-helloworld:v1 .
docker run -p 8080:80 -it functions-demo-helloworld:v1

curl -v http://localhost:8080/api/HttpTrigger
```
