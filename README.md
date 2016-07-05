# openstack-ansible-production
ansible scripts to automatically deploy openstack cluster

## Overview
This project uses ansible automation tool to deploy openstack compoents
according to the official openstack installation documentation.

## Supported Offical Installation Guides
* Mitaka
  * Ubuntu -
http://docs.openstack.org/mitaka/install-guide-ubuntu/
  * Redhat -
http://docs.openstack.org/mitaka/install-guide-rdo/

## Supported Openstack Components
* Environment Configuration
  * Host Networking
  * Network Time Protocol (NTP)
  * Openstack packages
  * SQL database (Mariadb/Mysql)
  * NoSQL database (MongoDB)
  * Message queue (RabbitMQ)
  * Memcached
* Indentity Service (Keystone)
* Image Service (Glance)
* Compute Service (Nova)
* Networking Service (Neutron)
* Dashboard (Horizon)
