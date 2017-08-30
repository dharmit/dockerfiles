FROM registry.centos.org/dharmit/base

MAINTAINER "Dharmit Shah <dshah@redhat.com>"

RUN  sudo yum -y update && \
     sudo yum -y install git make wget && \
     sudo yum -y --enablerepo=centosplus install golang && \
     sudo yum -y install epel-release && \
     sudo yum -y install glide && \
     sudo yum clean all

ENTRYPOINT ["/bin/bash"]
