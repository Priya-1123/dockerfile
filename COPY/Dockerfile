FROM almalinux
RUN yum install nginx -y
COPY /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
LABEL AUTHOR="priya"

