=========
AWS Intro
=========


.. footer:: Ales Zoulek (@aleszoulek) | <ales.zoulek@gmail.com>


General
=======

* Virtual hosting (+ additional services)
* Regions (3x US, EU Ireland, JP, Singapore, Brazil)
* Web UI
* Rest API (python: boto)

EC2
===

Virtual hosts

* Snapshots
* AMI
* EIP
* Security groups (firewall)

ELB
===

Load balancer

* HTTP / TCP
* Health check
* News:

  * HTTPS Support

S3
==

Storage

* Bucket
* URL
* ACL: Private / Public files
* (django-storages support)

Cloud front
===========

CDN

* CNAME
* S3 Bucket
* HTTP(S)

Route 53
========

DNS

* News:

  * DNS A records to ELB

SES
===

Simple email service

* Quota
* Max send rate
* Verified senders
* News:

  * Binary attachements
  * SMPT

Other services
==============
* DynamoDB - NoSQL key/value store
* SimpleDB - NoSQL key/value store
* RDS - scalable MySQL or Oracle DB
* Elastic MapReduce - Hadoop to S3 or DynamoDB
* CloudFormation - templates for EC2
* Elastic Beanstalk - deploying Java WAR files
* VPC - virtual private cloud
* CloudWatch - monitoring
* CloudFront - CDN
* ElastiCache - cache
* SQS - message queue
* IAM - users & permissions to AWS
* SNS - notifications and messages in AWS
* Storage Gateway - remote storage management


