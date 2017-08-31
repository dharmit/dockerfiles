FROM registry.centos.org/dharmit/base

MAINTAINER Dharmit Shah <dshah@redhat.com>

RUN sudo yum -y update && \
    sudo yum -y install centos-release-scl && \
    sudo yum -y install rh-python35 && \
    sudo scl enable rh-python35 "pip install --upgrade pip" && \
    sudo yum clean all && \
    cat /opt/rh/rh-python35/enable >> /home/user/.bashrc

CMD ["/bin/bash"]
