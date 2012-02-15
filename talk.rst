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
