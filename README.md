# MassTransitDemo
#Run RabbitMQ in docker
docker run -d --hostname my-rabbit --name ecomm-rabbit -p 15672 -p 5672:5672 rabbitmq:3-management
docker logs -f <container name or beginning letters of the name>
http://localhost:15672