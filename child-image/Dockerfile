FROM localhost/ex288-httpd:2.0

MAINTAINER Red Hat Training <training@redhat.com>

# DocumentRoot for Apache

ENV DOCROOT=/var/www/html

EXPOSE 8080

# This stuff is needed to ensure a clean start

# Launch httpd

CMD /usr/sbin/httpd -DFOREGROUND
