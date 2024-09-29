Prerequisite VPROFILE PROJECT SETUP

Oracle VM Virtualbox
Vagrant
Vagrant plugins
a. vagrant plugin install vagrant-hostmanager
Git bash or equivalent editor
VM SETUP

Clone source code.
Cd into the repository.
Switch to the main branch.
Bring up vm’s $ vagrant up

NOTE: Bringing up all the vm’s may take a long time based on various factors. If vm setup stops in the middle run “vagrant up” command again. INFO: All the vm’s hostname and /etc/hosts file entries will be automatically updated.

PROVISIONING Services

Services

Nginx (web sevice)
Tomcat (Application server)
RabbitMQ (Broker/Queuing Agent )
Memcached (DB Caching )
ElasticSearch (Indexing/Search service )
MySQL (SQL Database)
Setup should be done in below mentioned order

MySQL (Database SVC) Memcache (DB Caching SVC)
Memcache (DB Caching SVC)
RabbitMQ (Broker/Queue SVC)
Tomcat (Application SVC)
Nginx (Web SVC)
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 2 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Footer
© 2
