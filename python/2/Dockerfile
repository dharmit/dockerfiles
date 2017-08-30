FROM registry.centos.org/dharmit/base

MAINTAINER Dharmit Shah <dshah@redhat.com>

RUN  sudo yum -y update && \
     sudo yum -y install epel-release && \
     sudo yum -y install python-pip && \
    pip install --upgrade pip && \
     sudo yum -y remove epel-release && \
     sudo yum clean all 

CMD ["/bin/bash"]
