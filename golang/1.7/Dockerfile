FROM registry.centos.org/centos/centos

MAINTAINER "Dharmit Shah <dshah@redhat.com>"

RUN yum -y update && \
    yum -y install git make wget && \
    yum -y --enablerepo=centosplus install golang && \
    yum -y install epel-release && \
    yum -y install glide && \
    yum clean all

ENTRYPOINT ["/bin/bash"]
