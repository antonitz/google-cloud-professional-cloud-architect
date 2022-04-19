FROM centos:7
LABEL vendor="Bowtie Inc"
RUN yum install -y httpd
COPY index.html /var/www/html/
COPY boxofbowties*.jpg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
