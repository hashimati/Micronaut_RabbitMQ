[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/P5P411AKC)
<a href="https://www.buymeacoffee.com/hashimati"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=hashimati&button_colour=BD5FFF&font_colour=ffffff&font_family=Cookie&outline_colour=000000&coffee_colour=FFDD00"></a>
## Feature http-client documentation

- [Micronaut Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)

## Feature rabbitmq documentation

- [Micronaut RabbitMQ Messaging documentation](https://micronaut-projects.github.io/micronaut-rabbitmq/latest/guide/index.html)


## RabbitMQ Pre-requisite
- Erlang. Run the below command to install it. 
```shell script
sudo dnf -y install erlang
```
## Install RabbitMQ Server on Linux 
```shell script
sudo dnf -y install rabbitmq-server
```
``` shell script
rpm -qi rabbitmq-server
```
## Configure RabbitMQ Admin Console
```shell script
sudo rabbitmq-plugins enable rabbitmq_management
```
## To Start RabbitMQ Server on Linux

```shell script
sudo systemctl start rabbitmq-server
```

## To Stop RabbitMQ Server on Linux

```shell script
sudo systemctl stop rabbitmq-server
```

## RabbitMQ Docker Daemon
```shell script
docker run -d --hostname my-rabbit --name some-rabbit rabbitmq:3
```
