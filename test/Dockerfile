FROM centos:latest

MAINTAINER Hanif

RUN yum -y install httpd

COPY index.html /varwww/html/

CMD ["/usr/bin/httpd", "-D", "FOREGROUND"]

EXPOSE 80

