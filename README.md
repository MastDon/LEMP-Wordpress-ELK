# Ansible
# Install LEMP, Wordpress, ELK stack with auto creating indexes for for wordpress debug.log

## Features
- Installing php
- Installing Nginx and create vhost config from Jinja template
- Installing Mysql, creating db user, db password and database
- Installing Wordpress engine with connection to Mysql and Nginx vhost
- Generate letsencrypt sert
- Create SWAP partiotion
- Installing and configuring Elasticsearch , Logstash, Kibana with authomatic creation indexes for Wordpress debug.log

## Roles describe

- install_php
- letsencrypt
- swap
- nginx_vhost_install
- mysql_install
- wordpress_install
- elasticsearch
- logstash
- kibana
- filebeat

## How to use
1. Configure access for your instance in group_vars/lab
2. Run run.yml file
3. Respond to requests from vars_prompt about:
   - Version PHP
   - Vhost name
   - DB name
   - DB user name
   - DB user password 
4. Relax and show magic 

## Tech

- [Ansible]
- [PHP]
- [Nginx]
- [MySQL]
- [Wordpress]
- [Elasticsearch]
- [Logstash]
- [Kibana]

[PHP]: <https://www.php.net>
[Nginx]: <https://nginx.org>
[MySQL]: <https://mysql.com>
[Wordpress]: <https://wordpress.com>
[Elasticsearch]: <https://www.elastic.co>
[Logstash]: <https://www.elastic.co>
[Kibana]: <https://www.elastic.co>
[Ansible]: <https://www.ansible.com>
