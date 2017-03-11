FROM centos:latest
MAINTAINER Kolab Systems <vanmeeuwen@kolabsys.com>
RUN yum -y install epel-release
ADD http://obs.kolabsys.com/repositories/Kolab:/16/CentOS_7/Kolab:16.repo \
    /etc/yum.repos.d/Kolab:16.repo
RUN rpm --import https://ssl.kolabsys.com/community.asc
RUN yum clean all
RUN yum -y update
