# Intro To Docker - A Tool Every Developer Should Know

Docker is a powerful tool that allows developers to set up environments quickly, configure complex systems and servers easily, and deploy software reliably. In this project, we will get a look at what Docker is, how it works, and how to use it in our development tasks.


## Docker commands
```
docker build -t hello-docker:1.0.0 .
docker image history <image_id>
docker run -d --name first-container -p 8080:80 hello-docker:1.0.0
docker stop <container_id>

docker run -d --hostname my-rabbit --name some-rabbit -p8080:15672 rabbitmq:3-management
```
