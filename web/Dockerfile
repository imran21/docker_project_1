FROM centos
MAINTAINER imran@gmail.com

RUN yum install httpd -y

COPY httpd_start.sh /

WORKDIR /

CMD chmod 755 httpd_start.sh

WORKDIR 

EXPOSE 80:80

ENTRYPOINT /httpd_start.sh" && /bin/bash
