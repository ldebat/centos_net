FROM centos:latest

VOLUME [ "/data" ]

RUN yum -y update && \
    yum -y install telnet net-tools bind-utils vim-enhanced openssh-clients openldap-clients && \
    yum clean all

CMD ["bash", "-c", "while true; do echo Alive; sleep 10; done"]
