
Instructions to build Centos 7.x images to use in a clusterdock topology
========================================================================

To build a centos 7.x image, use the folowing command.

``docker build . -t clusterdock/topology_nodebase:centos7.8 --build-arg BASE_IMAGE=centos7.8.2003``

The build-arg BASE_IMAGE can take any valid centos 7.x tags from the official centos repo on docker hub. Some examples
are

========== ===============
Version    Tag
========== ===============
Centos 7.4 centos7.4.1708
Centos 7.5 centos7.5.1804
Centos 7.6 centos7.6.1810
Centos 7.8 centos7.8.2003
========== ===============

