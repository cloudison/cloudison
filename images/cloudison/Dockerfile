FROM busybox

MAINTAINER admin@cloudison.cloud

ADD cloudison/index.html /www/index.html
EXPOSE 80
CMD httpd -p 80 -h /www; tail -f /dev/null
