FROM registry.centos.org/dharmit/base

MAINTAINER "Dharmit Shah <dshah@redhat.com>"

RUN  sudo yum -y update && \
     sudo yum -y install git make wget && \
     sudo yum install -y centos-release-scl && \
     sudo yum -y install git go-toolset-7-golang && yum clean all && \
     sudo yum -y install epel-release && \
     sudo yum -y install glide && \
     sudo yum clean all

ENV GOPATH=/go \
    BASH_ENV=/opt/rh/go-toolset-7/enable \
    ENV=/opt/rh/go-toolset-7/enable \
    PROMPT_COMMAND=". /opt/rh/go-toolset-7/enable"

CMD ["/bin/bash"]
