# Workshop
Raspberry PI Workshop


Run RabbitMQ
sudo docker run -d --hostname my-rabbit --name rabbit-server -p 15672:15672 -p 5672:5672 -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=admin rabbitmq:3-management