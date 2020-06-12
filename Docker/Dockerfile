#This is a sample Image of Centos
FROM centos:latest
MAINTAINER Rana Pratik
RUN yum install git -y && yum install java -y && yum install httpd -y 
RUN useradd pratik && touch /tmp/testfile3
COPY test /tmp
RUN yum clean all
CMD [“echo”,”Image created”] 

