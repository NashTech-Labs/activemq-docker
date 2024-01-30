This contains the Dockerfile to build an ActiveMQ 5.18.1 Docker image. This image can then be used deploy ActiveMQ as a standalone instance or following a master-slave architecture. The Docker image and config is configured in such a way it supports filesystem as storage but can also use Microsoft SQL server as the backend storage.

## Building the Image

To build the Docker image, run the following command:
```
docker build -t activemq:5.18.1 .
```

Push the image to a registry and can be used with the [activemq helm chart](https://github.com/NashTech-Labs/Activemq-Helm-Chart)