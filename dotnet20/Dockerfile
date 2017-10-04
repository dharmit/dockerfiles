FROM registry.centos.org/dharmit/base

MAINTAINER "Dharmit Shah <dshah@redhat.com>"

RUN  sudo yum -y update && \
     sudo yum -y install centos-release-dotnet && \
     sudo yum -y install rh-dotnet20 && \
     sudo yum clean all

# dotnet run would, by default, listen on port 5000
EXPOSE 5000

CMD ["/bin/bash"]
