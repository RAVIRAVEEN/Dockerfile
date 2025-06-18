FROM almalinux/8-base
RUN yum install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
COPY index.html  /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/RAVIRAVEEN/shell-script/refs/heads/master/18-docker.sh  /tmp
CMD [ "nginx", "-g","daemon off;"]