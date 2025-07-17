FROM almalinux:9
RUN dnf install nginx -y
COPY sample1.html /usr/share/nginx/html
CMD [ "nginx","-g","daemon off;" ]
