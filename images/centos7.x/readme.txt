To build a centos 7.x image, use the folowing command.

docker build . -t clusterdock/topology_nodebase:centos7.8 --build-arg BASE_IMAGE=centos7.8.2003

The build-arg BASE_IMAGE can take any valid centos 7.x tags from the official centos repo on docker hub.
