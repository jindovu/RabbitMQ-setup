# RabbitMQ-setup
Setup rabbitmq cluter

1. set host name 10.1.2.1
	sudo hostnamectl set-hostname rabbitmq94
2. set host name 10.1.2.2
	sudo hostnamectl set-hostname rabbitmq95
3. copy 2 line into hosts
	sudo nano /etc/hosts

#test-ub-rmq01.com: domain 
	10.1.2.1      test-ub-rmq01.com rabbitmq94
	10.1.2.2     test-ub-rmq02.com rabbitmq95
4. setup same as: 
	https://www.howtoforge.com/how-to-set-up-rabbitmq-cluster-on-ubuntu-22-04/

