FROM registry.centos.org/dharmit/base

RUN sudo yum update -y && \
    sudo yum install -y git && \
    git clone https://github.com/CentOS/container-pipeline-service/ /opt/cccp-service

WORKDIR /opt/cccp-service

CMD ["tail", "-f", "/dev/null"]
