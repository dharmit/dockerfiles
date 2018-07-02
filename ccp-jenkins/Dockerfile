FROM registry.centos.org/openshift/jenkins-2-centos7

ADD plugins.txt /tmp/plugins.txt

RUN /usr/local/bin/install-plugins.sh /tmp/plugins.txt
