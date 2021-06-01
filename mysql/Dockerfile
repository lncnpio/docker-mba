FROM centos

RUN yum -y install epel-release
RUN yum -y update
RUN yum -y install mysql-server

ENTRYPOINT [ "/bin/bash", "-l", "-c" ]
