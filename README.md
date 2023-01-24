# manual_provisioning
muli tier web application manual locally setup 


VPROFILE PROJECT SETUP


Prerequisite:
1. Oracle VM Virtualbox
2. Vagrant
3. Vagrant plugins
a. vagrant plugin install vagrant-hostmanager
b. vagrant plugin install vagrant-vbguest
4. Git bash or equivalent editor


VM SETUP:
1. Clone source code.
2. Cd into the repository.
3. Switch to the local-setup branch.
4. cd into vagrant/Manual_provisioning.


Bring up vm’s
$ vagrant up

PROVISIONING
Services
1. Nginx:
Web Service
2. Tomcat
Application Server
3. RabbitMQ
Broker/Queuing Agent
4. Memcache
DB Caching
5. ElasticSearch
Indexing/Search service
6. MySQL
SQL Database


MYSQL Setup


