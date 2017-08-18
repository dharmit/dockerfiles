FROM registry.centos.org/centos/centos

MAINTAINER Dharmit Shah <dshah@redhat.com>

RUN yum -y update && \
    yum -y install epel-release && \
    yum -y install python-pip && \
    pip install --upgrade pip && \
    yum -y remove epel-release && \
    yum clean all 

ENTRYPOINT ["/bin/bash"]
