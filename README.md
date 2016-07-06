# openstack-ansible-神荼
ansible自动化安装openstack云计算 元件/平台

ansible scripts to automatically deploy openstack components/cluster

## 语言/Язык/Language

* [中文](#介绍)
* [Российская](#Общий-обзор)
* [English](#overview)

## 介绍
此项目以openstack官方安装教程为基础, 用ansible来自动化安装openstack云计算元件

## 支持的官方安装教程
* Liberty
  * 乌班图/优麒麟 (Ubuntu/Ubuntu Kylin) - http://docs.openstack.org/liberty/zh_CN/install-guide-ubuntu/
  * 红帽 (Redhat) - http://docs.openstack.org/liberty/zh_CN/install-guide-rdo/

## 支持的openstack元件
* 环境
  * 主机网络
  * 网络时间协议
  * Openstack包
  * SQL数据库
  * NoSQL数据库
  * 消息队列
* 身份认证服务 (Keystone)
* 镜像服务 (Glance)
* 计算服务 (Nova)
* 网络服务 (Neutron)
* 仪表盘 (Horizon)

## Общий обзор

## Overview
This project uses ansible automation tool to deploy openstack components
according to the official openstack installation documentation.

## Supported Offical Installation Guides
* Mitaka
  * Ubuntu -
http://docs.openstack.org/mitaka/install-guide-ubuntu/
  * Redhat -
http://docs.openstack.org/mitaka/install-guide-rdo/

## Supported Openstack Components
* Environment
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
