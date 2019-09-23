FROM centos:latest

VOLUME [ "/data" ]

RUN yum -y update && \
    yum -y install net-tools bind-utils vim-enhanced openssh-clients openldap-clients && \
    yum clean all

CMD ["bash"]
