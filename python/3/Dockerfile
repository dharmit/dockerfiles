FROM registry.centos.org/centos/centos

MAINTAINER Dharmit Shah <dshah@redhat.com>

RUN yum -y update && \
    yum -y install centos-release-scl && \
    yum -y install rh-python35 && \
    scl enable rh-python35 "pip install --upgrade pip" && \
    yum clean all && \
    cat /opt/rh/rh-python35/enable >> /root/.bashrc

ENTRYPOINT ["/bin/bash"]
