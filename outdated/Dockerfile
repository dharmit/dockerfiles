FROM registry.centos.org/centos/centos

RUN yum -y install http://mirror.centos.org/centos-7/7.4.1708/os/x86_64/Packages/git-1.8.3.1-11.el7.x86_64.rpm && \
    yum -y install epel-release && \
    yum -y install python-pip npm gem && \
    pip install flask==0.10 && \
    npm install express@4.16.0 && \
    gem install sinatra:1.4.0
