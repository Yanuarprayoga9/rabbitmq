docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=password rabbitmq:4.0.1-management-alpine
![alt text](image.png)