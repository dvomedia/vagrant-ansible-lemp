# LEMP stack with CentOS 7.0

## The stack

This is a basic LEMP stack using CentOS


## The setup

For the initial ansible package, I've used [Phansible](http://phansible.com/) - and kept its initial folder structure, but changed it to use CentOS instead of Ubuntu.

This dev box it has been configured with the following:

* It uses CentOS 6.5 minimal from [fillup/centos-6.5-x86_64-minimal](https://vagrantcloud.com/fillup/boxes/centos-6.5-x86_64-minimal)
* Nginx 1.8
* PHP 5.6 (congigured using PHP-FPM)
* MySQL 5.6
* RabbitMQ 3.5.3


## Configuration

The current configuration:

* Mounts current dir to /srv
* IP: 192.168.32.23
* Rabbit: 192.168.32.23:15672

For custom configuration you can edit the `Vagrantfile` as well as `ansible/vars/all.yml`

### Credentials

* Database: root / Admin123
* RabbitMQ: admin / Admin123




