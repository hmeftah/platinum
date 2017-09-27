#Dockerfile gitlab
FROM centos:7
MAINTAINER dockerlite@gmail 

RUN yum -y update && \
    yum -y install git tar wget unzip sudo && \
    yum -y install policycoreutils openssh-server openssh-clients && \
    curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.rpm.sh | sudo bash && \
    yum install -y gitlab-ce




