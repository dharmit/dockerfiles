FROM registry.centos.org/openshift/jenkins-2-centos7

ADD plugins.txt plugins.txt

RUN /usr/local/bin/install-plugins.sh plugins.txt && rm -f plugins.txt
